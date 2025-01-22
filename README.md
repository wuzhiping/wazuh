# wazuh
```code
git clone --depth 1 https://github.com/wazuh/wazuh-docker.git -b v4.10.1
docker compose -f generate-indexer-certs.yml run --rm generator
docker compose up -d

#docker compose down -v
```

# dashboard
kibanaserver / kibanaserver

# Agent client
## https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html
## Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.10.1-1.msi -OutFile $env:tmp\wazuh-agent; msiexec.exe /i $env:tmp\wazuh-agent /q WAZUH_MANAGER='10.17.1.26'
