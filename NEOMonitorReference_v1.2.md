# NEO Monitor Standard

The purpose of this standard is to standardize the monitoring of NEO blockchains, primarily for `mainnet` and `testnet`. We hope that the blockchain monitors that oversee the NEO platform can be implemented according to the corresponding standards.
This paper is divided into two parts, the first part is the monitoring of NEO block information standard, and the second part is the monitoring of NEO node information. For those who want to develop programs that monitor NEO information, they can choose the functions they need to develop during the development process.



## NEO Blockchain

The NEO blockchain monitor is used to monitor and display all NEO-related information and  some of the statistics  can display in the form of a chart.

#### Realtime

| Information                      | Description                              |
| -------------------------------- | ---------------------------------------- |
| Blockchain Height                | Height of the block chain                |
| Lastest Block Size               | The size of the last block               |
| Lastest Block Transactions Count | The transactions count of the last block |
| Lastest Block  Timestamp         | Time-stamp when the last block generated |
| Consensus Node List              | Consensus node list                      |
| Candidate Node list              | Candidate nodes list                     |

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

If the follwing does not work well at the same time, the node should be manual inspection.

Seed or testnet nodes need to be monitored, and nodes which continue to run well will have the opportunity to become the consensus nodes of the mainnet.

For security reasons, the IP of the consensus node and other important information are kept secret. The holder of consensus node can also monitor its nodes to ensure the normal operation of NEO blockchain.

#### Realtime

| Information     | Description                                                  |
| :-------------- | :----------------------------------------------------------- |
| Node-state      | Check if the node is online and the height is the latest height |
| Node-name       | Name of the node                                             |
| Block Height    | Lastest blockheight                                          |
| Last Block Time | Last synchronization time of block data                      |
| Lantency        | The lantency of get the infomation from node                 |
| Type            | Remote communication type: REST or RPC                       |
| Version         | Version of Neo client                                        |
| Peers           | The count of Peers connected                                 |
| P2P-state       | P2p state: available or not, standard port: 10333            |
| WS-state        | WS state: available or not, standard port: 10334             |
| RPC-state       | RPC state: enable or disable, standard port: 10331 for https, 10332 for http |
| Transaction     | Transactions unconfirmed in the node memory                  |
| Wallet-state    | Get node wallet state to make sure the node wallet is closed |

#### Statistic

| Information             | Description                                           |
| ----------------------- | ----------------------------------------------------- |
| Initial Run Time        | The time the node was first monitored on the page     |
| Online Time             | The length of time that the node is online normally   |
| Average latency         | Average latency of the node                           |
| Transactions per second | Transactions count submitted every second in the past |
| Stability               | Calculate the time of the node online in percentage   |