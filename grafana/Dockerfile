FROM grafana/grafana:10.3.3

COPY opensearch.json /var/lib/grafana/dashboards/

RUN chmod 644 /etc/grafana/provisioning

COPY grafana-provisioning/ /etc/grafana/provisioning/
