@little
@email : little199011@163.com

Tendermint 拜占庭容错协议栈


比特币是当今众所周知的基于区块链的密码学货币的开山鼻祖。Tendermint协议与比特币有着共同之处:这两种协议将
所有内容记录在区块链,然而它们都为"拜占庭将军问题"也称"共识"或者"协议"问题,提供了各自独特的解决方案。
Tendermint最早可以追溯到分布式计算和拜占庭容错(BFT)在学术界的文献 (例如，参见Ethan Buchman的学位论文)。
在经历了很多次早期的电子现金系统失败的尝试后-除了PayPal这个例外-比特币作为一个抗审查的去中心化货币系统脱颖而出。



鉴于比特币的主要功能是作为一个支付系统，比特币协议针对抗审查(不可追溯)的需求进行了优化。
在另一方面，Tendermint提升了在广域网中，比如说几百个节点(多节点数量)的通用拜占庭容错分布式应用和数据处理能力。
这个差别很小但是值得深入研究。


在学术界，对WAN的BFT(拜占庭式容错)系统的研究非常少，而且这些研究主要是针对节点数量较少———一般是4至7个节点且
只有单一管理域的场景。对于大量节点和多个管理域的WAN环境下的BFT系统，无重要的研究成果在实践中被广泛采用。


在2009年之前，当比特币引入一种范式转换技术——也就是区块链概念时，WAN环境中针对多节点数量的共识问题在很大程度上是
没有得到得不到解决。尽管解决了两位将军的问题，但在分布式系统研究领域的纯理论意义上，比特币并不是真正解决共识的
一种算法。进一步完善BFT领域的工作还远未完成。


2014年，计算机科学和系统工程背景出身的JaeKwon设想了一种完全基于BFT的协议，该协议以权益证明(PoS)作为底层安全机制,这个协议
可以自动扩展到数百个节点而无需设置. 于是. Tendermint应运而生。这种使用PoS作为广域网中大量验证节点的底层安全机制的系统模型
是一项非常复杂的工程尝试，耗时近4年才能在公开区块链环境下实施。这个公有链就是Cosmos，预计在2018年夏天推出。