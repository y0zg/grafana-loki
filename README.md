

#### Dashboard: 
https://grafana.com/dashboards/893

#### Display docker logs: 
https://github.com/deep-compute/docker-file-log-driver

Example: `alpine.yml`

#### Guidance:
- https://rtfm.co.ua/en/grafana-labs-loki-logs-collector-and-monitoring-system/ 
- https://rtfm.co.ua/en/grafana-labs-loki-distributed-system-labels-and-filters/

#### Grafana dashboard installation using Docker:
- https://grafana.com/docs/installation/docker/
- https://grafana.com/docs/installation/behind_proxy/

`grafana.ini`
```
Ensure domain and root_url are configured for grafana.ini
# The public facing domain name used to access grafana from a browser
domain = server.com


# The full public facing url
# root_url = %(protocol)s://%(domain)s:%(http_port)s/
root_url = %(protocol)s://%(domain)s/grafana/
```

