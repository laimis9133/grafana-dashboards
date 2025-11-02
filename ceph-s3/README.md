# grafana-ceph-s3
Grafana dashboard for Ceph S3 activity

Dashboard visualisations created using two sets of metrics:
- Per bucket/user metrics available since [Ceph Squid 19.2.0 release](https://docs.ceph.com/en/latest/releases/squid/#monitoring)
- RadosGW metrics exported with [radosgw_usage_exporter](https://github.com/blemmenes/radosgw_usage_exporter) (shoutout to the creators!)


Separate rows allow to monitor various bucket operation trends
![Here](https://github.com/laimis9133/grafana-dashboards/blob/main/ceph-s3/previews/example1.png?raw=true)

As well as overall user activites
![Here](https://github.com/laimis9133/grafana-dashboards/blob/main/ceph-s3/previews/example3.png?raw=true)

A single bucket view is also available using the dropdown menu
![Here](https://github.com/laimis9133/grafana-dashboards/blob/main/ceph-s3/previews/example4.png?raw=true)

Everything can be compared with general cluster activity to identify patterns
![Here](https://github.com/laimis9133/grafana-dashboards/blob/main/ceph-s3/previews/example2.png?raw=true)

Dashboard also uploaded for public use to [GrafanaLabs page here](https://grafana.com/grafana/dashboards/22580-ceph-squid-s3-bucket-metrics/). Enjoy.
