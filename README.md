# wazuh
```code
git clone --depth 1 https://github.com/wazuh/wazuh-docker.git -b v4.10.1
docker compose -f generate-indexer-certs.yml run --rm generator
docker compose up -d

#docker compose down -v
```
# OpenCVE
https://www.opencve.io/

# webhook 
### https://documentation.wazuh.com/current/user-manual/manager/integration-with-external-apis.html
### /app/notifications-dashboards#/channels
```code
- ./config/wazuh_indexer/internal_users.yml:/usr/share/wazuh-indexer/opensearch-security/internal_users.yml

  <integration>
    <name>slack</name>
    <hook_url>https://abc.sample.com/oauth2/ip</hook_url>
    <level>10</level>
    <alert_format>json</alert_format>
  </integration>
</ossec_config>
```

# CVE Update
https://documentation.wazuh.com/current/user-manual/capabilities/vulnerability-detection/offline-update.html

# Dashboard
kibanaserver / kibanaserver

# Agent client
## https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html
## Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.10.1-1.msi -OutFile $env:tmp\wazuh-agent; msiexec.exe /i $env:tmp\wazuh-agent /q WAZUH_MANAGER='10.17.1.26'

# AIops
https://www.keephq.dev/
