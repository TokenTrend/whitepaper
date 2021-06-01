## 7. System Design

We design a Four-layer structure to ensure the high reliability, scability, and integrity of the whole system, as well as the high security of all necessary data. As a result, we provide customers an efficient and trustable platform.

1. Network Layer: As the basic foundation of the TT cross-chain token, we will aggregate high-quality public chains and DeFi ecological systems based on these chains. This includes Ethereum, Binance Smart Chain and Huobi Chain to provide cross-chain trading.
2. Visualization Layer: We developed multiple visualized website layer with the most rigorous authentication methodology of blockchain to ensure the safety of users.
3. Application Layer: We put 2 load balancer clusters in front of components which distribute network traffic and workloads across 2 computing clusters, which increase the availability and fault tolerance of whole system. We build 2 application clusters to further ensure the stability and throughput of the system.
4. Data layer:  We use database to store necessary data so all the transaction and other activity data can be tracking and reused. We use Redis cluster as the cache layer and ES cluster to enhance the response efficiency and improve the protection of the database. For the data in Solidity, we isolate the data layer and logic layer so that the code in Sol can be updated and maintained easily in the future.

 ![avatar](./pic/system-design.png)