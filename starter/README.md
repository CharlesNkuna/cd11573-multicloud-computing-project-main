# Amazon DynamoDB vs Azure Cosmos DB
Developers describe Amazon DynamoDB as "Fully managed NoSQL database service". All data items are stored on Solid State Drives (SSDs), and are replicated across 3 Availability Zones for high availability and durability. With DynamoDB, you can offload the administrative burden of operating and scaling a highly available distributed database cluster, while paying a low price for only what you use. On the other hand, Azure Cosmos DB is detailed as "A fully-managed, globally distributed NoSQL database service". Azure DocumentDB is a fully managed NoSQL database service built for fast and predictable performance, high availability, elastic scaling, global distribution, and ease of development.

Amazon DynamoDB and Azure Cosmos DB belong to "NoSQL Database as a Service" category of the tech stack.

Some of the features offered by Amazon DynamoDB are:
- Automated Storage Scaling – There is no limit to the amount of data you can store in a DynamoDB table, and the service automatically allocates more storage, as you store more data using the DynamoDB write APIs.
- Provisioned Throughput – When creating a table, simply specify how much request capacity you require. DynamoDB allocates dedicated resources to your table to meet your performance requirements, and automatically partitions data over a sufficient number of servers to meet your request capacity. If your throughput requirements change, simply update your table's request capacity using the AWS Management Console or the Amazon DynamoDB APIs. You are still able to achieve your prior throughput levels while scaling is underway.
- Fully Distributed, Shared Nothing Architecture – Amazon DynamoDB scales horizontally and can seamlessly scale a single table over hundreds of servers.

On the other hand, Azure Cosmos DB provides the following key features:
- Fully managed with 99.99% Availability SLA
- Elastically and highly scalable (both throughput and storage)
- Predictable low latency: <10ms @ P99 reads and <15ms @ P99 fully-indexed writes