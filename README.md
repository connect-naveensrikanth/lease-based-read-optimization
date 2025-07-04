# latency
**It's a metric used to measure the number of requests a system receives and processes per second.**

**OPTIMIZING READ PERFORMANCE IN DISTRIBUTED SYSTEMS WITH LEASE-BASED LATENCY**
* Author: Naveen Srikanth Pasupuleti
* Published In : International Journal of Leading Research Publication (IJLRP)
* Publication Date: 02-2023
* E-ISSN: 2582-8010
* Impact Factor: 9.56
* Link: https://www.ijlrp.com/research-paper.php?id=1583

**Abstract**:\
In distributed systems like etcd, read index latency impacts the speed and efficiency of strongly consistent read operations. Etcd’s read index ensures linearizability by coordinating between follower and leader nodes, but this process introduces increased latency as cluster size grows. Higher latency can hinder performance in applications requiring fast, frequent reads. This paper proposes a lease-based approach to reduce read index latency while maintaining consistency. The method aims to balance responsiveness and data accuracy in large-scale etcd deployments.

**Key Contributions:** 
* **Algorithm Development** \
  Designed and optimized Lease based latency methodology targetting by reducing the latency.
* **Performance Comparison** \
  Conducted bench marking between ReadIndex Latency and Lease Based Latency.
* **Reserach Leadership**
  Led the research and technical implementation , focusing on advancing distributed database through algorithm innovation.

**Relevance & Real-World Impact**
* **Kubernetes infrastructure optimization:**\
    Enhances distributed key-value store performance by reducing the read latency.
* **Query Processing Improvement:** \
    need to add here
* **Academic Recognition :** \
    need to add here
* **Educational Impact:** \
    need to add here

**Experimental Results (Summary)**


| Cluster Size (Nodes) | ReadIndex Latency (ms) | Lease-Based Latency (ms)| Improvement (%) |
| ---------------------| --------------------- | ------------------------ | ----------------|
| 3                    | 3                     | 0.2                      | 93.33           |
| 5                    | 5                     | 0.3                      | 94.0            |
| 7                    | 7                     | 0.4                      | 94.29           |
| 9                    | 9                     | 0.5                      | 94.44           |
| 11                   | 11                    | 0.6                      | 94.55           |

**Citation**
* **OPTIMIZING READ PERFORMANCE IN DISTRIBUTED KEY-VALUE STORES BY REDUCING THE READ LATENCY**
*   Naveen Srikanth Pasupuleti
*   International Journal of Leading Research Publication
*   E-ISSN-2582-8010

**License**
* This research is shared for a academic and research purposes. For commercial use, please contact the author.

**Resources**
* https://www.ijlrp.com/

**Author Contact** 
  * LinkedIn: https://www.linkedin.com/in/naveensrikanth/
  * Email: connect.naveensrikanth@gmail.com
