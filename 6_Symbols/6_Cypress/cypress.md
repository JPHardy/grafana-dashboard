# Setting up Cypress to take screenshots

## Instructions

### 1. Initialize NPM Project

The most straightforward way I found to install Cypress was to use NPM and initialize a project. Execute the following in the root directory of the repository:

```zsh
brew install npm
npm init
```

You will be prompted for some details, the default values are mostly acceptable.

### 2. Configure Cypress

Still in the repository root directory execute the following:

```zsh
npm install cypress --save-dev
npx cypress open
```

This will launch the Cypress interface. Follow the instructions to set up an E2E project. Cypress will automatically create a folder structure for End-To-End testing.

### 3. Write a test

Our test needs to log into Grafana, navigate to a dashboard and create a screenshot. Copilot produced this:

```javascript
describe('Take Screenshot in Grafana', () => {
  it('Logs into Grafana, navigates to a panel, and takes a screenshot with a width of 1558 pixels', () => {
    // Set the viewport width and height
    cy.viewport(1558, 900); // Height can be adjusted based on your needs

    // Visit Grafana login page
    cy.visit('http://your-grafana-url/login'); // Replace with your Grafana URL

    // Log in to Grafana
    cy.get('input[name="user"]').type('your-username'); // Replace with your username
    cy.get('input[name="password"]').type('your-password'); // Replace with your password
    cy.get('button[type="submit"]').click();

    // Navigate to a specific panel
    cy.visit('http://your-grafana-url/d/your-panel-id'); // Replace with your panel's URL

    // Take a screenshot of the specific panel
    cy.screenshot('grafana-panel-screenshot'); // Customize screenshot name
  });
});
```

Save this file under `cypress/e2e/screenshot.cy.js`. Copilot suggested the name `screenshot.spec.js` but when I tried this, Cypress had no visibility over it

### 4. Run the test

Start Cypress:

```zsh
npx cypress open
```

Follow the instructions to start E2E testing in your browser of choice. You should be presented with the structure of your `cypress` directory. Navigate to the `screenshot.spec.js` test that you wrote earlier and run it.

If the test was successful you should see a new screenshot in `cypress/screenshots`

## Hold on...

The test is currently using plaintext credentials. This will need to be addressed.