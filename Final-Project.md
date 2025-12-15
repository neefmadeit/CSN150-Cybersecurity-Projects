# Cybersecurity : CSN150

## Name of Project
Monitor Everything With Wazuh 

## Purpose
The purpose of this project is to set up and deploy a SIEM. The SIEM that I will be using is called Wazuh. Wazuh is a free, open-source security platform, and it works by collecting, analyzing, and correlating security data from agents deployed on monitored systems to detect vulnerabilities, intrusions, and malicious activity.

## Tools used 
- Wazuh
- Linux
- Ubuntu
- Promox

## Links to documentation
- Wazuh Sever: https://documentation.wazuh.com/current/installation-guide/wazuh-server/index.html
- Wazuh Agent: https://documentation.wazuh.com/current/installation-guide/wazuh-agent/index.html
- Wazuh Dashbaord: https://documentation.wazuh.com/current/installation-guide/wazuh-dashboard/index.html

## Steps I followed
1. Installed the Ubuntu VM
2. Update Ubuntu using the follwing command in terminal - sudo apt update && sudo apt upgrade -y
3. Installed Wazuh using the follwing command in terminal - curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
4. Verified that the Wazuh sever is working
5. Downloaded and installed the Wazuh agent on two Linux VMs
6. Verifed that the agents are working

## Problems / Solutions

## Final Report
