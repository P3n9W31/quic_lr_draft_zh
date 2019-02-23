介绍
====================

QUIC (Quick UDP Internet Connection) 是一种建立在UDP协议之上的新型的可以实现
多路复用与安全传输的协议，该协议是从头开始设计的并针对HTTP / 2语义进行了优化。虽然
使用HTTP / 2作为主要应用程序协议构建，但QUIC建立在数十年的传输和安全经验之上，实现
的机制使其成为了一个现代、通用性强且具有吸引力的传输机制。QUIC协议的具体描述可以在文
档‘draft-tsvwg-quic-protocol’中查看。

QUIC实现了已知的TCP丢包恢复机制的核心思想——在RFC，各种Internet草案以及Linux TCP实
现中普遍存在的那些中描述。本文档描述了QUIC丢包恢复机制，并在一些情况下，描述了TCP在其
他的RFC，Internet草案，学术论文和/或TCP具体实现中所描述的一些属性。