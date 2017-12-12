# prometheus_bot

Containerised version of [prometheus_bot](https://github.com/inCaller/prometheus_bot)

prometheus_bot is a Telegram bot to accept alerts from Prometheus [Alertmanager](https://prometheus.io/docs/alerting/alertmanager/)

Map your prometheus_bot data folder with your config.yaml file as /config to the container

---
#### 0.0.1 (2017-12-12)

Initial release

---
#### Example Run Command

```
docker run -d -p 9087:9087 -v /srv/prometheus_bot:/config b3vis/prometheus_bot
```
---
