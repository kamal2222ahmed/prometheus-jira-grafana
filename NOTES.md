https://finestructure.co/blog/2016/5/16/monitoring-with-prometheus-grafana-docker-part-1



http://localhost:9090/graph#%5B%7B%22range_input%22%3A%221h%22%2C%22end_input%22%3A%22%22%2C%22step_input%22%3A%22%22%2C%22stacked%22%3A%22%22%2C%22expr%22%3A%22node_load1%22%2C%22tab%22%3A0%7D%2C%7B%22range_input%22%3A%221h%22%2C%22end_input%22%3A%22%22%2C%22step_input%22%3A%22%22%2C%22stacked%22%3A%22%22%2C%22expr%22%3A%22node_load1%22%2C%22tab%22%3A0%7D%5D

http://localhost:9090/graph#%5B%7B%22range_input%22%3A%221h%22%2C%22end_input%22%3A%22%22%2C%22step_input%22%3A%22%22%2C%22stacked%22%3A%22%22%2C%22expr%22%3A%22node_load1%22%2C%22tab%22%3A0%7D%2C%7B%22range_input%22%3A%221h%22%2C%22end_input%22%3A%22%22%2C%22step_input%22%3A%22%22%2C%22stacked%22%3A%22%22%2C%22expr%22%3A%22node_load1%22%2C%22tab%22%3A0%7D%5D

you can access Grafana at http://localhost:3000/login

https://stackoverflow.com/questions/37705017/create-named-docker-volume-with-docker-compose


$ docker-compose up -d
Creating volume "finestructureco_prometheus_data" with default driver
Creating volume "finestructureco_grafana_data" with default driver
Recreating finestructureco_prometheus_1 ...
Starting finestructureco_node-exporter_1 ...
Recreating finestructureco_prometheus_1  ... done
Starting finestructureco_node-exporter_1 ... done
Recreating finestructureco_grafana_1     ...
WARNING: Service "grafana" is using volume "/var/lib/grafana" from the previous container. Host mapping "finestructureco_grafana_data" has no effect. Remove the existing containers (with `docker-compose rm grafaRecreating finestructureco_grafana_1     ... done


