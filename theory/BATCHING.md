# Batching

When kafka client library sends data to Kafka, they do not send every message individually. 
Instead, the client libraries collect group of messages together and then send them to the Kafka broker.