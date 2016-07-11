# elastic_kibana
Easily run ElasticSearch &amp; Kibana in docker

# First-time install
1. Clone the repo:
```
git clone git@github.com:YotpoLtd/elastic_kibana.git
cd elastic_kibana
```
2. Build and add the images:
```
docker-compose up -d
```

# Every time after reboot
Start the images:
```
cd elastic_kibana
docker-compose start
```
