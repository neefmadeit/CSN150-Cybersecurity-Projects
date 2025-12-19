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

## Steps I followed
1. Installed the Ubuntu VM
2. Updated Ubuntu using the follwing command in terminal - sudo apt update && sudo apt upgrade -y
3. Installed the curl package using the follwing command in terminal - sudo apt install curl
4. Part 1 - installed Wazuh Sever using the follwing command in terminal - curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh
5. Part 2 - of installation by using the follwing command in terminal - sudo bash-wazuh-install.sh -a
6. Verified that the Wazuh sever is working by logging into the web dashboard
7. Downloaded and installed the Wazuh agents on my systems from the Wazuh website
8. Entered my server's ip address on the Wazuh agent setup tool
9. Verifed that the agents are working by checking the Wazuh's server web dashboard

## Problems / Solutions
Always remember to run the terminal as an admin when installing.
## Final Report
I am excited that I final got to install a SIEM and see how it works. The installation process was not very long and I recommend that anyone that is just starting out in the cybersecurity field should install Wazuh and give it a try for some hands on experience with SIEMS.
