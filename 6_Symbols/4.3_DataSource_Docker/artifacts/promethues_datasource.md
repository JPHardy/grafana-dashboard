Here’s the updated YAML configuration for a Prometheus datasource compatible with Grafana's datasource API version 1:

```yaml
apiVersion: 1

datasources:
  - name: TestData
    type: prometheus
    url: http://your-prometheus-server:9090
    access: proxy
    basicAuth: false
```

### Key Points:
1. **`type: prometheus`**: Specifies the datasource type as Prometheus.
2. **`url`**: Replace `http://your-prometheus-server:9090` with the URL of your Prometheus server.
3. **`access`**: The `proxy` mode lets Grafana proxy the data requests through the backend.
4. **`basicAuth`**: Set to `true` if you need basic authentication for Prometheus; otherwise, leave it as `false`.

Let me know if you need further adjustments or details!