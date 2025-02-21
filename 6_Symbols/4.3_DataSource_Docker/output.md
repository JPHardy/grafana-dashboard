# output

@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ docker run -d -p 3000:3000 --name=grafana grafana/grafana-enterprise
Unable to find image 'grafana/grafana-enterprise:latest' locally
latest: Pulling from grafana/grafana-enterprise
da9db072f522: Pull complete 
00e049413f28: Pull complete 
9f9f975099e7: Pull complete 
27b144bf79f9: Pull complete 
9d80ffe25c7d: Pull complete 
fb7e22b17612: Pull complete 
311a37fd7384: Pull complete 
2429d0c55872: Pull complete 
e80a452a7727: Pull complete 
c6109c799efd: Pull complete 
Digest: sha256:473a26e9ed1bef41abf2b8d85d0d810a9006534664d30dee7e92b03c9a9cccb2
Status: Downloaded newer image for grafana/grafana-enterprise:latest
9e7fb2b4c999f5e03eb2fb99d784c2e4f0b0342d8f7168108da86e6fe6c65237


- Semblance

@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ docker run -d -p 3000:3000 --name=grafan
a \
>     -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
>     grafana/grafana-enterprise
docker: Error response from daemon: Conflict. The container name "/grafana" is already in use by container "9e7fb2b4c999f5e03eb2fb99d784c2e4f0b0342d8f7168108da86e6fe6c65237". You have to remove (or rename) that container to be able to reuse that name.
See 'docker run --help'.
@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ 

@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ docker run -d -p 3000:3000 --name=grafana_ds \
>     -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
>     grafana/grafana-enterprise
ff2ceccfc6cafcef916a1b25dc34d5b6ae025709dcbc1fe209e664d669496eef
docker: Error response from daemon: driver failed programming external connectivity on endpoint grafana_ds (1f19b9b593b41a24cdc9c6bb1d215d726de7dea8dd96409dae6756463a13ccbb): Bind for 0.0.0.0:3000 failed: port is already allocated.


@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ docker run -d -p 3000:3001 --name=grafana_ds \
>     -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
>     grafana/grafana-enterprise
docker: Error response from daemon: Conflict. The container name "/grafana_ds" is already in use by container "ff2ceccfc6cafcef916a1b25dc34d5b6ae025709dcbc1fe209e664d669496eef". You have to remove (or rename) that container to be able to reuse that name.
See 'docker run --help'.


@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ docker run -d -p 3000:3001 --name=grafana_ds1 \
>     -e "GF_INSTALL_PLUGINS=grafana-clock-panel,grafana-simple-json-datasource" \
>     grafana/grafana-enterprise
1bb0cd1cc212edeebcb2bb46af599f5071ddc0b456f78da3ca75f6e2565ea163
docker: Error response from daemon: driver failed programming external connectivity on endpoint grafana_ds1 (0379725e2bc296de04a3acdb7ca0617feca1d6efd9d63f01a41478bf49c0093a): Bind for 0.0.0.0:3000 failed: port is already allocated.
@rifaterdemsahin ➜ /workspaces/grafana-dashboard (main) $ 

---

 (main) $ docker compose up -d
WARN[0000] /workspaces/grafana-dashboard/6_Symbols/4.3_DataSource_Docker/docker-compose.yaml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] Running 2/0
 ✔ Network 43_datasource_docker_default           Created                  0.1s 
 ✔ Volume "43_datasource_docker_grafana-storage"  Created                  0.0s 
 ⠋ Container grafana                              C...                     0.0s 
Error response from daemon: Conflict. The container name "/grafana" is already in use by container "9e7fb2b4c999f5e03eb2fb99d784c2e4f0b0342d8f7168108da86e6fe6c65237". You have to remove (or rename) that container to be able to reuse that name.
@rifaterdemsahin ➜ /workspaces/grafana-dashboard/6_Symbols/4.3_DataSource_Docker (main) $ 

---

To resolve the conflict, you need to remove the existing container first. You can do this with the following command:

```sh
docker rm -f grafana
```

Then, you can run the `docker compose up -d` command again:

```sh
(main) $ docker compose up -d
WARN[0000] /workspaces/grafana-dashboard/6_Symbols/4.3_DataSource_Docker/docker-compose.yaml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] Running 2/0
 ✔ Network 43_datasource_docker_default           Created                  0.1s 
 ✔ Volume "43_datasource_docker_grafana-storage"  Created                  0.0s 
 ✔ Container grafana                              Started                  0.1s 
```