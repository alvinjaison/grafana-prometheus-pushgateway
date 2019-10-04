# grafana-prometheus-pushgateway
Run Grafana, Prometheus and Pushgateway using docker-compose

* Clone this repo and enter into the repo

      $ cd grafana-prometheus-pushgateway/

* Make sure docker and docker-compose are running on your machine. Grafana uses port 3000. prometheus and pushgateway uses 9090 and 9091 ports respectively. Make sure those ports are not running in your machine.

* Start all 3 services using docker-compose
      $ docker-compose start
