# 📥 Input

## 📄 Documentation in Grafana
[Grafana Documentation](https://grafana.com/docs/)

## 🐳 Docker Steps to Install Grafana and Add Data Sources

To install Grafana using Docker and set up data sources, follow these steps:

### 🛠️ Install Grafana using Docker:
```sh
docker run -d -p 3000:3000 --name=grafana grafana/grafana-enterprise
```
This command runs the latest stable version of Grafana Enterprise, mapping port 3000 to allow access via your browser.

### 🌐 Access Grafana:
Open a browser and go to [http://localhost:3000](http://localhost:3000). Log in using the default credentials:
- **Username:** admin
- **Password:** admin

### ➕ Add Data Sources:
Once logged in, you can add data sources through the Grafana UI:
1. Click on "Connections" in the left-side menu.
2. Search for the data source you want to add.
3. Click on the data source and then "Add new data source".
4. Configure the data source with the required settings (URL, authentication, etc.).
5. Click "Save & Test" to verify the connection.

For more detailed steps on adding data sources through the UI, refer to [Grafana for beginners: Quick tips to add a data source, choose a visualization type, and more](https://grafana.com/docs/grafana/latest/getting-started/getting-started-grafana/).

### 🔌 Pre-install Data Source Plugins:
Alternatively, you can pre-install data source plugins when running the Docker container:
```sh
docker run -d -p 3001:3000 --name=grafana_ds2 \
    -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
    grafana/grafana-enterprise
```
This example installs the clock panel and simple JSON datasource plugins.

### 🧩 Advanced Setups:
For more advanced setups, you can use Docker Compose to define and run Grafana along with other services. Refer to the [Run Grafana via Docker Compose](https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/#run-grafana-via-docker-compose) section for an example of how to set this up.

Remember to configure your data sources appropriately based on your specific requirements and the types of data you want to visualize in Grafana.

---

## 🧪 Create a TestData Data Source in Grafana using Docker

To create a TestData data source in Grafana using Docker, you can use a Docker Compose file to set up Grafana and automatically provision the TestData data source. Here's how you can do it:

### 📄 Create a Docker Compose File:
Create a new file named `docker-compose.yaml` with the following content:
```yaml
version: '3'
services:
  grafana:
    image: grafana/grafana-enterprise
    container_name: grafana
    restart: unless-stopped
    ports:
      - '3000:3000'
    volumes:
      - grafana-storage:/var/lib/grafana
      - ./provisioning:/etc/grafana/provisioning
volumes:
  grafana-storage: {}
```

### 📁 Create Provisioning Directory:
Create a directory named `provisioning` in the same location as your `docker-compose.yaml` file.

### 📂 Create Datasources Directory:
Inside the `provisioning` directory, create another directory named `datasources`.

### 📝 Create TestData Configuration:
In the `datasources` directory, create a file named `testdata.yaml` with the following content:
```yaml
apiVersion: 1

datasources:
  - name: TestData
    type: testdata
```

### 🏗️ Directory Structure:
Your directory structure should look like this:
```
.
├── docker-compose.yaml
└── provisioning
    └── datasources
        └── testdata.yaml
```

### 🚀 Start Grafana:
cd /workspaces/grafana-dashboard/6_Symbols/4.3_DataSource_Docker/
Now, run the following command to start Grafana with the TestData data source provisioned:

```sh
docker rm -f grafana
cd /workspaces/grafana-dashboard/6_Symbols/4.3_DataSource_Docker/
docker compose up -d
```

This setup will automatically create and configure the TestData data source in Grafana when the container starts.

### 🌐 Access Grafana:
You can access Grafana at [http://localhost:3000](http://localhost:3000). The default login credentials are:
- **Username:** admin
- **Password:** admin

The TestData data source will be available for use in your dashboards and panels.

This method uses Grafana's provisioning feature to automatically set up the data source, as described in the [Provision dashboards and data sources](https://grafana.com/docs/grafana/latest/administration/provisioning/#provision-dashboards-and-data-sources) tutorial.

The [TestData data source](https://grafana.com/docs/grafana/latest/datasources/testdata/) provides more information on how to use this data source, including various scenarios you can use to generate different types of test data.

Remember, the TestData data source is built-in and doesn't require any additional installation steps. It's particularly useful for testing and development purposes.