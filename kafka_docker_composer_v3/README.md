```sh
  docker-compose up --force-recreate
```

### go to Kafka container directly
```sh
  docker exec -it kafka_docker_composer_v3_kafka_1 /bin/sh
```

### where Kafka located?
/opt/kafka/bin

### create one Topic
```
  ./opt/kafka/bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic selftuts
```

### read last created Topic
```
  ./opt/kafka/bin/kafka-topics.sh --list --zookeeper zookeeper:2181
```
