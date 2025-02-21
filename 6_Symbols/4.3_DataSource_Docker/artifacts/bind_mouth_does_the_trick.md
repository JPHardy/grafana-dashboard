### How `docker-compose up` Works with File Mounting in This Setup

When you run the `docker-compose up` command, Docker Compose orchestrates the process of setting up and running the services defined in your `docker-compose.yaml` file. Here's how the files are moved or mounted into the Grafana container:

---

### 1. **Mounting Volumes**
The `volumes` directive in your `docker-compose.yaml` file specifies how files and directories on your host system are linked to paths inside the container:

```yaml
volumes:
  - grafana-storage:/var/lib/grafana
  - ./provisioning:/etc/grafana/provisioning
```

- **`grafana-storage:/var/lib/grafana`**: This is a named volume that Docker manages. It ensures that Grafana's data (like dashboards and configurations) persists between container restarts.

- **`./provisioning:/etc/grafana/provisioning`**: This is a bind mount. The `./provisioning` directory on your host is mapped to the `/etc/grafana/provisioning` directory in the container. Any changes made to the `./provisioning` directory on the host will immediately reflect in the container.

---

### 2. **Role of Provisioning Files**
Grafana uses provisioning files to auto-configure data sources, dashboards, and other settings when the container starts:

- **`testdata.yaml`**: This file is placed inside the `datasources` directory under `provisioning`. It defines the TestData data source and is loaded by Grafana from the container's `/etc/grafana/provisioning/datasources` directory.

---

### 3. **What Happens During `docker-compose up`?**
- Docker Compose parses the `docker-compose.yaml` file.
- It pulls the required Grafana image (`grafana/grafana-enterprise`) if not already present.
- A new container is created and started with:
  - Port `3000` on the host mapped to port `3000` in the container.
  - The `grafana-storage` volume mounted at `/var/lib/grafana`.
  - The `./provisioning` directory bind-mounted to `/etc/grafana/provisioning` in the container.
- Inside the container, Grafana detects the provisioning files in `/etc/grafana/provisioning` and configures the TestData data source based on the `testdata.yaml` file.

---

### 4. **Directory Structure Inside the Container**
After `docker-compose up`, the container has the following structure:
```
/var/lib/grafana/                # Persistent storage for Grafana data
/etc/grafana/provisioning/       # Mounted provisioning directory
  └── datasources/
      └── testdata.yaml          # Your TestData data source configuration
```

---

### 5. **Verification**
Once Grafana starts:
- Access it at `http://localhost:3000`.
- Log in using the default credentials (`admin`/`admin`).
- Navigate to the "Data Sources" section to confirm that the TestData data source has been provisioned.

---

This setup ensures that the necessary configuration files are consistently available inside the container without being manually copied each time. Instead, they are directly accessed via the bind mount.