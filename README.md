# wazuh
```code
git clone --depth 1 https://github.com/wazuh/wazuh-docker.git -b v4.10.1
docker compose -f generate-indexer-certs.yml run --rm generator
docker compose up -d

#docker compose down -v
```
# Agent client
https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html
