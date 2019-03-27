---
title: null
---

# NEO Monitor Reference

> *Read this in other languages: [简体中文](#neo-监控标准).*

Change Log: 

**NEO Blockchain**

 - Statistic
     - Add "Incentive to consensus node" for information  

The purpose of this reference is to standardize the monitoring of NEO blockchains, primarily for `mainnet` and `testnet`. We hope that the blockchain monitors that oversee the NEO platform can be implemented according to the corresponding references.
This paper is divided into two parts, the first part is the monitoring of NEO block information, and the second part is the monitoring of NEO node information. For those who want to develop programs that monitor NEO information, they can choose the functions they need to develop during the development process.

## NEO Blockchain

The NEO blockchain monitor is used for monitoring and displaying all NEO-related information and  some of the statistics  can display in the form of a chart.

#### Realtime

| Information                      | Description                              |
| -------------------------------- | ---------------------------------------- |
| Blockchain Height                | Height of the block chain                |
| Lastest Block Size               | The size of the last block               |
| Lastest Block Transactions Count | The transactions count of the last block |
| Lastest Block  Timestamp         | Time-stamp when the last block generated |
| Consensus List                   | List of all consensus nodes              |
| Candidate List                   | List of all candidate nodes              |

#### Statistic

| Information                | Description                              |
| -------------------------- | ---------------------------------------- |
| Block Detail               | All information for each block, including height, hash, timestamp, transaction number, block size, validator, invocation script, verification script |
| Assets                     | All assets on NEO, including asset name,asset id,total supply,total addresses, total transactions and registered address |
| Banlance Rank              | The rank of balance of NEO/GAS token, display top 100 public address, balance with descending order |
| Average Block Size         | Average block size per hour/day/month    |
| Average Block Time         | Average time for the block to reach consensus per hour/day/month |
| Transaction Count Per Time | Number of transactions per hour/day/month |
| Transaction History        | NEO transaction history                  |
| Created Addresses          | Number of created addresses per hour/day/month |
| Total Addresses Number     | Total number of created addresses        |
| Active addresses           | The number of addresses  that have been transferred out within three month |
| Claimed Gas                | Accumulated GAS value of all claim transactions |
| Incentive to consensus node| The reward to the speaker node per hour/day/month, it can be obtained from the miner transaction of each block, and its value is equal to the sum of all the network fee in the block |


## NEO Node

Seed or testnet nodes need to be monitored, and nodes which continue to run well will have the opportunity to become the consensus nodes of the mainnet.

For security reasons, the IP of the consensus node and other important information are kept secret. The holder of consensus node can also monitor its nodes to ensure the normal operation of NEO blockchain.

#### Realtime

| Information     | Description                              |
| :-------------- | :--------------------------------------- |
| Node-state      | Check if the node is available, usually there are three types of state. 1. online and the height is the latest height 2. online but the height is not the latest height 3.offline |
| Node-name       | Name of the node, also the address or the endpoint of the node |
| Block Height    | Lastest blockheight                      |
| Last Block Time | Last synchronization time of block data  |
| Lantency        | The lantency of getting infomation from node |
| Type            | Remote communication type: REST or RPC   |
| Version         | Version of NEO client                    |
| Peers Count     | The count of peers connected             |
| P2P-state       | P2P state: available or not, standard port: 10333 |
| WS-state        | WebSocket state: available or not, standard port: 10334 |
| RPC-state       | RPC state: enable or disable, standard port: 10331 for https, 10332 for http |
| Transaction     | Unconfirmed transactions count in the node memory |
| Wallet-state    | Get node wallet state: closed or not closed |
| mempool status  | show all transaction hashes in mempool of each node with order, especially for a better visualization |
| transaction status(optional) | when user search on the page with a given transaction hash, then it can show which node the transaction belongs to |



#### Statistic

| Information             | Description                              |
| ----------------------- | ---------------------------------------- |
| First Run Time          | The time the node was first monitored on the page, for example:  x days x hours ago |
| Online Time             | The cumulative time that the node is online normally, based on the time of the monitor first run (hours) |
| Latest Run Time         | The last time the node was monitored     |
| Average latency         | Average latency of the node              |
| Peers                   | Peers count of the node                  |
| Stability               | Percentage of the cumulative online time of the node |





# NEO 监控标准 

> *其他语言: [英文](#neo-monitor-reference).*

Change Log: 

**NEO Blockchain**

- 统计
  - 新增 "Incentive to consensus node" 统计信息 

NEO监控标准旨在对NEO区块链，主要是主网和测试网的监控进行标准化。我们希望根据该监控标准实现的区块链监控器可以监督NEO平台的运行。

文章分为两部分，第一部分是针对NEO区块信息进行监控，第二部分是针对区块节点信息进行监控。对于想要开发监控NEO信息的项目的团队，可以在开发过程中选择功能进行监控。

## NEO 区块链

NEO区块链监控针对所有NEO相关实时和统计信息进行监控，一些统计数据可以以表格的形式显示：

#### 实时

| 监控信息                             | 备注           |
| -------------------------------- | ------------ |
| Blockchain Height                | 区块链的高度       |
| Lastest Block Size               | 最后一个区块的大小    |
| Lastest Block Transactions Count | 最后一个区块的交易数量  |
| Lastest Block  Timestamp         | 最后一个区块生成的时间戳 |
| Consensus Node List              | 共识节点列表       |
| Candidate Node list              | 候选节点列表       |

#### 统计

| 监控信息                       | 备注                                       |
| -------------------------- | ---------------------------------------- |
| Block Detail               | 每个区块的具体信息，包含：高度，时间戳，事务个数，区块大小，验证程序，调用脚本，验证脚本 |
| Assets                     | NEO所有资产，包含：资产名，资产ID，供应商总数，地址总数，交易总数，注册地址   |
| Banlance Rank              | NEO/GAS token的余额排名，显示余额最多的前100个token，包含：钱包地址， 余额 |
| Average Block Size         | 每小时/每天/每月的平均区块大小                         |
| Average Block Time         | 每小时/每天/每月区块用于达成共识的平均时间                   |
| Transaction Count Per Time | 每小时/每天/每月的事务总数                           |
| Transaction History        | NEO历史事务                                  |
| Created Addresses          | 每小时/每天/每月创建的地址个数                         |
| Total Addresses Number     | 创建的地址总数                                  |
| Active addresses           | 在3月内有给其他地址转账的地址总数                        |
| Claimed Gas                | 所有声明事务的累积GAS值                            |
| Incentive to consensus node| 每小时/每天/每月议长节点打包区块所获得的奖励，可从每一个区块的miner transaction中获得，其值等于该区块所有交易network fee的总和 |



## NEO 节点

需要同时监控种子节点和测试网节点，能继续运行的节点有机会成为主网的共识节点。

处于安全性考虑，共识节点的IP以及其他信息不对外公开，共识节点的持有者可对其节点进行监控，以保证NEO区块链的正常运作。

#### Realtime

| Information     | Description                              |
| :-------------- | :--------------------------------------- |
| Node-state      | 检查节点的状态，1. 在线并且高度等于最新高度 2. 在线但是高度不等于最新高度 3.下线 |
| Node-name       | 节点名，即节点地址                                |
| Block Height    | 最新区块高度                                   |
| Last Block Time | 区块数据最新同步时间                               |
| Lantency        | 从节点获取信息的延时                               |
| Type            | 远程通信类型：REST or RPC                       |
| Version         | NEO客户端版本                                 |
| Peers           | 连接的Peers数量                               |
| P2P-state       | P2P 状态: available or not, standard port: 10333 |
| WS-state        | WebSocket 状态: available or not, standard port: 10334 |
| RPC-state       | RPC 状态: enable or disable, standard port: 10331 for https, 10332 for http |
| Transaction     | 节点内存中未确认的事务数                             |
| Wallet-state    | 获取节点钱包状态：closed/not closed               |

#### Statistic

| Information             | Description                              |
| ----------------------- | ---------------------------------------- |
| First Run Time          | 节点第一次被监控到的时间，例如：x days x hours ago       |
| Online Time             | 节点online的统计时间，以监控器第一次运行时间为准，例如：在线时长 x days x hours |
| Latest Run Time         | 节点最后一次被监控的时间                             |
| Average latency         | 节点的平均延时                                  |                              |
| Peers                   | 与节点连接的Peers数                             |
| Stability               | 节点在线时间的百分比                               |
