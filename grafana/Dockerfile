FROM grafana/grafana:6.4.2

USER grafana

COPY ./datasources/Mysql-Agent.yaml /etc/grafana/provisioning/datasources/ 
COPY ./dashboards/mysql-simple-dashboard.json /var/lib/grafana/dashboards/
COPY ./dashboards/mysql-simple-dashboard.yaml /etc/grafana/provisioning/dashboards/