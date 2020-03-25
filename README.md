18:53 $ docker-compose ps
                 Name                                Command               State           Ports
---------------------------------------------------------------------------------------------------------
prometheus-jira-grafana_alertmanager_1    /bin/alertmanager --config ...   Up      0.0.0.0:9093->9093/tcp
prometheus-jira-grafana_cadvisor_1        /usr/bin/cadvisor -logtostderr   Up      0.0.0.0:8080->8080/tcp
prometheus-jira-grafana_grafana_1         /run.sh                          Up      0.0.0.0:3000->3000/tcp
prometheus-jira-grafana_node-exporter_1   /bin/node_exporter --path. ...   Up      0.0.0.0:9100->9100/tcp
prometheus-jira-grafana_prometheus_1      /bin/prometheus --storage. ...   Up      0.0.0.0:9090->9090/tcp

