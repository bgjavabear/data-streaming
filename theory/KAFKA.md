# Kafka

## Topic

Kafka Topics are roughly analogous to SQL tables  
Topics are not queryable like SQL tables  
All data in a topic is in key-value form

## Producer

Sends data to a topic

#### Synchronous producers

Block producer program execution until the broker has confirmed receipt

#### Asynchronous producers

Callback for delivered events or errors

## Consumer

Retrieve events from Kafka topics

## Broker

Kafka servers are referred to as brokers

## Cluster

All the brokers that work together are referred to as a cluster

## Zookeeper

Apache Zookeeper is used by Kafka brokers to determine which broker is the leader of a given partition and topic

