## Kafka architecture

1. Broker → A Kafka server that stores data.
2. Topic → A named stream of messages (like a channel).
3. Producer → Publishes messages to a topic.
4. Consumer → Reads messages from a topic.
5. Consumer Group → Group of consumers that share the load.
6. Partition → Kafka splits topics into partitions for parallelism.
7. Offset → Position of each message in a partition.