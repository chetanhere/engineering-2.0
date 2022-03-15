# <h1 align="center">Hyperledger Fabric Blockchain Boot Camp</h1>
designed by Bhaskar Bareth
# Contents
- [Summary](#summary)
- [Content Policy](#content-policy)
- [Curriculum](#curriculum)
- [Certification](#certifications)
## Summary
Hyperledger Fabric platform is an open source Blockchain framework hosted by The Linux Foundation which now comes under Hyperledger umbrella. It is based on Distributed Ledger Technology platform. Permissioned Fabric networks are permissioned, meaning all participating member's identities are known and authenticated.

Fabric acts as a foundation for developing Blockchain-based products, solutions, and applications using plug-and-play components that are aimed for use within private enterprises.

Current curriculum you are seeing is five days BootCamp. This curriculum is helpful for the students who want to aim for Blockchain Developer and want to get entry in Product Based Companies. Please keep revisiting the link, we shall also update the change log for any changes/modifications in the curriculum content.

## Prerequisites:
- Willingness to learn and to go extra mile (this course need dedicated 4 hours a day for 5 days).
- Practical programming is required. Should have one basic configuration laptop/PC or should have access on Laboratory/Library computers.
- Basic level knowledge of Programming Concepts and programming experience of at least one programming language (Java, Golang, Nodejs).
- Linux system understanding, if local desktop doesn’t support HLF setup. (Virtualbox can be preferred)
- Basic understanding of Linux commands.
- AWS EC2 understanding is optional.

This curriculum is a collection of YouTube Videos, Medium Articles, 101Blockchain Articles, Code Practices and Official documentation. Please follow it as per your ease. Students takes months for being comfortable with the environment. There is no such rule on time, please follow your own speed.

Taking extra time is no problem!

**Organization**: The curriculum is designed as follows:
- _Blockchain Basics_: Student will learn about basics of Blockchain Technology and understand about Distributed Ledger Technology. It will be helpful in getting real implementations knowledge.
- _Fabric Overview_: In this section Student will get to learn about the Fabric basics and Prerequisites of Fabric, Architecture and some dependencies.
- _Fabric Network Setup_: In this section Student will learn in depth about Fabric Orderer, Peer etc. 
- _Chaincode Lifecycle_: This section will give depth knowledge of 4 step chaincode lifecycle which includes package, install, approve and commit.
- _REST APIs_: This section gives introduction to Fabric SDK and connection of Fabric to chaincode. 
Duration: It is possible to complete basic level of understanding in 5 days.

## Cost:
Nearly all content is free of cost, still you may need to purchase few courses if you want to understand more Blockchain in depth. Don't worry for Certificates, I have attached some free certifications with the Boot Camp, which can be shared in professional profile and LinkedIn.

## Process:
- We recommend to follow curriculum step by step.
- Complete the mentioned exercise post every day lecture.
- Build small POC projects/GitHub repository and share them with your friends/world.
- If you have some good resources, then please comment them and we shall consider to add them too.
- Keep practicing shell scripts.

## Content Policy:
Don't share the solution files publicly until mentioned specifically. Help fellow learners but don't help in copying. Copying will break this good system, we need your support in keeping it clean.
Community
- Join us on Discord Chat with fellow developers.
- Join us on Telegram channel to follow announcements.
- Subscribe email list and get updates on your email.
- Be respectful while asking your doubts and share maximum information about what challenge you are facing.
- Add EduPass to your LinkedIn profile School section, it will help you in finding fellow learners.
## Curriculum
Curriculum version: 0.1 (see [CHANGELOG](CHANGELOG.md))

- [Blockchain Basics](#blockchain-basics)
  - What is Blockchain
  - What is DLT
  - Blockchain types 
  - Smart Contracts
  - Use-Cases
- [Fabric Getting Started](#fabric-introduction)
  - Introduction
  - Fabric Key Concepts
  - Architecture
  - Test Network
- [Fabric Network Overview](#network-overview)
  - Network Configuration
  - Genesis Block Creation
  - Channel Creation
- [Chaincode Lifecycle](#chaincode-lifecycle)
  - Assets
  - Chaincode Package and Install
  - Chaincode Approve and Commit
  - Query and Invoke
- [REST APIs](#rest-apis)
  - Fabric SDK
  - Connection
  - Wallet and Gateway
  - Complex Network Setup

________________________________________
## Blockchain Basics
**Getting Started with Blockchain (~ 4 Hours)**

This course is assuming that you are absolute beginner. Please feel free to comment your doubts.
This section is designed for students to start their journey with Blockchain from basics. It is a Boot Camp but it contains all topics related to Blockchain, go with your own pace as it needs time to get friendlier.

Topics | Duration |
:-- | :--: |
[What is Blockchain](https://www.youtube.com/watch?v=3xGLc-zz9cA&t=275s)|45 minutes
[What is DLT](https://youtu.be/JKYE5ti8-p0?t=10)|45 minutes
[Blockchain Types](https://101blockchains.com/wp-content/uploads/2020/05/Permissioned-vs-Permissionless-Blockchain.png)|30 minutes
[Smart Contracts](https://www.ibm.com/topics/smart-contracts#:~:text=Next%20Steps-,Smart%20contracts%20defined,-Smart%20contracts%20are)	| 60 minutes
[Use-Cases](https://101blockchains.com/enterprise-blockchain-use-cases/)	|60 minutes

For getting more clarity and sum-up all above topics click [here](https://www.youtube.com/watch?v=SSo_EIwHSd4&t=194s).
## Fabric Introduction
**Getting Started with Fabric Network (~ 5 Hours)**

This section gives introduction to Hyperledger Fabric Blockchain. Please go through each topic sequentially. It is always better to go through original [documentation](https://hyperledger-fabric.readthedocs.io/en/release-2.2/getting_started.html) if you want to.


Topics | Duration |
:-- | :--: |
[Introduction](https://medium.com/coinmonks/hyperledger-fabric-2-2-tutorial-eb21618d5fa)| 60 minutes
[Key Concepts](https://hyperledger-fabric.readthedocs.io/en/release-2.2/key_concepts.html#)|30 minutes
[Prerequisites](https://hyperledger-fabric.readthedocs.io/en/release-2.2/prereqs.html#)| 30 minutes
[Fabric Binaries](https://hyperledger-fabric.readthedocs.io/en/release-2.2/command_ref.html)	|30 minutes
[HLF Architecture](https://hyperledger-fabric.readthedocs.io/en/release-2.2/network/network.html#)|	30 minutes
[Test Network](https://hyperledger-fabric.readthedocs.io/en/release-2.2/test_network.html#)|	120 minutes

There is a course from Udemy for Hyperledger Fabric network setup and design. Please click [here](https://www.udemy.com/course/hyperledger-fabric-network-design-setup/) to avail the course.

There is a free tutorial in Youtube. Please click [here](https://www.youtube.com/watch?v=SJTdJt6N6Ow&list=PLSBNVhWU6KjW4qo1RlmR7cvvV8XIILub6) to avail the course.
All courses above mentioned are stick to **Fabric 2.x**. 
## Network Overview
**Fabric Network Depth (~ 3 Hours)**

This section gives in depth knowledge of configuration files i.e. **.yaml** files. It contains all commands for generating binaries and creating Genesis Block.
Topics | Duration |
:-- | :--: |
[crypto-config.yaml](https://medium.com/@msakhilvinayak/understanding-configurations-in-hyperledger-fabric-ff3f5c23625a)	| 30 minutes
[Configtx.yaml](https://medium.com/@msakhilvinayak/understanding-configurations-in-hyperledger-fabric-ff3f5c23625a)|30 minutes
[docker-compose.yaml](https://docs.divio.com/en/latest/reference/docker-docker-compose/)	| 30 minutes
[Generating Tx files](https://hyperledger-fabric.readthedocs.io/en/release-2.2/test_network.html#creating-a-channel) |90 minutes


## Chaincode Lifecycle
**Chaincode understanding in depth (~ 4 Hours)**

This section gives in depth knowledge of chaincode configuration, install, package, approve and commit.
This section also covers how to write chaincode in Golang, but it is not part of boot camp as it requires practice to deal with it.

Students who want to explore more about chaincode please go through this [Udemy course](https://www.udemy.com/course/golang-chaincode-development/) totally designed for chaincode development in Golang and gives full access to Fabric Node SDK.

You can go though writing your first [Chaincode](https://hyperledger-fabric.readthedocs.io/en/release-2.2/chaincode4ade.html#)
Topics | Duration |
:-- | :--: |
[Assets]([https://hyperledger-fabric.readthedocs.io/en/release-2.2/secured_asset_transfer/secured_private_asset_transfer_tutorial.html?highlight=asset#:~:text=Edit%20on%20GitHub-,Secured,transfer%20in%20Fabric,-This%20tutorial%20will])	| 30 minutes
[Package, Install, Approve, Commit](https://hyperledger-fabric.readthedocs.io/en/release-2.2/commands/peerlifecycle.html?highlight=chaincode%20life)	|90 minutes
[Query and Invoke](https://hyperledger-fabric.readthedocs.io/en/release-2.2/chaincode4ade.html#)	|60 minutes
[Chaincode Upgrade](https://hyperledger-fabric.readthedocs.io/en/release-2.2/enable_cc_lifecycle.html#)	| 60 minutes

## REST APIs
**Getting started with Fabric SDK (~ 4 Hours)**

This section gives in depth knowledge of connection to fabric network via REST APIs.
Topics | Duration |
:-- | :--: |
[Fabric SDK](https://hyperledger.github.io/fabric-sdk-node/release-2.2/module-fabric-network.html)	| 60 minutes
[Wallet](https://hyperledger-fabric.readthedocs.io/en/release-2.2/developapps/wallet.html#) |45 minutes
[Gateway](https://hyperledger-fabric.readthedocs.io/en/release-2.2/developapps/wallet.html#)	|45 minutes
[Complex network setup](https://kctheservant.medium.com/multi-host-setup-with-raft-based-ordering-service-29730788b171)	| 90 minutes



## Certifications
This section is having links to various free certifications:
- [IBM Blockchain Essentials](https://cognitiveclass.ai/courses/blockchain-course)
- [IBM Blockchain Foundation Developer](https://cognitiveclass.ai/courses/ibm-blockchain-foundation-dev)
- [101 Enterprise Blockchain Essentials](https://101blockchains.com/free-blockchain-course/)
