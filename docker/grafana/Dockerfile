FROM grafana/grafana:latest

ADD ./config/dashboards /etc/grafana/provisioning/dashboards
ADD ./config/datasources /etc/grafana/provisioning/datasources
ADD ./config/config.ini /etc/grafana/config.ini
ADD ./dashboards /var/lib/grafana/dashboards
