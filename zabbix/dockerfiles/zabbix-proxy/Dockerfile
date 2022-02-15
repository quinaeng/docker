FROM mariadb:latest

COPY ../../config/zabbix-proxy/schema.sql /docker-entrypoint-initdb.d/

VOLUME [ "/var/lib/mysql" ]
