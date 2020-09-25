> Version 1.1 - (2020.9.25)

### Zabbix Template for GitLab health check

for Zabbix 3.x+ (test in 4.4)

zabbix-agent must be installed on the monitored node

### Install

* define macros {$GIT_TOKEN} for each host
* Change <YOU_GITLAB_URL> (http or https) and copy userparameter_githealth.conf into /etc/zabbix/zabbix_agent.d 
* import Template 
* restart zabbix_agent

### Files

* template_githealth.xml - Zabbix template 
* userparameter_githealth.conf - Zabbix userparameters file

### References


### Version

* 1.0 - initial
* 1.1(remix) -for Gitlab 12.4+





