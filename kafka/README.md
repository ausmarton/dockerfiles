# Kafka in a docker image
A minimal docker image with Kafka

Default run tries to connect to a Broker with a Consumer
To run:
```bash
docker run --env BROKER=example.broker.host --env TOPIC=example.topic -it ausmarton/kafka:latest
```
