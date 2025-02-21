@rifaterdemsahin ➜ /workspaces/grafana-dashboard/6_Symbols/4.1_DatasourceSetup_StandAlone (main) $ helm install grafana bitn
ami/grafana --namespace grafana-monitoring -f grafana-dashboard-deployment.yaml --dry-run --debug
install.go:224: 2025-01-16 14:09:35.996349329 +0000 UTC m=+0.307522143 [debug] Original chart version: ""
install.go:241: 2025-01-16 14:09:39.88494835 +0000 UTC m=+4.196121184 [debug] CHART PATH: /home/codespace/.cache/helm/repository/grafana-11.4.2.tgz

NAME: grafana
LAST DEPLOYED: Thu Jan 16 14:09:40 2025
NAMESPACE: grafana-monitoring
STATUS: pending-install
REVISION: 1
TEST SUITE: None
USER-SUPPLIED VALUES:
admin:
  password: your-password
  user: admin
config:
  grafanaIniConfigMap: myconfig
  useGrafanaIniFile: false
dashboardsConfigMaps:
- configMapName: grafana-dashboard-config1
  fileName: grafana_dashboard_config1.json
- configMapName: grafana-dashboard-config2
  fileName: grafana_dashboard_config2.json
dashboardsProvider:
  enabled: true
datasources:
  secretName: grafana-datasource-secret
grafana:
  envVars:
  - name: GF_LOG_LEVEL
    value: debug
  extraVolumes:
  - emptyDir: {}
    name: grafana-storage
  - name: grafana-datasource-secret
    secret:
      secretName: grafana-datasource-secret
  - configMap:
      name: grafana-datasources
    name: datasource
  persistence:
    accessModes:
    - ReadWriteOnce
    enabled: true
    size: 100Mi
    storageClassName: standard
  replicaCount: 1
  resources:
    limits:
      cpu: 200m
      memory: 256Mi
    requests:
      cpu: 100m
      memory: 128Mi
  volumeMounts:
  - mountPath: /opt/bitnami/grafana
    name: grafana-storage
  - mountPath: /opt/bitnami/grafana/provisioning/datasources
    name: datasource
service:
  ports:
    grafana: 3000
  type: ClusterIP
sidecars:
- command:
  - sh
  - -c
  - mkdir -p /opt/bitnami/grafana/provisioning/datasources
  image: busybox
  name: init-grafana
  volumeMounts:
  - mountPath: /opt/bitnami/grafana
    name: grafana-storage

COMPUTED VALUES:
admin:
  existingSecret: ""
  existingSecretPasswordKey: password
  password: your-password
  user: admin
alerting:
  configMapName: ""
clusterDomain: cluster.local
common:
  exampleValue: common-chart
  global:
    compatibility:
      openshift:
        adaptSecurityContext: auto
    defaultStorageClass: ""
    imagePullSecrets: []
    imageRegistry: ""
    security:
      allowInsecureImages: false
    storageClass: ""
commonAnnotations: {}
commonLabels: {}
config:
  grafanaIniConfigMap: myconfig
  grafanaIniSecret: ""
  useGrafanaIniFile: false
dashboardsConfigMaps:
- configMapName: grafana-dashboard-config1
  fileName: grafana_dashboard_config1.json
- configMapName: grafana-dashboard-config2
  fileName: grafana_dashboard_config2.json
dashboardsProvider:
  configMapName: ""
  enabled: true
datasources:
  secretDefinition: {}
  secretName: grafana-datasource-secret
diagnosticMode:
  args:
  - infinity
  command:
  - sleep
  enabled: false
extraDeploy: []
fullnameOverride: ""
global:
  compatibility:
    openshift:
      adaptSecurityContext: auto
  defaultStorageClass: ""
  imagePullSecrets: []
  imageRegistry: ""
  security:
    allowInsecureImages: false
  storageClass: ""
