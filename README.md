# Data-Engineering
## Project 1: Real Time Data Processing 
### Real-Time Data Processing

**Why is it essential?**

Real-time data processing is crucial in modern applications for the following reasons:

- **Timely Decision Making**
- **Improved Customer Experience**
- **Enhanced Monitoring & Alerts**
- **Automation & Efficiency**
- **IoT (Internet of Things)**
- **Data-Driven Insights**
- **Fraud Detection & Security**
- **Competitive Advantage**

**What is Kafka?**
Distributed event store and stream processing platform
#### Kafka Components
**Producers**, **Kafka Brokers**- Broker- A Single member server of the Kafka cluster, **Consumers** -- Reports/Dashboards/Insights/Processors, **Zookeeper** - Open Source Apache Project, Enables highly reliable distributed coordination, Distributed key value store, Maintains configuration information, Stores ACLs and Secrets, distributed synchronization, **Topics** - Logical buckets inside Kafka broker, **Partition**, **Log**
- Producer sends messages to brokers, Brokers receive and store messages, A Kafka Cluster can have many Brokers, Each Broker manages multiple Partitions.
- **Stream** - An unbounded sequence of ordered, immutable data
- **Stream Processing** - Continual calculations performed on one or more Streams
- **Immutable Data** - Data that cannot be changed once it has been created
- **Event** - An immutable fact regarding something that has occured in system.

### Architecture Diagram

