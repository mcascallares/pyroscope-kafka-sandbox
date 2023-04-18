# pyroscope-kafka-sandbox

## Overview
Instrumenting a typical Kafka environment using Pyroscope

## Environment

The environment has 1 Zokeeper, 2 Kafka Brokers, 1 Connect and 1 Schema Registry. All the mentioned components are instrumented

## Executing

```
docker-compose up -d
```

## Browser Pyroscope UI

Hit http://localhost:4040 from your browser

![PyroscopeUI](https://github.com/mcascallares/pyroscope-kafka-sandbox/raw/main/screenshots/pyroscope-ui.png)
