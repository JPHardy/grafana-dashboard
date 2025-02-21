[38;5;6mgrafana [38;5;5m17:23:34.63 [0m[38;5;2mINFO [0m ==> 
[38;5;6mgrafana [38;5;5m17:23:34.69 [0m[38;5;2mINFO [0m ==> [1mWelcome to the Bitnami grafana container[0m
[38;5;6mgrafana [38;5;5m17:23:34.69 [0m[38;5;2mINFO [0m ==> Subscribe to project updates by watching [1mhttps://github.com/bitnami/containers[0m
[38;5;6mgrafana [38;5;5m17:23:34.69 [0m[38;5;2mINFO [0m ==> Did you know there are enterprise versions of the Bitnami catalog? For enhanced secure software supply chain features, unlimited pulls from Docker, LTS support, or application customization, see Bitnami Premium or Tanzu Application Catalog. See https://www.arrow.com/globalecs/na/vendors/bitnami/ for more information.
[38;5;6mgrafana [38;5;5m17:23:34.70 [0m[38;5;2mINFO [0m ==> 
[38;5;6mgrafana [38;5;5m17:23:36.18 [0m[38;5;2mINFO [0m ==> ** Grafana setup finished! **

[38;5;6mgrafana [38;5;5m17:23:36.21 [0m[38;5;2mINFO [0m ==> ** Starting Grafana **
Error checking server process execution privilege. error: could not get current OS user to detect process privileges
logger=settings t=2025-01-13T17:23:37.91387594Z level=info msg="Starting Grafana" version=11.3.1 commit=b5870186 branch=HEAD compiled=2024-12-04T21:19:30Z
logger=settings t=2025-01-13T17:23:37.914386171Z level=info msg="Config loaded from" file=/opt/bitnami/grafana/conf/defaults.ini
logger=settings t=2025-01-13T17:23:37.914406589Z level=info msg="Config loaded from" file=/opt/bitnami/grafana/conf/grafana.ini
logger=settings t=2025-01-13T17:23:37.914413031Z level=info msg="Config overridden from command line" arg="default.paths.data=/opt/bitnami/grafana/data"
logger=settings t=2025-01-13T17:23:37.91441803Z level=info msg="Config overridden from command line" arg="default.paths.logs=/opt/bitnami/grafana/logs"
logger=settings t=2025-01-13T17:23:37.91442291Z level=info msg="Config overridden from command line" arg="default.paths.plugins=/opt/bitnami/grafana/data/plugins"
logger=settings t=2025-01-13T17:23:37.914427498Z level=info msg="Config overridden from command line" arg="default.paths.provisioning=/opt/bitnami/grafana/conf/provisioning"
logger=settings t=2025-01-13T17:23:37.914433379Z level=info msg="Config overridden from command line" arg="default.log.mode=console"
logger=settings t=2025-01-13T17:23:37.914438759Z level=info msg="Config overridden from Environment variable" var="GF_PATHS_DATA=/opt/bitnami/grafana/data"
logger=settings t=2025-01-13T17:23:37.914512887Z level=info msg="Config overridden from Environment variable" var="GF_PATHS_LOGS=/opt/bitnami/grafana/logs"
logger=settings t=2025-01-13T17:23:37.914521453Z level=info msg="Config overridden from Environment variable" var="GF_PATHS_PLUGINS=/opt/bitnami/grafana/data/plugins"
logger=settings t=2025-01-13T17:23:37.914527294Z level=info msg="Config overridden from Environment variable" var="GF_PATHS_PROVISIONING=/opt/bitnami/grafana/conf/provisioning"
logger=settings t=2025-01-13T17:23:37.914532554Z level=info msg="Config overridden from Environment variable" var="GF_SECURITY_ADMIN_USER=admin"
logger=settings t=2025-01-13T17:23:37.914537813Z level=info msg="Config overridden from Environment variable" var="GF_SECURITY_ADMIN_PASSWORD=*********"
logger=settings t=2025-01-13T17:23:37.914542933Z level=info msg="Config overridden from Environment variable" var="GF_AUTH_LDAP_ENABLED=false"
logger=settings t=2025-01-13T17:23:37.914549676Z level=info msg="Config overridden from Environment variable" var="GF_AUTH_LDAP_CONFIG_FILE=/opt/bitnami/grafana/conf/ldap.toml"
logger=settings t=2025-01-13T17:23:37.914593187Z level=info msg="Config overridden from Environment variable" var="GF_AUTH_LDAP_ALLOW_SIGN_UP=false"
logger=settings t=2025-01-13T17:23:37.914615518Z level=info msg=Target target=[all]
logger=settings t=2025-01-13T17:23:37.914629455Z level=info msg="Path Home" path=/opt/bitnami/grafana
logger=settings t=2025-01-13T17:23:37.914634865Z level=info msg="Path Data" path=/opt/bitnami/grafana/data
logger=settings t=2025-01-13T17:23:37.914639463Z level=info msg="Path Logs" path=/opt/bitnami/grafana/logs
logger=settings t=2025-01-13T17:23:37.914644753Z level=info msg="Path Plugins" path=/opt/bitnami/grafana/data/plugins
logger=settings t=2025-01-13T17:23:37.914650454Z level=info msg="Path Provisioning" path=/opt/bitnami/grafana/conf/provisioning
logger=settings t=2025-01-13T17:23:37.914656044Z level=info msg="App mode production"
logger=featuremgmt t=2025-01-13T17:23:37.91512061Z level=info msg=FeatureToggles groupToNestedTableTransformation=true promQLScope=true openSearchBackendFlowEnabled=true topnav=true logsInfiniteScrolling=true panelMonitoring=true kubernetesPlaylists=true prometheusConfigOverhaulAuth=true accessControlOnCall=true logsExploreTableVisualisation=true logRowsPopoverMenu=true dashboardScene=true nestedFolders=true publicDashboards=true addFieldFromCalculationStatFunctions=true pinNavItems=true lokiQuerySplitting=true alertingSimplifiedRouting=true alertingInsights=true lokiStructuredMetadata=true transformationsVariableSupport=true dashgpt=true lokiQueryHints=true formatString=true correlations=true autoMigrateXYChartPanel=true annotationPermissionUpdate=true recoveryThreshold=true exploreMetrics=true angularDeprecationUI=true prometheusMetricEncyclopedia=true cloudWatchRoundUpEndTime=true logsContextDatasourceUi=true awsAsyncQueryCaching=true prometheusAzureOverrideAudience=true notificationBanner=true lokiMetricDataplane=true dashboardSceneForViewers=true recordedQueriesMulti=true managedPluginsInstall=true cloudWatchCrossAccountQuerying=true influxdbBackendMigration=true ssoSettingsApi=true transformationsRedesign=true publicDashboardsScene=true tlsMemcached=true dataplaneFrontendFallback=true dashboardSceneSolo=true cloudWatchNewLabelParsing=true alertingNoDataErrorExecution=true
logger=sqlstore t=2025-01-13T17:23:37.915235534Z level=info msg="Connecting to DB" dbtype=sqlite3
logger=sqlstore t=2025-01-13T17:23:37.915255571Z level=info msg="Creating SQLite database file" path=/opt/bitnami/grafana/data/grafana.db
logger=migrator t=2025-01-13T17:23:37.924354222Z level=info msg="Locking database"
logger=migrator t=2025-01-13T17:23:37.924377035Z level=info msg="Starting DB migrations"
logger=migrator t=2025-01-13T17:23:37.924769196Z level=info msg="Executing migration" id="create migration_log table"
logger=migrator t=2025-01-13T17:23:37.9251579Z level=info msg="Migration successfully executed" id="create migration_log table" duration=388.053µs
logger=migrator t=2025-01-13T17:23:37.928805833Z level=info msg="Executing migration" id="create user table"
logger=migrator t=2025-01-13T17:23:37.929268927Z level=info msg="Migration successfully executed" id="create user table" duration=463.253µs
logger=migrator t=2025-01-13T17:23:37.93200678Z level=info msg="Executing migration" id="add unique index user.login"
logger=migrator t=2025-01-13T17:23:37.932359628Z level=info msg="Migration successfully executed" id="add unique index user.login" duration=352.737µs
logger=migrator t=2025-01-13T17:23:37.934687658Z level=info msg="Executing migration" id="add unique index user.email"
logger=migrator t=2025-01-13T17:23:37.935060449Z level=info msg="Migration successfully executed" id="add unique index user.email" duration=381.698µs
logger=migrator t=2025-01-13T17:23:37.938058979Z level=info msg="Executing migration" id="drop index UQE_user_login - v1"
logger=migrator t=2025-01-13T17:23:37.938697058Z level=info msg="Migration successfully executed" id="drop index UQE_user_login - v1" duration=637.569µs
logger=migrator t=2025-01-13T17:23:37.941022065Z level=info msg="Executing migration" id="drop index UQE_user_email - v1"
logger=migrator t=2025-01-13T17:23:37.941345609Z level=info msg="Migration successfully executed" id="drop index UQE_user_email - v1" duration=324.565µs
logger=migrator t=2025-01-13T17:23:37.944217589Z level=info msg="Executing migration" id="Rename table user to user_v1 - v1"
logger=migrator t=2025-01-13T17:23:37.945150818Z level=info msg="Migration successfully executed" id="Rename table user to user_v1 - v1" duration=932.899µs
logger=migrator t=2025-01-13T17:23:37.947295066Z level=info msg="Executing migration" id="create user table v2"
logger=migrator t=2025-01-13T17:23:37.94762458Z level=info msg="Migration successfully executed" id="create user table v2" duration=329.544µs
logger=migrator t=2025-01-13T17:23:37.949521045Z level=info msg="Executing migration" id="create index UQE_user_login - v2"
logger=migrator t=2025-01-13T17:23:37.949882509Z level=info msg="Migration successfully executed" id="create index UQE_user_login - v2" duration=361.754µs
logger=migrator t=2025-01-13T17:23:37.998553335Z level=info msg="Executing migration" id="create index UQE_user_email - v2"
logger=migrator t=2025-01-13T17:23:37.998861519Z level=info msg="Migration successfully executed" id="create index UQE_user_email - v2" duration=308.996µs
logger=migrator t=2025-01-13T17:23:38.002071423Z level=info msg="Executing migration" id="copy data_source v1 to v2"
logger=migrator t=2025-01-13T17:23:38.002291413Z level=info msg="Migration successfully executed" id="copy data_source v1 to v2" duration=220.451µs
logger=migrator t=2025-01-13T17:23:38.004403043Z level=info msg="Executing migration" id="Drop old table user_v1"
logger=migrator t=2025-01-13T17:23:38.004689486Z level=info msg="Migration successfully executed" id="Drop old table user_v1" duration=287.115µs
logger=migrator t=2025-01-13T17:23:38.016872293Z level=info msg="Executing migration" id="Add column help_flags1 to user table"
logger=migrator t=2025-01-13T17:23:38.017193552Z level=info msg="Migration successfully executed" id="Add column help_flags1 to user table" duration=321.389µs
logger=migrator t=2025-01-13T17:23:38.019561496Z level=info msg="Executing migration" id="Update user table charset"
logger=migrator t=2025-01-13T17:23:38.019665259Z level=info msg="Migration successfully executed" id="Update user table charset" duration=104.265µs
logger=migrator t=2025-01-13T17:23:38.021348106Z level=info msg="Executing migration" id="Add last_seen_at column to user"
logger=migrator t=2025-01-13T17:23:38.021651752Z level=info msg="Migration successfully executed" id="Add last_seen_at column to user" duration=303.846µs
logger=migrator t=2025-01-13T17:23:38.023771326Z level=info msg="Executing migration" id="Add missing user data"
logger=migrator t=2025-01-13T17:23:38.023968223Z level=info msg="Migration successfully executed" id="Add missing user data" duration=198.079µs
logger=migrator t=2025-01-13T17:23:38.025636152Z level=info msg="Executing migration" id="Add is_disabled column to user"
logger=migrator t=2025-01-13T17:23:38.025878384Z level=info msg="Migration successfully executed" id="Add is_disabled column to user" duration=242.943µs
logger=migrator t=2025-01-13T17:23:38.027942562Z level=info msg="Executing migration" id="Add index user.login/user.email"
logger=migrator t=2025-01-13T17:23:38.028178562Z level=info msg="Migration successfully executed" id="Add index user.login/user.email" duration=236.731µs
logger=migrator t=2025-01-13T17:23:38.029865296Z level=info msg="Executing migration" id="Add is_service_account column to user"
logger=migrator t=2025-01-13T17:23:38.030114781Z level=info msg="Migration successfully executed" id="Add is_service_account column to user" duration=249.044µs
logger=migrator t=2025-01-13T17:23:38.032263897Z level=info msg="Executing migration" id="Update is_service_account column to nullable"
logger=migrator t=2025-01-13T17:23:38.033609686Z level=info msg="Migration successfully executed" id="Update is_service_account column to nullable" duration=1.345548ms
logger=migrator t=2025-01-13T17:23:38.036273057Z level=info msg="Executing migration" id="Add uid column to user"
logger=migrator t=2025-01-13T17:23:38.036623661Z level=info msg="Migration successfully executed" id="Add uid column to user" duration=351.365µs
logger=migrator t=2025-01-13T17:23:38.039784887Z level=info msg="Executing migration" id="Update uid column values for users"
logger=migrator t=2025-01-13T17:23:38.039982836Z level=info msg="Migration successfully executed" id="Update uid column values for users" duration=198.25µs
logger=migrator t=2025-01-13T17:23:38.044016094Z level=info msg="Executing migration" id="Add unique index user_uid"
logger=migrator t=2025-01-13T17:23:38.044586327Z level=info msg="Migration successfully executed" id="Add unique index user_uid" duration=570.523µs
logger=migrator t=2025-01-13T17:23:38.04735069Z level=info msg="Executing migration" id="update login field with orgid to allow for multiple service accounts with same name across orgs"
logger=migrator t=2025-01-13T17:23:38.047505138Z level=info msg="Migration successfully executed" id="update login field with orgid to allow for multiple service accounts with same name across orgs" duration=154.798µs
logger=migrator t=2025-01-13T17:23:38.049609117Z level=info msg="Executing migration" id="update login and email fields to lowercase"
logger=migrator t=2025-01-13T17:23:38.049859874Z level=info msg="Migration successfully executed" id="update login and email fields to lowercase" duration=250.808µs
logger=migrator t=2025-01-13T17:23:38.052614599Z level=info msg="Executing migration" id="update login and email fields to lowercase2"
logger=migrator t=2025-01-13T17:23:38.052791178Z level=info msg="Migration successfully executed" id="update login and email fields to lowercase2" duration=176.94µs
logger=migrator t=2025-01-13T17:23:38.055637224Z level=info msg="Executing migration" id="create temp user table v1-7"
logger=migrator t=2025-01-13T17:23:38.055900835Z level=info msg="Migration successfully executed" id="create temp user table v1-7" duration=263.562µs
logger=migrator t=2025-01-13T17:23:38.058340847Z level=info msg="Executing migration" id="create index IDX_temp_user_email - v1-7"
logger=migrator t=2025-01-13T17:23:38.058668718Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_email - v1-7" duration=328.752µs
logger=migrator t=2025-01-13T17:23:38.061084177Z level=info msg="Executing migration" id="create index IDX_temp_user_org_id - v1-7"
logger=migrator t=2025-01-13T17:23:38.061378646Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_org_id - v1-7" duration=295.25µs
logger=migrator t=2025-01-13T17:23:38.097349488Z level=info msg="Executing migration" id="create index IDX_temp_user_code - v1-7"
logger=migrator t=2025-01-13T17:23:38.09767207Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_code - v1-7" duration=322.421µs
logger=migrator t=2025-01-13T17:23:38.100767493Z level=info msg="Executing migration" id="create index IDX_temp_user_status - v1-7"
logger=migrator t=2025-01-13T17:23:38.101723665Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_status - v1-7" duration=486.126µs
logger=migrator t=2025-01-13T17:23:38.116420849Z level=info msg="Executing migration" id="Update temp_user table charset"
logger=migrator t=2025-01-13T17:23:38.116444373Z level=info msg="Migration successfully executed" id="Update temp_user table charset" duration=24.165µs
logger=migrator t=2025-01-13T17:23:38.118375405Z level=info msg="Executing migration" id="drop index IDX_temp_user_email - v1"
logger=migrator t=2025-01-13T17:23:38.118924038Z level=info msg="Migration successfully executed" id="drop index IDX_temp_user_email - v1" duration=551.578µs
logger=migrator t=2025-01-13T17:23:38.121418385Z level=info msg="Executing migration" id="drop index IDX_temp_user_org_id - v1"
logger=migrator t=2025-01-13T17:23:38.121697134Z level=info msg="Migration successfully executed" id="drop index IDX_temp_user_org_id - v1" duration=279.391µs
logger=migrator t=2025-01-13T17:23:38.124122375Z level=info msg="Executing migration" id="drop index IDX_temp_user_code - v1"
logger=migrator t=2025-01-13T17:23:38.124421292Z level=info msg="Migration successfully executed" id="drop index IDX_temp_user_code - v1" duration=300.16µs
logger=migrator t=2025-01-13T17:23:38.126334131Z level=info msg="Executing migration" id="drop index IDX_temp_user_status - v1"
logger=migrator t=2025-01-13T17:23:38.126684905Z level=info msg="Migration successfully executed" id="drop index IDX_temp_user_status - v1" duration=351.925µs
logger=migrator t=2025-01-13T17:23:38.129049002Z level=info msg="Executing migration" id="Rename table temp_user to temp_user_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:38.129600971Z level=info msg="Migration successfully executed" id="Rename table temp_user to temp_user_tmp_qwerty - v1" duration=552.39µs
logger=migrator t=2025-01-13T17:23:38.131803487Z level=info msg="Executing migration" id="create temp_user v2"
logger=migrator t=2025-01-13T17:23:38.132092836Z level=info msg="Migration successfully executed" id="create temp_user v2" duration=289.379µs
logger=migrator t=2025-01-13T17:23:38.133954666Z level=info msg="Executing migration" id="create index IDX_temp_user_email - v2"
logger=migrator t=2025-01-13T17:23:38.134233516Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_email - v2" duration=278.079µs
logger=migrator t=2025-01-13T17:23:38.136927779Z level=info msg="Executing migration" id="create index IDX_temp_user_org_id - v2"
logger=migrator t=2025-01-13T17:23:38.137184106Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_org_id - v2" duration=257.16µs
logger=migrator t=2025-01-13T17:23:38.139808335Z level=info msg="Executing migration" id="create index IDX_temp_user_code - v2"
logger=migrator t=2025-01-13T17:23:38.140138841Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_code - v2" duration=331.438µs
logger=migrator t=2025-01-13T17:23:38.14192833Z level=info msg="Executing migration" id="create index IDX_temp_user_status - v2"
logger=migrator t=2025-01-13T17:23:38.142231645Z level=info msg="Migration successfully executed" id="create index IDX_temp_user_status - v2" duration=304.167µs
logger=migrator t=2025-01-13T17:23:38.144678693Z level=info msg="Executing migration" id="copy temp_user v1 to v2"
logger=migrator t=2025-01-13T17:23:38.144926415Z level=info msg="Migration successfully executed" id="copy temp_user v1 to v2" duration=247.391µs
logger=migrator t=2025-01-13T17:23:38.147105641Z level=info msg="Executing migration" id="drop temp_user_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:38.147383088Z level=info msg="Migration successfully executed" id="drop temp_user_tmp_qwerty" duration=278.258µs
logger=migrator t=2025-01-13T17:23:38.149576467Z level=info msg="Executing migration" id="Set created for temp users that will otherwise prematurely expire"
logger=migrator t=2025-01-13T17:23:38.149683446Z level=info msg="Migration successfully executed" id="Set created for temp users that will otherwise prematurely expire" duration=107.36µs
logger=migrator t=2025-01-13T17:23:38.152049496Z level=info msg="Executing migration" id="create star table"
logger=migrator t=2025-01-13T17:23:38.152283192Z level=info msg="Migration successfully executed" id="create star table" duration=234.717µs
logger=migrator t=2025-01-13T17:23:38.153997217Z level=info msg="Executing migration" id="add unique index star.user_id_dashboard_id"
logger=migrator t=2025-01-13T17:23:38.154300519Z level=info msg="Migration successfully executed" id="add unique index star.user_id_dashboard_id" duration=304.194µs
logger=migrator t=2025-01-13T17:23:38.157167934Z level=info msg="Executing migration" id="create org table v1"
logger=migrator t=2025-01-13T17:23:38.157454519Z level=info msg="Migration successfully executed" id="create org table v1" duration=287.737µs
logger=migrator t=2025-01-13T17:23:38.160349796Z level=info msg="Executing migration" id="create index UQE_org_name - v1"
logger=migrator t=2025-01-13T17:23:38.16064708Z level=info msg="Migration successfully executed" id="create index UQE_org_name - v1" duration=298.346µs
logger=migrator t=2025-01-13T17:23:38.164434263Z level=info msg="Executing migration" id="create org_user table v1"
logger=migrator t=2025-01-13T17:23:38.164737979Z level=info msg="Migration successfully executed" id="create org_user table v1" duration=304.458µs
logger=migrator t=2025-01-13T17:23:38.167536796Z level=info msg="Executing migration" id="create index IDX_org_user_org_id - v1"
logger=migrator t=2025-01-13T17:23:38.167758339Z level=info msg="Migration successfully executed" id="create index IDX_org_user_org_id - v1" duration=222.554µs
logger=migrator t=2025-01-13T17:23:38.169921598Z level=info msg="Executing migration" id="create index UQE_org_user_org_id_user_id - v1"
logger=migrator t=2025-01-13T17:23:38.196476899Z level=info msg="Migration successfully executed" id="create index UQE_org_user_org_id_user_id - v1" duration=26.553327ms
logger=migrator t=2025-01-13T17:23:38.216542256Z level=info msg="Executing migration" id="create index IDX_org_user_user_id - v1"
logger=migrator t=2025-01-13T17:23:38.216822378Z level=info msg="Migration successfully executed" id="create index IDX_org_user_user_id - v1" duration=280.132µs
logger=migrator t=2025-01-13T17:23:38.219580186Z level=info msg="Executing migration" id="Update org table charset"
logger=migrator t=2025-01-13T17:23:38.219604711Z level=info msg="Migration successfully executed" id="Update org table charset" duration=25.548µs
logger=migrator t=2025-01-13T17:23:38.221865896Z level=info msg="Executing migration" id="Update org_user table charset"
logger=migrator t=2025-01-13T17:23:38.221892616Z level=info msg="Migration successfully executed" id="Update org_user table charset" duration=27.281µs
logger=migrator t=2025-01-13T17:23:38.224174971Z level=info msg="Executing migration" id="Migrate all Read Only Viewers to Viewers"
logger=migrator t=2025-01-13T17:23:38.22428206Z level=info msg="Migration successfully executed" id="Migrate all Read Only Viewers to Viewers" duration=107.311µs
logger=migrator t=2025-01-13T17:23:38.226006678Z level=info msg="Executing migration" id="create dashboard table"
logger=migrator t=2025-01-13T17:23:38.226299584Z level=info msg="Migration successfully executed" id="create dashboard table" duration=293.387µs
logger=migrator t=2025-01-13T17:23:38.22932992Z level=info msg="Executing migration" id="add index dashboard.account_id"
logger=migrator t=2025-01-13T17:23:38.229638064Z level=info msg="Migration successfully executed" id="add index dashboard.account_id" duration=308.906µs
logger=migrator t=2025-01-13T17:23:38.23249527Z level=info msg="Executing migration" id="add unique index dashboard_account_id_slug"
logger=migrator t=2025-01-13T17:23:38.232755085Z level=info msg="Migration successfully executed" id="add unique index dashboard_account_id_slug" duration=259.644µs
logger=migrator t=2025-01-13T17:23:38.235263811Z level=info msg="Executing migration" id="create dashboard_tag table"
logger=migrator t=2025-01-13T17:23:38.235496355Z level=info msg="Migration successfully executed" id="create dashboard_tag table" duration=232.583µs
logger=migrator t=2025-01-13T17:23:38.23799391Z level=info msg="Executing migration" id="add unique index dashboard_tag.dasboard_id_term"
logger=migrator t=2025-01-13T17:23:38.23827267Z level=info msg="Migration successfully executed" id="add unique index dashboard_tag.dasboard_id_term" duration=279.27µs
logger=migrator t=2025-01-13T17:23:38.240794801Z level=info msg="Executing migration" id="drop index UQE_dashboard_tag_dashboard_id_term - v1"
logger=migrator t=2025-01-13T17:23:38.241103527Z level=info msg="Migration successfully executed" id="drop index UQE_dashboard_tag_dashboard_id_term - v1" duration=309.537µs
logger=migrator t=2025-01-13T17:23:38.243511956Z level=info msg="Executing migration" id="Rename table dashboard to dashboard_v1 - v1"
logger=migrator t=2025-01-13T17:23:38.244093741Z level=info msg="Migration successfully executed" id="Rename table dashboard to dashboard_v1 - v1" duration=581.795µs
logger=migrator t=2025-01-13T17:23:38.246126864Z level=info msg="Executing migration" id="create dashboard v2"
logger=migrator t=2025-01-13T17:23:38.246420722Z level=info msg="Migration successfully executed" id="create dashboard v2" duration=294.94µs
logger=migrator t=2025-01-13T17:23:38.249599487Z level=info msg="Executing migration" id="create index IDX_dashboard_org_id - v2"
logger=migrator t=2025-01-13T17:23:38.251368291Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_org_id - v2" duration=1.769776ms
logger=migrator t=2025-01-13T17:23:38.254074836Z level=info msg="Executing migration" id="create index UQE_dashboard_org_id_slug - v2"
logger=migrator t=2025-01-13T17:23:38.254381428Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_org_id_slug - v2" duration=307.844µs
logger=migrator t=2025-01-13T17:23:38.256861791Z level=info msg="Executing migration" id="copy dashboard v1 to v2"
logger=migrator t=2025-01-13T17:23:38.257023843Z level=info msg="Migration successfully executed" id="copy dashboard v1 to v2" duration=162.343µs
logger=migrator t=2025-01-13T17:23:38.258712411Z level=info msg="Executing migration" id="drop table dashboard_v1"
logger=migrator t=2025-01-13T17:23:38.258999767Z level=info msg="Migration successfully executed" id="drop table dashboard_v1" duration=288.117µs
logger=migrator t=2025-01-13T17:23:38.261666381Z level=info msg="Executing migration" id="alter dashboard.data to mediumtext v1"
logger=migrator t=2025-01-13T17:23:38.2617786Z level=info msg="Migration successfully executed" id="alter dashboard.data to mediumtext v1" duration=113.01µs
logger=migrator t=2025-01-13T17:23:38.264287804Z level=info msg="Executing migration" id="Add column updated_by in dashboard - v2"
logger=migrator t=2025-01-13T17:23:38.264676759Z level=info msg="Migration successfully executed" id="Add column updated_by in dashboard - v2" duration=389.296µs
logger=migrator t=2025-01-13T17:23:38.266426544Z level=info msg="Executing migration" id="Add column created_by in dashboard - v2"
logger=migrator t=2025-01-13T17:23:38.267058001Z level=info msg="Migration successfully executed" id="Add column created_by in dashboard - v2" duration=628.982µs
logger=migrator t=2025-01-13T17:23:38.298643519Z level=info msg="Executing migration" id="Add column gnetId in dashboard"
logger=migrator t=2025-01-13T17:23:38.299081455Z level=info msg="Migration successfully executed" id="Add column gnetId in dashboard" duration=437.816µs
logger=migrator t=2025-01-13T17:23:38.301472603Z level=info msg="Executing migration" id="Add index for gnetId in dashboard"
logger=migrator t=2025-01-13T17:23:38.301757273Z level=info msg="Migration successfully executed" id="Add index for gnetId in dashboard" duration=284.84µs
logger=migrator t=2025-01-13T17:23:38.304182364Z level=info msg="Executing migration" id="Add column plugin_id in dashboard"
logger=migrator t=2025-01-13T17:23:38.304647481Z level=info msg="Migration successfully executed" id="Add column plugin_id in dashboard" duration=465.447µs
logger=migrator t=2025-01-13T17:23:38.316469538Z level=info msg="Executing migration" id="Add index for plugin_id in dashboard"
logger=migrator t=2025-01-13T17:23:38.316844366Z level=info msg="Migration successfully executed" id="Add index for plugin_id in dashboard" duration=375.67µs
logger=migrator t=2025-01-13T17:23:38.318896352Z level=info msg="Executing migration" id="Add index for dashboard_id in dashboard_tag"
logger=migrator t=2025-01-13T17:23:38.319215897Z level=info msg="Migration successfully executed" id="Add index for dashboard_id in dashboard_tag" duration=319.916µs
logger=migrator t=2025-01-13T17:23:38.321935464Z level=info msg="Executing migration" id="Update dashboard table charset"
logger=migrator t=2025-01-13T17:23:38.322040099Z level=info msg="Migration successfully executed" id="Update dashboard table charset" duration=106.268µs
logger=migrator t=2025-01-13T17:23:38.324309402Z level=info msg="Executing migration" id="Update dashboard_tag table charset"
logger=migrator t=2025-01-13T17:23:38.324387287Z level=info msg="Migration successfully executed" id="Update dashboard_tag table charset" duration=78.607µs
logger=migrator t=2025-01-13T17:23:38.326105346Z level=info msg="Executing migration" id="Add column folder_id in dashboard"
logger=migrator t=2025-01-13T17:23:38.326524338Z level=info msg="Migration successfully executed" id="Add column folder_id in dashboard" duration=419.752µs
logger=migrator t=2025-01-13T17:23:38.328737526Z level=info msg="Executing migration" id="Add column isFolder in dashboard"
logger=migrator t=2025-01-13T17:23:38.329103629Z level=info msg="Migration successfully executed" id="Add column isFolder in dashboard" duration=366.974µs
logger=migrator t=2025-01-13T17:23:38.331399919Z level=info msg="Executing migration" id="Add column has_acl in dashboard"
logger=migrator t=2025-01-13T17:23:38.331736958Z level=info msg="Migration successfully executed" id="Add column has_acl in dashboard" duration=337.769µs
logger=migrator t=2025-01-13T17:23:38.333466592Z level=info msg="Executing migration" id="Add column uid in dashboard"
logger=migrator t=2025-01-13T17:23:38.333779094Z level=info msg="Migration successfully executed" id="Add column uid in dashboard" duration=313.123µs
logger=migrator t=2025-01-13T17:23:38.336014999Z level=info msg="Executing migration" id="Update uid column values in dashboard"
logger=migrator t=2025-01-13T17:23:38.336163816Z level=info msg="Migration successfully executed" id="Update uid column values in dashboard" duration=149.92µs
logger=migrator t=2025-01-13T17:23:38.337873066Z level=info msg="Executing migration" id="Add unique index dashboard_org_id_uid"
logger=migrator t=2025-01-13T17:23:38.338209413Z level=info msg="Migration successfully executed" id="Add unique index dashboard_org_id_uid" duration=337.309µs
logger=migrator t=2025-01-13T17:23:38.34101521Z level=info msg="Executing migration" id="Remove unique index org_id_slug"
logger=migrator t=2025-01-13T17:23:38.341325217Z level=info msg="Migration successfully executed" id="Remove unique index org_id_slug" duration=311.05µs
logger=migrator t=2025-01-13T17:23:38.344386006Z level=info msg="Executing migration" id="Update dashboard title length"
logger=migrator t=2025-01-13T17:23:38.344565801Z level=info msg="Migration successfully executed" id="Update dashboard title length" duration=180.356µs
logger=migrator t=2025-01-13T17:23:38.34671814Z level=info msg="Executing migration" id="Add unique index for dashboard_org_id_title_folder_id"
logger=migrator t=2025-01-13T17:23:38.347055109Z level=info msg="Migration successfully executed" id="Add unique index for dashboard_org_id_title_folder_id" duration=335.836µs
logger=migrator t=2025-01-13T17:23:38.349643133Z level=info msg="Executing migration" id="create dashboard_provisioning"
logger=migrator t=2025-01-13T17:23:38.349902666Z level=info msg="Migration successfully executed" id="create dashboard_provisioning" duration=262.159µs
logger=migrator t=2025-01-13T17:23:38.352417935Z level=info msg="Executing migration" id="Rename table dashboard_provisioning to dashboard_provisioning_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:38.353457526Z level=info msg="Migration successfully executed" id="Rename table dashboard_provisioning to dashboard_provisioning_tmp_qwerty - v1" duration=1.03882ms
logger=migrator t=2025-01-13T17:23:38.356128722Z level=info msg="Executing migration" id="create dashboard_provisioning v2"
logger=migrator t=2025-01-13T17:23:38.35642268Z level=info msg="Migration successfully executed" id="create dashboard_provisioning v2" duration=294.81µs
logger=migrator t=2025-01-13T17:23:38.35910869Z level=info msg="Executing migration" id="create index IDX_dashboard_provisioning_dashboard_id - v2"
logger=migrator t=2025-01-13T17:23:38.359440118Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_provisioning_dashboard_id - v2" duration=332.48µs
logger=migrator t=2025-01-13T17:23:38.397542Z level=info msg="Executing migration" id="create index IDX_dashboard_provisioning_dashboard_id_name - v2"
logger=migrator t=2025-01-13T17:23:38.397888689Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_provisioning_dashboard_id_name - v2" duration=347.29µs
logger=migrator t=2025-01-13T17:23:38.400775661Z level=info msg="Executing migration" id="copy dashboard_provisioning v1 to v2"
logger=migrator t=2025-01-13T17:23:38.400962048Z level=info msg="Migration successfully executed" id="copy dashboard_provisioning v1 to v2" duration=186.949µs
logger=migrator t=2025-01-13T17:23:38.41418852Z level=info msg="Executing migration" id="drop dashboard_provisioning_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:38.414879832Z level=info msg="Migration successfully executed" id="drop dashboard_provisioning_tmp_qwerty" duration=691.673µs
logger=migrator t=2025-01-13T17:23:38.417818647Z level=info msg="Executing migration" id="Add check_sum column"
logger=migrator t=2025-01-13T17:23:38.418255291Z level=info msg="Migration successfully executed" id="Add check_sum column" duration=437.345µs
logger=migrator t=2025-01-13T17:23:38.420762665Z level=info msg="Executing migration" id="Add index for dashboard_title"
logger=migrator t=2025-01-13T17:23:38.421061582Z level=info msg="Migration successfully executed" id="Add index for dashboard_title" duration=299.97µs
logger=migrator t=2025-01-13T17:23:38.423476156Z level=info msg="Executing migration" id="delete tags for deleted dashboards"
logger=migrator t=2025-01-13T17:23:38.423624673Z level=info msg="Migration successfully executed" id="delete tags for deleted dashboards" duration=149.85µs
logger=migrator t=2025-01-13T17:23:38.425377708Z level=info msg="Executing migration" id="delete stars for deleted dashboards"
logger=migrator t=2025-01-13T17:23:38.425521957Z level=info msg="Migration successfully executed" id="delete stars for deleted dashboards" duration=144.71µs
logger=migrator t=2025-01-13T17:23:38.427931902Z level=info msg="Executing migration" id="Add index for dashboard_is_folder"
logger=migrator t=2025-01-13T17:23:38.428219979Z level=info msg="Migration successfully executed" id="Add index for dashboard_is_folder" duration=289.039µs
logger=migrator t=2025-01-13T17:23:38.430835815Z level=info msg="Executing migration" id="Add isPublic for dashboard"
logger=migrator t=2025-01-13T17:23:38.431215914Z level=info msg="Migration successfully executed" id="Add isPublic for dashboard" duration=380.56µs
logger=migrator t=2025-01-13T17:23:38.433598355Z level=info msg="Executing migration" id="Add deleted for dashboard"
logger=migrator t=2025-01-13T17:23:38.433973985Z level=info msg="Migration successfully executed" id="Add deleted for dashboard" duration=375.861µs
logger=migrator t=2025-01-13T17:23:38.44027474Z level=info msg="Executing migration" id="Add index for deleted"
logger=migrator t=2025-01-13T17:23:38.442411363Z level=info msg="Migration successfully executed" id="Add index for deleted" duration=2.136252ms
logger=migrator t=2025-01-13T17:23:38.448392579Z level=info msg="Executing migration" id="create data_source table"
logger=migrator t=2025-01-13T17:23:38.448727694Z level=info msg="Migration successfully executed" id="create data_source table" duration=335.695µs
logger=migrator t=2025-01-13T17:23:38.452015042Z level=info msg="Executing migration" id="add index data_source.account_id"
logger=migrator t=2025-01-13T17:23:38.452400841Z level=info msg="Migration successfully executed" id="add index data_source.account_id" duration=385.709µs
logger=migrator t=2025-01-13T17:23:38.45502349Z level=info msg="Executing migration" id="add unique index data_source.account_id_name"
logger=migrator t=2025-01-13T17:23:38.455432913Z level=info msg="Migration successfully executed" id="add unique index data_source.account_id_name" duration=409.343µs
logger=migrator t=2025-01-13T17:23:38.457947049Z level=info msg="Executing migration" id="drop index IDX_data_source_account_id - v1"
logger=migrator t=2025-01-13T17:23:38.458378774Z level=info msg="Migration successfully executed" id="drop index IDX_data_source_account_id - v1" duration=431.554µs
logger=migrator t=2025-01-13T17:23:38.460859979Z level=info msg="Executing migration" id="drop index UQE_data_source_account_id_name - v1"
logger=migrator t=2025-01-13T17:23:38.461352076Z level=info msg="Migration successfully executed" id="drop index UQE_data_source_account_id_name - v1" duration=491.927µs
logger=migrator t=2025-01-13T17:23:38.463942796Z level=info msg="Executing migration" id="Rename table data_source to data_source_v1 - v1"
logger=migrator t=2025-01-13T17:23:38.465679253Z level=info msg="Migration successfully executed" id="Rename table data_source to data_source_v1 - v1" duration=1.735796ms
logger=migrator t=2025-01-13T17:23:38.468918211Z level=info msg="Executing migration" id="create data_source table v2"
logger=migrator t=2025-01-13T17:23:38.469450593Z level=info msg="Migration successfully executed" id="create data_source table v2" duration=532.824µs
logger=migrator t=2025-01-13T17:23:38.497324121Z level=info msg="Executing migration" id="create index IDX_data_source_org_id - v2"
logger=migrator t=2025-01-13T17:23:38.497665671Z level=info msg="Migration successfully executed" id="create index IDX_data_source_org_id - v2" duration=342.151µs
logger=migrator t=2025-01-13T17:23:38.51671633Z level=info msg="Executing migration" id="create index UQE_data_source_org_id_name - v2"
logger=migrator t=2025-01-13T17:23:38.517079016Z level=info msg="Migration successfully executed" id="create index UQE_data_source_org_id_name - v2" duration=362.466µs
logger=migrator t=2025-01-13T17:23:38.519718295Z level=info msg="Executing migration" id="Drop old table data_source_v1 #2"
logger=migrator t=2025-01-13T17:23:38.519948254Z level=info msg="Migration successfully executed" id="Drop old table data_source_v1 #2" duration=230.63µs
logger=migrator t=2025-01-13T17:23:38.522914066Z level=info msg="Executing migration" id="Add column with_credentials"
logger=migrator t=2025-01-13T17:23:38.523548699Z level=info msg="Migration successfully executed" id="Add column with_credentials" duration=634.383µs
logger=migrator t=2025-01-13T17:23:38.52886019Z level=info msg="Executing migration" id="Add secure json data column"
logger=migrator t=2025-01-13T17:23:38.529315689Z level=info msg="Migration successfully executed" id="Add secure json data column" duration=455.74µs
logger=migrator t=2025-01-13T17:23:38.532003707Z level=info msg="Executing migration" id="Update data_source table charset"
logger=migrator t=2025-01-13T17:23:38.532099385Z level=info msg="Migration successfully executed" id="Update data_source table charset" duration=98.584µs
logger=migrator t=2025-01-13T17:23:38.534006664Z level=info msg="Executing migration" id="Update initial version to 1"
logger=migrator t=2025-01-13T17:23:38.534149309Z level=info msg="Migration successfully executed" id="Update initial version to 1" duration=143.067µs
logger=migrator t=2025-01-13T17:23:38.536435691Z level=info msg="Executing migration" id="Add read_only data column"
logger=migrator t=2025-01-13T17:23:38.536787096Z level=info msg="Migration successfully executed" id="Add read_only data column" duration=351.695µs
logger=migrator t=2025-01-13T17:23:38.538659597Z level=info msg="Executing migration" id="Migrate logging ds to loki ds"
logger=migrator t=2025-01-13T17:23:38.538810538Z level=info msg="Migration successfully executed" id="Migrate logging ds to loki ds" duration=151.833µs
logger=migrator t=2025-01-13T17:23:38.541394966Z level=info msg="Executing migration" id="Update json_data with nulls"
logger=migrator t=2025-01-13T17:23:38.541492758Z level=info msg="Migration successfully executed" id="Update json_data with nulls" duration=98.363µs
logger=migrator t=2025-01-13T17:23:38.54379153Z level=info msg="Executing migration" id="Add uid column"
logger=migrator t=2025-01-13T17:23:38.544195553Z level=info msg="Migration successfully executed" id="Add uid column" duration=405.005µs
logger=migrator t=2025-01-13T17:23:38.545992002Z level=info msg="Executing migration" id="Update uid value"
logger=migrator t=2025-01-13T17:23:38.546135159Z level=info msg="Migration successfully executed" id="Update uid value" duration=143.748µs
logger=migrator t=2025-01-13T17:23:38.548315443Z level=info msg="Executing migration" id="Add unique index datasource_org_id_uid"
logger=migrator t=2025-01-13T17:23:38.548581609Z level=info msg="Migration successfully executed" id="Add unique index datasource_org_id_uid" duration=266.667µs
logger=migrator t=2025-01-13T17:23:38.550377116Z level=info msg="Executing migration" id="add unique index datasource_org_id_is_default"
logger=migrator t=2025-01-13T17:23:38.550667507Z level=info msg="Migration successfully executed" id="add unique index datasource_org_id_is_default" duration=291.172µs
logger=migrator t=2025-01-13T17:23:38.553294183Z level=info msg="Executing migration" id="Add is_prunable column"
logger=migrator t=2025-01-13T17:23:38.553702865Z level=info msg="Migration successfully executed" id="Add is_prunable column" duration=409.473µs
logger=migrator t=2025-01-13T17:23:38.556488528Z level=info msg="Executing migration" id="Add api_version column"
logger=migrator t=2025-01-13T17:23:38.556869959Z level=info msg="Migration successfully executed" id="Add api_version column" duration=382.032µs
logger=migrator t=2025-01-13T17:23:38.558890098Z level=info msg="Executing migration" id="create api_key table"
logger=migrator t=2025-01-13T17:23:38.559244068Z level=info msg="Migration successfully executed" id="create api_key table" duration=353.839µs
logger=migrator t=2025-01-13T17:23:38.562273872Z level=info msg="Executing migration" id="add index api_key.account_id"
logger=migrator t=2025-01-13T17:23:38.56259426Z level=info msg="Migration successfully executed" id="add index api_key.account_id" duration=320.898µs
logger=migrator t=2025-01-13T17:23:38.565179369Z level=info msg="Executing migration" id="add index api_key.key"
logger=migrator t=2025-01-13T17:23:38.565573573Z level=info msg="Migration successfully executed" id="add index api_key.key" duration=394.466µs
logger=migrator t=2025-01-13T17:23:38.568373105Z level=info msg="Executing migration" id="add index api_key.account_id_name"
logger=migrator t=2025-01-13T17:23:38.568687331Z level=info msg="Migration successfully executed" id="add index api_key.account_id_name" duration=315.267µs
logger=migrator t=2025-01-13T17:23:38.571262461Z level=info msg="Executing migration" id="drop index IDX_api_key_account_id - v1"
logger=migrator t=2025-01-13T17:23:38.596857933Z level=info msg="Migration successfully executed" id="drop index IDX_api_key_account_id - v1" duration=25.595ms
logger=migrator t=2025-01-13T17:23:38.615565352Z level=info msg="Executing migration" id="drop index UQE_api_key_key - v1"
logger=migrator t=2025-01-13T17:23:38.616063854Z level=info msg="Migration successfully executed" id="drop index UQE_api_key_key - v1" duration=498.492µs
logger=migrator t=2025-01-13T17:23:38.618028684Z level=info msg="Executing migration" id="drop index UQE_api_key_account_id_name - v1"
logger=migrator t=2025-01-13T17:23:38.618386581Z level=info msg="Migration successfully executed" id="drop index UQE_api_key_account_id_name - v1" duration=357.977µs
logger=migrator t=2025-01-13T17:23:38.621131708Z level=info msg="Executing migration" id="Rename table api_key to api_key_v1 - v1"
logger=migrator t=2025-01-13T17:23:38.622037927Z level=info msg="Migration successfully executed" id="Rename table api_key to api_key_v1 - v1" duration=908.674µs
logger=migrator t=2025-01-13T17:23:38.624361682Z level=info msg="Executing migration" id="create api_key table v2"
logger=migrator t=2025-01-13T17:23:38.624664226Z level=info msg="Migration successfully executed" id="create api_key table v2" duration=302.885µs
logger=migrator t=2025-01-13T17:23:38.626568185Z level=info msg="Executing migration" id="create index IDX_api_key_org_id - v2"
logger=migrator t=2025-01-13T17:23:38.626980494Z level=info msg="Migration successfully executed" id="create index IDX_api_key_org_id - v2" duration=415.684µs
logger=migrator t=2025-01-13T17:23:38.630473926Z level=info msg="Executing migration" id="create index UQE_api_key_key - v2"
logger=migrator t=2025-01-13T17:23:38.630829128Z level=info msg="Migration successfully executed" id="create index UQE_api_key_key - v2" duration=355.192µs
logger=migrator t=2025-01-13T17:23:38.633881177Z level=info msg="Executing migration" id="create index UQE_api_key_org_id_name - v2"
logger=migrator t=2025-01-13T17:23:38.634208697Z level=info msg="Migration successfully executed" id="create index UQE_api_key_org_id_name - v2" duration=327.3µs
logger=migrator t=2025-01-13T17:23:38.638956034Z level=info msg="Executing migration" id="copy api_key v1 to v2"
logger=migrator t=2025-01-13T17:23:38.639315564Z level=info msg="Migration successfully executed" id="copy api_key v1 to v2" duration=359.3µs
logger=migrator t=2025-01-13T17:23:38.642000118Z level=info msg="Executing migration" id="Drop old table api_key_v1"
logger=migrator t=2025-01-13T17:23:38.642353517Z level=info msg="Migration successfully executed" id="Drop old table api_key_v1" duration=348.821µs
logger=migrator t=2025-01-13T17:23:38.64474605Z level=info msg="Executing migration" id="Update api_key table charset"
logger=migrator t=2025-01-13T17:23:38.644770826Z level=info msg="Migration successfully executed" id="Update api_key table charset" duration=25.498µs
logger=migrator t=2025-01-13T17:23:38.646356392Z level=info msg="Executing migration" id="Add expires to api_key table"
logger=migrator t=2025-01-13T17:23:38.646871392Z level=info msg="Migration successfully executed" id="Add expires to api_key table" duration=515.471µs
logger=migrator t=2025-01-13T17:23:38.648934778Z level=info msg="Executing migration" id="Add service account foreign key"
logger=migrator t=2025-01-13T17:23:38.64938636Z level=info msg="Migration successfully executed" id="Add service account foreign key" duration=452.444µs
logger=migrator t=2025-01-13T17:23:38.651541784Z level=info msg="Executing migration" id="set service account foreign key to nil if 0"
logger=migrator t=2025-01-13T17:23:38.651659477Z level=info msg="Migration successfully executed" id="set service account foreign key to nil if 0" duration=115.969µs
logger=migrator t=2025-01-13T17:23:38.65310559Z level=info msg="Executing migration" id="Add last_used_at to api_key table"
logger=migrator t=2025-01-13T17:23:38.653474951Z level=info msg="Migration successfully executed" id="Add last_used_at to api_key table" duration=370.144µs
logger=migrator t=2025-01-13T17:23:38.655588378Z level=info msg="Executing migration" id="Add is_revoked column to api_key table"
logger=migrator t=2025-01-13T17:23:38.656014893Z level=info msg="Migration successfully executed" id="Add is_revoked column to api_key table" duration=425.834µs
logger=migrator t=2025-01-13T17:23:38.657682434Z level=info msg="Executing migration" id="create dashboard_snapshot table v4"
logger=migrator t=2025-01-13T17:23:38.657927101Z level=info msg="Migration successfully executed" id="create dashboard_snapshot table v4" duration=245.508µs
logger=migrator t=2025-01-13T17:23:38.660262744Z level=info msg="Executing migration" id="drop table dashboard_snapshot_v4 #1"
logger=migrator t=2025-01-13T17:23:38.660527438Z level=info msg="Migration successfully executed" id="drop table dashboard_snapshot_v4 #1" duration=265.735µs
logger=migrator t=2025-01-13T17:23:38.698556146Z level=info msg="Executing migration" id="create dashboard_snapshot table v5 #2"
logger=migrator t=2025-01-13T17:23:38.698813606Z level=info msg="Migration successfully executed" id="create dashboard_snapshot table v5 #2" duration=257.821µs
logger=migrator t=2025-01-13T17:23:38.701750217Z level=info msg="Executing migration" id="create index UQE_dashboard_snapshot_key - v5"
logger=migrator t=2025-01-13T17:23:38.702140003Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_snapshot_key - v5" duration=390.749µs
logger=migrator t=2025-01-13T17:23:38.716609415Z level=info msg="Executing migration" id="create index UQE_dashboard_snapshot_delete_key - v5"
logger=migrator t=2025-01-13T17:23:38.719690469Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_snapshot_delete_key - v5" duration=3.065845ms
logger=migrator t=2025-01-13T17:23:38.722221727Z level=info msg="Executing migration" id="create index IDX_dashboard_snapshot_user_id - v5"
logger=migrator t=2025-01-13T17:23:38.722616987Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_snapshot_user_id - v5" duration=396.132µs
logger=migrator t=2025-01-13T17:23:38.725085579Z level=info msg="Executing migration" id="alter dashboard_snapshot to mediumtext v2"
logger=migrator t=2025-01-13T17:23:38.725156702Z level=info msg="Migration successfully executed" id="alter dashboard_snapshot to mediumtext v2" duration=71.754µs
logger=migrator t=2025-01-13T17:23:38.727598173Z level=info msg="Executing migration" id="Update dashboard_snapshot table charset"
logger=migrator t=2025-01-13T17:23:38.727658695Z level=info msg="Migration successfully executed" id="Update dashboard_snapshot table charset" duration=61.816µs
logger=migrator t=2025-01-13T17:23:38.729331951Z level=info msg="Executing migration" id="Add column external_delete_url to dashboard_snapshots table"
logger=migrator t=2025-01-13T17:23:38.729779065Z level=info msg="Migration successfully executed" id="Add column external_delete_url to dashboard_snapshots table" duration=447.835µs
logger=migrator t=2025-01-13T17:23:38.732318508Z level=info msg="Executing migration" id="Add encrypted dashboard json column"
logger=migrator t=2025-01-13T17:23:38.732741677Z level=info msg="Migration successfully executed" id="Add encrypted dashboard json column" duration=423.98µs
logger=migrator t=2025-01-13T17:23:38.734565731Z level=info msg="Executing migration" id="Change dashboard_encrypted column to MEDIUMBLOB"
logger=migrator t=2025-01-13T17:23:38.734700422Z level=info msg="Migration successfully executed" id="Change dashboard_encrypted column to MEDIUMBLOB" duration=135.894µs
logger=migrator t=2025-01-13T17:23:38.737276784Z level=info msg="Executing migration" id="create quota table v1"
logger=migrator t=2025-01-13T17:23:38.737506332Z level=info msg="Migration successfully executed" id="create quota table v1" duration=230.239µs
logger=migrator t=2025-01-13T17:23:38.740303754Z level=info msg="Executing migration" id="create index UQE_quota_org_id_user_id_target - v1"
logger=migrator t=2025-01-13T17:23:38.7406504Z level=info msg="Migration successfully executed" id="create index UQE_quota_org_id_user_id_target - v1" duration=347.217µs
logger=migrator t=2025-01-13T17:23:38.743482749Z level=info msg="Executing migration" id="Update quota table charset"
logger=migrator t=2025-01-13T17:23:38.743618402Z level=info msg="Migration successfully executed" id="Update quota table charset" duration=136.715µs
logger=migrator t=2025-01-13T17:23:38.74574145Z level=info msg="Executing migration" id="create plugin_setting table"
logger=migrator t=2025-01-13T17:23:38.746025209Z level=info msg="Migration successfully executed" id="create plugin_setting table" duration=284.611µs
logger=migrator t=2025-01-13T17:23:38.748673088Z level=info msg="Executing migration" id="create index UQE_plugin_setting_org_id_plugin_id - v1"
logger=migrator t=2025-01-13T17:23:38.749060089Z level=info msg="Migration successfully executed" id="create index UQE_plugin_setting_org_id_plugin_id - v1" duration=387.753µs
logger=migrator t=2025-01-13T17:23:38.751877842Z level=info msg="Executing migration" id="Add column plugin_version to plugin_settings"
logger=migrator t=2025-01-13T17:23:38.752314406Z level=info msg="Migration successfully executed" id="Add column plugin_version to plugin_settings" duration=437.416µs
logger=migrator t=2025-01-13T17:23:38.754096307Z level=info msg="Executing migration" id="Update plugin_setting table charset"
logger=migrator t=2025-01-13T17:23:38.754156629Z level=info msg="Migration successfully executed" id="Update plugin_setting table charset" duration=61.254µs
logger=migrator t=2025-01-13T17:23:38.756338704Z level=info msg="Executing migration" id="create session table"
logger=migrator t=2025-01-13T17:23:38.756611072Z level=info msg="Migration successfully executed" id="create session table" duration=274.552µs
logger=migrator t=2025-01-13T17:23:38.759211322Z level=info msg="Executing migration" id="Drop old table playlist table"
logger=migrator t=2025-01-13T17:23:38.759311248Z level=info msg="Migration successfully executed" id="Drop old table playlist table" duration=100.838µs
logger=migrator t=2025-01-13T17:23:38.761313878Z level=info msg="Executing migration" id="Drop old table playlist_item table"
logger=migrator t=2025-01-13T17:23:38.761454971Z level=info msg="Migration successfully executed" id="Drop old table playlist_item table" duration=141.695µs
logger=migrator t=2025-01-13T17:23:38.763674308Z level=info msg="Executing migration" id="create playlist table v2"
logger=migrator t=2025-01-13T17:23:38.763917351Z level=info msg="Migration successfully executed" id="create playlist table v2" duration=241.179µs
logger=migrator t=2025-01-13T17:23:38.766610191Z level=info msg="Executing migration" id="create playlist item table v2"
logger=migrator t=2025-01-13T17:23:38.766853294Z level=info msg="Migration successfully executed" id="create playlist item table v2" duration=243.814µs
logger=migrator t=2025-01-13T17:23:38.824721127Z level=info msg="Executing migration" id="Update playlist table charset"
logger=migrator t=2025-01-13T17:23:38.824768886Z level=info msg="Migration successfully executed" id="Update playlist table charset" duration=54.963µs
logger=migrator t=2025-01-13T17:23:38.826784243Z level=info msg="Executing migration" id="Update playlist_item table charset"
logger=migrator t=2025-01-13T17:23:38.826816513Z level=info msg="Migration successfully executed" id="Update playlist_item table charset" duration=32.691µs
logger=migrator t=2025-01-13T17:23:38.829163839Z level=info msg="Executing migration" id="Add playlist column created_at"
logger=migrator t=2025-01-13T17:23:38.829802028Z level=info msg="Migration successfully executed" id="Add playlist column created_at" duration=638.641µs
logger=migrator t=2025-01-13T17:23:38.832768635Z level=info msg="Executing migration" id="Add playlist column updated_at"
logger=migrator t=2025-01-13T17:23:38.833371529Z level=info msg="Migration successfully executed" id="Add playlist column updated_at" duration=603.225µs
logger=migrator t=2025-01-13T17:23:38.836308397Z level=info msg="Executing migration" id="drop preferences table v2"
logger=migrator t=2025-01-13T17:23:38.836425675Z level=info msg="Migration successfully executed" id="drop preferences table v2" duration=117.75µs
logger=migrator t=2025-01-13T17:23:38.838394936Z level=info msg="Executing migration" id="drop preferences table v3"
logger=migrator t=2025-01-13T17:23:38.838507556Z level=info msg="Migration successfully executed" id="drop preferences table v3" duration=113.381µs
logger=migrator t=2025-01-13T17:23:38.840754571Z level=info msg="Executing migration" id="create preferences table v3"
logger=migrator t=2025-01-13T17:23:38.841069769Z level=info msg="Migration successfully executed" id="create preferences table v3" duration=316.67µs
logger=migrator t=2025-01-13T17:23:38.843755976Z level=info msg="Executing migration" id="Update preferences table charset"
logger=migrator t=2025-01-13T17:23:38.843857826Z level=info msg="Migration successfully executed" id="Update preferences table charset" duration=103.232µs
logger=migrator t=2025-01-13T17:23:38.845604522Z level=info msg="Executing migration" id="Add column team_id in preferences"
logger=migrator t=2025-01-13T17:23:38.846060672Z level=info msg="Migration successfully executed" id="Add column team_id in preferences" duration=457.233µs
logger=migrator t=2025-01-13T17:23:38.848367633Z level=info msg="Executing migration" id="Update team_id column values in preferences"
logger=migrator t=2025-01-13T17:23:38.848459344Z level=info msg="Migration successfully executed" id="Update team_id column values in preferences" duration=92.082µs
logger=migrator t=2025-01-13T17:23:38.850109764Z level=info msg="Executing migration" id="Add column week_start in preferences"
logger=migrator t=2025-01-13T17:23:38.850604916Z level=info msg="Migration successfully executed" id="Add column week_start in preferences" duration=496.015µs
logger=migrator t=2025-01-13T17:23:38.852800055Z level=info msg="Executing migration" id="Add column preferences.json_data"
logger=migrator t=2025-01-13T17:23:38.853280721Z level=info msg="Migration successfully executed" id="Add column preferences.json_data" duration=480.606µs
logger=migrator t=2025-01-13T17:23:38.855677629Z level=info msg="Executing migration" id="alter preferences.json_data to mediumtext v1"
logger=migrator t=2025-01-13T17:23:38.855786903Z level=info msg="Migration successfully executed" id="alter preferences.json_data to mediumtext v1" duration=109.674µs
logger=migrator t=2025-01-13T17:23:38.8574952Z level=info msg="Executing migration" id="Add preferences index org_id"
logger=migrator t=2025-01-13T17:23:38.857788758Z level=info msg="Migration successfully executed" id="Add preferences index org_id" duration=293.227µs
logger=migrator t=2025-01-13T17:23:38.860961879Z level=info msg="Executing migration" id="Add preferences index user_id"
logger=migrator t=2025-01-13T17:23:38.861280383Z level=info msg="Migration successfully executed" id="Add preferences index user_id" duration=319.124µs
logger=migrator t=2025-01-13T17:23:38.864309342Z level=info msg="Executing migration" id="create alert table v1"
logger=migrator t=2025-01-13T17:23:38.864718054Z level=info msg="Migration successfully executed" id="create alert table v1" duration=409.614µs
logger=migrator t=2025-01-13T17:23:38.867670548Z level=info msg="Executing migration" id="add index alert org_id & id "
logger=migrator t=2025-01-13T17:23:38.867998349Z level=info msg="Migration successfully executed" id="add index alert org_id & id " duration=328.722µs
logger=migrator t=2025-01-13T17:23:38.870407129Z level=info msg="Executing migration" id="add index alert state"
logger=migrator t=2025-01-13T17:23:38.870685598Z level=info msg="Migration successfully executed" id="add index alert state" duration=279.331µs
logger=migrator t=2025-01-13T17:23:38.873115414Z level=info msg="Executing migration" id="add index alert dashboard_id"
logger=migrator t=2025-01-13T17:23:38.873398693Z level=info msg="Migration successfully executed" id="add index alert dashboard_id" duration=284.03µs
logger=migrator t=2025-01-13T17:23:38.875860832Z level=info msg="Executing migration" id="Create alert_rule_tag table v1"
logger=migrator t=2025-01-13T17:23:38.876123412Z level=info msg="Migration successfully executed" id="Create alert_rule_tag table v1" duration=263.301µs
logger=migrator t=2025-01-13T17:23:38.878312686Z level=info msg="Executing migration" id="Add unique index alert_rule_tag.alert_id_tag_id"
logger=migrator t=2025-01-13T17:23:38.878637551Z level=info msg="Migration successfully executed" id="Add unique index alert_rule_tag.alert_id_tag_id" duration=325.717µs
logger=migrator t=2025-01-13T17:23:38.881456416Z level=info msg="Executing migration" id="drop index UQE_alert_rule_tag_alert_id_tag_id - v1"
logger=migrator t=2025-01-13T17:23:38.881690582Z level=info msg="Migration successfully executed" id="drop index UQE_alert_rule_tag_alert_id_tag_id - v1" duration=235.148µs
logger=migrator t=2025-01-13T17:23:38.916547325Z level=info msg="Executing migration" id="Rename table alert_rule_tag to alert_rule_tag_v1 - v1"
logger=migrator t=2025-01-13T17:23:38.917553841Z level=info msg="Migration successfully executed" id="Rename table alert_rule_tag to alert_rule_tag_v1 - v1" duration=1.007258ms
logger=migrator t=2025-01-13T17:23:38.919984595Z level=info msg="Executing migration" id="Create alert_rule_tag table v2"
logger=migrator t=2025-01-13T17:23:38.920260219Z level=info msg="Migration successfully executed" id="Create alert_rule_tag table v2" duration=276.766µs
logger=migrator t=2025-01-13T17:23:38.922058368Z level=info msg="Executing migration" id="create index UQE_alert_rule_tag_alert_id_tag_id - Add unique index alert_rule_tag.alert_id_tag_id V2"
logger=migrator t=2025-01-13T17:23:38.92239217Z level=info msg="Migration successfully executed" id="create index UQE_alert_rule_tag_alert_id_tag_id - Add unique index alert_rule_tag.alert_id_tag_id V2" duration=334.394µs
logger=migrator t=2025-01-13T17:23:38.924931133Z level=info msg="Executing migration" id="copy alert_rule_tag v1 to v2"
logger=migrator t=2025-01-13T17:23:38.925084819Z level=info msg="Migration successfully executed" id="copy alert_rule_tag v1 to v2" duration=154.097µs
logger=migrator t=2025-01-13T17:23:38.92670371Z level=info msg="Executing migration" id="drop table alert_rule_tag_v1"
logger=migrator t=2025-01-13T17:23:38.926978252Z level=info msg="Migration successfully executed" id="drop table alert_rule_tag_v1" duration=277.046µs
logger=migrator t=2025-01-13T17:23:38.93203579Z level=info msg="Executing migration" id="create alert_notification table v1"
logger=migrator t=2025-01-13T17:23:38.932327524Z level=info msg="Migration successfully executed" id="create alert_notification table v1" duration=291.914µs
logger=migrator t=2025-01-13T17:23:38.935968127Z level=info msg="Executing migration" id="Add column is_default"
logger=migrator t=2025-01-13T17:23:38.936521258Z level=info msg="Migration successfully executed" id="Add column is_default" duration=553.171µs
logger=migrator t=2025-01-13T17:23:38.938383459Z level=info msg="Executing migration" id="Add column frequency"
logger=migrator t=2025-01-13T17:23:38.93895264Z level=info msg="Migration successfully executed" id="Add column frequency" duration=569.201µs
logger=migrator t=2025-01-13T17:23:38.941363644Z level=info msg="Executing migration" id="Add column send_reminder"
logger=migrator t=2025-01-13T17:23:38.941940009Z level=info msg="Migration successfully executed" id="Add column send_reminder" duration=576.184µs
logger=migrator t=2025-01-13T17:23:38.944010288Z level=info msg="Executing migration" id="Add column disable_resolve_message"
logger=migrator t=2025-01-13T17:23:38.944595138Z level=info msg="Migration successfully executed" id="Add column disable_resolve_message" duration=586.834µs
logger=migrator t=2025-01-13T17:23:38.946245013Z level=info msg="Executing migration" id="add index alert_notification org_id & name"
logger=migrator t=2025-01-13T17:23:38.946585578Z level=info msg="Migration successfully executed" id="add index alert_notification org_id & name" duration=349.702µs
logger=migrator t=2025-01-13T17:23:38.948856281Z level=info msg="Executing migration" id="Update alert table charset"
logger=migrator t=2025-01-13T17:23:38.948881799Z level=info msg="Migration successfully executed" id="Update alert table charset" duration=26.128µs
logger=migrator t=2025-01-13T17:23:38.950522327Z level=info msg="Executing migration" id="Update alert_notification table charset"
logger=migrator t=2025-01-13T17:23:38.950549297Z level=info msg="Migration successfully executed" id="Update alert_notification table charset" duration=27.701µs
logger=migrator t=2025-01-13T17:23:38.952785325Z level=info msg="Executing migration" id="create notification_journal table v1"
logger=migrator t=2025-01-13T17:23:38.953115391Z level=info msg="Migration successfully executed" id="create notification_journal table v1" duration=329.975µs
logger=migrator t=2025-01-13T17:23:38.955667858Z level=info msg="Executing migration" id="add index notification_journal org_id & alert_id & notifier_id"
logger=migrator t=2025-01-13T17:23:38.955987344Z level=info msg="Migration successfully executed" id="add index notification_journal org_id & alert_id & notifier_id" duration=319.436µs
logger=migrator t=2025-01-13T17:23:38.958054758Z level=info msg="Executing migration" id="drop alert_notification_journal"
logger=migrator t=2025-01-13T17:23:38.958301207Z level=info msg="Migration successfully executed" id="drop alert_notification_journal" duration=246.229µs
logger=migrator t=2025-01-13T17:23:38.960575987Z level=info msg="Executing migration" id="create alert_notification_state table v1"
logger=migrator t=2025-01-13T17:23:38.960851972Z level=info msg="Migration successfully executed" id="create alert_notification_state table v1" duration=275.844µs
logger=migrator t=2025-01-13T17:23:38.962607394Z level=info msg="Executing migration" id="add index alert_notification_state org_id & alert_id & notifier_id"
logger=migrator t=2025-01-13T17:23:38.962926529Z level=info msg="Migration successfully executed" id="add index alert_notification_state org_id & alert_id & notifier_id" duration=319.095µs
logger=migrator t=2025-01-13T17:23:38.999676063Z level=info msg="Executing migration" id="Add for to alert table"
logger=migrator t=2025-01-13T17:23:39.000332817Z level=info msg="Migration successfully executed" id="Add for to alert table" duration=656.233µs
logger=migrator t=2025-01-13T17:23:39.022771354Z level=info msg="Executing migration" id="Add column uid in alert_notification"
logger=migrator t=2025-01-13T17:23:39.023239557Z level=info msg="Migration successfully executed" id="Add column uid in alert_notification" duration=468.985µs
logger=migrator t=2025-01-13T17:23:39.02759734Z level=info msg="Executing migration" id="Update uid column values in alert_notification"
logger=migrator t=2025-01-13T17:23:39.027675035Z level=info msg="Migration successfully executed" id="Update uid column values in alert_notification" duration=76.253µs
logger=migrator t=2025-01-13T17:23:39.029545622Z level=info msg="Executing migration" id="Add unique index alert_notification_org_id_uid"
logger=migrator t=2025-01-13T17:23:39.029918197Z level=info msg="Migration successfully executed" id="Add unique index alert_notification_org_id_uid" duration=373.416µs
logger=migrator t=2025-01-13T17:23:39.03299399Z level=info msg="Executing migration" id="Remove unique index org_id_name"
logger=migrator t=2025-01-13T17:23:39.033259435Z level=info msg="Migration successfully executed" id="Remove unique index org_id_name" duration=265.845µs
logger=migrator t=2025-01-13T17:23:39.035656286Z level=info msg="Executing migration" id="Add column secure_settings in alert_notification"
logger=migrator t=2025-01-13T17:23:39.036172298Z level=info msg="Migration successfully executed" id="Add column secure_settings in alert_notification" duration=516.783µs
logger=migrator t=2025-01-13T17:23:39.037937478Z level=info msg="Executing migration" id="alter alert.settings to mediumtext"
logger=migrator t=2025-01-13T17:23:39.03799183Z level=info msg="Migration successfully executed" id="alter alert.settings to mediumtext" duration=36.137µs
logger=migrator t=2025-01-13T17:23:39.040250761Z level=info msg="Executing migration" id="Add non-unique index alert_notification_state_alert_id"
logger=migrator t=2025-01-13T17:23:39.040606594Z level=info msg="Migration successfully executed" id="Add non-unique index alert_notification_state_alert_id" duration=356.103µs
logger=migrator t=2025-01-13T17:23:39.042393575Z level=info msg="Executing migration" id="Add non-unique index alert_rule_tag_alert_id"
logger=migrator t=2025-01-13T17:23:39.042746322Z level=info msg="Migration successfully executed" id="Add non-unique index alert_rule_tag_alert_id" duration=353.69µs
logger=migrator t=2025-01-13T17:23:39.045853615Z level=info msg="Executing migration" id="Drop old annotation table v4"
logger=migrator t=2025-01-13T17:23:39.045913356Z level=info msg="Migration successfully executed" id="Drop old annotation table v4" duration=60.102µs
logger=migrator t=2025-01-13T17:23:39.048598351Z level=info msg="Executing migration" id="create annotation table v5"
logger=migrator t=2025-01-13T17:23:39.048871731Z level=info msg="Migration successfully executed" id="create annotation table v5" duration=273.61µs
logger=migrator t=2025-01-13T17:23:39.052862897Z level=info msg="Executing migration" id="add index annotation 0 v3"
logger=migrator t=2025-01-13T17:23:39.053095751Z level=info msg="Migration successfully executed" id="add index annotation 0 v3" duration=233.495µs
logger=migrator t=2025-01-13T17:23:39.055858194Z level=info msg="Executing migration" id="add index annotation 1 v3"
logger=migrator t=2025-01-13T17:23:39.056176167Z level=info msg="Migration successfully executed" id="add index annotation 1 v3" duration=318.043µs
logger=migrator t=2025-01-13T17:23:39.058718295Z level=info msg="Executing migration" id="add index annotation 2 v3"
logger=migrator t=2025-01-13T17:23:39.05899985Z level=info msg="Migration successfully executed" id="add index annotation 2 v3" duration=282.376µs
logger=migrator t=2025-01-13T17:23:39.061685116Z level=info msg="Executing migration" id="add index annotation 3 v3"
logger=migrator t=2025-01-13T17:23:39.061986878Z level=info msg="Migration successfully executed" id="add index annotation 3 v3" duration=303.536µs
logger=migrator t=2025-01-13T17:23:39.064596593Z level=info msg="Executing migration" id="add index annotation 4 v3"
logger=migrator t=2025-01-13T17:23:39.064895821Z level=info msg="Migration successfully executed" id="add index annotation 4 v3" duration=300.079µs
logger=migrator t=2025-01-13T17:23:39.067705365Z level=info msg="Executing migration" id="Update annotation table charset"
logger=migrator t=2025-01-13T17:23:39.067730181Z level=info msg="Migration successfully executed" id="Update annotation table charset" duration=25.958µs
logger=migrator t=2025-01-13T17:23:39.069861878Z level=info msg="Executing migration" id="Add column region_id to annotation table"
logger=migrator t=2025-01-13T17:23:39.070376046Z level=info msg="Migration successfully executed" id="Add column region_id to annotation table" duration=514.99µs
logger=migrator t=2025-01-13T17:23:39.072632012Z level=info msg="Executing migration" id="Drop category_id index"
logger=migrator t=2025-01-13T17:23:39.072914709Z level=info msg="Migration successfully executed" id="Drop category_id index" duration=283.669µs
logger=migrator t=2025-01-13T17:23:39.099388475Z level=info msg="Executing migration" id="Add column tags to annotation table"
logger=migrator t=2025-01-13T17:23:39.100022136Z level=info msg="Migration successfully executed" id="Add column tags to annotation table" duration=634.352µs
logger=migrator t=2025-01-13T17:23:39.116430452Z level=info msg="Executing migration" id="Create annotation_tag table v2"
logger=migrator t=2025-01-13T17:23:39.116930244Z level=info msg="Migration successfully executed" id="Create annotation_tag table v2" duration=499.701µs
logger=migrator t=2025-01-13T17:23:39.119829892Z level=info msg="Executing migration" id="Add unique index annotation_tag.annotation_id_tag_id"
logger=migrator t=2025-01-13T17:23:39.120190554Z level=info msg="Migration successfully executed" id="Add unique index annotation_tag.annotation_id_tag_id" duration=360.692µs
logger=migrator t=2025-01-13T17:23:39.122658364Z level=info msg="Executing migration" id="drop index UQE_annotation_tag_annotation_id_tag_id - v2"
logger=migrator t=2025-01-13T17:23:39.12292448Z level=info msg="Migration successfully executed" id="drop index UQE_annotation_tag_annotation_id_tag_id - v2" duration=266.868µs
logger=migrator t=2025-01-13T17:23:39.125385999Z level=info msg="Executing migration" id="Rename table annotation_tag to annotation_tag_v2 - v2"
logger=migrator t=2025-01-13T17:23:39.126599511Z level=info msg="Migration successfully executed" id="Rename table annotation_tag to annotation_tag_v2 - v2" duration=1.213702ms
logger=migrator t=2025-01-13T17:23:39.128869389Z level=info msg="Executing migration" id="Create annotation_tag table v3"
logger=migrator t=2025-01-13T17:23:39.129145514Z level=info msg="Migration successfully executed" id="Create annotation_tag table v3" duration=276.916µs
logger=migrator t=2025-01-13T17:23:39.131618213Z level=info msg="Executing migration" id="create index UQE_annotation_tag_annotation_id_tag_id - Add unique index annotation_tag.annotation_id_tag_id V3"
logger=migrator t=2025-01-13T17:23:39.131944111Z level=info msg="Migration successfully executed" id="create index UQE_annotation_tag_annotation_id_tag_id - Add unique index annotation_tag.annotation_id_tag_id V3" duration=328.643µs
logger=migrator t=2025-01-13T17:23:39.134634175Z level=info msg="Executing migration" id="copy annotation_tag v2 to v3"
logger=migrator t=2025-01-13T17:23:39.134804182Z level=info msg="Migration successfully executed" id="copy annotation_tag v2 to v3" duration=170.798µs
logger=migrator t=2025-01-13T17:23:39.137010545Z level=info msg="Executing migration" id="drop table annotation_tag_v2"
logger=migrator t=2025-01-13T17:23:39.1372387Z level=info msg="Migration successfully executed" id="drop table annotation_tag_v2" duration=229.307µs
logger=migrator t=2025-01-13T17:23:39.139621392Z level=info msg="Executing migration" id="Update alert annotations and set TEXT to empty"
logger=migrator t=2025-01-13T17:23:39.139694688Z level=info msg="Migration successfully executed" id="Update alert annotations and set TEXT to empty" duration=74.128µs
logger=migrator t=2025-01-13T17:23:39.141374443Z level=info msg="Executing migration" id="Add created time to annotation table"
logger=migrator t=2025-01-13T17:23:39.141896937Z level=info msg="Migration successfully executed" id="Add created time to annotation table" duration=522.915µs
logger=migrator t=2025-01-13T17:23:39.144164941Z level=info msg="Executing migration" id="Add updated time to annotation table"
logger=migrator t=2025-01-13T17:23:39.14476529Z level=info msg="Migration successfully executed" id="Add updated time to annotation table" duration=600.048µs
logger=migrator t=2025-01-13T17:23:39.146918083Z level=info msg="Executing migration" id="Add index for created in annotation table"
logger=migrator t=2025-01-13T17:23:39.147255402Z level=info msg="Migration successfully executed" id="Add index for created in annotation table" duration=338.27µs
logger=migrator t=2025-01-13T17:23:39.149882389Z level=info msg="Executing migration" id="Add index for updated in annotation table"
logger=migrator t=2025-01-13T17:23:39.15017255Z level=info msg="Migration successfully executed" id="Add index for updated in annotation table" duration=291.042µs
logger=migrator t=2025-01-13T17:23:39.152887631Z level=info msg="Executing migration" id="Convert existing annotations from seconds to milliseconds"
logger=migrator t=2025-01-13T17:23:39.153025989Z level=info msg="Migration successfully executed" id="Convert existing annotations from seconds to milliseconds" duration=137.276µs
logger=migrator t=2025-01-13T17:23:39.154716273Z level=info msg="Executing migration" id="Add epoch_end column"
logger=migrator t=2025-01-13T17:23:39.155286636Z level=info msg="Migration successfully executed" id="Add epoch_end column" duration=571.124µs
logger=migrator t=2025-01-13T17:23:39.157856463Z level=info msg="Executing migration" id="Add index for epoch_end"
logger=migrator t=2025-01-13T17:23:39.158153878Z level=info msg="Migration successfully executed" id="Add index for epoch_end" duration=298.637µs
logger=migrator t=2025-01-13T17:23:39.160632478Z level=info msg="Executing migration" id="Make epoch_end the same as epoch"
logger=migrator t=2025-01-13T17:23:39.160749717Z level=info msg="Migration successfully executed" id="Make epoch_end the same as epoch" duration=118.151µs
logger=migrator t=2025-01-13T17:23:39.162490004Z level=info msg="Executing migration" id="Move region to single row"
logger=migrator t=2025-01-13T17:23:39.162730412Z level=info msg="Migration successfully executed" id="Move region to single row" duration=241.069µs
logger=migrator t=2025-01-13T17:23:39.164931525Z level=info msg="Executing migration" id="Remove index org_id_epoch from annotation table"
logger=migrator t=2025-01-13T17:23:39.165203081Z level=info msg="Migration successfully executed" id="Remove index org_id_epoch from annotation table" duration=272.347µs
logger=migrator t=2025-01-13T17:23:39.198997293Z level=info msg="Executing migration" id="Remove index org_id_dashboard_id_panel_id_epoch from annotation table"
logger=migrator t=2025-01-13T17:23:39.199308262Z level=info msg="Migration successfully executed" id="Remove index org_id_dashboard_id_panel_id_epoch from annotation table" duration=312.012µs
logger=migrator t=2025-01-13T17:23:39.20152796Z level=info msg="Executing migration" id="Add index for org_id_dashboard_id_epoch_end_epoch on annotation table"
logger=migrator t=2025-01-13T17:23:39.213960769Z level=info msg="Migration successfully executed" id="Add index for org_id_dashboard_id_epoch_end_epoch on annotation table" duration=12.440022ms
logger=migrator t=2025-01-13T17:23:39.217109445Z level=info msg="Executing migration" id="Add index for org_id_epoch_end_epoch on annotation table"
logger=migrator t=2025-01-13T17:23:39.217457604Z level=info msg="Migration successfully executed" id="Add index for org_id_epoch_end_epoch on annotation table" duration=348.53µs
logger=migrator t=2025-01-13T17:23:39.220170451Z level=info msg="Executing migration" id="Remove index org_id_epoch_epoch_end from annotation table"
logger=migrator t=2025-01-13T17:23:39.220484346Z level=info msg="Migration successfully executed" id="Remove index org_id_epoch_epoch_end from annotation table" duration=315.037µs
logger=migrator t=2025-01-13T17:23:39.222548744Z level=info msg="Executing migration" id="Add index for alert_id on annotation table"
logger=migrator t=2025-01-13T17:23:39.222871686Z level=info msg="Migration successfully executed" id="Add index for alert_id on annotation table" duration=324.174µs
logger=migrator t=2025-01-13T17:23:39.22525368Z level=info msg="Executing migration" id="Increase tags column to length 4096"
logger=migrator t=2025-01-13T17:23:39.22533419Z level=info msg="Migration successfully executed" id="Increase tags column to length 4096" duration=81.011µs
logger=migrator t=2025-01-13T17:23:39.227463269Z level=info msg="Executing migration" id="create test_data table"
logger=migrator t=2025-01-13T17:23:39.227775982Z level=info msg="Migration successfully executed" id="create test_data table" duration=312.663µs
logger=migrator t=2025-01-13T17:23:39.233392561Z level=info msg="Executing migration" id="create dashboard_version table v1"
logger=migrator t=2025-01-13T17:23:39.233951013Z level=info msg="Migration successfully executed" id="create dashboard_version table v1" duration=558.3µs
logger=migrator t=2025-01-13T17:23:39.23707199Z level=info msg="Executing migration" id="add index dashboard_version.dashboard_id"
logger=migrator t=2025-01-13T17:23:39.237636462Z level=info msg="Migration successfully executed" id="add index dashboard_version.dashboard_id" duration=564.181µs
logger=migrator t=2025-01-13T17:23:39.240642733Z level=info msg="Executing migration" id="add unique index dashboard_version.dashboard_id and dashboard_version.version"
logger=migrator t=2025-01-13T17:23:39.240947521Z level=info msg="Migration successfully executed" id="add unique index dashboard_version.dashboard_id and dashboard_version.version" duration=304.969µs
logger=migrator t=2025-01-13T17:23:39.243767267Z level=info msg="Executing migration" id="Set dashboard version to 1 where 0"
logger=migrator t=2025-01-13T17:23:39.243845994Z level=info msg="Migration successfully executed" id="Set dashboard version to 1 where 0" duration=79.147µs
logger=migrator t=2025-01-13T17:23:39.245704508Z level=info msg="Executing migration" id="save existing dashboard data in dashboard_version table v1"
logger=migrator t=2025-01-13T17:23:39.245922605Z level=info msg="Migration successfully executed" id="save existing dashboard data in dashboard_version table v1" duration=218.837µs
logger=migrator t=2025-01-13T17:23:39.248204679Z level=info msg="Executing migration" id="alter dashboard_version.data to mediumtext v1"
logger=migrator t=2025-01-13T17:23:39.248240245Z level=info msg="Migration successfully executed" id="alter dashboard_version.data to mediumtext v1" duration=36.598µs
logger=migrator t=2025-01-13T17:23:39.250058855Z level=info msg="Executing migration" id="create team table"
logger=migrator t=2025-01-13T17:23:39.250376989Z level=info msg="Migration successfully executed" id="create team table" duration=319.074µs
logger=migrator t=2025-01-13T17:23:39.253695407Z level=info msg="Executing migration" id="add index team.org_id"
logger=migrator t=2025-01-13T17:23:39.254066409Z level=info msg="Migration successfully executed" id="add index team.org_id" duration=371.252µs
logger=migrator t=2025-01-13T17:23:39.257000455Z level=info msg="Executing migration" id="add unique index team_org_id_name"
logger=migrator t=2025-01-13T17:23:39.257349726Z level=info msg="Migration successfully executed" id="add unique index team_org_id_name" duration=349.862µs
logger=migrator t=2025-01-13T17:23:39.25989808Z level=info msg="Executing migration" id="Add column uid in team"
logger=migrator t=2025-01-13T17:23:39.260524207Z level=info msg="Migration successfully executed" id="Add column uid in team" duration=626.247µs
logger=migrator t=2025-01-13T17:23:39.262374062Z level=info msg="Executing migration" id="Update uid column values in team"
logger=migrator t=2025-01-13T17:23:39.262566811Z level=info msg="Migration successfully executed" id="Update uid column values in team" duration=193.421µs
logger=migrator t=2025-01-13T17:23:39.264800324Z level=info msg="Executing migration" id="Add unique index team_org_id_uid"
logger=migrator t=2025-01-13T17:23:39.265119199Z level=info msg="Migration successfully executed" id="Add unique index team_org_id_uid" duration=319.986µs
logger=migrator t=2025-01-13T17:23:39.267739016Z level=info msg="Executing migration" id="create team member table"
logger=migrator t=2025-01-13T17:23:39.268049484Z level=info msg="Migration successfully executed" id="create team member table" duration=310.549µs
logger=migrator t=2025-01-13T17:23:39.299513222Z level=info msg="Executing migration" id="add index team_member.org_id"
logger=migrator t=2025-01-13T17:23:39.299879675Z level=info msg="Migration successfully executed" id="add index team_member.org_id" duration=367.295µs
logger=migrator t=2025-01-13T17:23:39.316640061Z level=info msg="Executing migration" id="add unique index team_member_org_id_team_id_user_id"
logger=migrator t=2025-01-13T17:23:39.316958966Z level=info msg="Migration successfully executed" id="add unique index team_member_org_id_team_id_user_id" duration=319.476µs
logger=migrator t=2025-01-13T17:23:39.319924984Z level=info msg="Executing migration" id="add index team_member.team_id"
logger=migrator t=2025-01-13T17:23:39.320245061Z level=info msg="Migration successfully executed" id="add index team_member.team_id" duration=317.802µs
logger=migrator t=2025-01-13T17:23:39.322666705Z level=info msg="Executing migration" id="Add column email to team table"
logger=migrator t=2025-01-13T17:23:39.323244162Z level=info msg="Migration successfully executed" id="Add column email to team table" duration=578.348µs
logger=migrator t=2025-01-13T17:23:39.325473414Z level=info msg="Executing migration" id="Add column external to team_member table"
logger=migrator t=2025-01-13T17:23:39.326019702Z level=info msg="Migration successfully executed" id="Add column external to team_member table" duration=547.09µs
logger=migrator t=2025-01-13T17:23:39.328301579Z level=info msg="Executing migration" id="Add column permission to team_member table"
logger=migrator t=2025-01-13T17:23:39.32884903Z level=info msg="Migration successfully executed" id="Add column permission to team_member table" duration=548.553µs
logger=migrator t=2025-01-13T17:23:39.330660483Z level=info msg="Executing migration" id="add unique index team_member_user_id_org_id"
logger=migrator t=2025-01-13T17:23:39.330997741Z level=info msg="Migration successfully executed" id="add unique index team_member_user_id_org_id" duration=338.251µs
logger=migrator t=2025-01-13T17:23:39.333561921Z level=info msg="Executing migration" id="create dashboard acl table"
logger=migrator t=2025-01-13T17:23:39.333867541Z level=info msg="Migration successfully executed" id="create dashboard acl table" duration=306.531µs
logger=migrator t=2025-01-13T17:23:39.336561713Z level=info msg="Executing migration" id="add index dashboard_acl_dashboard_id"
logger=migrator t=2025-01-13T17:23:39.336913098Z level=info msg="Migration successfully executed" id="add index dashboard_acl_dashboard_id" duration=351.665µs
logger=migrator t=2025-01-13T17:23:39.339874863Z level=info msg="Executing migration" id="add unique index dashboard_acl_dashboard_id_user_id"
logger=migrator t=2025-01-13T17:23:39.340358694Z level=info msg="Migration successfully executed" id="add unique index dashboard_acl_dashboard_id_user_id" duration=484.323µs
logger=migrator t=2025-01-13T17:23:39.34349648Z level=info msg="Executing migration" id="add unique index dashboard_acl_dashboard_id_team_id"
logger=migrator t=2025-01-13T17:23:39.343830663Z level=info msg="Migration successfully executed" id="add unique index dashboard_acl_dashboard_id_team_id" duration=335.957µs
logger=migrator t=2025-01-13T17:23:39.346383251Z level=info msg="Executing migration" id="add index dashboard_acl_user_id"
logger=migrator t=2025-01-13T17:23:39.346703578Z level=info msg="Migration successfully executed" id="add index dashboard_acl_user_id" duration=319.316µs
logger=migrator t=2025-01-13T17:23:39.349633704Z level=info msg="Executing migration" id="add index dashboard_acl_team_id"
logger=migrator t=2025-01-13T17:23:39.349992372Z level=info msg="Migration successfully executed" id="add index dashboard_acl_team_id" duration=359.17µs
logger=migrator t=2025-01-13T17:23:39.352730212Z level=info msg="Executing migration" id="add index dashboard_acl_org_id_role"
logger=migrator t=2025-01-13T17:23:39.353029861Z level=info msg="Migration successfully executed" id="add index dashboard_acl_org_id_role" duration=300.641µs
logger=migrator t=2025-01-13T17:23:39.355948725Z level=info msg="Executing migration" id="add index dashboard_permission"
logger=migrator t=2025-01-13T17:23:39.356252472Z level=info msg="Migration successfully executed" id="add index dashboard_permission" duration=304.758µs
logger=migrator t=2025-01-13T17:23:39.358573254Z level=info msg="Executing migration" id="save default acl rules in dashboard_acl table"
logger=migrator t=2025-01-13T17:23:39.358913158Z level=info msg="Migration successfully executed" id="save default acl rules in dashboard_acl table" duration=339.452µs
logger=migrator t=2025-01-13T17:23:39.36188593Z level=info msg="Executing migration" id="delete acl rules for deleted dashboards and folders"
logger=migrator t=2025-01-13T17:23:39.362038193Z level=info msg="Migration successfully executed" id="delete acl rules for deleted dashboards and folders" duration=152.555µs
logger=migrator t=2025-01-13T17:23:39.364531344Z level=info msg="Executing migration" id="create tag table"
logger=migrator t=2025-01-13T17:23:39.364795847Z level=info msg="Migration successfully executed" id="create tag table" duration=265.444µs
logger=migrator t=2025-01-13T17:23:39.367347333Z level=info msg="Executing migration" id="add index tag.key_value"
logger=migrator t=2025-01-13T17:23:39.36766728Z level=info msg="Migration successfully executed" id="add index tag.key_value" duration=320.788µs
logger=migrator t=2025-01-13T17:23:39.370220649Z level=info msg="Executing migration" id="create login attempt table"
logger=migrator t=2025-01-13T17:23:39.370559551Z level=info msg="Migration successfully executed" id="create login attempt table" duration=337.9µs
logger=migrator t=2025-01-13T17:23:39.399249471Z level=info msg="Executing migration" id="add index login_attempt.username"
logger=migrator t=2025-01-13T17:23:39.399595146Z level=info msg="Migration successfully executed" id="add index login_attempt.username" duration=345.153µs
logger=migrator t=2025-01-13T17:23:39.416972939Z level=info msg="Executing migration" id="drop index IDX_login_attempt_username - v1"
logger=migrator t=2025-01-13T17:23:39.417322691Z level=info msg="Migration successfully executed" id="drop index IDX_login_attempt_username - v1" duration=350.603µs
logger=migrator t=2025-01-13T17:23:39.419944809Z level=info msg="Executing migration" id="Rename table login_attempt to login_attempt_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:39.421254841Z level=info msg="Migration successfully executed" id="Rename table login_attempt to login_attempt_tmp_qwerty - v1" duration=1.309211ms
logger=migrator t=2025-01-13T17:23:39.423604521Z level=info msg="Executing migration" id="create login_attempt v2"
logger=migrator t=2025-01-13T17:23:39.423857743Z level=info msg="Migration successfully executed" id="create login_attempt v2" duration=253.873µs
logger=migrator t=2025-01-13T17:23:39.42611635Z level=info msg="Executing migration" id="create index IDX_login_attempt_username - v2"
logger=migrator t=2025-01-13T17:23:39.426509122Z level=info msg="Migration successfully executed" id="create index IDX_login_attempt_username - v2" duration=393.273µs
logger=migrator t=2025-01-13T17:23:39.429097086Z level=info msg="Executing migration" id="copy login_attempt v1 to v2"
logger=migrator t=2025-01-13T17:23:39.429339849Z level=info msg="Migration successfully executed" id="copy login_attempt v1 to v2" duration=243.483µs
logger=migrator t=2025-01-13T17:23:39.431532028Z level=info msg="Executing migration" id="drop login_attempt_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:39.431781784Z level=info msg="Migration successfully executed" id="drop login_attempt_tmp_qwerty" duration=250.447µs
logger=migrator t=2025-01-13T17:23:39.433670164Z level=info msg="Executing migration" id="create user auth table"
logger=migrator t=2025-01-13T17:23:39.433921713Z level=info msg="Migration successfully executed" id="create user auth table" duration=250.377µs
logger=migrator t=2025-01-13T17:23:39.436469211Z level=info msg="Executing migration" id="create index IDX_user_auth_auth_module_auth_id - v1"
logger=migrator t=2025-01-13T17:23:39.436720831Z level=info msg="Migration successfully executed" id="create index IDX_user_auth_auth_module_auth_id - v1" duration=252.36µs
logger=migrator t=2025-01-13T17:23:39.439250833Z level=info msg="Executing migration" id="alter user_auth.auth_id to length 190"
logger=migrator t=2025-01-13T17:23:39.439398078Z level=info msg="Migration successfully executed" id="alter user_auth.auth_id to length 190" duration=148.467µs
logger=migrator t=2025-01-13T17:23:39.441385756Z level=info msg="Executing migration" id="Add OAuth access token to user_auth"
logger=migrator t=2025-01-13T17:23:39.442007365Z level=info msg="Migration successfully executed" id="Add OAuth access token to user_auth" duration=622.22µs
logger=migrator t=2025-01-13T17:23:39.444354838Z level=info msg="Executing migration" id="Add OAuth refresh token to user_auth"
logger=migrator t=2025-01-13T17:23:39.445048531Z level=info msg="Migration successfully executed" id="Add OAuth refresh token to user_auth" duration=694.113µs
logger=migrator t=2025-01-13T17:23:39.447467954Z level=info msg="Executing migration" id="Add OAuth token type to user_auth"
logger=migrator t=2025-01-13T17:23:39.448110602Z level=info msg="Migration successfully executed" id="Add OAuth token type to user_auth" duration=643.47µs
logger=migrator t=2025-01-13T17:23:39.449918953Z level=info msg="Executing migration" id="Add OAuth expiry to user_auth"
logger=migrator t=2025-01-13T17:23:39.450564406Z level=info msg="Migration successfully executed" id="Add OAuth expiry to user_auth" duration=644.211µs
logger=migrator t=2025-01-13T17:23:39.453089243Z level=info msg="Executing migration" id="Add index to user_id column in user_auth"
logger=migrator t=2025-01-13T17:23:39.453398789Z level=info msg="Migration successfully executed" id="Add index to user_id column in user_auth" duration=310.469µs
logger=migrator t=2025-01-13T17:23:39.455914138Z level=info msg="Executing migration" id="Add OAuth ID token to user_auth"
logger=migrator t=2025-01-13T17:23:39.456496574Z level=info msg="Migration successfully executed" id="Add OAuth ID token to user_auth" duration=585.24µs
logger=migrator t=2025-01-13T17:23:39.458259217Z level=info msg="Executing migration" id="create server_lock table"
logger=migrator t=2025-01-13T17:23:39.458590023Z level=info msg="Migration successfully executed" id="create server_lock table" duration=331.388µs
logger=migrator t=2025-01-13T17:23:39.461272423Z level=info msg="Executing migration" id="add index server_lock.operation_uid"
logger=migrator t=2025-01-13T17:23:39.461599286Z level=info msg="Migration successfully executed" id="add index server_lock.operation_uid" duration=329.107µs
logger=migrator t=2025-01-13T17:23:39.49743898Z level=info msg="Executing migration" id="create user auth token table"
logger=migrator t=2025-01-13T17:23:39.497716087Z level=info msg="Migration successfully executed" id="create user auth token table" duration=277.557µs
logger=migrator t=2025-01-13T17:23:39.5174486Z level=info msg="Executing migration" id="add unique index user_auth_token.auth_token"
logger=migrator t=2025-01-13T17:23:39.51781352Z level=info msg="Migration successfully executed" id="add unique index user_auth_token.auth_token" duration=361.865µs
logger=migrator t=2025-01-13T17:23:39.520790623Z level=info msg="Executing migration" id="add unique index user_auth_token.prev_auth_token"
logger=migrator t=2025-01-13T17:23:39.521101282Z level=info msg="Migration successfully executed" id="add unique index user_auth_token.prev_auth_token" duration=310.699µs
logger=migrator t=2025-01-13T17:23:39.523782149Z level=info msg="Executing migration" id="add index user_auth_token.user_id"
logger=migrator t=2025-01-13T17:23:39.524174538Z level=info msg="Migration successfully executed" id="add index user_auth_token.user_id" duration=393.13µs
logger=migrator t=2025-01-13T17:23:39.526773773Z level=info msg="Executing migration" id="Add revoked_at to the user auth token"
logger=migrator t=2025-01-13T17:23:39.527458549Z level=info msg="Migration successfully executed" id="Add revoked_at to the user auth token" duration=685.047µs
logger=migrator t=2025-01-13T17:23:39.530128977Z level=info msg="Executing migration" id="add index user_auth_token.revoked_at"
logger=migrator t=2025-01-13T17:23:39.530435859Z level=info msg="Migration successfully executed" id="add index user_auth_token.revoked_at" duration=307.754µs
logger=migrator t=2025-01-13T17:23:39.53304703Z level=info msg="Executing migration" id="add external_session_id to user_auth_token"
logger=migrator t=2025-01-13T17:23:39.533650695Z level=info msg="Migration successfully executed" id="add external_session_id to user_auth_token" duration=604.507µs
logger=migrator t=2025-01-13T17:23:39.535997019Z level=info msg="Executing migration" id="create cache_data table"
logger=migrator t=2025-01-13T17:23:39.536292309Z level=info msg="Migration successfully executed" id="create cache_data table" duration=295.971µs
logger=migrator t=2025-01-13T17:23:39.539048387Z level=info msg="Executing migration" id="add unique index cache_data.cache_key"
logger=migrator t=2025-01-13T17:23:39.540075361Z level=info msg="Migration successfully executed" id="add unique index cache_data.cache_key" duration=1.027545ms
logger=migrator t=2025-01-13T17:23:39.543171289Z level=info msg="Executing migration" id="create short_url table v1"
logger=migrator t=2025-01-13T17:23:39.543479814Z level=info msg="Migration successfully executed" id="create short_url table v1" duration=308.135µs
logger=migrator t=2025-01-13T17:23:39.546107986Z level=info msg="Executing migration" id="add index short_url.org_id-uid"
logger=migrator t=2025-01-13T17:23:39.546494948Z level=info msg="Migration successfully executed" id="add index short_url.org_id-uid" duration=387.552µs
logger=migrator t=2025-01-13T17:23:39.549111432Z level=info msg="Executing migration" id="alter table short_url alter column created_by type to bigint"
logger=migrator t=2025-01-13T17:23:39.549234Z level=info msg="Migration successfully executed" id="alter table short_url alter column created_by type to bigint" duration=121.336µs
logger=migrator t=2025-01-13T17:23:39.551550582Z level=info msg="Executing migration" id="delete alert_definition table"
logger=migrator t=2025-01-13T17:23:39.551696844Z level=info msg="Migration successfully executed" id="delete alert_definition table" duration=147.104µs
logger=migrator t=2025-01-13T17:23:39.553408702Z level=info msg="Executing migration" id="recreate alert_definition table"
logger=migrator t=2025-01-13T17:23:39.553745771Z level=info msg="Migration successfully executed" id="recreate alert_definition table" duration=335.856µs
logger=migrator t=2025-01-13T17:23:39.556758777Z level=info msg="Executing migration" id="add index in alert_definition on org_id and title columns"
logger=migrator t=2025-01-13T17:23:39.557051262Z level=info msg="Migration successfully executed" id="add index in alert_definition on org_id and title columns" duration=293.447µs
logger=migrator t=2025-01-13T17:23:39.559949127Z level=info msg="Executing migration" id="add index in alert_definition on org_id and uid columns"
logger=migrator t=2025-01-13T17:23:39.560268673Z level=info msg="Migration successfully executed" id="add index in alert_definition on org_id and uid columns" duration=314.396µs
logger=migrator t=2025-01-13T17:23:39.562587065Z level=info msg="Executing migration" id="alter alert_definition table data column to mediumtext in mysql"
logger=migrator t=2025-01-13T17:23:39.562621579Z level=info msg="Migration successfully executed" id="alter alert_definition table data column to mediumtext in mysql" duration=35.255µs
logger=migrator t=2025-01-13T17:23:39.56483209Z level=info msg="Executing migration" id="drop index in alert_definition on org_id and title columns"
logger=migrator t=2025-01-13T17:23:39.565087516Z level=info msg="Migration successfully executed" id="drop index in alert_definition on org_id and title columns" duration=256.398µs
logger=migrator t=2025-01-13T17:23:39.566873762Z level=info msg="Executing migration" id="drop index in alert_definition on org_id and uid columns"
logger=migrator t=2025-01-13T17:23:39.567198257Z level=info msg="Migration successfully executed" id="drop index in alert_definition on org_id and uid columns" duration=325.236µs
logger=migrator t=2025-01-13T17:23:39.569952381Z level=info msg="Executing migration" id="add unique index in alert_definition on org_id and title columns"
logger=migrator t=2025-01-13T17:23:39.570700509Z level=info msg="Migration successfully executed" id="add unique index in alert_definition on org_id and title columns" duration=748.879µs
logger=migrator t=2025-01-13T17:23:39.599029126Z level=info msg="Executing migration" id="add unique index in alert_definition on org_id and uid columns"
logger=migrator t=2025-01-13T17:23:39.599370071Z level=info msg="Migration successfully executed" id="add unique index in alert_definition on org_id and uid columns" duration=340.975µs
logger=migrator t=2025-01-13T17:23:39.616764753Z level=info msg="Executing migration" id="Add column paused in alert_definition"
logger=migrator t=2025-01-13T17:23:39.617458005Z level=info msg="Migration successfully executed" id="Add column paused in alert_definition" duration=693.733µs
logger=migrator t=2025-01-13T17:23:39.619829416Z level=info msg="Executing migration" id="drop alert_definition table"
logger=migrator t=2025-01-13T17:23:39.620215124Z level=info msg="Migration successfully executed" id="drop alert_definition table" duration=386.481µs
logger=migrator t=2025-01-13T17:23:39.622268806Z level=info msg="Executing migration" id="delete alert_definition_version table"
logger=migrator t=2025-01-13T17:23:39.622375345Z level=info msg="Migration successfully executed" id="delete alert_definition_version table" duration=106.699µs
logger=migrator t=2025-01-13T17:23:39.624575466Z level=info msg="Executing migration" id="recreate alert_definition_version table"
logger=migrator t=2025-01-13T17:23:39.624847583Z level=info msg="Migration successfully executed" id="recreate alert_definition_version table" duration=272.908µs
logger=migrator t=2025-01-13T17:23:39.626846369Z level=info msg="Executing migration" id="add index in alert_definition_version table on alert_definition_id and version columns"
logger=migrator t=2025-01-13T17:23:39.627155024Z level=info msg="Migration successfully executed" id="add index in alert_definition_version table on alert_definition_id and version columns" duration=304.117µs
logger=migrator t=2025-01-13T17:23:39.62949692Z level=info msg="Executing migration" id="add index in alert_definition_version table on alert_definition_uid and version columns"
logger=migrator t=2025-01-13T17:23:39.629784015Z level=info msg="Migration successfully executed" id="add index in alert_definition_version table on alert_definition_uid and version columns" duration=286.274µs
logger=migrator t=2025-01-13T17:23:39.632105713Z level=info msg="Executing migration" id="alter alert_definition_version table data column to mediumtext in mysql"
logger=migrator t=2025-01-13T17:23:39.632142091Z level=info msg="Migration successfully executed" id="alter alert_definition_version table data column to mediumtext in mysql" duration=37.26µs
logger=migrator t=2025-01-13T17:23:39.633884969Z level=info msg="Executing migration" id="drop alert_definition_version table"
logger=migrator t=2025-01-13T17:23:39.634192442Z level=info msg="Migration successfully executed" id="drop alert_definition_version table" duration=307.844µs
logger=migrator t=2025-01-13T17:23:39.636694797Z level=info msg="Executing migration" id="create alert_instance table"
logger=migrator t=2025-01-13T17:23:39.637004304Z level=info msg="Migration successfully executed" id="create alert_instance table" duration=310.088µs
logger=migrator t=2025-01-13T17:23:39.639616083Z level=info msg="Executing migration" id="add index in alert_instance table on def_org_id, def_uid and current_state columns"
logger=migrator t=2025-01-13T17:23:39.639901936Z level=info msg="Migration successfully executed" id="add index in alert_instance table on def_org_id, def_uid and current_state columns" duration=286.915µs
logger=migrator t=2025-01-13T17:23:39.642135369Z level=info msg="Executing migration" id="add index in alert_instance table on def_org_id, current_state columns"
logger=migrator t=2025-01-13T17:23:39.642393289Z level=info msg="Migration successfully executed" id="add index in alert_instance table on def_org_id, current_state columns" duration=257.029µs
logger=migrator t=2025-01-13T17:23:39.644867699Z level=info msg="Executing migration" id="add column current_state_end to alert_instance"
logger=migrator t=2025-01-13T17:23:39.64554982Z level=info msg="Migration successfully executed" id="add column current_state_end to alert_instance" duration=682.462µs
logger=migrator t=2025-01-13T17:23:39.647993619Z level=info msg="Executing migration" id="remove index def_org_id, def_uid, current_state on alert_instance"
logger=migrator t=2025-01-13T17:23:39.648309047Z level=info msg="Migration successfully executed" id="remove index def_org_id, def_uid, current_state on alert_instance" duration=318.102µs
logger=migrator t=2025-01-13T17:23:39.650423418Z level=info msg="Executing migration" id="remove index def_org_id, current_state on alert_instance"
logger=migrator t=2025-01-13T17:23:39.650718889Z level=info msg="Migration successfully executed" id="remove index def_org_id, current_state on alert_instance" duration=295.571µs
logger=migrator t=2025-01-13T17:23:39.653415062Z level=info msg="Executing migration" id="rename def_org_id to rule_org_id in alert_instance"
logger=migrator t=2025-01-13T17:23:39.656117492Z level=info msg="Migration successfully executed" id="rename def_org_id to rule_org_id in alert_instance" duration=2.70186ms
logger=migrator t=2025-01-13T17:23:39.700652806Z level=info msg="Executing migration" id="rename def_uid to rule_uid in alert_instance"
logger=migrator t=2025-01-13T17:23:39.716374877Z level=info msg="Migration successfully executed" id="rename def_uid to rule_uid in alert_instance" duration=15.721609ms
logger=migrator t=2025-01-13T17:23:39.71931628Z level=info msg="Executing migration" id="add index rule_org_id, rule_uid, current_state on alert_instance"
logger=migrator t=2025-01-13T17:23:39.719666132Z level=info msg="Migration successfully executed" id="add index rule_org_id, rule_uid, current_state on alert_instance" duration=350.523µs
logger=migrator t=2025-01-13T17:23:39.722053579Z level=info msg="Executing migration" id="add index rule_org_id, current_state on alert_instance"
logger=migrator t=2025-01-13T17:23:39.722400897Z level=info msg="Migration successfully executed" id="add index rule_org_id, current_state on alert_instance" duration=350.313µs
logger=migrator t=2025-01-13T17:23:39.724849514Z level=info msg="Executing migration" id="add current_reason column related to current_state"
logger=migrator t=2025-01-13T17:23:39.725495308Z level=info msg="Migration successfully executed" id="add current_reason column related to current_state" duration=646.535µs
logger=migrator t=2025-01-13T17:23:39.727818088Z level=info msg="Executing migration" id="add result_fingerprint column to alert_instance"
logger=migrator t=2025-01-13T17:23:39.728406775Z level=info msg="Migration successfully executed" id="add result_fingerprint column to alert_instance" duration=593.887µs
logger=migrator t=2025-01-13T17:23:39.730225412Z level=info msg="Executing migration" id="create alert_rule table"
logger=migrator t=2025-01-13T17:23:39.730704956Z level=info msg="Migration successfully executed" id="create alert_rule table" duration=463.393µs
logger=migrator t=2025-01-13T17:23:39.733261962Z level=info msg="Executing migration" id="add index in alert_rule on org_id and title columns"
logger=migrator t=2025-01-13T17:23:39.733544569Z level=info msg="Migration successfully executed" id="add index in alert_rule on org_id and title columns" duration=283.258µs
logger=migrator t=2025-01-13T17:23:39.73602353Z level=info msg="Executing migration" id="add index in alert_rule on org_id and uid columns"
logger=migrator t=2025-01-13T17:23:39.736299294Z level=info msg="Migration successfully executed" id="add index in alert_rule on org_id and uid columns" duration=276.716µs
logger=migrator t=2025-01-13T17:23:39.739066426Z level=info msg="Executing migration" id="add index in alert_rule on org_id, namespace_uid, group_uid columns"
logger=migrator t=2025-01-13T17:23:39.739407501Z level=info msg="Migration successfully executed" id="add index in alert_rule on org_id, namespace_uid, group_uid columns" duration=341.677µs
logger=migrator t=2025-01-13T17:23:39.741691315Z level=info msg="Executing migration" id="alter alert_rule table data column to mediumtext in mysql"
logger=migrator t=2025-01-13T17:23:39.741803384Z level=info msg="Migration successfully executed" id="alter alert_rule table data column to mediumtext in mysql" duration=113.712µs
logger=migrator t=2025-01-13T17:23:39.744095507Z level=info msg="Executing migration" id="add column for to alert_rule"
logger=migrator t=2025-01-13T17:23:39.744834524Z level=info msg="Migration successfully executed" id="add column for to alert_rule" duration=739.217µs
logger=migrator t=2025-01-13T17:23:39.747483913Z level=info msg="Executing migration" id="add column annotations to alert_rule"
logger=migrator t=2025-01-13T17:23:39.748265891Z level=info msg="Migration successfully executed" id="add column annotations to alert_rule" duration=782.469µs
logger=migrator t=2025-01-13T17:23:39.75027164Z level=info msg="Executing migration" id="add column labels to alert_rule"
logger=migrator t=2025-01-13T17:23:39.75097443Z level=info msg="Migration successfully executed" id="add column labels to alert_rule" duration=703.562µs
logger=migrator t=2025-01-13T17:23:39.753729956Z level=info msg="Executing migration" id="remove unique index from alert_rule on org_id, title columns"
logger=migrator t=2025-01-13T17:23:39.754040475Z level=info msg="Migration successfully executed" id="remove unique index from alert_rule on org_id, title columns" duration=312.612µs
logger=migrator t=2025-01-13T17:23:39.756585229Z level=info msg="Executing migration" id="add index in alert_rule on org_id, namespase_uid and title columns"
logger=migrator t=2025-01-13T17:23:39.756873176Z level=info msg="Migration successfully executed" id="add index in alert_rule on org_id, namespase_uid and title columns" duration=288.729µs
logger=migrator t=2025-01-13T17:23:39.799126462Z level=info msg="Executing migration" id="add dashboard_uid column to alert_rule"
logger=migrator t=2025-01-13T17:23:39.799955297Z level=info msg="Migration successfully executed" id="add dashboard_uid column to alert_rule" duration=829.576µs
logger=migrator t=2025-01-13T17:23:39.816608957Z level=info msg="Executing migration" id="add panel_id column to alert_rule"
logger=migrator t=2025-01-13T17:23:39.817289165Z level=info msg="Migration successfully executed" id="add panel_id column to alert_rule" duration=680.929µs
logger=migrator t=2025-01-13T17:23:39.819696433Z level=info msg="Executing migration" id="add index in alert_rule on org_id, dashboard_uid and panel_id columns"
logger=migrator t=2025-01-13T17:23:39.819949094Z level=info msg="Migration successfully executed" id="add index in alert_rule on org_id, dashboard_uid and panel_id columns" duration=253.152µs
logger=migrator t=2025-01-13T17:23:39.824504398Z level=info msg="Executing migration" id="add rule_group_idx column to alert_rule"
logger=migrator t=2025-01-13T17:23:39.825179096Z level=info msg="Migration successfully executed" id="add rule_group_idx column to alert_rule" duration=675.82µs
logger=migrator t=2025-01-13T17:23:39.827535358Z level=info msg="Executing migration" id="add is_paused column to alert_rule table"
logger=migrator t=2025-01-13T17:23:39.828243669Z level=info msg="Migration successfully executed" id="add is_paused column to alert_rule table" duration=711.226µs
logger=migrator t=2025-01-13T17:23:39.830141496Z level=info msg="Executing migration" id="fix is_paused column for alert_rule table"
logger=migrator t=2025-01-13T17:23:39.830249317Z level=info msg="Migration successfully executed" id="fix is_paused column for alert_rule table" duration=105.787µs
logger=migrator t=2025-01-13T17:23:39.832235029Z level=info msg="Executing migration" id="create alert_rule_version table"
logger=migrator t=2025-01-13T17:23:39.832611871Z level=info msg="Migration successfully executed" id="create alert_rule_version table" duration=375.83µs
logger=migrator t=2025-01-13T17:23:39.835429904Z level=info msg="Executing migration" id="add index in alert_rule_version table on rule_org_id, rule_uid and version columns"
logger=migrator t=2025-01-13T17:23:39.835956696Z level=info msg="Migration successfully executed" id="add index in alert_rule_version table on rule_org_id, rule_uid and version columns" duration=526.702µs
logger=migrator t=2025-01-13T17:23:39.839091059Z level=info msg="Executing migration" id="add index in alert_rule_version table on rule_org_id, rule_namespace_uid and rule_group columns"
logger=migrator t=2025-01-13T17:23:39.839698171Z level=info msg="Migration successfully executed" id="add index in alert_rule_version table on rule_org_id, rule_namespace_uid and rule_group columns" duration=606.811µs
logger=migrator t=2025-01-13T17:23:39.842372766Z level=info msg="Executing migration" id="alter alert_rule_version table data column to mediumtext in mysql"
logger=migrator t=2025-01-13T17:23:39.842579993Z level=info msg="Migration successfully executed" id="alter alert_rule_version table data column to mediumtext in mysql" duration=207.447µs
logger=migrator t=2025-01-13T17:23:39.844977592Z level=info msg="Executing migration" id="add column for to alert_rule_version"
logger=migrator t=2025-01-13T17:23:39.846497976Z level=info msg="Migration successfully executed" id="add column for to alert_rule_version" duration=1.520114ms
logger=migrator t=2025-01-13T17:23:39.849074479Z level=info msg="Executing migration" id="add column annotations to alert_rule_version"
logger=migrator t=2025-01-13T17:23:39.850525995Z level=info msg="Migration successfully executed" id="add column annotations to alert_rule_version" duration=1.451837ms
logger=migrator t=2025-01-13T17:23:39.853412135Z level=info msg="Executing migration" id="add column labels to alert_rule_version"
logger=migrator t=2025-01-13T17:23:39.854877306Z level=info msg="Migration successfully executed" id="add column labels to alert_rule_version" duration=1.464871ms
logger=migrator t=2025-01-13T17:23:39.898499791Z level=info msg="Executing migration" id="add rule_group_idx column to alert_rule_version"
logger=migrator t=2025-01-13T17:23:39.899477805Z level=info msg="Migration successfully executed" id="add rule_group_idx column to alert_rule_version" duration=977.061µs
logger=migrator t=2025-01-13T17:23:39.91681892Z level=info msg="Executing migration" id="add is_paused column to alert_rule_versions table"
logger=migrator t=2025-01-13T17:23:39.917526358Z level=info msg="Migration successfully executed" id="add is_paused column to alert_rule_versions table" duration=708.42µs
logger=migrator t=2025-01-13T17:23:39.919826683Z level=info msg="Executing migration" id="fix is_paused column for alert_rule_version table"
logger=migrator t=2025-01-13T17:23:39.919859143Z level=info msg="Migration successfully executed" id="fix is_paused column for alert_rule_version table" duration=34.825µs
logger=migrator t=2025-01-13T17:23:39.921651307Z level=info msg="Executing migration" id=create_alert_configuration_table
logger=migrator t=2025-01-13T17:23:39.921981643Z level=info msg="Migration successfully executed" id=create_alert_configuration_table duration=331.218µs
logger=migrator t=2025-01-13T17:23:39.924481663Z level=info msg="Executing migration" id="Add column default in alert_configuration"
logger=migrator t=2025-01-13T17:23:39.925154778Z level=info msg="Migration successfully executed" id="Add column default in alert_configuration" duration=673.807µs
logger=migrator t=2025-01-13T17:23:39.927425688Z level=info msg="Executing migration" id="alert alert_configuration alertmanager_configuration column from TEXT to MEDIUMTEXT if mysql"
logger=migrator t=2025-01-13T17:23:39.927548688Z level=info msg="Migration successfully executed" id="alert alert_configuration alertmanager_configuration column from TEXT to MEDIUMTEXT if mysql" duration=123.921µs
logger=migrator t=2025-01-13T17:23:39.929257316Z level=info msg="Executing migration" id="add column org_id in alert_configuration"
logger=migrator t=2025-01-13T17:23:39.929923988Z level=info msg="Migration successfully executed" id="add column org_id in alert_configuration" duration=667.465µs
logger=migrator t=2025-01-13T17:23:39.932694303Z level=info msg="Executing migration" id="add index in alert_configuration table on org_id column"
logger=migrator t=2025-01-13T17:23:39.933010753Z level=info msg="Migration successfully executed" id="add index in alert_configuration table on org_id column" duration=316.85µs
logger=migrator t=2025-01-13T17:23:39.935832763Z level=info msg="Executing migration" id="add configuration_hash column to alert_configuration"
logger=migrator t=2025-01-13T17:23:39.93651258Z level=info msg="Migration successfully executed" id="add configuration_hash column to alert_configuration" duration=680.488µs
logger=migrator t=2025-01-13T17:23:39.938289439Z level=info msg="Executing migration" id=create_ngalert_configuration_table
logger=migrator t=2025-01-13T17:23:39.938639632Z level=info msg="Migration successfully executed" id=create_ngalert_configuration_table duration=350.103µs
logger=migrator t=2025-01-13T17:23:39.941409057Z level=info msg="Executing migration" id="add index in ngalert_configuration on org_id column"
logger=migrator t=2025-01-13T17:23:39.941733593Z level=info msg="Migration successfully executed" id="add index in ngalert_configuration on org_id column" duration=324.475µs
logger=migrator t=2025-01-13T17:23:39.9444273Z level=info msg="Executing migration" id="add column send_alerts_to in ngalert_configuration"
logger=migrator t=2025-01-13T17:23:39.945120272Z level=info msg="Migration successfully executed" id="add column send_alerts_to in ngalert_configuration" duration=693.673µs
logger=migrator t=2025-01-13T17:23:39.947443342Z level=info msg="Executing migration" id="create provenance_type table"
logger=migrator t=2025-01-13T17:23:39.947713646Z level=info msg="Migration successfully executed" id="create provenance_type table" duration=270.714µs
logger=migrator t=2025-01-13T17:23:39.949956728Z level=info msg="Executing migration" id="add index to uniquify (record_key, record_type, org_id) columns"
logger=migrator t=2025-01-13T17:23:39.950256166Z level=info msg="Migration successfully executed" id="add index to uniquify (record_key, record_type, org_id) columns" duration=299.899µs
logger=migrator t=2025-01-13T17:23:39.952680816Z level=info msg="Executing migration" id="create alert_image table"
logger=migrator t=2025-01-13T17:23:39.952915243Z level=info msg="Migration successfully executed" id="create alert_image table" duration=233.696µs
logger=migrator t=2025-01-13T17:23:39.955324453Z level=info msg="Executing migration" id="add unique index on token to alert_image table"
logger=migrator t=2025-01-13T17:23:39.955580371Z level=info msg="Migration successfully executed" id="add unique index on token to alert_image table" duration=256.628µs
logger=migrator t=2025-01-13T17:23:39.958129633Z level=info msg="Executing migration" id="support longer URLs in alert_image table"
logger=migrator t=2025-01-13T17:23:39.958199393Z level=info msg="Migration successfully executed" id="support longer URLs in alert_image table" duration=72.866µs
logger=migrator t=2025-01-13T17:23:39.960412318Z level=info msg="Executing migration" id=create_alert_configuration_history_table
logger=migrator t=2025-01-13T17:23:39.960727024Z level=info msg="Migration successfully executed" id=create_alert_configuration_history_table duration=315.648µs
logger=migrator t=2025-01-13T17:23:39.96347644Z level=info msg="Executing migration" id="drop non-unique orgID index on alert_configuration"
logger=migrator t=2025-01-13T17:23:39.963736715Z level=info msg="Migration successfully executed" id="drop non-unique orgID index on alert_configuration" duration=262.349µs
logger=migrator t=2025-01-13T17:23:39.998779677Z level=info msg="Executing migration" id="drop unique orgID index on alert_configuration if exists"
logger=migrator t=2025-01-13T17:23:39.998944344Z level=warn msg="Skipping migration: Already executed, but not recorded in migration log" id="drop unique orgID index on alert_configuration if exists"
logger=migrator t=2025-01-13T17:23:40.016691109Z level=info msg="Executing migration" id="extract alertmanager configuration history to separate table"
logger=migrator t=2025-01-13T17:23:40.016962164Z level=info msg="Migration successfully executed" id="extract alertmanager configuration history to separate table" duration=273.971µs
logger=migrator t=2025-01-13T17:23:40.018779308Z level=info msg="Executing migration" id="add unique index on orgID to alert_configuration"
logger=migrator t=2025-01-13T17:23:40.019095648Z level=info msg="Migration successfully executed" id="add unique index on orgID to alert_configuration" duration=317.081µs
logger=migrator t=2025-01-13T17:23:40.021459594Z level=info msg="Executing migration" id="add last_applied column to alert_configuration_history"
logger=migrator t=2025-01-13T17:23:40.022110668Z level=info msg="Migration successfully executed" id="add last_applied column to alert_configuration_history" duration=651.935µs
logger=migrator t=2025-01-13T17:23:40.024333602Z level=info msg="Executing migration" id="create library_element table v1"
logger=migrator t=2025-01-13T17:23:40.024617601Z level=info msg="Migration successfully executed" id="create library_element table v1" duration=284.761µs
logger=migrator t=2025-01-13T17:23:40.027358704Z level=info msg="Executing migration" id="add index library_element org_id-folder_id-name-kind"
logger=migrator t=2025-01-13T17:23:40.027713896Z level=info msg="Migration successfully executed" id="add index library_element org_id-folder_id-name-kind" duration=356.084µs
logger=migrator t=2025-01-13T17:23:40.029938914Z level=info msg="Executing migration" id="create library_element_connection table v1"
logger=migrator t=2025-01-13T17:23:40.030162972Z level=info msg="Migration successfully executed" id="create library_element_connection table v1" duration=225.31µs
logger=migrator t=2025-01-13T17:23:40.032723431Z level=info msg="Executing migration" id="add index library_element_connection element_id-kind-connection_id"
logger=migrator t=2025-01-13T17:23:40.033057514Z level=info msg="Migration successfully executed" id="add index library_element_connection element_id-kind-connection_id" duration=334.724µs
logger=migrator t=2025-01-13T17:23:40.035655367Z level=info msg="Executing migration" id="add unique index library_element org_id_uid"
logger=migrator t=2025-01-13T17:23:40.035996302Z level=info msg="Migration successfully executed" id="add unique index library_element org_id_uid" duration=341.687µs
logger=migrator t=2025-01-13T17:23:40.038364486Z level=info msg="Executing migration" id="increase max description length to 2048"
logger=migrator t=2025-01-13T17:23:40.038391327Z level=info msg="Migration successfully executed" id="increase max description length to 2048" duration=27.802µs
logger=migrator t=2025-01-13T17:23:40.040931752Z level=info msg="Executing migration" id="alter library_element model to mediumtext"
logger=migrator t=2025-01-13T17:23:40.040970965Z level=info msg="Migration successfully executed" id="alter library_element model to mediumtext" duration=59.187µs
logger=migrator t=2025-01-13T17:23:40.043465755Z level=info msg="Executing migration" id="add library_element folder uid"
logger=migrator t=2025-01-13T17:23:40.044353651Z level=info msg="Migration successfully executed" id="add library_element folder uid" duration=888.396µs
logger=migrator t=2025-01-13T17:23:40.046306124Z level=info msg="Executing migration" id="populate library_element folder_uid"
logger=migrator t=2025-01-13T17:23:40.046517077Z level=info msg="Migration successfully executed" id="populate library_element folder_uid" duration=212.265µs
logger=migrator t=2025-01-13T17:23:40.048728586Z level=info msg="Executing migration" id="add index library_element org_id-folder_uid-name-kind"
logger=migrator t=2025-01-13T17:23:40.049076765Z level=info msg="Migration successfully executed" id="add index library_element org_id-folder_uid-name-kind" duration=348.65µs
logger=migrator t=2025-01-13T17:23:40.051735751Z level=info msg="Executing migration" id="clone move dashboard alerts to unified alerting"
logger=migrator t=2025-01-13T17:23:40.05295604Z level=info msg="Migration successfully executed" id="clone move dashboard alerts to unified alerting" duration=1.219947ms
logger=migrator t=2025-01-13T17:23:40.056344422Z level=info msg="Executing migration" id="create data_keys table"
logger=migrator t=2025-01-13T17:23:40.056614756Z level=info msg="Migration successfully executed" id="create data_keys table" duration=270.154µs
logger=migrator t=2025-01-13T17:23:40.05923455Z level=info msg="Executing migration" id="create secrets table"
logger=migrator t=2025-01-13T17:23:40.059479897Z level=info msg="Migration successfully executed" id="create secrets table" duration=246.008µs
logger=migrator t=2025-01-13T17:23:40.062417025Z level=info msg="Executing migration" id="rename data_keys name column to id"
logger=migrator t=2025-01-13T17:23:40.066000796Z level=info msg="Migration successfully executed" id="rename data_keys name column to id" duration=3.581336ms
logger=migrator t=2025-01-13T17:23:40.116649479Z level=info msg="Executing migration" id="add name column into data_keys"
logger=migrator t=2025-01-13T17:23:40.117516535Z level=info msg="Migration successfully executed" id="add name column into data_keys" duration=867.537µs
logger=migrator t=2025-01-13T17:23:40.120155044Z level=info msg="Executing migration" id="copy data_keys id column values into name"
logger=migrator t=2025-01-13T17:23:40.120318288Z level=info msg="Migration successfully executed" id="copy data_keys id column values into name" duration=164.246µs
logger=migrator t=2025-01-13T17:23:40.12219142Z level=info msg="Executing migration" id="rename data_keys name column to label"
logger=migrator t=2025-01-13T17:23:40.126298806Z level=info msg="Migration successfully executed" id="rename data_keys name column to label" duration=4.107727ms
logger=migrator t=2025-01-13T17:23:40.128585705Z level=info msg="Executing migration" id="rename data_keys id column back to name"
logger=migrator t=2025-01-13T17:23:40.131351892Z level=info msg="Migration successfully executed" id="rename data_keys id column back to name" duration=2.767148ms
logger=migrator t=2025-01-13T17:23:40.133677828Z level=info msg="Executing migration" id="create kv_store table v1"
logger=migrator t=2025-01-13T17:23:40.13395832Z level=info msg="Migration successfully executed" id="create kv_store table v1" duration=281.255µs
logger=migrator t=2025-01-13T17:23:40.136520336Z level=info msg="Executing migration" id="add index kv_store.org_id-namespace-key"
logger=migrator t=2025-01-13T17:23:40.136883333Z level=info msg="Migration successfully executed" id="add index kv_store.org_id-namespace-key" duration=363.647µs
logger=migrator t=2025-01-13T17:23:40.13983775Z level=info msg="Executing migration" id="update dashboard_uid and panel_id from existing annotations"
logger=migrator t=2025-01-13T17:23:40.140032122Z level=info msg="Migration successfully executed" id="update dashboard_uid and panel_id from existing annotations" duration=194.863µs
logger=migrator t=2025-01-13T17:23:40.142188906Z level=info msg="Executing migration" id="create permission table"
logger=migrator t=2025-01-13T17:23:40.14253412Z level=info msg="Migration successfully executed" id="create permission table" duration=344.883µs
logger=migrator t=2025-01-13T17:23:40.145270598Z level=info msg="Executing migration" id="add unique index permission.role_id"
logger=migrator t=2025-01-13T17:23:40.214007939Z level=info msg="Migration successfully executed" id="add unique index permission.role_id" duration=68.738233ms
logger=migrator t=2025-01-13T17:23:40.217418791Z level=info msg="Executing migration" id="add unique index role_id_action_scope"
logger=migrator t=2025-01-13T17:23:40.217771418Z level=info msg="Migration successfully executed" id="add unique index role_id_action_scope" duration=354.581µs
logger=migrator t=2025-01-13T17:23:40.220439198Z level=info msg="Executing migration" id="create role table"
logger=migrator t=2025-01-13T17:23:40.220723427Z level=info msg="Migration successfully executed" id="create role table" duration=285.082µs
logger=migrator t=2025-01-13T17:23:40.22368964Z level=info msg="Executing migration" id="add column display_name"
logger=migrator t=2025-01-13T17:23:40.224547038Z level=info msg="Migration successfully executed" id="add column display_name" duration=857.408µs
logger=migrator t=2025-01-13T17:23:40.2272212Z level=info msg="Executing migration" id="add column group_name"
logger=migrator t=2025-01-13T17:23:40.228054814Z level=info msg="Migration successfully executed" id="add column group_name" duration=836.5µs
logger=migrator t=2025-01-13T17:23:40.230082864Z level=info msg="Executing migration" id="add index role.org_id"
logger=migrator t=2025-01-13T17:23:40.230350373Z level=info msg="Migration successfully executed" id="add index role.org_id" duration=268.019µs
logger=migrator t=2025-01-13T17:23:40.233554826Z level=info msg="Executing migration" id="add unique index role_org_id_name"
logger=migrator t=2025-01-13T17:23:40.233908295Z level=info msg="Migration successfully executed" id="add unique index role_org_id_name" duration=357.105µs
logger=migrator t=2025-01-13T17:23:40.2370477Z level=info msg="Executing migration" id="add index role_org_id_uid"
logger=migrator t=2025-01-13T17:23:40.237419663Z level=info msg="Migration successfully executed" id="add index role_org_id_uid" duration=372.685µs
logger=migrator t=2025-01-13T17:23:40.242026358Z level=info msg="Executing migration" id="create team role table"
logger=migrator t=2025-01-13T17:23:40.242354529Z level=info msg="Migration successfully executed" id="create team role table" duration=328.191µs
logger=migrator t=2025-01-13T17:23:40.245477905Z level=info msg="Executing migration" id="add index team_role.org_id"
logger=migrator t=2025-01-13T17:23:40.245836123Z level=info msg="Migration successfully executed" id="add index team_role.org_id" duration=359.019µs
logger=migrator t=2025-01-13T17:23:40.248572423Z level=info msg="Executing migration" id="add unique index team_role_org_id_team_id_role_id"
logger=migrator t=2025-01-13T17:23:40.24885514Z level=info msg="Migration successfully executed" id="add unique index team_role_org_id_team_id_role_id" duration=282.988µs
logger=migrator t=2025-01-13T17:23:40.251508797Z level=info msg="Executing migration" id="add index team_role.team_id"
logger=migrator t=2025-01-13T17:23:40.25181643Z level=info msg="Migration successfully executed" id="add index team_role.team_id" duration=308.806µs
logger=migrator t=2025-01-13T17:23:40.254132989Z level=info msg="Executing migration" id="create user role table"
logger=migrator t=2025-01-13T17:23:40.254374038Z level=info msg="Migration successfully executed" id="create user role table" duration=241.581µs
logger=migrator t=2025-01-13T17:23:40.256811321Z level=info msg="Executing migration" id="add index user_role.org_id"
logger=migrator t=2025-01-13T17:23:40.257143961Z level=info msg="Migration successfully executed" id="add index user_role.org_id" duration=333.662µs
logger=migrator t=2025-01-13T17:23:40.259700343Z level=info msg="Executing migration" id="add unique index user_role_org_id_user_id_role_id"
logger=migrator t=2025-01-13T17:23:40.260054924Z level=info msg="Migration successfully executed" id="add unique index user_role_org_id_user_id_role_id" duration=355.572µs
logger=migrator t=2025-01-13T17:23:40.262349481Z level=info msg="Executing migration" id="add index user_role.user_id"
logger=migrator t=2025-01-13T17:23:40.262699935Z level=info msg="Migration successfully executed" id="add index user_role.user_id" duration=351.255µs
logger=migrator t=2025-01-13T17:23:40.265196181Z level=info msg="Executing migration" id="create builtin role table"
logger=migrator t=2025-01-13T17:23:40.265486011Z level=info msg="Migration successfully executed" id="create builtin role table" duration=289.039µs
logger=migrator t=2025-01-13T17:23:40.2679922Z level=info msg="Executing migration" id="add index builtin_role.role_id"
logger=migrator t=2025-01-13T17:23:40.296303815Z level=info msg="Migration successfully executed" id="add index builtin_role.role_id" duration=28.307958ms
logger=migrator t=2025-01-13T17:23:40.299808792Z level=info msg="Executing migration" id="add index builtin_role.name"
logger=migrator t=2025-01-13T17:23:40.300066742Z level=info msg="Migration successfully executed" id="add index builtin_role.name" duration=258.882µs
logger=migrator t=2025-01-13T17:23:40.316763566Z level=info msg="Executing migration" id="Add column org_id to builtin_role table"
logger=migrator t=2025-01-13T17:23:40.31758604Z level=info msg="Migration successfully executed" id="Add column org_id to builtin_role table" duration=829.596µs
logger=migrator t=2025-01-13T17:23:40.320514886Z level=info msg="Executing migration" id="add index builtin_role.org_id"
logger=migrator t=2025-01-13T17:23:40.320848478Z level=info msg="Migration successfully executed" id="add index builtin_role.org_id" duration=334.363µs
logger=migrator t=2025-01-13T17:23:40.323716805Z level=info msg="Executing migration" id="add unique index builtin_role_org_id_role_id_role"
logger=migrator t=2025-01-13T17:23:40.323993691Z level=info msg="Migration successfully executed" id="add unique index builtin_role_org_id_role_id_role" duration=270.224µs
logger=migrator t=2025-01-13T17:23:40.326225735Z level=info msg="Executing migration" id="Remove unique index role_org_id_uid"
logger=migrator t=2025-01-13T17:23:40.326587469Z level=info msg="Migration successfully executed" id="Remove unique index role_org_id_uid" duration=362.405µs
logger=migrator t=2025-01-13T17:23:40.328972962Z level=info msg="Executing migration" id="add unique index role.uid"
logger=migrator t=2025-01-13T17:23:40.329307737Z level=info msg="Migration successfully executed" id="add unique index role.uid" duration=335.676µs
logger=migrator t=2025-01-13T17:23:40.331936878Z level=info msg="Executing migration" id="create seed assignment table"
logger=migrator t=2025-01-13T17:23:40.332195449Z level=info msg="Migration successfully executed" id="create seed assignment table" duration=258.462µs
logger=migrator t=2025-01-13T17:23:40.338037473Z level=info msg="Executing migration" id="add unique index builtin_role_role_name"
logger=migrator t=2025-01-13T17:23:40.33857265Z level=info msg="Migration successfully executed" id="add unique index builtin_role_role_name" duration=535.218µs
logger=migrator t=2025-01-13T17:23:40.344764088Z level=info msg="Executing migration" id="add column hidden to role table"
logger=migrator t=2025-01-13T17:23:40.34625113Z level=info msg="Migration successfully executed" id="add column hidden to role table" duration=1.486671ms
logger=migrator t=2025-01-13T17:23:40.349930302Z level=info msg="Executing migration" id="permission kind migration"
logger=migrator t=2025-01-13T17:23:40.353010043Z level=info msg="Migration successfully executed" id="permission kind migration" duration=3.079851ms
logger=migrator t=2025-01-13T17:23:40.357129528Z level=info msg="Executing migration" id="permission attribute migration"
logger=migrator t=2025-01-13T17:23:40.358171641Z level=info msg="Migration successfully executed" id="permission attribute migration" duration=1.041922ms
logger=migrator t=2025-01-13T17:23:40.397542962Z level=info msg="Executing migration" id="permission identifier migration"
logger=migrator t=2025-01-13T17:23:40.413865739Z level=info msg="Migration successfully executed" id="permission identifier migration" duration=16.322757ms
logger=migrator t=2025-01-13T17:23:40.417687664Z level=info msg="Executing migration" id="add permission identifier index"
logger=migrator t=2025-01-13T17:23:40.418111624Z level=info msg="Migration successfully executed" id="add permission identifier index" duration=423.971µs
logger=migrator t=2025-01-13T17:23:40.420839168Z level=info msg="Executing migration" id="add permission action scope role_id index"
logger=migrator t=2025-01-13T17:23:40.421158744Z level=info msg="Migration successfully executed" id="add permission action scope role_id index" duration=319.576µs
logger=migrator t=2025-01-13T17:23:40.424656978Z level=info msg="Executing migration" id="remove permission role_id action scope index"
logger=migrator t=2025-01-13T17:23:40.425115853Z level=info msg="Migration successfully executed" id="remove permission role_id action scope index" duration=458.575µs
logger=migrator t=2025-01-13T17:23:40.429092784Z level=info msg="Executing migration" id="add group mapping UID column to user_role table"
logger=migrator t=2025-01-13T17:23:40.42992237Z level=info msg="Migration successfully executed" id="add group mapping UID column to user_role table" duration=829.667µs
logger=migrator t=2025-01-13T17:23:40.432492033Z level=info msg="Executing migration" id="add user_role org ID, user ID, role ID, group mapping UID index"
logger=migrator t=2025-01-13T17:23:40.432905564Z level=info msg="Migration successfully executed" id="add user_role org ID, user ID, role ID, group mapping UID index" duration=414.192µs
logger=migrator t=2025-01-13T17:23:40.435653446Z level=info msg="Executing migration" id="remove user_role org ID, user ID, role ID index"
logger=migrator t=2025-01-13T17:23:40.435911768Z level=info msg="Migration successfully executed" id="remove user_role org ID, user ID, role ID index" duration=259.103µs
logger=migrator t=2025-01-13T17:23:40.437727312Z level=info msg="Executing migration" id="create query_history table v1"
logger=migrator t=2025-01-13T17:23:40.437997967Z level=info msg="Migration successfully executed" id="create query_history table v1" duration=271.276µs
logger=migrator t=2025-01-13T17:23:40.441177761Z level=info msg="Executing migration" id="add index query_history.org_id-created_by-datasource_uid"
logger=migrator t=2025-01-13T17:23:40.441534866Z level=info msg="Migration successfully executed" id="add index query_history.org_id-created_by-datasource_uid" duration=357.156µs
logger=migrator t=2025-01-13T17:23:40.444138069Z level=info msg="Executing migration" id="alter table query_history alter column created_by type to bigint"
logger=migrator t=2025-01-13T17:23:40.444174076Z level=info msg="Migration successfully executed" id="alter table query_history alter column created_by type to bigint" duration=36.678µs
logger=migrator t=2025-01-13T17:23:40.445958265Z level=info msg="Executing migration" id="create query_history_details table v1"
logger=migrator t=2025-01-13T17:23:40.446285405Z level=info msg="Migration successfully executed" id="create query_history_details table v1" duration=323.123µs
logger=migrator t=2025-01-13T17:23:40.449339485Z level=info msg="Executing migration" id="rbac disabled migrator"
logger=migrator t=2025-01-13T17:23:40.449455521Z level=info msg="Migration successfully executed" id="rbac disabled migrator" duration=116.036µs
logger=migrator t=2025-01-13T17:23:40.452503175Z level=info msg="Executing migration" id="teams permissions migration"
logger=migrator t=2025-01-13T17:23:40.452781815Z level=info msg="Migration successfully executed" id="teams permissions migration" duration=281.906µs
logger=migrator t=2025-01-13T17:23:40.454589551Z level=info msg="Executing migration" id="dashboard permissions"
logger=migrator t=2025-01-13T17:23:40.454932601Z level=info msg="Migration successfully executed" id="dashboard permissions" duration=344.873µs
logger=migrator t=2025-01-13T17:23:40.457186562Z level=info msg="Executing migration" id="dashboard permissions uid scopes"
logger=migrator t=2025-01-13T17:23:40.457389731Z level=info msg="Migration successfully executed" id="dashboard permissions uid scopes" duration=203.639µs
logger=migrator t=2025-01-13T17:23:40.516264992Z level=info msg="Executing migration" id="drop managed folder create actions"
logger=migrator t=2025-01-13T17:23:40.516421544Z level=info msg="Migration successfully executed" id="drop managed folder create actions" duration=155.059µs
logger=migrator t=2025-01-13T17:23:40.518432349Z level=info msg="Executing migration" id="alerting notification permissions"
logger=migrator t=2025-01-13T17:23:40.518723863Z level=info msg="Migration successfully executed" id="alerting notification permissions" duration=291.684µs
logger=migrator t=2025-01-13T17:23:40.521248903Z level=info msg="Executing migration" id="create query_history_star table v1"
logger=migrator t=2025-01-13T17:23:40.521568709Z level=info msg="Migration successfully executed" id="create query_history_star table v1" duration=320.768µs
logger=migrator t=2025-01-13T17:23:40.524481786Z level=info msg="Executing migration" id="add index query_history.user_id-query_uid"
logger=migrator t=2025-01-13T17:23:40.52548521Z level=info msg="Migration successfully executed" id="add index query_history.user_id-query_uid" duration=1.004005ms
logger=migrator t=2025-01-13T17:23:40.528908491Z level=info msg="Executing migration" id="add column org_id in query_history_star"
logger=migrator t=2025-01-13T17:23:40.530543989Z level=info msg="Migration successfully executed" id="add column org_id in query_history_star" duration=1.667298ms
logger=migrator t=2025-01-13T17:23:40.533602037Z level=info msg="Executing migration" id="alter table query_history_star_mig column user_id type to bigint"
logger=migrator t=2025-01-13T17:23:40.533641119Z level=info msg="Migration successfully executed" id="alter table query_history_star_mig column user_id type to bigint" duration=39.714µs
logger=migrator t=2025-01-13T17:23:40.536070227Z level=info msg="Executing migration" id="create correlation table v1"
logger=migrator t=2025-01-13T17:23:40.536392528Z level=info msg="Migration successfully executed" id="create correlation table v1" duration=322.07µs
logger=migrator t=2025-01-13T17:23:40.540196549Z level=info msg="Executing migration" id="add index correlations.uid"
logger=migrator t=2025-01-13T17:23:40.540708844Z level=info msg="Migration successfully executed" id="add index correlations.uid" duration=511.874µs
logger=migrator t=2025-01-13T17:23:40.676484223Z level=info msg="Executing migration" id="add index correlations.source_uid"
logger=migrator t=2025-01-13T17:23:40.676990136Z level=info msg="Migration successfully executed" id="add index correlations.source_uid" duration=508.477µs
logger=migrator t=2025-01-13T17:23:40.680524752Z level=info msg="Executing migration" id="add correlation config column"
logger=migrator t=2025-01-13T17:23:40.682345696Z level=info msg="Migration successfully executed" id="add correlation config column" duration=1.825062ms
logger=migrator t=2025-01-13T17:23:40.684901951Z level=info msg="Executing migration" id="drop index IDX_correlation_uid - v1"
logger=migrator t=2025-01-13T17:23:40.685404528Z level=info msg="Migration successfully executed" id="drop index IDX_correlation_uid - v1" duration=502.277µs
logger=migrator t=2025-01-13T17:23:40.687766861Z level=info msg="Executing migration" id="drop index IDX_correlation_source_uid - v1"
logger=migrator t=2025-01-13T17:23:40.688267274Z level=info msg="Migration successfully executed" id="drop index IDX_correlation_source_uid - v1" duration=500.934µs
logger=migrator t=2025-01-13T17:23:40.691774145Z level=info msg="Executing migration" id="Rename table correlation to correlation_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:40.695279669Z level=info msg="Migration successfully executed" id="Rename table correlation to correlation_tmp_qwerty - v1" duration=3.505544ms
logger=migrator t=2025-01-13T17:23:40.69746871Z level=info msg="Executing migration" id="create correlation v2"
logger=migrator t=2025-01-13T17:23:40.697826577Z level=info msg="Migration successfully executed" id="create correlation v2" duration=357.767µs
logger=migrator t=2025-01-13T17:23:40.701220433Z level=info msg="Executing migration" id="create index IDX_correlation_uid - v2"
logger=migrator t=2025-01-13T17:23:40.701632862Z level=info msg="Migration successfully executed" id="create index IDX_correlation_uid - v2" duration=412.68µs
logger=migrator t=2025-01-13T17:23:40.704026925Z level=info msg="Executing migration" id="create index IDX_correlation_source_uid - v2"
logger=migrator t=2025-01-13T17:23:40.7044699Z level=info msg="Migration successfully executed" id="create index IDX_correlation_source_uid - v2" duration=443.677µs
logger=migrator t=2025-01-13T17:23:40.706971995Z level=info msg="Executing migration" id="create index IDX_correlation_org_id - v2"
logger=migrator t=2025-01-13T17:23:40.707314343Z level=info msg="Migration successfully executed" id="create index IDX_correlation_org_id - v2" duration=342.318µs
logger=migrator t=2025-01-13T17:23:40.709462647Z level=info msg="Executing migration" id="copy correlation v1 to v2"
logger=migrator t=2025-01-13T17:23:40.709584344Z level=info msg="Migration successfully executed" id="copy correlation v1 to v2" duration=120.064µs
logger=migrator t=2025-01-13T17:23:40.711783203Z level=info msg="Executing migration" id="drop correlation_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:40.712155066Z level=info msg="Migration successfully executed" id="drop correlation_tmp_qwerty" duration=371.873µs
logger=migrator t=2025-01-13T17:23:40.714062372Z level=info msg="Executing migration" id="add provisioning column"
logger=migrator t=2025-01-13T17:23:40.718897114Z level=info msg="Migration successfully executed" id="add provisioning column" duration=4.834512ms
logger=migrator t=2025-01-13T17:23:40.721297398Z level=info msg="Executing migration" id="add type column"
logger=migrator t=2025-01-13T17:23:40.722136833Z level=info msg="Migration successfully executed" id="add type column" duration=839.425µs
logger=migrator t=2025-01-13T17:23:40.724704259Z level=info msg="Executing migration" id="create entity_events table"
logger=migrator t=2025-01-13T17:23:40.724983259Z level=info msg="Migration successfully executed" id="create entity_events table" duration=278.89µs
logger=migrator t=2025-01-13T17:23:40.727553366Z level=info msg="Executing migration" id="create dashboard public config v1"
logger=migrator t=2025-01-13T17:23:40.727890194Z level=info msg="Migration successfully executed" id="create dashboard public config v1" duration=337.9µs
logger=migrator t=2025-01-13T17:23:40.730401025Z level=info msg="Executing migration" id="drop index UQE_dashboard_public_config_uid - v1"
logger=migrator t=2025-01-13T17:23:40.730652467Z level=warn msg="Skipping migration: Already executed, but not recorded in migration log" id="drop index UQE_dashboard_public_config_uid - v1"
logger=migrator t=2025-01-13T17:23:40.732858238Z level=info msg="Executing migration" id="drop index IDX_dashboard_public_config_org_id_dashboard_uid - v1"
logger=migrator t=2025-01-13T17:23:40.733011093Z level=warn msg="Skipping migration: Already executed, but not recorded in migration log" id="drop index IDX_dashboard_public_config_org_id_dashboard_uid - v1"
logger=migrator t=2025-01-13T17:23:40.734718062Z level=info msg="Executing migration" id="Drop old dashboard public config table"
logger=migrator t=2025-01-13T17:23:40.73528027Z level=info msg="Migration successfully executed" id="Drop old dashboard public config table" duration=561.717µs
logger=migrator t=2025-01-13T17:23:40.737791751Z level=info msg="Executing migration" id="recreate dashboard public config v1"
logger=migrator t=2025-01-13T17:23:40.738186607Z level=info msg="Migration successfully executed" id="recreate dashboard public config v1" duration=393.583µs
logger=migrator t=2025-01-13T17:23:40.740504391Z level=info msg="Executing migration" id="create index UQE_dashboard_public_config_uid - v1"
logger=migrator t=2025-01-13T17:23:40.740831912Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_public_config_uid - v1" duration=328.402µs
logger=migrator t=2025-01-13T17:23:40.743385238Z level=info msg="Executing migration" id="create index IDX_dashboard_public_config_org_id_dashboard_uid - v1"
logger=migrator t=2025-01-13T17:23:40.743706167Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_public_config_org_id_dashboard_uid - v1" duration=322µs
logger=migrator t=2025-01-13T17:23:40.745901479Z level=info msg="Executing migration" id="drop index UQE_dashboard_public_config_uid - v2"
logger=migrator t=2025-01-13T17:23:40.746227096Z level=info msg="Migration successfully executed" id="drop index UQE_dashboard_public_config_uid - v2" duration=326.598µs
logger=migrator t=2025-01-13T17:23:40.748555235Z level=info msg="Executing migration" id="drop index IDX_dashboard_public_config_org_id_dashboard_uid - v2"
logger=migrator t=2025-01-13T17:23:40.748899848Z level=info msg="Migration successfully executed" id="drop index IDX_dashboard_public_config_org_id_dashboard_uid - v2" duration=345.183µs
logger=migrator t=2025-01-13T17:23:40.751143073Z level=info msg="Executing migration" id="Drop public config table"
logger=migrator t=2025-01-13T17:23:40.751471595Z level=info msg="Migration successfully executed" id="Drop public config table" duration=329.484µs
logger=migrator t=2025-01-13T17:23:40.754277152Z level=info msg="Executing migration" id="Recreate dashboard public config v2"
logger=migrator t=2025-01-13T17:23:40.754693077Z level=info msg="Migration successfully executed" id="Recreate dashboard public config v2" duration=416.065µs
logger=migrator t=2025-01-13T17:23:40.757956614Z level=info msg="Executing migration" id="create index UQE_dashboard_public_config_uid - v2"
logger=migrator t=2025-01-13T17:23:40.758354576Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_public_config_uid - v2" duration=398.773µs
logger=migrator t=2025-01-13T17:23:40.799112278Z level=info msg="Executing migration" id="create index IDX_dashboard_public_config_org_id_dashboard_uid - v2"
logger=migrator t=2025-01-13T17:23:40.799554762Z level=info msg="Migration successfully executed" id="create index IDX_dashboard_public_config_org_id_dashboard_uid - v2" duration=444.439µs
logger=migrator t=2025-01-13T17:23:40.80209462Z level=info msg="Executing migration" id="create index UQE_dashboard_public_config_access_token - v2"
logger=migrator t=2025-01-13T17:23:40.802518661Z level=info msg="Migration successfully executed" id="create index UQE_dashboard_public_config_access_token - v2" duration=428.539µs
logger=migrator t=2025-01-13T17:23:40.805360976Z level=info msg="Executing migration" id="Rename table dashboard_public_config to dashboard_public - v2"
logger=migrator t=2025-01-13T17:23:40.808052753Z level=info msg="Migration successfully executed" id="Rename table dashboard_public_config to dashboard_public - v2" duration=2.692289ms
logger=migrator t=2025-01-13T17:23:40.816665862Z level=info msg="Executing migration" id="add annotations_enabled column"
logger=migrator t=2025-01-13T17:23:40.817676977Z level=info msg="Migration successfully executed" id="add annotations_enabled column" duration=1.011586ms
logger=migrator t=2025-01-13T17:23:40.820253406Z level=info msg="Executing migration" id="add time_selection_enabled column"
logger=migrator t=2025-01-13T17:23:40.821240597Z level=info msg="Migration successfully executed" id="add time_selection_enabled column" duration=999.504µs
logger=migrator t=2025-01-13T17:23:40.823636676Z level=info msg="Executing migration" id="delete orphaned public dashboards"
logger=migrator t=2025-01-13T17:23:40.823786706Z level=info msg="Migration successfully executed" id="delete orphaned public dashboards" duration=150.712µs
logger=migrator t=2025-01-13T17:23:40.825455473Z level=info msg="Executing migration" id="add share column"
logger=migrator t=2025-01-13T17:23:40.826922271Z level=info msg="Migration successfully executed" id="add share column" duration=1.466407ms
logger=migrator t=2025-01-13T17:23:41.304260606Z level=info msg="Executing migration" id="backfill empty share column fields with default of public"
logger=migrator t=2025-01-13T17:23:41.304396719Z level=info msg="Migration successfully executed" id="backfill empty share column fields with default of public" duration=140.051µs
logger=migrator t=2025-01-13T17:23:41.306319363Z level=info msg="Executing migration" id="create file table"
logger=migrator t=2025-01-13T17:23:41.3066931Z level=info msg="Migration successfully executed" id="create file table" duration=390.407µs
logger=migrator t=2025-01-13T17:23:41.330405979Z level=info msg="Executing migration" id="file table idx: path natural pk"
logger=migrator t=2025-01-13T17:23:41.330990198Z level=info msg="Migration successfully executed" id="file table idx: path natural pk" duration=584.63µs
logger=migrator t=2025-01-13T17:23:41.334258243Z level=info msg="Executing migration" id="file table idx: parent_folder_path_hash fast folder retrieval"
logger=migrator t=2025-01-13T17:23:41.334606753Z level=info msg="Migration successfully executed" id="file table idx: parent_folder_path_hash fast folder retrieval" duration=349.231µs
logger=migrator t=2025-01-13T17:23:41.337318485Z level=info msg="Executing migration" id="create file_meta table"
logger=migrator t=2025-01-13T17:23:41.337611471Z level=info msg="Migration successfully executed" id="create file_meta table" duration=293.838µs
logger=migrator t=2025-01-13T17:23:41.340570186Z level=info msg="Executing migration" id="file table idx: path key"
logger=migrator t=2025-01-13T17:23:41.340886636Z level=info msg="Migration successfully executed" id="file table idx: path key" duration=316.63µs
logger=migrator t=2025-01-13T17:23:41.343756539Z level=info msg="Executing migration" id="set path collation in file table"
logger=migrator t=2025-01-13T17:23:41.343787727Z level=info msg="Migration successfully executed" id="set path collation in file table" duration=32.731µs
logger=migrator t=2025-01-13T17:23:41.346141241Z level=info msg="Executing migration" id="migrate contents column to mediumblob for MySQL"
logger=migrator t=2025-01-13T17:23:41.346309965Z level=info msg="Migration successfully executed" id="migrate contents column to mediumblob for MySQL" duration=169.596µs
logger=migrator t=2025-01-13T17:23:41.348886882Z level=info msg="Executing migration" id="managed permissions migration"
logger=migrator t=2025-01-13T17:23:41.349058432Z level=info msg="Migration successfully executed" id="managed permissions migration" duration=172.201µs
logger=migrator t=2025-01-13T17:23:41.351153587Z level=info msg="Executing migration" id="managed folder permissions alert actions migration"
logger=migrator t=2025-01-13T17:23:41.351236733Z level=info msg="Migration successfully executed" id="managed folder permissions alert actions migration" duration=83.896µs
logger=migrator t=2025-01-13T17:23:41.353097919Z level=info msg="Executing migration" id="RBAC action name migrator"
logger=migrator t=2025-01-13T17:23:41.353471876Z level=info msg="Migration successfully executed" id="RBAC action name migrator" duration=374.899µs
logger=migrator t=2025-01-13T17:23:41.356047727Z level=info msg="Executing migration" id="Add UID column to playlist"
logger=migrator t=2025-01-13T17:23:41.357169839Z level=info msg="Migration successfully executed" id="Add UID column to playlist" duration=1.122062ms
logger=migrator t=2025-01-13T17:23:41.359767885Z level=info msg="Executing migration" id="Update uid column values in playlist"
logger=migrator t=2025-01-13T17:23:41.359831644Z level=info msg="Migration successfully executed" id="Update uid column values in playlist" duration=64.37µs
logger=migrator t=2025-01-13T17:23:41.362345216Z level=info msg="Executing migration" id="Add index for uid in playlist"
logger=migrator t=2025-01-13T17:23:41.362794076Z level=info msg="Migration successfully executed" id="Add index for uid in playlist" duration=448.71µs
logger=migrator t=2025-01-13T17:23:41.365556222Z level=info msg="Executing migration" id="update group index for alert rules"
logger=migrator t=2025-01-13T17:23:41.36589329Z level=info msg="Migration successfully executed" id="update group index for alert rules" duration=338.12µs
logger=migrator t=2025-01-13T17:23:41.368302491Z level=info msg="Executing migration" id="managed folder permissions alert actions repeated migration"
logger=migrator t=2025-01-13T17:23:41.368483759Z level=info msg="Migration successfully executed" id="managed folder permissions alert actions repeated migration" duration=181.909µs
logger=migrator t=2025-01-13T17:23:41.370341315Z level=info msg="Executing migration" id="admin only folder/dashboard permission"
logger=migrator t=2025-01-13T17:23:41.370650691Z level=info msg="Migration successfully executed" id="admin only folder/dashboard permission" duration=270.534µs
logger=migrator t=2025-01-13T17:23:41.3730175Z level=info msg="Executing migration" id="add action column to seed_assignment"
logger=migrator t=2025-01-13T17:23:41.374032102Z level=info msg="Migration successfully executed" id="add action column to seed_assignment" duration=1.014541ms
logger=migrator t=2025-01-13T17:23:41.376962895Z level=info msg="Executing migration" id="add scope column to seed_assignment"
logger=migrator t=2025-01-13T17:23:41.39635354Z level=info msg="Migration successfully executed" id="add scope column to seed_assignment" duration=19.390406ms
logger=migrator t=2025-01-13T17:23:41.39947396Z level=info msg="Executing migration" id="remove unique index builtin_role_role_name before nullable update"
logger=migrator t=2025-01-13T17:23:41.399750896Z level=info msg="Migration successfully executed" id="remove unique index builtin_role_role_name before nullable update" duration=276.736µs
logger=migrator t=2025-01-13T17:23:41.416162519Z level=info msg="Executing migration" id="update seed_assignment role_name column to nullable"
logger=migrator t=2025-01-13T17:23:41.424040464Z level=info msg="Migration successfully executed" id="update seed_assignment role_name column to nullable" duration=7.878025ms
logger=migrator t=2025-01-13T17:23:41.426386334Z level=info msg="Executing migration" id="add unique index builtin_role_name back"
logger=migrator t=2025-01-13T17:23:41.426811296Z level=info msg="Migration successfully executed" id="add unique index builtin_role_name back" duration=425.864µs
logger=migrator t=2025-01-13T17:23:41.429231481Z level=info msg="Executing migration" id="add unique index builtin_role_action_scope"
logger=migrator t=2025-01-13T17:23:41.429565944Z level=info msg="Migration successfully executed" id="add unique index builtin_role_action_scope" duration=335.386µs
logger=migrator t=2025-01-13T17:23:41.432193231Z level=info msg="Executing migration" id="add primary key to seed_assigment"
logger=migrator t=2025-01-13T17:23:41.496957664Z level=info msg="Migration successfully executed" id="add primary key to seed_assigment" duration=64.764833ms
logger=migrator t=2025-01-13T17:23:41.516776211Z level=info msg="Executing migration" id="add origin column to seed_assignment"
logger=migrator t=2025-01-13T17:23:41.518064782Z level=info msg="Migration successfully executed" id="add origin column to seed_assignment" duration=1.28757ms
logger=migrator t=2025-01-13T17:23:41.520830314Z level=info msg="Executing migration" id="add origin to plugin seed_assignment"
logger=migrator t=2025-01-13T17:23:41.520957812Z level=info msg="Migration successfully executed" id="add origin to plugin seed_assignment" duration=127.919µs
logger=migrator t=2025-01-13T17:23:41.523414902Z level=info msg="Executing migration" id="prevent seeding OnCall access"
logger=migrator t=2025-01-13T17:23:41.523534655Z level=info msg="Migration successfully executed" id="prevent seeding OnCall access" duration=120.374µs
logger=migrator t=2025-01-13T17:23:41.525198009Z level=info msg="Executing migration" id="managed folder permissions alert actions repeated fixed migration"
logger=migrator t=2025-01-13T17:23:41.525351355Z level=info msg="Migration successfully executed" id="managed folder permissions alert actions repeated fixed migration" duration=153.526µs
logger=migrator t=2025-01-13T17:23:41.527858539Z level=info msg="Executing migration" id="managed folder permissions library panel actions migration"
logger=migrator t=2025-01-13T17:23:41.528044285Z level=info msg="Migration successfully executed" id="managed folder permissions library panel actions migration" duration=186.417µs
logger=migrator t=2025-01-13T17:23:41.529845029Z level=info msg="Executing migration" id="migrate external alertmanagers to datsourcse"
logger=migrator t=2025-01-13T17:23:41.530009375Z level=info msg="Migration successfully executed" id="migrate external alertmanagers to datsourcse" duration=165.027µs
logger=migrator t=2025-01-13T17:23:41.532249965Z level=info msg="Executing migration" id="create folder table"
logger=migrator t=2025-01-13T17:23:41.532581302Z level=info msg="Migration successfully executed" id="create folder table" duration=332.159µs
logger=migrator t=2025-01-13T17:23:41.534745496Z level=info msg="Executing migration" id="Add index for parent_uid"
logger=migrator t=2025-01-13T17:23:41.535028985Z level=info msg="Migration successfully executed" id="Add index for parent_uid" duration=283.819µs
logger=migrator t=2025-01-13T17:23:41.537464816Z level=info msg="Executing migration" id="Add unique index for folder.uid and folder.org_id"
logger=migrator t=2025-01-13T17:23:41.537787998Z level=info msg="Migration successfully executed" id="Add unique index for folder.uid and folder.org_id" duration=323.914µs
logger=migrator t=2025-01-13T17:23:41.540492486Z level=info msg="Executing migration" id="Update folder title length"
logger=migrator t=2025-01-13T17:23:41.540638488Z level=info msg="Migration successfully executed" id="Update folder title length" duration=147.034µs
logger=migrator t=2025-01-13T17:23:41.542314456Z level=info msg="Executing migration" id="Add unique index for folder.title and folder.parent_uid"
logger=migrator t=2025-01-13T17:23:41.542714121Z level=info msg="Migration successfully executed" id="Add unique index for folder.title and folder.parent_uid" duration=400.617µs
logger=migrator t=2025-01-13T17:23:41.545802758Z level=info msg="Executing migration" id="Remove unique index for folder.title and folder.parent_uid"
logger=migrator t=2025-01-13T17:23:41.546221539Z level=info msg="Migration successfully executed" id="Remove unique index for folder.title and folder.parent_uid" duration=419.531µs
logger=migrator t=2025-01-13T17:23:41.548860949Z level=info msg="Executing migration" id="Add unique index for title, parent_uid, and org_id"
logger=migrator t=2025-01-13T17:23:41.549191585Z level=info msg="Migration successfully executed" id="Add unique index for title, parent_uid, and org_id" duration=331.428µs
logger=migrator t=2025-01-13T17:23:41.551767944Z level=info msg="Executing migration" id="Sync dashboard and folder table"
logger=migrator t=2025-01-13T17:23:41.5520018Z level=info msg="Migration successfully executed" id="Sync dashboard and folder table" duration=234.727µs
logger=migrator t=2025-01-13T17:23:41.553563191Z level=info msg="Executing migration" id="Remove ghost folders from the folder table"
logger=migrator t=2025-01-13T17:23:41.553645635Z level=info msg="Migration successfully executed" id="Remove ghost folders from the folder table" duration=82.835µs
logger=migrator t=2025-01-13T17:23:41.555918532Z level=info msg="Executing migration" id="Remove unique index UQE_folder_uid_org_id"
logger=migrator t=2025-01-13T17:23:41.556269305Z level=info msg="Migration successfully executed" id="Remove unique index UQE_folder_uid_org_id" duration=345.595µs
logger=migrator t=2025-01-13T17:23:41.558036372Z level=info msg="Executing migration" id="Add unique index UQE_folder_org_id_uid"
logger=migrator t=2025-01-13T17:23:41.558393849Z level=info msg="Migration successfully executed" id="Add unique index UQE_folder_org_id_uid" duration=358.328µs
logger=migrator t=2025-01-13T17:23:41.560927018Z level=info msg="Executing migration" id="Remove unique index UQE_folder_title_parent_uid_org_id"
logger=migrator t=2025-01-13T17:23:41.561272341Z level=info msg="Migration successfully executed" id="Remove unique index UQE_folder_title_parent_uid_org_id" duration=346.195µs
logger=migrator t=2025-01-13T17:23:41.563554315Z level=info msg="Executing migration" id="Add unique index UQE_folder_org_id_parent_uid_title"
logger=migrator t=2025-01-13T17:23:41.563871236Z level=info msg="Migration successfully executed" id="Add unique index UQE_folder_org_id_parent_uid_title" duration=317.663µs
logger=migrator t=2025-01-13T17:23:41.599004009Z level=info msg="Executing migration" id="Remove index IDX_folder_parent_uid_org_id"
logger=migrator t=2025-01-13T17:23:41.599341989Z level=info msg="Migration successfully executed" id="Remove index IDX_folder_parent_uid_org_id" duration=338.361µs
logger=migrator t=2025-01-13T17:23:41.601670437Z level=info msg="Executing migration" id="create anon_device table"
logger=migrator t=2025-01-13T17:23:41.601971097Z level=info msg="Migration successfully executed" id="create anon_device table" duration=301.252µs
logger=migrator t=2025-01-13T17:23:41.616371661Z level=info msg="Executing migration" id="add unique index anon_device.device_id"
logger=migrator t=2025-01-13T17:23:41.616766426Z level=info msg="Migration successfully executed" id="add unique index anon_device.device_id" duration=395.217µs
logger=migrator t=2025-01-13T17:23:41.619422671Z level=info msg="Executing migration" id="add index anon_device.updated_at"
logger=migrator t=2025-01-13T17:23:41.619789585Z level=info msg="Migration successfully executed" id="add index anon_device.updated_at" duration=367.896µs
logger=migrator t=2025-01-13T17:23:41.62220626Z level=info msg="Executing migration" id="create signing_key table"
logger=migrator t=2025-01-13T17:23:41.622488246Z level=info msg="Migration successfully executed" id="create signing_key table" duration=282.757µs
logger=migrator t=2025-01-13T17:23:41.625034899Z level=info msg="Executing migration" id="add unique index signing_key.key_id"
logger=migrator t=2025-01-13T17:23:41.625417683Z level=info msg="Migration successfully executed" id="add unique index signing_key.key_id" duration=383.646µs
logger=migrator t=2025-01-13T17:23:41.627942212Z level=info msg="Executing migration" id="set legacy alert migration status in kvstore"
logger=migrator t=2025-01-13T17:23:41.62837023Z level=info msg="Migration successfully executed" id="set legacy alert migration status in kvstore" duration=429.05µs
logger=migrator t=2025-01-13T17:23:41.630384766Z level=info msg="Executing migration" id="migrate record of created folders during legacy migration to kvstore"
logger=migrator t=2025-01-13T17:23:41.630534494Z level=info msg="Migration successfully executed" id="migrate record of created folders during legacy migration to kvstore" duration=150.641µs
logger=migrator t=2025-01-13T17:23:41.632721191Z level=info msg="Executing migration" id="Add folder_uid for dashboard"
logger=migrator t=2025-01-13T17:23:41.633590842Z level=info msg="Migration successfully executed" id="Add folder_uid for dashboard" duration=870.493µs
logger=migrator t=2025-01-13T17:23:41.635785743Z level=info msg="Executing migration" id="Populate dashboard folder_uid column"
logger=migrator t=2025-01-13T17:23:41.635947324Z level=info msg="Migration successfully executed" id="Populate dashboard folder_uid column" duration=162.653µs
logger=migrator t=2025-01-13T17:23:41.63762019Z level=info msg="Executing migration" id="Add unique index for dashboard_org_id_folder_uid_title"
logger=migrator t=2025-01-13T17:23:41.637722009Z level=info msg="Migration successfully executed" id="Add unique index for dashboard_org_id_folder_uid_title" duration=102.962µs
logger=migrator t=2025-01-13T17:23:41.640051886Z level=info msg="Executing migration" id="Delete unique index for dashboard_org_id_folder_id_title"
logger=migrator t=2025-01-13T17:23:41.640411867Z level=info msg="Migration successfully executed" id="Delete unique index for dashboard_org_id_folder_id_title" duration=360.842µs
logger=migrator t=2025-01-13T17:23:41.642205567Z level=info msg="Executing migration" id="Delete unique index for dashboard_org_id_folder_uid_title"
logger=migrator t=2025-01-13T17:23:41.642297428Z level=info msg="Migration successfully executed" id="Delete unique index for dashboard_org_id_folder_uid_title" duration=93.394µs
logger=migrator t=2025-01-13T17:23:41.645107399Z level=info msg="Executing migration" id="Add unique index for dashboard_org_id_folder_uid_title_is_folder"
logger=migrator t=2025-01-13T17:23:41.645542921Z level=info msg="Migration successfully executed" id="Add unique index for dashboard_org_id_folder_uid_title_is_folder" duration=436.333µs
logger=migrator t=2025-01-13T17:23:41.648082325Z level=info msg="Executing migration" id="Restore index for dashboard_org_id_folder_id_title"
logger=migrator t=2025-01-13T17:23:41.648439831Z level=info msg="Migration successfully executed" id="Restore index for dashboard_org_id_folder_id_title" duration=358.288µs
logger=migrator t=2025-01-13T17:23:41.650928701Z level=info msg="Executing migration" id="create sso_setting table"
logger=migrator t=2025-01-13T17:23:41.65118024Z level=info msg="Migration successfully executed" id="create sso_setting table" duration=252.09µs
logger=migrator t=2025-01-13T17:23:41.653523795Z level=info msg="Executing migration" id="copy kvstore migration status to each org"
logger=migrator t=2025-01-13T17:23:41.65392356Z level=info msg="Migration successfully executed" id="copy kvstore migration status to each org" duration=400.747µs
logger=migrator t=2025-01-13T17:23:41.656352107Z level=info msg="Executing migration" id="add back entry for orgid=0 migrated status"
logger=migrator t=2025-01-13T17:23:41.656526653Z level=info msg="Migration successfully executed" id="add back entry for orgid=0 migrated status" duration=175.517µs
logger=migrator t=2025-01-13T17:23:41.658179677Z level=info msg="Executing migration" id="managed dashboard permissions annotation actions migration"
logger=migrator t=2025-01-13T17:23:41.658389288Z level=info msg="Migration successfully executed" id="managed dashboard permissions annotation actions migration" duration=210.503µs
logger=migrator t=2025-01-13T17:23:41.660727476Z level=info msg="Executing migration" id="create cloud_migration table v1"
logger=migrator t=2025-01-13T17:23:41.660970419Z level=info msg="Migration successfully executed" id="create cloud_migration table v1" duration=243.043µs
logger=migrator t=2025-01-13T17:23:41.697676963Z level=info msg="Executing migration" id="create cloud_migration_run table v1"
logger=migrator t=2025-01-13T17:23:41.697998569Z level=info msg="Migration successfully executed" id="create cloud_migration_run table v1" duration=322.157µs
logger=migrator t=2025-01-13T17:23:41.700800432Z level=info msg="Executing migration" id="add stack_id column"
logger=migrator t=2025-01-13T17:23:41.701873002Z level=info msg="Migration successfully executed" id="add stack_id column" duration=1.071928ms
logger=migrator t=2025-01-13T17:23:41.716493028Z level=info msg="Executing migration" id="add region_slug column"
logger=migrator t=2025-01-13T17:23:41.717536212Z level=info msg="Migration successfully executed" id="add region_slug column" duration=1.035831ms
logger=migrator t=2025-01-13T17:23:41.720018306Z level=info msg="Executing migration" id="add cluster_slug column"
logger=migrator t=2025-01-13T17:23:41.720919546Z level=info msg="Migration successfully executed" id="add cluster_slug column" duration=902.131µs
logger=migrator t=2025-01-13T17:23:41.72276709Z level=info msg="Executing migration" id="add migration uid column"
logger=migrator t=2025-01-13T17:23:41.724358209Z level=info msg="Migration successfully executed" id="add migration uid column" duration=1.590748ms
logger=migrator t=2025-01-13T17:23:41.72735939Z level=info msg="Executing migration" id="Update uid column values for migration"
logger=migrator t=2025-01-13T17:23:41.727457012Z level=info msg="Migration successfully executed" id="Update uid column values for migration" duration=106.348µs
logger=migrator t=2025-01-13T17:23:41.729571634Z level=info msg="Executing migration" id="Add unique index migration_uid"
logger=migrator t=2025-01-13T17:23:41.730052811Z level=info msg="Migration successfully executed" id="Add unique index migration_uid" duration=481.077µs
logger=migrator t=2025-01-13T17:23:41.732736296Z level=info msg="Executing migration" id="add migration run uid column"
logger=migrator t=2025-01-13T17:23:41.733558609Z level=info msg="Migration successfully executed" id="add migration run uid column" duration=823.225µs
logger=migrator t=2025-01-13T17:23:41.736057247Z level=info msg="Executing migration" id="Update uid column values for migration run"
logger=migrator t=2025-01-13T17:23:41.73611795Z level=info msg="Migration successfully executed" id="Update uid column values for migration run" duration=61.835µs
logger=migrator t=2025-01-13T17:23:41.738115253Z level=info msg="Executing migration" id="Add unique index migration_run_uid"
logger=migrator t=2025-01-13T17:23:41.738557508Z level=info msg="Migration successfully executed" id="Add unique index migration_run_uid" duration=442.876µs
logger=migrator t=2025-01-13T17:23:41.740995349Z level=info msg="Executing migration" id="Rename table cloud_migration to cloud_migration_session_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:41.743933005Z level=info msg="Migration successfully executed" id="Rename table cloud_migration to cloud_migration_session_tmp_qwerty - v1" duration=2.937776ms
logger=migrator t=2025-01-13T17:23:41.746996054Z level=info msg="Executing migration" id="create cloud_migration_session v2"
logger=migrator t=2025-01-13T17:23:41.747325619Z level=info msg="Migration successfully executed" id="create cloud_migration_session v2" duration=330.596µs
logger=migrator t=2025-01-13T17:23:41.7990302Z level=info msg="Executing migration" id="create index UQE_cloud_migration_session_uid - v2"
logger=migrator t=2025-01-13T17:23:41.799420247Z level=info msg="Migration successfully executed" id="create index UQE_cloud_migration_session_uid - v2" duration=391.53µs
logger=migrator t=2025-01-13T17:23:41.816630572Z level=info msg="Executing migration" id="copy cloud_migration_session v1 to v2"
logger=migrator t=2025-01-13T17:23:41.816858046Z level=info msg="Migration successfully executed" id="copy cloud_migration_session v1 to v2" duration=227.394µs
logger=migrator t=2025-01-13T17:23:41.818702534Z level=info msg="Executing migration" id="drop cloud_migration_session_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:41.819015116Z level=info msg="Migration successfully executed" id="drop cloud_migration_session_tmp_qwerty" duration=313.124µs
logger=migrator t=2025-01-13T17:23:41.821732802Z level=info msg="Executing migration" id="Rename table cloud_migration_run to cloud_migration_snapshot_tmp_qwerty - v1"
logger=migrator t=2025-01-13T17:23:41.824050262Z level=info msg="Migration successfully executed" id="Rename table cloud_migration_run to cloud_migration_snapshot_tmp_qwerty - v1" duration=2.318382ms
logger=migrator t=2025-01-13T17:23:41.827058507Z level=info msg="Executing migration" id="create cloud_migration_snapshot v2"
logger=migrator t=2025-01-13T17:23:41.82740888Z level=info msg="Migration successfully executed" id="create cloud_migration_snapshot v2" duration=342.288µs
logger=migrator t=2025-01-13T17:23:41.829760694Z level=info msg="Executing migration" id="create index UQE_cloud_migration_snapshot_uid - v2"
logger=migrator t=2025-01-13T17:23:41.830091911Z level=info msg="Migration successfully executed" id="create index UQE_cloud_migration_snapshot_uid - v2" duration=332.409µs
logger=migrator t=2025-01-13T17:23:41.832357354Z level=info msg="Executing migration" id="copy cloud_migration_snapshot v1 to v2"
logger=migrator t=2025-01-13T17:23:41.832580991Z level=info msg="Migration successfully executed" id="copy cloud_migration_snapshot v1 to v2" duration=215.642µs
logger=migrator t=2025-01-13T17:23:41.834234076Z level=info msg="Executing migration" id="drop cloud_migration_snapshot_tmp_qwerty"
logger=migrator t=2025-01-13T17:23:41.834573158Z level=info msg="Migration successfully executed" id="drop cloud_migration_snapshot_tmp_qwerty" duration=339.793µs
logger=migrator t=2025-01-13T17:23:41.837157683Z level=info msg="Executing migration" id="add snapshot upload_url column"
logger=migrator t=2025-01-13T17:23:41.83817562Z level=info msg="Migration successfully executed" id="add snapshot upload_url column" duration=1.017918ms
logger=migrator t=2025-01-13T17:23:41.840652707Z level=info msg="Executing migration" id="add snapshot status column"
logger=migrator t=2025-01-13T17:23:41.841604371Z level=info msg="Migration successfully executed" id="add snapshot status column" duration=943.509µs
logger=migrator t=2025-01-13T17:23:41.843892958Z level=info msg="Executing migration" id="add snapshot local_directory column"
logger=migrator t=2025-01-13T17:23:41.844808785Z level=info msg="Migration successfully executed" id="add snapshot local_directory column" duration=916.107µs
logger=migrator t=2025-01-13T17:23:41.84676456Z level=info msg="Executing migration" id="add snapshot gms_snapshot_uid column"
logger=migrator t=2025-01-13T17:23:41.847777949Z level=info msg="Migration successfully executed" id="add snapshot gms_snapshot_uid column" duration=1.013619ms
logger=migrator t=2025-01-13T17:23:41.850217657Z level=info msg="Executing migration" id="add snapshot encryption_key column"
logger=migrator t=2025-01-13T17:23:41.851130358Z level=info msg="Migration successfully executed" id="add snapshot encryption_key column" duration=913.413µs
logger=migrator t=2025-01-13T17:23:41.897932184Z level=info msg="Executing migration" id="add snapshot error_string column"
logger=migrator t=2025-01-13T17:23:41.914280719Z level=info msg="Migration successfully executed" id="add snapshot error_string column" duration=16.348244ms
logger=migrator t=2025-01-13T17:23:41.917361512Z level=info msg="Executing migration" id="create cloud_migration_resource table v1"
logger=migrator t=2025-01-13T17:23:41.917859981Z level=info msg="Migration successfully executed" id="create cloud_migration_resource table v1" duration=498.238µs
logger=migrator t=2025-01-13T17:23:41.920746511Z level=info msg="Executing migration" id="delete cloud_migration_snapshot.result column"
logger=migrator t=2025-01-13T17:23:41.926749472Z level=info msg="Migration successfully executed" id="delete cloud_migration_snapshot.result column" duration=6.002479ms
logger=migrator t=2025-01-13T17:23:41.929548516Z level=info msg="Executing migration" id="add cloud_migration_resource.name column"
logger=migrator t=2025-01-13T17:23:41.931169537Z level=info msg="Migration successfully executed" id="add cloud_migration_resource.name column" duration=1.620431ms
logger=migrator t=2025-01-13T17:23:41.934283031Z level=info msg="Executing migration" id="add cloud_migration_resource.parent_name column"
logger=migrator t=2025-01-13T17:23:41.935756458Z level=info msg="Migration successfully executed" id="add cloud_migration_resource.parent_name column" duration=1.473356ms
logger=migrator t=2025-01-13T17:23:41.938152344Z level=info msg="Executing migration" id="add cloud_migration_session.org_id column"
logger=migrator t=2025-01-13T17:23:41.939597027Z level=info msg="Migration successfully executed" id="add cloud_migration_session.org_id column" duration=1.444072ms
logger=migrator t=2025-01-13T17:23:41.99924037Z level=info msg="Executing migration" id="alter kv_store.value to longtext"
logger=migrator t=2025-01-13T17:23:41.999542012Z level=info msg="Migration successfully executed" id="alter kv_store.value to longtext" duration=303.155µs
logger=migrator t=2025-01-13T17:23:42.017051959Z level=info msg="Executing migration" id="add notification_settings column to alert_rule table"
logger=migrator t=2025-01-13T17:23:42.018764712Z level=info msg="Migration successfully executed" id="add notification_settings column to alert_rule table" duration=1.712712ms
logger=migrator t=2025-01-13T17:23:42.023583474Z level=info msg="Executing migration" id="add notification_settings column to alert_rule_version table"
logger=migrator t=2025-01-13T17:23:42.0251314Z level=info msg="Migration successfully executed" id="add notification_settings column to alert_rule_version table" duration=1.547885ms
logger=migrator t=2025-01-13T17:23:42.028028911Z level=info msg="Executing migration" id="removing scope from alert.instances:read action migration"
logger=migrator t=2025-01-13T17:23:42.028242509Z level=info msg="Migration successfully executed" id="removing scope from alert.instances:read action migration" duration=213.498µs
logger=migrator t=2025-01-13T17:23:42.030294734Z level=info msg="Executing migration" id="managed folder permissions alerting silences actions migration"
logger=migrator t=2025-01-13T17:23:42.030536736Z level=info msg="Migration successfully executed" id="managed folder permissions alerting silences actions migration" duration=242.021µs
logger=migrator t=2025-01-13T17:23:42.032879423Z level=info msg="Executing migration" id="add record column to alert_rule table"
logger=migrator t=2025-01-13T17:23:42.034295723Z level=info msg="Migration successfully executed" id="add record column to alert_rule table" duration=1.41631ms
logger=migrator t=2025-01-13T17:23:42.036568269Z level=info msg="Executing migration" id="add record column to alert_rule_version table"
logger=migrator t=2025-01-13T17:23:42.038008544Z level=info msg="Migration successfully executed" id="add record column to alert_rule_version table" duration=1.440215ms
logger=migrator t=2025-01-13T17:23:42.041352016Z level=info msg="Executing migration" id="add resolved_at column to alert_instance table"
logger=migrator t=2025-01-13T17:23:42.042854016Z level=info msg="Migration successfully executed" id="add resolved_at column to alert_instance table" duration=1.50203ms
logger=migrator t=2025-01-13T17:23:42.045367331Z level=info msg="Executing migration" id="add last_sent_at column to alert_instance table"
logger=migrator t=2025-01-13T17:23:42.046812064Z level=info msg="Migration successfully executed" id="add last_sent_at column to alert_instance table" duration=1.444863ms
logger=migrator t=2025-01-13T17:23:42.049077477Z level=info msg="Executing migration" id="Enable traceQL streaming for all Tempo datasources"
logger=migrator t=2025-01-13T17:23:42.049216346Z level=info msg="Migration successfully executed" id="Enable traceQL streaming for all Tempo datasources" duration=139.581µs
logger=migrator t=2025-01-13T17:23:42.123059525Z level=info msg="Executing migration" id="Add scope to alert.notifications.receivers:read and alert.notifications.receivers.secrets:read"
logger=migrator t=2025-01-13T17:23:42.123299232Z level=info msg="Migration successfully executed" id="Add scope to alert.notifications.receivers:read and alert.notifications.receivers.secrets:read" duration=241.85µs
logger=migrator t=2025-01-13T17:23:42.125799356Z level=info msg="Executing migration" id="add metadata column to alert_rule table"
logger=migrator t=2025-01-13T17:23:42.12723586Z level=info msg="Migration successfully executed" id="add metadata column to alert_rule table" duration=1.436965ms
logger=migrator t=2025-01-13T17:23:42.130277212Z level=info msg="Executing migration" id="add metadata column to alert_rule_version table"
logger=migrator t=2025-01-13T17:23:42.131362275Z level=info msg="Migration successfully executed" id="add metadata column to alert_rule_version table" duration=1.085784ms
logger=migrator t=2025-01-13T17:23:42.13398797Z level=info msg="Executing migration" id="delete orphaned service account permissions"
logger=migrator t=2025-01-13T17:23:42.13412241Z level=info msg="Migration successfully executed" id="delete orphaned service account permissions" duration=113.572µs
logger=migrator t=2025-01-13T17:23:42.136427668Z level=info msg="Executing migration" id="adding action set permissions"
logger=migrator t=2025-01-13T17:23:42.136578378Z level=info msg="Migration successfully executed" id="adding action set permissions" duration=167.432µs
logger=migrator t=2025-01-13T17:23:42.138274557Z level=info msg="Executing migration" id="create user_external_session table"
logger=migrator t=2025-01-13T17:23:42.138661218Z level=info msg="Migration successfully executed" id="create user_external_session table" duration=387.482µs
logger=migrator t=2025-01-13T17:23:42.141345431Z level=info msg="Executing migration" id="increase name_id column length to 1024"
logger=migrator t=2025-01-13T17:23:42.14141418Z level=info msg="Migration successfully executed" id="increase name_id column length to 1024" duration=69.339µs
logger=migrator t=2025-01-13T17:23:42.143695312Z level=info msg="Executing migration" id="increase session_id column length to 1024"
logger=migrator t=2025-01-13T17:23:42.1438019Z level=info msg="Migration successfully executed" id="increase session_id column length to 1024" duration=107.18µs
logger=migrator t=2025-01-13T17:23:42.145424345Z level=info msg="migrations completed" performed=611 skipped=0 duration=4.220676178s
logger=migrator t=2025-01-13T17:23:42.145630809Z level=info msg="Unlocking database"
logger=sqlstore t=2025-01-13T17:23:42.152130716Z level=info msg="Created default admin" user=admin
logger=sqlstore t=2025-01-13T17:23:42.196259064Z level=info msg="Created default organization"
logger=secrets t=2025-01-13T17:23:42.200112822Z level=info msg="Envelope encryption state" enabled=true currentprovider=secretKey.v1
logger=plugin.angulardetectorsprovider.dynamic t=2025-01-13T17:23:42.722969512Z level=info msg="Restored cache from database" duration=240.689µs
logger=plugin.store t=2025-01-13T17:23:42.742406988Z level=info msg="Loading plugins..."
logger=plugins.registration t=2025-01-13T17:23:43.130268471Z level=error msg="Could not register plugin" pluginId=xychart error="plugin xychart is already registered"
logger=plugins.initialization t=2025-01-13T17:23:43.130298438Z level=error msg="Could not initialize plugin" pluginId=xychart error="plugin xychart is already registered"
logger=local.finder t=2025-01-13T17:23:43.130398093Z level=warn msg="Skipping finding plugins as directory does not exist" path=/opt/bitnami/grafana/plugins-bundled
logger=plugins.validator.angular t=2025-01-13T17:23:44.41858657Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=agenty-flowcharting-panel
logger=plugins.validation t=2025-01-13T17:23:44.420910903Z level=error msg="Plugin validation failed" pluginId=agenty-flowcharting-panel error="angular plugins are not supported"
logger=plugins.validator.angular t=2025-01-13T17:23:44.635233406Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=briangann-datatable-panel
logger=plugins.validation t=2025-01-13T17:23:44.635260597Z level=error msg="Plugin validation failed" pluginId=briangann-datatable-panel error="angular plugins are not supported"
logger=plugins.registration t=2025-01-13T17:23:44.816597543Z level=info msg="Plugin registered" pluginId=briangann-gauge-panel
logger=plugins.validator.angular t=2025-01-13T17:23:44.918297138Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=digiapulssi-organisations-panel
logger=plugins.validation t=2025-01-13T17:23:44.918318078Z level=error msg="Plugin validation failed" pluginId=digiapulssi-organisations-panel error="angular plugins are not supported"
logger=plugins.registration t=2025-01-13T17:23:45.222615594Z level=info msg="Plugin registered" pluginId=grafana-clock-panel
logger=plugins.validator.angular t=2025-01-13T17:23:45.32299008Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=grafana-piechart-panel
logger=plugins.validation t=2025-01-13T17:23:45.323012021Z level=error msg="Plugin validation failed" pluginId=grafana-piechart-panel error="angular plugins are not supported"
logger=plugins.registration t=2025-01-13T17:23:45.515611037Z level=info msg="Plugin registered" pluginId=grafana-polystat-panel
logger=plugins.registration t=2025-01-13T17:23:45.915561735Z level=info msg="Plugin registered" pluginId=jdbranham-diagram-panel
logger=plugins.registration t=2025-01-13T17:23:46.023223234Z level=info msg="Plugin registered" pluginId=larona-epict-panel
logger=plugins.validator.angular t=2025-01-13T17:23:46.323302968Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=marcuscalidus-svg-panel
logger=plugins.validation t=2025-01-13T17:23:46.32332543Z level=error msg="Plugin validation failed" pluginId=marcuscalidus-svg-panel error="angular plugins are not supported"
logger=plugins.validator.angular t=2025-01-13T17:23:46.419878572Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=michaeldmoore-annunciator-panel
logger=plugins.validation t=2025-01-13T17:23:46.419953873Z level=error msg="Plugin validation failed" pluginId=michaeldmoore-annunciator-panel error="angular plugins are not supported"
logger=plugins.validator.angular t=2025-01-13T17:23:46.516778511Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=michaeldmoore-multistat-panel
logger=plugins.validation t=2025-01-13T17:23:46.516794491Z level=error msg="Plugin validation failed" pluginId=michaeldmoore-multistat-panel error="angular plugins are not supported"
logger=plugins.validator.angular t=2025-01-13T17:23:46.61728902Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=natel-discrete-panel
logger=plugins.validation t=2025-01-13T17:23:46.617304369Z level=error msg="Plugin validation failed" pluginId=natel-discrete-panel error="angular plugins are not supported"
logger=plugins.validator.angular t=2025-01-13T17:23:46.723879553Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=neocat-cal-heatmap-panel
logger=plugins.validation t=2025-01-13T17:23:46.723901995Z level=error msg="Plugin validation failed" pluginId=neocat-cal-heatmap-panel error="angular plugins are not supported"
logger=plugins.registration t=2025-01-13T17:23:46.925787902Z level=info msg="Plugin registered" pluginId=pierosavi-imageit-panel
logger=plugins.registration t=2025-01-13T17:23:47.115170626Z level=info msg="Plugin registered" pluginId=scadavis-synoptic-panel
logger=plugins.validator.angular t=2025-01-13T17:23:47.226120418Z level=error msg="Refusing to initialize plugin because it's using Angular, which has been disabled" pluginId=snuids-trafficlights-panel
logger=plugins.validation t=2025-01-13T17:23:47.226324438Z level=error msg="Plugin validation failed" pluginId=snuids-trafficlights-panel error="angular plugins are not supported"
logger=plugins.registration t=2025-01-13T17:23:47.317190289Z level=info msg="Plugin registered" pluginId=vonage-status-panel
logger=plugin.store t=2025-01-13T17:23:47.317221377Z level=info msg="Plugins loaded" count=62 duration=4.57481549s
logger=query_data t=2025-01-13T17:23:47.479045897Z level=info msg="Query Service initialization"
logger=live.push_http t=2025-01-13T17:23:47.540821862Z level=info msg="Live Push Gateway initialization"
logger=ngalert.notifier.alertmanager org=1 t=2025-01-13T17:23:47.624559435Z level=info msg="Applying new configuration to Alertmanager" configHash=d2c56faca6af2a5772ff4253222f7386
logger=ngalert.state.manager t=2025-01-13T17:23:47.646600735Z level=info msg="Running in alternative execution of Error/NoData mode"
logger=infra.usagestats.collector t=2025-01-13T17:23:47.723706302Z level=info msg="registering usage stat providers" usageStatsProvidersLen=2
logger=server t=2025-01-13T17:23:47.724049064Z level=info msg="Writing PID file" path=/opt/bitnami/grafana/tmp/grafana.pid pid=1
logger=provisioning.alerting t=2025-01-13T17:23:47.730986954Z level=info msg="starting to provision alerting"
logger=provisioning.alerting t=2025-01-13T17:23:47.731011359Z level=info msg="finished to provision alerting"
logger=grafanaStorageLogger t=2025-01-13T17:23:47.741739691Z level=info msg="Storage starting"
logger=http.server t=2025-01-13T17:23:47.755782224Z level=info msg="HTTP Server Listen" address=[::]:3000 protocol=http subUrl= socket=
logger=ngalert.state.manager t=2025-01-13T17:23:47.763481019Z level=info msg="Warming state cache for startup"
logger=ngalert.state.manager t=2025-01-13T17:23:47.769237599Z level=info msg="State cache has been initialized" states=0 duration=5.755389ms
logger=plugin.backgroundinstaller t=2025-01-13T17:23:47.797496526Z level=info msg="Installing plugin" pluginId=grafana-lokiexplore-app version=
logger=provisioning.dashboard t=2025-01-13T17:23:47.925868221Z level=info msg="starting to provision dashboards"
logger=provisioning.dashboard t=2025-01-13T17:23:47.925922068Z level=info msg="finished to provision dashboards"
logger=ngalert.multiorg.alertmanager t=2025-01-13T17:23:47.93998755Z level=info msg="Starting MultiOrg Alertmanager"
logger=ngalert.scheduler t=2025-01-13T17:23:47.940180186Z level=info msg="Starting scheduler" tickInterval=10s maxAttempts=1
logger=ticker t=2025-01-13T17:23:47.941486892Z level=info msg=starting first_tick=2025-01-13T17:23:50Z
logger=grafana.update.checker t=2025-01-13T17:23:48.614330967Z level=info msg="Update check succeeded" duration=684.919936ms
logger=plugins.update.checker t=2025-01-13T17:23:48.614759833Z level=info msg="Update check succeeded" duration=684.762886ms
logger=plugin.angulardetectorsprovider.dynamic t=2025-01-13T17:23:48.622140405Z level=info msg="Patterns update finished" duration=799.099753ms
logger=plugin.installer t=2025-01-13T17:23:49.616303649Z level=info msg="Installing plugin" pluginId=grafana-lokiexplore-app version=
logger=installer.fs t=2025-01-13T17:23:51.91416701Z level=info msg="Downloaded and extracted grafana-lokiexplore-app v1.0.5 zip successfully to /opt/bitnami/grafana/data/plugins/grafana-lokiexplore-app"
logger=plugins.registration t=2025-01-13T17:23:52.121661104Z level=info msg="Plugin registered" pluginId=grafana-lokiexplore-app
logger=plugin.backgroundinstaller t=2025-01-13T17:23:52.218531014Z level=info msg="Plugin successfully installed" pluginId=grafana-lokiexplore-app version= duration=4.421013459s
logger=grafana-apiserver t=2025-01-13T17:23:52.324527783Z level=info msg="failed to read in-cluster kubeconfig for delegated authentication: open /var/run/secrets/kubernetes.io/serviceaccount/token: no such file or directory"
logger=grafana-apiserver t=2025-01-13T17:23:52.458380114Z level=info msg="Adding GroupVersion playlist.grafana.app v0alpha1 to ResourceManager"
logger=grafana-apiserver t=2025-01-13T17:23:52.459552389Z level=info msg="Adding GroupVersion featuretoggle.grafana.app v0alpha1 to ResourceManager"
logger=grafana-apiserver t=2025-01-13T17:23:52.468560097Z level=info msg="Adding GroupVersion iam.grafana.app v0alpha1 to ResourceManager"
logger=infra.usagestats t=2025-01-13T17:24:27.949315948Z level=info msg="Usage stats are ready to report"
logger=authn.service t=2025-01-13T17:29:32.027114266Z level=warn msg="Failed to authenticate request" client=auth.client.session error="user token not found"
logger=context userId=0 orgId=0 uname= t=2025-01-13T17:29:32.027193063Z level=info msg="Request Completed" method=GET path=/ status=302 remote_addr=10.240.2.99 time_ms=0 duration=594.278µs size=29 referer=https://upgraded-space-halibut-g6rgjvwxpwhvvp4.github.dev/ handler=/ status_source=server
logger=authn.service t=2025-01-13T17:29:32.749537274Z level=warn msg="Failed to authenticate request" client=auth.client.session error="user token not found"
logger=authn.service t=2025-01-13T17:29:37.531702841Z level=warn msg="Failed to authenticate request" client=auth.client.session error="user token not found"
logger=context userId=0 orgId=0 uname= t=2025-01-13T17:29:37.531759215Z level=warn msg=Unauthorized error="user token not found" remote_addr=10.240.1.34 traceID=
logger=context userId=0 orgId=0 uname= t=2025-01-13T17:29:37.531799621Z level=info msg="Request Completed" method=GET path=/api/live/ws status=401 remote_addr=10.240.1.34 time_ms=0 duration=375.069µs size=40 referer= handler=/api/live/ws status_source=server
logger=authn.service t=2025-01-13T17:29:38.881155271Z level=warn msg="Failed to authenticate request" client=auth.client.session error="user token not found"
logger=context userId=1 orgId=1 uname=admin t=2025-01-13T17:29:40.147607183Z level=info msg="Request Completed" method=GET path=/api/live/ws status=-1 remote_addr=10.240.1.34 time_ms=2 duration=2.867485ms size=0 referer= handler=/api/live/ws status_source=server
logger=context userId=1 orgId=1 uname=admin t=2025-01-13T17:29:47.720117236Z level=info msg="Request Completed" method=GET path=/api/live/ws status=-1 remote_addr=10.240.0.69 time_ms=294 duration=294.32876ms size=0 referer= handler=/api/live/ws status_source=server
