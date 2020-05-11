# DLB: Deep Learning Based Load Balancing
## Abstruct
Load balancing mechanisms have been widely adopted by distributed platforms and their effectiveness is of great importance to the quality of services provided by such platforms. The core of the existing load balancing mechanisms, such as consistent hashing, is a hash function, which is expected to be able to uniformly map both client workloads and the servers to a hash circle, and each workload is assigned to its clockwise closest server. Under this assumption, the load distribution among different servers can be balanced. However, hash functions do not perform well on the skew data sets, which commonly exist in the real-world. Therefore, using hash functions in load balancing could lead to unbalanced load distribution and eventually harm the performance of applications running on the distributed platforms. In this paper, we introduce DLB, a deep learning based load balancing mechanism, to effectively address the data skew problem. The core idea of DLB is to replace the hash function in the load balancing mechanism by deep learning models, which can be trained to uniformly map the client workloads to the hash circle, especially when the distribution of the workloads is skewed. Experimental results using both synthetic and real-world data sets show that compared with traditional hash function based load balancing methods, DLB is able to generate more balanced results, especially when the input data is skewed.
