# NEO Monitor Standard

This initiative is to set a protocol to adhere to for future blockchain monitors that wish to oversee the NEO platform. The functionality should be present to ensure the utlity and transparency of the network's health. The Standard applies to both the `mainnet` and the `testnet`. Consensus nodes, in particular, are extremely important and thus their IP and other important information are confidential; no interface should expose it.
### NEO Chain Monitor
>NEO Chain Monitoring is the overview of functionality that displays **blockchain** details 

| Information                          |  Data Type |                                      Description |
|--------------------------------------|:----------:|-------------------------------------------------:|
| Block height                         |  Realtime  |                        Height of the block chain |
| Last Block size                      |  Realtime  |                       The size of the last block |
| Last block Transactions count        |  Realtime  |         The transactions count of the last block |
| Last block time                      |  Realtime  |         Time-stamp when the last block generated |
| Consensus node                       |  Realtime  |                             Consensus nodes list |
| Candidate node                       |  Realtime  |                             Candidate nodes list |
| Average block time                   | Statistics | How long it takes to generate a block on average |
| Average transaction count per block  | Statistics |         Average transactions count of the blocks |
| Average transaction count per second | Statistics |  Transactions confirmed every second in the past |

### NEO Node Monitor
>NEO Chain Monitoring is the overview of functionality that displays **node** details 

| Information             |  Data Type |                                                                        Description |
|-------------------------|:----------:|-----------------------------------------------------------------------------------:|
| Node-name               | Realtime   |                                                                   Name of the node |
| Node-type               | Realtime   |                                             Remote communication type: REST or RPC |
| Node-version            | Realtime   |                                                              Version of Neo client |
| Last block              |  Realtime  | block height, the hash value of the last block and transactions count in the block |
| Last block time         |  Realtime  |                                            Last synchronization time of block data |
| Node-latency            | Statistics |                                         Round trip time to the node. request delay |
| Peers                   |  Realtime  |                                                       The count of Peers connected |
| P2P-state               |  Realtime  |                                  P2p state: available or not, standard port: 10333 |
| WS-state                |  Realtime  |                                   WS state: available or not, standard port: 10334 |
| RPC-state               |  Realtime  |       RPC state: enable or disable, standard port: 10331 for https, 10332 for http |
| Transaction             |  Realtime  |                                        Transactions unconfirmed in the node memory |
| Transactions per second | Statistics |                               Transactions count submitted every second in the past |
| Stability                | Statistics |                                                    How long the node works, Uptime |
| Wallet-state          |  Realtime  |                                                             If a wallet is open or closed |

### NEO Character Monitor
>NEO Chain Monitoring is the overview of functionality that displays **voting** details 

<table>
<thead>
<tr>
   <th>Information</th>
    <th>Data Type</th>
    <th>Description</th>
  </tr>
</thead>
    
  <tr>
   <td>PK</td>
    <td>Realtime</td>
    <td>Public key</td>
  </tr>
  <tr>
   <td>Character</td>
    <td>Realtime</td>
    <td>Consensus node or candidate</td>
  </tr>
  <tr>
     <th colspan="3">Candidate</th>
  </tr>
  <tr>
   <td>Votes</td>
    <td>Realtime</td>
    <td>Votes the node gets</td>
  </tr>
  <tr>
     <th colspan="3">Consensus</th>
  </tr>
  <tr>
   <td>State</td>
    <td>Realtime</td>
    <td>Node state during consensus process:  prepareRequest, prepareResponse, changeview</td>
  </tr>
</table>
