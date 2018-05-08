# zabbix-varnish
Basic varnish monitoring template and config file for zabbix

Usage instructions are as simple as:
1. upload userparameters to /etc/zabbix/zabbix-agent.d/
2. import template into zabbix and attach to vm which has varnish installed and running

if permissions become an issue - execute
#usermod -a --groups varnish zabbix