grafana:
  affinity: {}
  args: []
  automountServiceAccountToken: false
  command: []
  containerPorts:
    grafana: 3000
  containerSecurityContext:
    allowPrivilegeEscalation: false
    capabilities:
      drop:
      - ALL
    enabled: true
    privileged: false
    readOnlyRootFilesystem: true
    runAsGroup: 1001
    runAsNonRoot: true
    runAsUser: 1001
    seLinuxOptions: {}
    seccompProfile:
      type: RuntimeDefault
  customLivenessProbe: {}
  customReadinessProbe: {}
  customStartupProbe: {}
  enableServiceLinks: true
  envVars:
  - name: GF_LOG_LEVEL
    value: debug
  extraConfigmaps: []
  extraEnvVars: []
  extraEnvVarsCM: ""
  extraEnvVarsSecret: ""
  extraPorts: []
  extraVolumeMounts: []
  extraVolumes:
  - emptyDir: {}
    name: grafana-storage
  - name: grafana-datasource-secret
    secret:
      secretName: grafana-datasource-secret
  - configMap:
      name: grafana-datasources
    name: datasource
  hostAliases: []
  initContainers: []
  lifecycleHooks: {}
  livenessProbe:
    enabled: true
    failureThreshold: 6
    initialDelaySeconds: 120
    periodSeconds: 10
    successThreshold: 1
    timeoutSeconds: 5
  nodeAffinityPreset:
    key: ""
    type: ""
    values: []
  nodeSelector: {}
  pdb:
    create: true
    maxUnavailable: ""
    minAvailable: ""
  persistence:
    accessModes:
    - ReadWriteOnce
    enabled: true
    size: 100Mi
    storageClassName: standard
  podAffinityPreset: ""
  podAnnotations: {}
  podAntiAffinityPreset: soft
  podLabels: {}
  podSecurityContext:
    enabled: true
    fsGroup: 1001
    fsGroupChangePolicy: Always
    supplementalGroups: []
    sysctls: []
  priorityClassName: ""
  readinessProbe:
    enabled: true
    failureThreshold: 6
    initialDelaySeconds: 30
    path: /api/health
    periodSeconds: 10
    scheme: HTTP
    successThreshold: 1
    timeoutSeconds: 5
  replicaCount: 1
  resources:
    limits:
      cpu: 200m
      memory: 256Mi
    requests:
      cpu: 100m
      memory: 128Mi
  resourcesPreset: nano
  schedulerName: ""
  sidecars: []
  startupProbe:
    enabled: false
    failureThreshold: 6
    initialDelaySeconds: 30
    path: /api/health
    periodSeconds: 10
    scheme: HTTP
    successThreshold: 1
    timeoutSeconds: 5
  terminationGracePeriodSeconds: ""
  tolerations: []
  topologySpreadConstraints: []
  updateStrategy:
    type: RollingUpdate
  volumeMounts:
  - mountPath: /opt/bitnami/grafana
    name: grafana-storage
  - mountPath: /opt/bitnami/grafana/provisioning/datasources
    name: datasource
image:
  digest: ""
  pullPolicy: IfNotPresent
  pullSecrets: []
  registry: docker.io
  repository: bitnami/grafana
  tag: 11.4.0-debian-12-r0
imageRenderer:
  callbackURL: ""
  enabled: false
  serverURL: ""
ingress:
  annotations: {}
  apiVersion: ""
  enabled: false
  extraHosts: []
  extraPaths: []
  extraRules: []
  extraTls: []
  hostname: grafana.local
  ingressClassName: ""
  path: /
  pathType: ImplementationSpecific
  secrets: []
  selfSigned: false
  tls: false
kubeVersion: ""
ldap:
  allowSignUp: false
  basedn: ""
  binddn: ""
  bindpw: ""
  configMapName: ""
  configuration: ""
  enabled: false
  extraConfiguration: ""
  searchAttribute: uid
  searchFilter: ""
  secretName: ""
  tls:
    CAFilename: ""
    certFilename: ""
    certKeyFilename: ""
    certificatesMountPath: /opt/bitnami/grafana/conf/ldap/
    certificatesSecret: ""
    enabled: false
    skipVerify: false
    startTls: false
  uri: ""
