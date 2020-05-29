## 度中心性
* 中心度用来量化一个顶点在图中的重要性。

### 1. 点度中心性(Degree Centrality)

#### 1.1 概念

* 用户刻画节点中心性的最直接指标，节点度越大表示该节点中中心性越高，在网络中更重要。

#### 1.2 公式

* 无向图

$C_D(N_i)=\sum_{J=1}^{g}x_{xj}(i \neq j)$

其中，$ C_D(N_i)$ 表示节点i的度中心度， $\sum_{J=1}^{g}x_{ij}(i \neq j)$ 计算每个节点i与其它g-1个j节点之间的直接联系数量。

标准化后的测量公式，



#### 接近中心性

#### 中介中心性

#### 特征向量中心性

### 参考
* [量化一个节点在网络中的重要性：中心度(centrality)](http://sparkandshine.net/quantifying-the-importance-of-a-node-in-the-network-centrality-centrality/)
* [百度百科 - 度中心性](https://baike.baidu.com/item/%E5%BA%A6%E4%B8%AD%E5%BF%83%E6%80%A7)

