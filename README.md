# pyroscope-kafka-sandbox


## Overview
Profiling a typical Kafka environment using Pyroscope


## Environment

The environment has 1 Zookeeper, 2 Kafka Brokers, 1 Connect, and 1 Schema Registry. All the mentioned components are instrumented with the pyroscope agent that you can find in the `pyroscope-agent` folder.


## Executing

```
docker compose up -d
```

## Checking the logs (interactive), just in case :)

```
docker compose logs -f
```


## Accessing the Pyroscope UI

Hit http://localhost:4040 from your browser

![PyroscopeUI](https://github.com/mcascallares/pyroscope-kafka-sandbox/raw/main/screenshots/pyroscope-ui.png)
