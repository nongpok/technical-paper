# Messaging Queues
A Message Queue(MQ) is a software engineering component used for communication between processes or between threads within the same process. Message queues provide an asynchronous communication protocol in which the sender and receiver of messages don't need to interact at the same time. Messages are held in queue until the recipient retrieves them. 


## Features
- Asynchronous Communications Protocol
- Message Encryption
- Message storage, retrieval, and deletion
- Permissions for users and software
- System decoupling
- Data error reduction
- Cloud-based or on-premises installation


## Why Message Queues are used?
Let's break it down to something very plain and simple:

* **Message:** Applications communicate by writing and retrieving inbound and outbound data (messages) in a queue.
* **Queue:** A queue eliminates the need for applications to send and receive at the same time.

MQ allows decoupling between upstream and downstream applications. The upstream application sends messages to MQ and the downstream application receives messages from MQ. The upstream and downstream applications no longer depend on each other, instead, they only depend on MQ. Due to the queuing mechanism, MQ can act as a buffer between the upstream and downstream applications. Messages from the upstream application are cached and the downstream application then pulls messages from MQ when it can, reducing peak traffic.


## Popular Tools
- [MuleSoft Anypoint Platform](https://www.mulesoft.com/platform/enterprise-integration)
- [IBM MQ](https://www.ibm.com/products/mq)
- [Azure Scheduler](https://azure.microsoft.com/en-us/services/logic-apps/)
- [Apache Kafka](https://kafka.apache.org/intro)
- [Rabbit MQ](https://www.rabbitmq.com/)


## Enterprise Message Bus
A combination of a common data model, a common command set, and a messaging infrastructure to allow different systems to communicate through a shared set of interfaces. This is analogous to a communications bus in a computer system, which serves as the focal point for communication between the CPU, main memory, and peripherals.


## References
- https://www.cloudamqp.com/blog/what-is-message-queuing.html
- https://aws.amazon.com/message-queue/
- https://www.g2.com/categories/message-queue-mq
- https://www.ibm.com/cloud/learn/message-queues