metrics:
  enabled: false
  prometheusRule:
    additionalLabels: {}
    enabled: false
    namespace: ""
    rules: []
  service:
    annotations:
      prometheus.io/path: /metrics
      prometheus.io/port: "3000"
      prometheus.io/scrape: "true"
  serviceMonitor:
    enabled: false
    honorLabels: false
    interval: ""
    jobLabel: ""
    labels: {}
    metricRelabelings: []
    namespace: ""
    relabelings: []
    scrapeTimeout: ""
    selector: {}
nameOverride: ""
networkPolicy:
  addExternalClientAccess: true
  allowExternal: true
  allowExternalEgress: true
  enabled: true
  extraEgress: []
  extraIngress: []
  ingressNSMatchLabels: {}
  ingressNSPodMatchLabels: {}
  ingressPodMatchLabels: {}
notifiers:
  configMapName: ""
persistence:
  accessMode: ReadWriteOnce
  accessModes: []
  annotations: {}
  enabled: true
  existingClaim: ""
  size: 10Gi
  storageClass: ""
plugins: ""
service:
  annotations: {}
  clusterIP: ""
  externalTrafficPolicy: Cluster
  extraPorts: []
  loadBalancerClass: ""
  loadBalancerIP: ""
  loadBalancerSourceRanges: []
  nodePorts:
    grafana: ""
  ports:
    grafana: 3000
  sessionAffinity: None
  sessionAffinityConfig: {}
  type: ClusterIP
serviceAccount:
  annotations: {}
  automountServiceAccountToken: false
  create: true
  name: ""
sidecars:
- command:
  - sh
  - -c
  - mkdir -p /opt/bitnami/grafana/provisioning/datasources
  image: busybox
  name: init-grafana
  volumeMounts:
  - mountPath: /opt/bitnami/grafana
    name: grafana-storage
smtp:
  enabled: false
  existingSecret: ""
  existingSecretPasswordKey: password
  existingSecretUserKey: user
  fromAddress: ""
  fromName: ""
  host: ""
  password: password
  skipVerify: "false"
  user: user
volumePermissions:
  containerSecurityContext:
    runAsUser: 0
    seLinuxOptions: {}
  enabled: false
  image:
    digest: ""
    pullPolicy: IfNotPresent
    pullSecrets: []
    registry: docker.io
    repository: bitnami/os-shell
    tag: 12-debian-12-r34
  resources: {}
  resourcesPreset: nano

HOOKS:
MANIFEST:
---
# Source: grafana/templates/networkpolicy.yaml
kind: NetworkPolicy
apiVersion: networking.k8s.io/v1
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
spec:
  podSelector:
    matchLabels:
      app.kubernetes.io/instance: grafana
      app.kubernetes.io/name: grafana
      app.kubernetes.io/component: grafana
  policyTypes:
    - Ingress
    - Egress
  egress:
    - {}
  ingress:
    - ports:
        - port: 3000
---
# Source: grafana/templates/pdb.yaml
apiVersion: policy/v1
kind: PodDisruptionBudget
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
spec:
  maxUnavailable: 1
  selector:
    matchLabels:
      app.kubernetes.io/instance: grafana
      app.kubernetes.io/name: grafana
      app.kubernetes.io/component: grafana
---
# Source: grafana/templates/serviceaccount.yaml
apiVersion: v1
kind: ServiceAccount
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
secrets:
  - name: grafana-admin
  - name: grafana-datasource-secret
automountServiceAccountToken: false
---
# Source: grafana/templates/secret.yaml
apiVersion: v1
kind: Secret
metadata:
  name: grafana-admin
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
type: Opaque
data:
  GF_SECURITY_ADMIN_PASSWORD: "eW91ci1wYXNzd29yZA=="
---
# Source: grafana/templates/configmap.yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: grafana-envvars
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
data:
  GF_SECURITY_ADMIN_USER: "admin"
  GF_INSTALL_PLUGINS: ""
  GF_PATHS_PLUGINS: "/opt/bitnami/grafana/data/plugins"
  GF_AUTH_LDAP_ENABLED: "false"
  GF_AUTH_LDAP_CONFIG_FILE: "/opt/bitnami/grafana/conf/ldap.toml"
  GF_AUTH_LDAP_ALLOW_SIGN_UP: "false"
  GF_PATHS_PROVISIONING: "/opt/bitnami/grafana/conf/provisioning"
  GF_PATHS_CONFIG: "/opt/bitnami/grafana/conf/grafana.ini"
  GF_PATHS_DATA: "/opt/bitnami/grafana/data"
  GF_PATHS_LOGS: "/opt/bitnami/grafana/logs"
