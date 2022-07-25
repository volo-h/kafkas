```
  docker exec -it kafka /bin/sh
  ./opt/bitnami/kafka/bin/kafka-topics.sh --create --bootstrap-server localhost:9092 --replication-factor 1 --partitions 3 --topic topic2
  ./opt/bitnami/kafka/bin/kafka-topics.sh --list --bootstrap-server localhost:9092
```
