# Metric ...
* Appication/service
* Tools => redis, kafka

## Solution 1 :: OpenTelemetry
* Redis 
* [Redis receiver](https://github.com/open-telemetry/opentelemetry-collector-contrib/tree/main/receiver/redisreceiver)

```
$docker compose up -d
```
Open prometheus ui at http://localhost:9090/

## Solution 2 :: Prometheus
* Prometheus
* [Redis exporter](https://github.com/oliver006/redis_exporter)
