# Techniki komunikacji serwisów

## Sync

- REST API (e.g., https://www.openapis.org), websockets, GraphQL (https://graphql.org)
- [gRPC](https://grpc.io)

Note: losing messages, harder too scale, retries strategies, repeated messages

## Async

- even-driven
- queue (e.g., RabbitMQ)
- message-based (Kafka, AWS SQS)

Note: dead-letter-queue, ordering, ...

## Consensus

- Hashicop Consul, etcd 

## References

- [Communication between Microservices](https://softwaremill.com/how-to-communicate-java-microservices/)
- [Practice of Cloud System Administration](https://www.amazon.com/Practice-Cloud-System-Administration-Practices/dp/032194318X)
- [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321/ref=d_pd_sbs_vft_none_sccl_2_5/132-3064294-1858128)
- [Talks from Martin Thompson, aka queues are everywhere](https://www.youtube.com/watch?v=S4LzzuMTqjs)
