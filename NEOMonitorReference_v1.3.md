# NEO Monitor Standard

> *Read this in other languages: [简体中文](NEO-监控标准.md).

Change Log: 

**NEO Node**

 - Statistic
     - Add "Latest Run Time for statistic" for information 
     - Add "Transactions per block" for information
     - Add "Peers" for information
 - Realtime 
     - Modify description for Node-state.  

The purpose of this standard is to standardize the monitoring of NEO blockchains, primarily for `mainnet` and `testnet`. We hope that the blockchain monitors that oversee the NEO platform can be implemented according to the corresponding standards.
This paper is divided into two parts, the first part is the monitoring of NEO block information standard, and the second part is the monitoring of NEO node information. For those who want to develop programs that monitor NEO information, they can choose the functions they need to develop during the development process.

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

| Information                | Description                                                  |
| -------------------------- | ------------------------------------------------------------ |
| Block Detail               | All information for each block, including height, hash, timestamp, transaction number, block size, validator, invocation script, verification script |
| Assets                     | All assets on NEO, including asset name,asset id,supply number,addresses number, transaction number and registered address |
| Banlance Rank              | The rank of address about remaining token                    |
| Average Block Size         | Average block size per hour/day/month                        |
| Average Block Time         | Average time for the block to reach consensus per hour/day/month |
| Transaction Count Per Time | Number of transactions per hour/day/month                    |
| Transaction History        | NEO transaction history                                      |
| Created Addresses          | Number of created addresses per hour/day/month               |
| Total Addresses Number     | Total number of created addresses                            |
| Active addresses           | The number of addresses  that have been transferred out within three month |
| Claimed Gas                | Accumulated GAS value of all claim transactions              |



## NEO Node

If the following does not work well at the same time, the node should be under manually inspection.

Seed or testnet nodes need to be monitored, and nodes which continue to run well will have the opportunity to become the consensus nodes of the mainnet.

For security reasons, the IP of the consensus nodes and other important information are kept secret. The holder of consensus node can also monitor its nodes to ensure the normal operation of NEO blockchain.

#### Realtime

| Information     | Description                                                  |
| :-------------- | :----------------------------------------------------------- |
| Node-state      | Check if the node is available, usually there are three types of state. 1. online and the height is the latest height 2. online but the height is not the latest height 3.offline |
| Node-name       | Name of the node, also the address or the endpoint of the node |
| Block Height    | Lastest blockheight                                          |
| Last Block Time | Last synchronization time of block data                      |
| Lantency        | The lantency of getting infomation from node                 |
| Type            | Remote communication type: REST or RPC                       |
| Version         | Version of NEO client                                        |
| Peers Count     | The count of peers connected                                 |
| P2P-state       | P2P state: available or not, standard port: 10333            |
| WS-state        | WebSocket state: available or not, standard port: 10334      |
| RPC-state       | RPC state: enable or disable, standard port: 10331 for https, 10332 for http |
| Transaction     | Unconfirmed transactions count in the node memory            |
| Wallet-state    | Get node wallet state to make sure the node wallet is closed |



#### Statistic

| Information             | Description                                                  |
| ----------------------- | ------------------------------------------------------------ |
| First Run Time          | The time the node was first monitored on the page, for example:  x days x hours ago |
| Online Time             | The cumulative time that the node is online normally, based on the time of the monitor first run (hours) |
| Latest Run Time         | The last time the node was monitored                         |
| Average latency         | Average latency of the node                                  |
| Transactions per block  | Transactions count submitted every block in the past         |
| Transactions per second | Transactions count submitted every second in the past        |
| Peers                   | Peers count of the node                                      |
| Stability               | Percentage of the cumulative online time of the node         |