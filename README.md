# wazuh
```code
git clone https://github.com/wazuh/wazuh-docker.git -b v4.10.1
docker compose -f generate-indexer-certs.yml run --rm generator
docker compose up -d
```
