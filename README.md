# zabbix-varnish
Basic varnish monitoring template and config file for zabbix

Usage instructions are as simple as:
1. allow zabbix to run scripts with varnish permissions by adding to group:
  #usermod -a --groups varnish zabbix
2. upload userparameters to /etc/zabbix/zabbix-agent.d/
3. import template into zabbix and attach to vm which has varnish installed and running
