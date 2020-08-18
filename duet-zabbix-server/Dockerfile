FROM zabbix/zabbix-server-mysql:alpine-latest

USER root
RUN apk add --update python2 python2-dev py2-pip build-base
RUN pip install pysnmp
RUN pip install requests
RUN pip install workalendar

USER zabbix