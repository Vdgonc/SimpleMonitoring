# Simple Monitoring Stack With Prometheus, InfluxDB and Grafana

---

### Description:

This is a simple ansible-playbook for you to create a monitoring server using Prometheus, InfluxDB, and Grafana. 
With this stack, you can create a server to centralize the metrics of your environment and view it's in your dashboards in Grafana.

With Node Exporter you can centralize the metrics in Prometheus, with Telegraf you can send the metrics to InfluxDB, and Grafana you can view these metrics. 



### How to use:

After inserting the IP address in the host, execute the command in your terminal:

​	`ansible-playbook -i hosts main.yml --key-file='you-key.pem'`

### Notes:

This playbook was tested on AWS EC2 using one t3.medium. The distro is Ubuntu 18.04.



### References:

https://prometheus.io/docs/

https://docs.influxdata.com/influxdb/v1.7/

https://grafana.com/docs/grafana/latest/

https://docs.ansible.com/