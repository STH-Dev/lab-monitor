# STH lab-monitor
This is a project to bring ELK Stack Monitoring via Docker to Lab environments.

Objective: Monitor Lab Environments

Technologies: Elasticsearch, Logstash, Kibana, Docker

# Description
We should have a standard launcher for an ELK stack in Docker. Then, we should work on getting Proxmox, pfSense and FreeNAS logs into the ELK stack.

# Steps 
1. Create Docker launche for ELK stack using Docker Compose with username/ password credentials entered as a variable
2. Build simple monitoring features for:
  i. FreeNAS
  ii. pfSense
  iii. Proxmox VE
  iv. MySQL/ MariaDB
  v. nginx
  
# Discussion Thread
Discuss the project on the STH forums here: https://forums.servethehome.com/index.php?threads/project-proposal-elk-stack-for-monitoring-proxmox-pfsense-freenas.14513/
