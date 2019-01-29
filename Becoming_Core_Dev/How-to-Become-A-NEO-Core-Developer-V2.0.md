---

---

# How to Become A NEO Core Developer

> *Ver. 2.0* \| [中文版](如何成为核心开发者V2.0.md)

#### Table of Contents

- [What & Why](#what-why)
- [Evaluation](#evaluation)
- [Privileges](#privileges)
- [Responsibilities](#responsibilities)
- [Incentivization](#incentivization)
- [Core Developer List](#core-developer-list)

------

## What & Why

### Definition of a Core Developer

NEO operates as an open-source project. Developers who are interested in contributing to core NEO projects are welcome and encouraged. Anyone can make contributions, ranging from GitHub issues, documentations to providing new features and patches. 

Community developers who have made outstanding contributions to the NEO core code, after being evaluated by the NEO Foundation, are given the chance to become a 'Core Developer'. Core Developers have the authority to manage the core code base, and therefore, have more obligations to participate in core project contributions. 

### Why We Need More Core Developers

1. As the NEO community grows, so does the need for the development of low-level infrastructure. The intention with awarding Core Developer roles is to deepen the engagement with developers who are currently making outstanding contributions to the NEO community, and motivating them to focus more on the low-level development of NEO. 
2. NEO's code base is constantly improving, and therefore needs more maintainers. During the earlier stages of NEO development, Erik Zhang was the sole maintainer of the core project. But as NEO accelerates its decentralization, more power to the community in terms of the core code will benefit the overall development. 

*Note that community contributors who become 'core developers' are not employees of NEO. The goal is to encourage and cultivate the interest in learning about and contributing to the fundamental levels of NEO's development.*

## Evaluation

### Projects to Contribute

You can become a core developer by contributing to one or more of the following core projects on GitHub. To contribute, please fork, fix, commit and send a Pull Request for the maintainers to review and merge into the main code base. Before sending a Pull Request, please consult the [**Contribution Guideline**](https://github.com/neo-project/neo#how-to-contribute) found on the NEO core project. 

- NEO's core project, VM, compilers, nodes and development packs. 
  - [neo](https://github.com/neo-project/neo)
  - [neo-vm](https://github.com/neo-project/neo-vm)
  - [neo-compiler](https://github.com/neo-project/neo-compiler)
  - [neo-cli](https://github.com/neo-project/neo-cli)
  - [neo-gui](https://github.com/neo-project/neo-gui)
  - [neo-devpack-dotnet](https://github.com/neo-project/neo-devpack-dotnet)

Contributor who make significant submissions to these repositories can become a core developer. See the next section for details on how contributions are evaluated. 

### Evaluation System

The *Neo Core Developers* tool by Erik Zhang is written for the NEO Foundation to track contributions and evaluate contributors. Its source is available on [GitHub](https://github.com/erikzhang/NeoCoreDevelopers). 

Each commit to one of the aforementioned repositories is evaluated and given a score of 'work' and 'importance' by NEO Foundation. 'Work' is a measure of the amount of changes or additions that the given commit contains. Therefore, longer commits tend to have a higher 'work' score. 'Importance' measures how valuable the change is to the project or NEO at large. The tool then assigns a score to each commit and contributor based on the two valued provided by NEO Foundation. 

For each commit, the score is calculated as: 

> ***Commit Score = Work * Importance***

For each contributor, their score is calculated as: 

> ***Contributor Score = Scores of Authored Commits + 10% * (Scores of Assisted Commits + Scores of Reviewed Commits)***

*Contributor Score* is therefore an indication of one's contribution to NEO core projects. 

## Privileges

As you become a core developer, you gain access to a few things that you should note: 

#### Commit Privileges

You will be added on the corresponding GitHub repository as a `collaborator` or higher. This means that you are granted `commit` privileges to the repositories of the project. You will also be able to approve or reject all Pull Requests to this repository. 

#### Monitoring Merges

Core developers are able to approve or reject changes to the repository, they are also able to request that even already merged changes be escalated to NEO developers for further discussion, and potentially even be reverted prior to release.

#### Issue Tracker

You would be able to manage the `issues` tab on the GitHub repository, including opening and closing issues, and assigning issues to different categories and closing them. 

## Responsibilities

As core developers of the NEO core project, there is a shared responsibility to collaborate constructively with other core developers and contributors. That includes the following: 

- You should maintain [effective communication](https://opensource.guide/how-to-contribute/#communicating-effectively) and be prompt in responding to questions, including processing issues on GitHub. 
- As you first become a core developer, you should inform the core developers responsible for the same repository as to what areas you are inclined to contribute. This allows the relevant topics and issues to be redirected to you. 
- You are responsible for handling the consequences of accepting/committing a change into the code base. This mostly includes reverting or fixing the commit if it causes any problems for the project. 


- You are responsible for for tracking the `issues` tab of the project you are contributing to. The core developer should reply to issues assigned to them, and decide when issues listed or changes proposed should be escalated for discussion with NEO developers. 

The scope of some of the responsibilities above may vary according to the area you may choose to contribute. 

## Incentivization

A core developer is added to the [Contributors Page](https://neo.org/team) on the NEO website. They will also be given quarterly monetary rewards. The reward is directly proportional to a contributor's score as evaluated in the [*NeoCoreDevelopers*](#evaluation-system) tool. Reward is calculated as follows: 

> ***Reward = Contributor Score * Dollars Per Point***

Currently *Dollars Per Point* is set by NEO Foundation at $200. 

## Core Developer List

A list of core developers will be compiled at the end of each year. The [Contributors Page](https://neo.org/team) on GitHub will also be updated accordingly.  Contributors who qualify as core developers in the previous year may become core developers again through the same criteria. 

This section is dedicated to listing core developer lists as they are published each year. 



------

#### *References:*

1. *[How To Contribute to Open Source](https://opensource.guide/how-to-contribute/)*
2. *[neo-project contributors page](https://github.com/neo-project/neo/graphs/contributors)*
3. [erikzhang/NeoCoreDevelopers](https://github.com/erikzhang/NeoCoreDevelopers)

