## [<< back](./index.html)

The following lecture schedule is *tentative* and might be updated during the semester. 
We will be keeping you informed of any changes via [Piazza](https://piazza.com/bu/fall2025/cascs651/home). 
You may also want to take a look at the [Official Semester Dates](https://www.bu.edu/reg/calendars/semester/).

**MSAT** refers to the textbook [Distributed Systems, 4th Edition](https://www.distributed-systems.net/index.php/books/ds4/) by Maarten van Steen and Andrew S. Tanenbaum.


| Date  | Topic | Assigned Reading | 
| ----- | ----------- | ----------- |
|  9/3  | L1:  Course Overview  | - |
|  9/8  | L2:  Computation and Communication Primitives (threads; RPCs)  | MSAT Ch. 3.1, 4.1, 4.2 |
|  9/10  | L3:  Concurrency and Parallelism  | [The Go Programming Language and Environment](https://cacm.acm.org/research/the-go-programming-language-and-environment/) |
|  9/15  | L4:  Data-parallel computation  | [MapReduce](https://dl.acm.org/doi/10.1145/1327452.1327492) | 
|  9/17  | L5:  Fault Tolerance (primary-backup replication; checkpointing; write-ahead logging)| [GFS](https://dl.acm.org/doi/10.1145/945445.945450) |
|  9/22  | L6:  Data Consistency (strong vs weak consistency; linearizability) | [Zookeeper](https://dl.acm.org/doi/10.5555/1855840.1855851) |
|  9/24  | L7:  State Machine Replication I (distributed consensus; leader election)| [OmniPaxos](https://dl.acm.org/doi/abs/10.1145/3552326.3587441) (Sec. 1-3, 5)  |
|  9/29  | L8:  State Machine Replication II (log replication; persistence; reconfiguration) | [OmniPaxos](https://dl.acm.org/doi/abs/10.1145/3552326.3587441) (Sec. 4, 6)|
|  10/1  | L9:  Geo-replicated Systems | [PNUTS](https://dl.acm.org/doi/10.14778/1454159.1454167) |
|  10/6  | L10:  Publish-Subscribe (asynchronous, reliable, event-driven communication)  | [The Many Faces of Publish/Subscribe](https://dl.acm.org/doi/10.1145/857076.857078) |
|  10/8  | L11: Distributed Shared Memory (write amplification; false sharing; causal consistency)| [TreadMarks](https://www.eecg.toronto.edu/~amza/ece1747h/papers/treadmarks94.pdf) |
|  10/14 |  Hacking Day (No lecture) | - |
|  10/15 |  **Review: Lectures 1-12 / Practice Exam** | - |
|  10/20  | L12:  Guest Lecture by Prof. Romaric Duvignau (Chalmers): DHTs and Trackerless BitTorrent | TBD |
|  10/22  | L13:  Eventual Consistency (conflict resolution; gossip protocols)  | [Dynamo](https://dl.acm.org/doi/10.1145/1323293.1294281) |
|  10/27  | **Midterm (during lecture)** | Lectures 1-11 |
|  10/29  | L14: Distributed Transactions I (serializability; snapshot isolation)  | [Spanner](https://www.usenix.org/conference/osdi12/technical-sessions/presentation/corbett) |
|  11/3  | L15: Distributed Transactions II (atomicity; two-phase commit)  | - |
|  11/5  | L16:  Distributed Transactions III (optimistic concurrency control)  | [FaRM](https://dl.acm.org/doi/10.1145/2815400.2815425) | 
|  11/10  | L17: Cluster Computing I (dataflow model) | [Spark](https://dl.acm.org/doi/10.5555/2228298.2228301) |
|  11/12  | L18: Cluster Computing II (distributed futures)  | [Ray](https://www.usenix.org/conference/nsdi21/presentation/cheng) |  
|  11/17  | L19: Cluster Management (resource consolidation; job scheduling)| [Borg](https://dl.acm.org/doi/10.1145/2741948.2741964) |
|  11/19  | L20: Distributed Tracing (microservices) | [Pivot Tracing](https://dl.acm.org/doi/10.1145/2815400.2815415) |  
|  11/24  | L21: Distributed Training (ML) | TBD |
|  11/26  | L22: Serverless Computing  | [Cloud Programming Simplified](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2019/EECS-2019-3.pdf) | 
|  12/1  | L23:  Decentralized Trust  | [Conclave](https://dl.acm.org/doi/10.1145/3302424.3303982) |    
|  12/3  | L24: Bitcoin | [Bitcoin](https://bitcoin.org/bitcoin.pdf) |
|  12/8  | L25: Research Topics in Distributed Systems  | - | 
|  12/10  |  **Review: Lectures 13-24 / Practice Exam**  | - |
