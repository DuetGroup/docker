FROM zabbix/zabbix-agent:alpine-4.4-latest

USER root
RUN apk add --update python2 python2-dev py2-pip build-base
RUN pip install requests
RUN pip install workalendar

USER zabbix