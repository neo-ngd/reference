---
title: null
---

# How To Become NEO Consensus Node

> *version 1.3 \| [中文版](如何成为NEO共识节点v1.3.md)*

#### Table Of Contents
  * [0. Background](#0-background)
      * [Current Consensus Nodes](#current-consensus-nodes)
      * [Distribution and Governance](#distribution-and-governance)
      * [Incentives](#incentives)
  * [1. Overview](#1-overview)
  * [2. Requirements](#2-requirements)
  * [3. Partnering With NEO Foundation (Optional)](#3-partnering-with-neo-foundation-optional)
      * [3.1 Sending Application](#31-sending-application)
      * [3.2 Test-Running Consensus Node](#32-test-running-consensus-node)
      * [3.3 NEO Foundation's Selection Schedule](#33-neo-foundations-selection-schedule)
  * [4. Main-net Candidate & Voting](#4-main-net-candidate--voting)
    + [4.1 Registering As Candidate](#41-registering-as-candidate)
    + [4.2 Voting](#42-voting)
  * [5. Gather Votes & Support](#5-gather-votes--support)
  * [Appendix 1. Checking Candidates and Votes using API](#appendix-1-checking-candidates-and-votes-using-api)
  * [Appendix 2. Add Candidate Info to Consensus Node Page](#appendix-2-add-candidate-info-to-consensus-node-page)





## 0. Background

### Current Consensus Nodes

The NEO main-net currently has 7 consensus nodes. (see the consensus node monitoring [page](https://neo.org/consensus))

- NEO Foundation maintains 5 of the nodes
- CityOfZion maintains 1 node
- KPN maintains 1 node

The NEO test-net currently has 7 consensus nodes. 

- NEO Foundation maintains 2 of the nodes
- NEO Global Development maintains 1 node
- CityOfZion maintains 2 nodes
- KPN maintains 1node
- Swisscom maintains 1 node

### Distribution and Governance

NEO has two native tokens, NEO (abbreviated symbol NEO) and NeoGas (abbreviated symbol GAS).

NEO, with a total of 100 million tokens, represents the right to manage the network. Management rights include voting for bookkeeping, NEO network parameter changes, and so on. The minimum unit of NEO is 1 and tokens cannot be subdivided.

GAS is the fuel token for the realization of NEO network resource control, with a maximum total limit of 100 million. The NEO network charges for the operation and storage of tokens and smart contracts, thereby creating economic incentives for bookkeepers and preventing the abuse of resources. The minimum unit of GAS is 0.00000001. 

NEO's 100 million tokens is divided into two portions. The first portion is 50 million tokens distributed proportionally to supporters of NEO during the crowdfunding. This portion has been distributed.

*The second portion is 50 million NEO managed by the NEO Council to support NEO's long-term development, operation and maintenance and ecosystem.* The NEO in this portion has a lockout period of 1 year and is unlocked only after October 16, 2017. This portion will not enter the exchanges and is only for long-term support of NEO projects. The plans for it are as below:

🔹 10 million tokens (10% total) will be used to motivate NEO developers and members of the NEO Foundation

🔹 10 million tokens (10% total) will be used to motivate developers in the NEO ecosystem

🔹 15 million tokens (15% total) will be used to cross-invest in other block-chain projects, which are owned by the NEO Council and are used only for NEO projects

🔹 15 million (15% total) will be retained as contingency

🔹 The annual use of NEO in principle shall not exceed 15 million tokens

Below is a timeline of how NEO is to be unlocked. 

| Year | NEO Unlocked | Total NEO Unlocked |
| ---- | ------------ | ------------------ |
| 2016 | 50 Million   | 50 Million         |
| 2017 | 15 Million   | 65 Million         |
| 2018 | 15 Million   | 80 Million         |
| 2019 | 15 Million   | 95 Million         |
| 2020 | 5 Million    | 100 Million        |

<a name="on-chain-off-chain"> </a>

NEO is committed to building a decentralized network. But it is worth noting that due to the unlocking plan, NEO Foundation will have access to a considerable number of votes in the next few years. As a result, **the governance of NEO's network currently consists of two methods: chain governance and off-chain governance.**

#### On-Chain Governance

Chain governance relies on the mechanisms of the NEO blockchain itself. It is what NEO hopes to be the main source of governance in the future. 

NEO token holders are the network owners and managers, managing the network through voting in the network, using the GAS generated from NEO to utilize the functions in the network. NEO tokens can be transferred. 

#### Off-Chain Governance

Off-chain governance relies on the continued support from NEO Foundation. 

Aside from maintaining current consensus nodes, developing NEO's core projects and promoting NEO's ecosystem, NEO Foundation will vote for qualified partners who wish to run a consensus node. 

### Incentives

According to NEO's economic model, the maintainer of NEO consensus node will be rewarded with network fees. New economical model is being discussed.  
This section will be updated if the incentive mechanism changes. 

## 1. Overview

As NEO currently has two components to its governance, (as detailed <a href="#user-content-on-chain-off-chain">here</a> in the previous section) there are two ways of becoming a consensus node. 

**1) On-Chain governance Candidates**

If you wish to become a consensus node through the votes of NEO holders and maintain it independently, the steps are as follows: 

- [2. Requirements](#2-requirements)
- [4. Main-net Candidate & Voting](#4-main-net-candidate---voting)
- [5. Gathering Votes & Support](#5-gathering-votes--support)

**2) Off-chain governance Candidates**

If you want to establish a strategic partnership with the NEO Foundation (off-chain governance) and receive votes from the NEO Foundation(in addition to votes from NEO holders), the steps are as follows: 

- [2. Requirements](#2-requirements)
- [3. Partnering With NEO Foundation](#3-partnering-with-neo-foundation-optional)
- [4. Main-net Candidate & Voting](#4-main-net-candidate---voting)
- [5. Gathering Votes & Support](#5-gathering-votes--support)

## 2. Requirements

> **Applicable to both chain governance and off-chain governance candidates.**

All potential candidates are advised to provide some, or all of the information listed below. These information can be published on the [Consensus Node Page](#appendix-2-add-candidate-info-to-consensus-node-page) and the organization's official website. 

- Applicant/Organization Information

  - A public website and social media account
  - Organization name and location
  - A list of at least 2/3 of the team with pictures and relevant background qualifications on each
  - Contact methods (e.g: e-mail address, discord accounts)

- Server type and specifications

- The applicant's solutions to

  - Safety & security of the node
  - Maintenance
  - Long term stability
  - Failure tolerance/recovery backup
  - Maintenance personnel
  - Budget

- Plans for potential hardware scaling/upgrading

- NEO Community participation/contribution *(if applicable)*

**Advised Minimum Hardware Specifications:**

- 4 Core CPU
- 8 GB RAM
- 10M Bandwidth
- 100G Hard Drive

## 3. Partnering With NEO Foundation (Optional)

> **Applicable only to off-chain governance candidates. For chain governance candidates, skip to [3. Main-net Cadidate&Voting](#3-main-net-candidate---voting)**

### 3.1 Sending Application

Off-chain governance candidates can apply by sending organization information and maintenance proposals to: 

consensus@neo.org

The proposal should contain information listed in [1. Requirements](#1-requirements). 

Application results will be sent to the applicants through email. If the application were to be unsuccessful, a new proposal can be sent after reviewing and improving specifications and solutions. 

### 3.2 Test-Running Consensus Node

If the application is successful, the applicant will start by test-running a consensus node on the Test-net. A test-running period of 6 months is often required before running a consensus node in main-net. 

To become a consensus node on Test-net, you need to first register as candidate on the blockchain. 

#### 3.2.1 Registering as Candidate

> *The GUI operations of becoming a candidate and voting (Sections 3 and 4) are the same on both Test-net and Main-net. The difference is determined by which chain the GUI is synced to. To switch between test-net and main-net on GUI, see [this document](http://docs.neo.org/en-us/network/testnet.html).* 

You can use the NEO GUI to register as a candidate. Candidates will be voted by NEO token holders to determine how many nodes and which nodes will become the consensus node. 

1. In NEO-GUI, open a wallet. 

2. Select `Advanced` -> `Election` 

3. Select the public key of the account in the list and click `OK`. Note that 1000 GAS will be charged at this step.

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/candidate-EN.png" width="725">

4. If the message of a transaction ID is displayed, then the transaction is constructed successfully. You can check if the candidate has been successfully registered by accessing the API. (See [Appendix 1](#appendix-1-checking-candidates-and-votes-using-api))

#### 3.2.2 Maintaining the Consensus Node

Once the node has become a candidate, NEO Foundation will vote for the node so that it becomes a consensus node on test-net. 

If problem arises with the consensus node during this period, active communication and troubleshooting is expected. NGD will provide technical support if these situations arise. 

After 6 months of running the test-net, the applicant will be qualified to become a candidate for a consensus node on the main-net. 

### 3.3 NEO Foundation's Selection Schedule 

Starting from 30th Nov, 2018, NEO Foundation plans to select at least 1 consensus node from the applicant pool every 3 months. This means by 28th Feb, 2019, one or more consensus nodes will be chosen and will be running on the test-net. Candidates who have applied but have not been chosen as consensus nodes will automatically enter the candidate pool for the next 3-month cycle. 

Below is the selection schedule in 2019: 

- *30th Nov, 2018 - 28th Feb, 2019*
- *28th Feb 2019 - 31st May, 2019*
- *31st May, 2019 - 31st Aug, 2019*
- *31st Aug, 2019 - 30th Nov, 2019*


## 4. Main-net Candidate & Voting

> **Applicable to both chain governance and off-chain governance candidates.**

### 4.1 Registering as Candidate

Make sure your NEO GUI is connected to the main-net; Then register as a candidate by repeating the steps in [2.2.1](#221-registering-as-candidate)

### 4.2 Voting

#### 4.2.0 BACKGROUND: The Voting Mechanism\*

> *\*: NEO3.0 will make adjustments to the voting mechanism. This section will be updated accordingly when 3.0 launches.*

Each NEO node can vote for the candidates. The number of NEO in the current voting account will be automatically calculated as the number of the candidate's votes. When voting for multiple candidates, each candidate gets the votes equal to the NEO number of the current voting account. For example, if there are 100 NEO in the current account and three candidates are voted for from this account, each candidate receives 100 votes. If NEO in the account is spent after the vote, the candidates' votes will simultaneously be decreased to the current NEO balance.

After voting, the NEO network calculates in real time based on the number of candidates cast by each account and determines the consensus nodes. The calculation method is:

1. Sort the number of the candidates each account voted for by size, e.g. C1, C2, ..., Cn
2. Remove the first 25% and the last 25% of the data in the array
3. Calculate the weighted average of the remaining 50% data, which is then determined as the current NEO consensus node number N
4. The top N candidates with the highest number of votes become consensus nodes

#### 4.2.1 Voting with NEO GUI

> **Applicable to all candidates and all NEO holders**

Anyone holding NEO can vote using the GUI. Candidates are allowed to vote for their own nodes. 

1. In NEO-GUI, open the wallet account to vote. 

2. Right-click on the account -> `Vote`.

3. In the Candidates field, enter the public key of the candidate to vote. You can enter multiple public keys separated by Line feeds. Note that each line cannot contain spaces, as shown in the following figure:

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/votemulti-EN.png" width="725">
   *Example: giving three candidates each 100000000 votes.*

4. If the message of a transaction ID is displayed, then you have voted successfully. You can check the number of votes for each candidate by accessing the API. (See [Appendix 1](#appendix-1-checking-candidates-and-votes-using-api))

## 5. Gathering Votes & Support

> **Applicable to both chain governance and off-chain governance candidates.**

Once successfully becoming a candidate on the blockchain, off-chain governance candidates will receive votes from NEO Foundation. 

For chain governance candidates, gaining community understanding and support will increase the likelihood that NEO holders will vote. These are some of the advised actions: 

- Adding candidate information to the [Consensus Nodes](http://neo.org/consensus) page on the NEO website. [See Appendix 2 on how to do it.](#appendix-2-add-candidate-info-to-consensus-node-page)

- Make a page for running NEO consensus node on the organisation/candidate's own website.  

- Let the community know your candidacy through NEO's Reddit, Discord and other community platforms. 

*A candidate will become consensus node if enough votes are gathered.*

---


## Appendix 1. Checking Candidates and Votes using API

To check the number of votes on each candidate that has registered, you can use Postman or any other RPC program to access the API. (For instructions on how to, see [this document](Using RPC to Call NEO API.md))

As shown below, send a `getvalidators` request to the API. 

<img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/getvalidator2.png" width="725">

The node returns a json file containing public keys of candidates and the votes each one received. 

In the picture, the candidate with the public key `3076fc0ee6c6ccf3fb0c9b3ff9d0e3d9ba7ef97e54c77240991ec1dffa295503b` was given 100000000 votes. 

### Consensus Node Status

The **`active`** field in the returning json file indicates the status of the node. 

`false` means the node is a candidate node. 

`true` means the node is a consensus node. 

## Appendix 2. Add Candidate Info to Consensus Node Page

The [Consensus Nodes](http://neo.org/consensus) page can be used to track the status and number of votes for each candidate on the main-net. 

<img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSited1a-EN.png" width="755">

**To Add Candidate Info: **

1. Select <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSited2a-EN.png" width="200">, which opens the Candidate Info tab. 

2. Select the public key of your consensus node from the drop-down menu. Enter information about the candidate. 

3. Once the information is complete, select `Generate Hash`. Which will generate a hash string. 

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSited3a-EN.png" width="620">

4. Open NEO GUI, select `Advanced` -> `Sign Message...` (*Available only to v3.0 or above*)

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSite4-EN.png" width="725">

5. Select the address of your candidate in `Address`, paste the hash string into the `Input` field and select `Sign`. 
   Copy the output signature. 

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSite5-EN.png" width="725">

6. Return to the Candidate Info tab on the browser, paste the signature and select `Submit`. 

   <img src="https://raw.githubusercontent.com/taomo-eo/docs/master/Becoming_Consensus_Node/img/consensusSite6a-EN.png" width="620">

   If the green arrow to the right of your node on the page is green and expandable,  then your candidate info is successfully submitted! 
