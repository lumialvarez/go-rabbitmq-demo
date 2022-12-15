# go-rabbitmq-demo

Run RabbitMQ with Docker

```
# latest RabbitMQ 3.11
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management
```

## Basic
 A single publisher and single consumer