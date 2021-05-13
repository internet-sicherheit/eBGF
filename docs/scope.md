# Scope of the eBGF

## Abstract

The eBGF will provide a blockchain network and community governance framework that will focus on **consortial blockchains**.

## Motivation

There are different types of blockchain networks. 

|             	|       **permissioned**      	| **permissionless** 	|
|:-----------:	|:---------------------------:	|:------------------:	|
|  **public** 	| *EnergyWeb, bloxberg, Sovrin*	|  *Bitcoin, Ethereum* 	|
| **private** 	|      *Hyperledger Fabric*    	|         *n/a*        	|


Usually, the following permission types are distinguished: 

1) Private-permissioned  
2) Public-permissioned  
3) Public-permissionless

*Public-permissioned blockchains* are networks on which: 

+  some or all data on the network is public   
+  some or all functions of the network are permissioned   
+  some or all functions accessible

### Examples of what can be public
- Transaction data
- Public keys and blockchain addresses

### Examples of what can be permissionless
- Setting up a full node to access the network and read transaction (not participating in the consensus) 
- Witness functions (which can strengthen the network)
- Indexing and publication of transactions and data for discoverability in order to allow the public to read and analyse the network (node interface)

### Examples of what can be permissioned
- Validation of transactions / participating in the consensus mechanism
- Deploying smart contracts to use for business application (only specific addresses may deploy them)
- Opening namespaces or streams 
    
## Elaboration

**Consortial blockchains** can be defined as:

+ public-permissioned blockchain networks  
+ consortial blockchains provide a transparent network and community governance    
+ are institutionalised by a set of entities – which can be companies, organizations or governments 
+ that participate in various roles with different attributes and rights in the network 
+ consortial blockchains are dedicated to a specific purpose in order to achieve a common goal

### Advantages of consortial blockchains

The advantages of consortial blockchains are: 

**Scalability** – The throughput of transactions can be much higher than with public-permissionless blockchains.

**Sustainability** – While currently, Bitcoin, Ethereum and other public-permissionless blockchains rely on energy-consuming proof-of-work (PoW) consensus algorithms, consortial blockchains can afford to use alternative, less-secure, “green” validation algorithms, such as proof-of-authority (PoA) to reach consensus among nodes that are identifiably and known to the members. 

**Transaction costs** – Using a blockchain that is in control of the consortium allows to regulate or entirely avoid potentially high transaction costs.

**Regulatory compliance** – Being able to define a membership governance according to the regulatory requirements of a specific industry sector, allows to be regulatorily compliant and be aware of potential legal liabilities. Furthermore, a stronger control can help to limit or avoid illegal activities on the network.

**Flexibility** – As the members are in control of the nodes, network development and updates can be done much faster (given that there is a certain investment in development of the underlying open-source technologies)  and more flexible with a focus on the need of the individual industry sector.

### Requirement for a network governance

A consortial blockchain network strikes a compromise between the highly decentralized public-permissionless blockchain networks such as Bitcoin or Ethereum – which pay their trustless operation model with high energy usage – and classic IT systems, which often aren’t engineered to be run by a set of different organisations. 

However, since blockchain is a relatively new and highly complicated technology, sometimes the trick lies in the detail. It might not be easy for all industries to get acquainted with the idea of setting up and maintaining a permissioned blockchain. While it's true, that in theory the network can be adapted to the needs of the consortium, in practice it requires a comparably high investment into the underlying technology, both in order to understand capabilities and limitations, but also to perform actual changes to the code base or updates in order to be compatible in the future. Furthermore, running a consortial blockchain requires a committment to actively participate in the governing and developing communities of the consortium. 

## References to best practice, examples  

 Bloxberg. ‘Bloxberg – Blockchain Infrastructure for Scientific Research’. Accessed 13 May 2021. [https://bloxberg.org/](https://bloxberg.org/).

Energy Web. ‘Energy Web’. Accessed 13 May 2021. [https://www.energyweb.org/](https://www.energyweb.org/).

Sovrin. ‘Sovrin’. Accessed 13 May 2021. [https://sovrin.org/](https://sovrin.org/).
	
## Bibliography of selected references

101 Blockchains. ‘Introduction to Permissioned Blockchains’, 2 June 2019. [https://101blockchains.com/permissioned-blockchain/](https://101blockchains.com/permissioned-blockchain/).


________

Contributing authors: **Sebastian Posth**  
Status of this document: **work in progress**    
Last day modified: **2021-05-13**