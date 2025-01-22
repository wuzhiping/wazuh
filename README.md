# wazuh
```code
git clone https://github.com/wazuh/wazuh-docker.git -b v4.10.1
docker compose -f generate-indexer-certs.yml run --rm generator
docker compose up -d
```
# Agent client
https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html