---
# Source: grafana/templates/dashboard-provider.yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: grafana-provider
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
data:
  default-provider.yaml: |-
    apiVersion: 1

    providers:
      # <string> an unique provider name
    - name: 'default-provider'
      # <int> org id. will default to orgId 1 if not specified
      orgId: 1
      # <string, required> name of the dashboard folder. Required
      folder: dashboards
      # <string> folder UID. will be automatically generated if not specified
      folderUid: ''
      # <string, required> provider type. Required
      type: file
      # <bool> disable dashboard deletion
      disableDeletion: false
      # <bool> enable dashboard editing
      editable: true
      # <int> how often Grafana will scan for changed dashboards
      updateIntervalSeconds: 10
      options:
        # <string, required> path to dashboard files on disk. Required
        path: /opt/bitnami/grafana/dashboards
        # <bool> enable folders creation for dashboards
        #foldersFromFilesStructure: true
---
# Source: grafana/templates/pvc.yaml
kind: PersistentVolumeClaim
apiVersion: v1
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
spec:
  accessModes:
    - "ReadWriteOnce"
  resources:
    requests:
      storage: "10Gi"
---
# Source: grafana/templates/service.yaml
apiVersion: v1
kind: Service
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
spec:
  type: ClusterIP
  sessionAffinity: None
  ports:
    - port: 3000
      targetPort: dashboard
      protocol: TCP
      name: http
      nodePort: null
  selector:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/name: grafana
    app.kubernetes.io/component: grafana
---
# Source: grafana/templates/deployment.yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: grafana
  namespace: "grafana-monitoring"
  labels:
    app.kubernetes.io/instance: grafana
    app.kubernetes.io/managed-by: Helm
    app.kubernetes.io/name: grafana
    app.kubernetes.io/version: 11.4.0
    helm.sh/chart: grafana-11.4.2
    app.kubernetes.io/component: grafana
