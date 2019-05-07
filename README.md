# SoC-Validation

A SoC design typically integrates a large number of IP blocks connected with a network structure. System level functions are realized by executing multiple IPs following certain communication protocols.  IP executions are coordinated by exchanging messages.   On the other hand, validation of SoC design is extremely challenging due to stringent time-to-market requirement and the scale of complexity.  Additionally, limited observability adds another dimension of complexity for post-silicon debug of SoC designs.  

To address the above challenges, this research project explores the communication-centric approach where validation and debug focus on whether exchanges of messages among different IPs adhere to defined specifications, i.e. *message flows*.  By raising the abstraction level, the complexity of validation and debug is greatly reduced. 

# Related Publications

* [*A Communication-Centric Observability Selection for Post-Silicon System-on-Chip Integration Debug*](), Yuting Cao, Hao Zheng, Sandip Ray, ISQED'2019

* [*Enhancing Observability for Post-Silicon Debug with On-chip Communication Monitors*](), Yuting Cao, Hernan M. Palombo, Sandip Ray, Hao Zheng, ISVLSI'2018

* [*A Post-Silicon Trace Analysis Approach for System-on-Chip Protocol Debug*](), Yuting Cao, Hao Zheng, Hernan M. Palombo, Sandip Ray, Jin Yang, ICCD'2017

* [*Protocol-guided analysis of post-silicon traces under limited observability*](), Hao Zheng, Yuting Cao, Sandip Ray, Jin Yang, ISQED'2016

