# OCP4_Health_Check

EDIT Inventory hosts accordingly

------------------------------------------------------------

EDIT roles/apache_install/templates/httpd_config.j2 if you would like to change which ports to listen to E.g. "Listen 8080"

ADD semanage port to httpd in roles/firewalld_open/tasks/main.yml

------------------------------------------------------------

RUN healthcheck.yml 
