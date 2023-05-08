# 🗯 Hybrid Consensus Algorithm

## What is consensus in a DAE context? <a href="#what-is-consensus-in-a-dag-context" id="what-is-consensus-in-a-dag-context"></a>

When the subject is cryptographic networks, consensus can be defined as being the task of getting a group of computers or [validators ](https://docs.phi.network/phi-wiki/glossary#v)to come to an agreement as for the current state of the network ledger or database. The steps used for these computers to reach to this agreement is called a consensus mechanism, or consensus protocol.

## PHI Network's Consensus Mechanism <a href="#nova-networks-consensus-mechanism" id="nova-networks-consensus-mechanism"></a>

​[PHI Network](https://phi.network) uses a novel consensus mechanism called Hybrid Consensus Algorithm, or HCA. It is based on the standard, well-known, and stress-tested Nakamoto Proof of Work concept, with the implementation of a modified Ethash algorithm for mining and sealing blocks.

## Hybrid Consensus Algorithm <a href="#hybrid-consensus-approach" id="hybrid-consensus-approach"></a>

The Hybrid Consensus Algorithm is a novel structuring standard for decentralized infrastructure, which invokes different elements of[ Proof of Work (PoW)](https://docs.phi.network/phi-wiki/glossary#p), [Proof of Authority (PoA)](https://docs.phi.network/phi-wiki/glossary#p), and[ Proof of Stake (PoS),](https://docs.phi.network/phi-wiki/glossary#p) to create a secure, democratic, reliable, and scalable network. The concept is relatively simple, and implies on controlled[ mining ](https://docs.phi.network/phi-wiki/glossary#m)and participation input. The Genesis Block Validates & Seals Transactions Users & Rewarded By Contribution of Assets.

### **Controlled Mining** <a href="#controlled-mining" id="controlled-mining"></a>

The controlled mining is important for three main reasons: energy efficiency, applicability of penalties for misbehaving, speed. _Energy Efficiency_&#x20;

An essential element and major drawback of standard PoW applications, controlled mining helps avoiding the usage of energy-intensive hardware, as well as makes it possible for the network to be secure and decentralized with just a fraction of the number of nodes and miners required on a standard PoW network. _Applicability of Penalties for Misbehaving_Controlled mining is a prime component of the HCA because it allows the creation and distribution of validator keys; the exchange of these keys for a consignment of a set amount of funds from the validator; and enables the community to penalize these validators if they misbehave, by burning – or slashing - these funds.&#x20;

This creates a huge financial disincentive to misbehave and addresses one of the most critical security concerns with standard PoW applications.&#x20;

After all, if a miner gathers enough hashpower to manipulate the network (eg. with a 51% attack) and decides to do so, there are no real consequences to their actions ([as we have seen in the past with Ethereum Classic, for example](https://decrypt.co/40196/hackers-launch-third-51-attack-on-ethereum-classic-this-month)), once no one can realistically break into their premises and seize their mining equipment. Also, these individuals are often anonymous, so any legal and/or criminal accountability is also very unlikely.&#x20;

With having validator keys that can be revoked at any time, and their funds consigned, it is much less likely for them to misbehave, as they will not only have a lot to lose financially, but the fact their identities are known and verified means that legal accountability is at stake, and if a validator misbehave they can be held personally responsible for their actions.&#x20;

_Speed_ Controlled hashpower also contributes to overall speed, as the rate in which the [difficulty](https://docs.phi.network/phi-wiki/glossary#d) of the network increases is substantially lower than on standard PoW applications and can be managed in such way that ensures longevity and long-term sustainability for the network.

### **The Structure** <a href="#the-structure" id="the-structure"></a>

To make HCA possible, three layers of nodes are required. The first one is the core layer – layer zero –, that hosts all the network’s history and ensures security and functioning of the chain, even if all the validators fail at once. The core layer connects to an upper layer of bridging nodes that are used to generate the validator keys – layer one – and by the validators on the execution layer – layer two – to connect and sync with the network.![](https://novanetwork.io/wp-content/uploads/2022/04/Picture1-1024x299.png)

_Core Layer or Layer Zero_It’s the core layer of nodes, and it can have as many nodes as the blockchain constructor wants it to have. It stores a full record of the network’s history and is used as the main layer of security of the network too. It can have one or more nodes with mining enabled, to ensure that even if all validators’ nodes fail, the chain will remain operational.&#x20;

It needs to have restricted connection parameters to ensure that only nodes from the layer one are allowed to connect and sync. Otherwise, there will not be possible to ensure and achieve controlled mining. Today, even the most basic iterations of Ethereum will offer ways and mechanisms for users to control peer connection requests. _Bridging Layer or Layer One_&#x20;

These will be the midpoint between the core of the network and the validator nodes, and can only allow two connections per node, one to a layer zero node, and one to a layer two node. Once this is accomplished, the _enode_ address can be used as the _validator key_, and distributed to a layer two validator, which will use it to connect and sync.&#x20;

This layer of nodes can also be used by PHI Network. to revoke validator keys by resetting individual nodes, or to mitigate any potential threats or attacks by shutting down nodes altogether, which would then break the link between a particular validator from which a potential attack is originating, and the main network._Execution Layer or Layer Two_

This layer of nodes represent the validators themselves.&#x20;

They will be granted the _right to mine_ using their _validator keys_ upon consignment of a previously set amount of funds.&#x20;

PHI Network. can set the mining parameters to ensure fair distribution of rewards, and can use penalties mechanisms to penalize validators that do not work in tandem with these parameters.

## The Subnet Layer <a href="#the-subnet-layer" id="the-subnet-layer"></a>

In addition to the three layers required by HCA, we have added an extra subnet layer, that effectively acts as an endpoint for scaling infrastructure, including purpose-built public subnet ledgers and private or public third-party blockchains or[ DAGs.](https://docs.phi.network/phi-wiki/glossary#d)
