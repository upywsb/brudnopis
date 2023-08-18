# brudnopis
Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.5.0-1.msi -OutFile ${env:tmp}\wazuh-agent.msi; msiexec.exe /i ${env:tmp}\wazuh-agent.msi /q WAZUH_MANAGER='192.168.50.50' WAZUH_REGISTRATION_SERVER='192.168.50.50' WAZUH_AGENT_GROUP='default' WAZUH_AGENT_NAME='w10Test' 
