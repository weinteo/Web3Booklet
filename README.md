# Web3Booklet
a web3 booklet for explain some web3 concept

### BlockChain

[1.以太坊中的Ghost协议](https://www.cnblogs.com/wanghui-garcia/p/9607356.html)

Ghost（Greedy Heaviest Observed Subtree），幽灵协议。

`GHOST`协议的目的就是怎么样才能激励（给予他们一些奖励）其他分叉的叔叔区块快速地与大矿池的主链合并，解决叔块白挖（矿工没有任何奖励）导致的不公平问题。

比如主链上的大区块将会使用奖励来招安叔块的矿口，与此同时，主链愿意招安也将会得到一定的奖励。这样就会双向激励双方都进行合并。
在以太坊中，7代内的叔块都能够接受招安并得到奖励，超过则不行，这样是为了避免有些矿工专门在之前的链上制造分叉后坐等被后面的节点招安情况。