spec:
  replicas: 1
  selector:
    matchLabels:
      app.kubernetes.io/instance: grafana
      app.kubernetes.io/name: grafana
      app.kubernetes.io/component: grafana
  strategy: 
    type: RollingUpdate
  template:
    metadata:
      labels:
        app.kubernetes.io/instance: grafana
        app.kubernetes.io/managed-by: Helm
        app.kubernetes.io/name: grafana
        app.kubernetes.io/version: 11.4.0
        helm.sh/chart: grafana-11.4.2
        app.kubernetes.io/component: grafana
      annotations:
        checksum/secret: 4392d22dc063d7ffda1126edc47da819eefc80a1e3130abeb719c2232887e531
        checksum/config: 19c20dc5bd07bc522511ffab5d9eac1446dcd3a6450e7bbfdf09a5d562286cec
        checksum/dashboard-provider: cd54948bf37e0721fd87481725f1618776aa7ba6f4259f9eb094412c9ca9d1f6
    spec:
      
      automountServiceAccountToken: false
      serviceAccountName: grafana
      affinity:
        podAffinity:
          
        podAntiAffinity:
          preferredDuringSchedulingIgnoredDuringExecution:
            - podAffinityTerm:
                labelSelector:
                  matchLabels:
                    app.kubernetes.io/instance: grafana
                    app.kubernetes.io/name: grafana
                    app.kubernetes.io/component: grafana
                topologyKey: kubernetes.io/hostname
              weight: 1
        nodeAffinity:
          
      securityContext:
        fsGroup: 1001
        fsGroupChangePolicy: Always
        supplementalGroups: []
        sysctls: []
      enableServiceLinks: true
      initContainers:
      containers:
        - name: grafana
          image: docker.io/bitnami/grafana:11.4.0-debian-12-r0
          imagePullPolicy: IfNotPresent
          securityContext:
            allowPrivilegeEscalation: false
            capabilities:
              drop:
              - ALL
            privileged: false
            readOnlyRootFilesystem: true
            runAsGroup: 1001
            runAsNonRoot: true
            runAsUser: 1001
            seLinuxOptions: {}
            seccompProfile:
              type: RuntimeDefault
          envFrom:
            - configMapRef:
                name: grafana-envvars
          env:
            - name: GF_SECURITY_ADMIN_PASSWORD
              valueFrom:
                secretKeyRef:
                  name: grafana-admin
                  key: GF_SECURITY_ADMIN_PASSWORD
          volumeMounts:
            - name: empty-dir
              mountPath: /tmp
              subPath: tmp-dir
            - name: empty-dir
              mountPath: /opt/bitnami/grafana/conf
              subPath: app-conf-dir
            - name: empty-dir
              mountPath: /opt/bitnami/grafana/tmp
              subPath: app-tmp-dir
            - name: empty-dir
              mountPath: /bitnami/grafana
              subPath: app-volume-dir
            - name: data
              mountPath: /opt/bitnami/grafana/data
            - name: dashboards-provider
              mountPath: /opt/bitnami/grafana/conf.default/provisioning/dashboards
            - name: grafana-dashboard-config1
              mountPath: /opt/bitnami/grafana/dashboards/grafana_dashboard_config1.json
              subPath: grafana_dashboard_config1.json
            - name: grafana-dashboard-config2
              mountPath: /opt/bitnami/grafana/dashboards/grafana_dashboard_config2.json
              subPath: grafana_dashboard_config2.json
            - name: datasources
              mountPath: /opt/bitnami/grafana/conf.default/provisioning/datasources
          ports:
            - name: dashboard
              containerPort: 3000
              protocol: TCP
          livenessProbe:
            tcpSocket:
              port: dashboard
            initialDelaySeconds: 120
            periodSeconds: 10
            timeoutSeconds: 5
            successThreshold: 1
            failureThreshold: 6
          readinessProbe:
            httpGet:
              path: /api/health
              port: dashboard
              scheme: HTTP
            initialDelaySeconds: 30
            periodSeconds: 10
            timeoutSeconds: 5
            successThreshold: 1
            failureThreshold: 6
          resources:
            limits:
              cpu: 200m
              memory: 256Mi
            requests:
              cpu: 100m
              memory: 128Mi
      volumes:
        - name: empty-dir
          emptyDir: {}
        - name: data
          persistentVolumeClaim:
            claimName: grafana
        - name: dashboards-provider
          configMap:
            name: grafana-provider
        - name: grafana-dashboard-config1
          configMap:
            name: grafana-dashboard-config1
        - name: grafana-dashboard-config2
          configMap:
            name: grafana-dashboard-config2
        - name: datasources
          secret:
            secretName: grafana-datasource-secret
        - emptyDir: {}
          name: grafana-storage
        - name: grafana-datasource-secret
          secret:
            secretName: grafana-datasource-secret
        - configMap:
            name: grafana-datasources
          name: datasource

NOTES:
CHART NAME: grafana
CHART VERSION: 11.4.2
APP VERSION: 11.4.0

Did you know there are enterprise versions of the Bitnami catalog? For enhanced secure software supply chain features, unlimited pulls from Docker, LTS support, or application customization, see Bitnami Premium or Tanzu Application Catalog. See https://www.arrow.com/globalecs/na/vendors/bitnami for more information.

** Please be patient while the chart is being deployed **

1. Get the application URL by running these commands:
    echo "Browse to http://127.0.0.1:8080"
    kubectl port-forward svc/grafana 8080:3000 &

2. Get the admin credentials:

    echo "User: admin"
    echo "Password: $(kubectl get secret grafana-admin --namespace grafana-monitoring -o jsonpath="{.data.GF_SECURITY_ADMIN_PASSWORD}" | base64 -d)"
# Note: Do not include grafana.validateValues.database here. See https://github.com/bitnami/charts/issues/20629
@rifaterdemsahin ➜ /workspaces/grafana-dashboard/6_Symbols/4.1_DatasourceSetup_StandAlone (main) $ 