# Zabbix
This creates a setup, using Vagrant, with three VM's based on CentOS 7 and Zabbix 4.4

1. *Zabbix server* (10.0.15.30) - Runs Zabbix server + nginx / php-fpm
2. *Zabbix proxy* (10.0.15.31) - Runs Zabbix proxy (active mode)
3. *Zabbix client* (10.0.15.32) - Runs Zabbix agent and connects with proxy

The Ansible playbook makes sure that the server, proxy and client are linked
