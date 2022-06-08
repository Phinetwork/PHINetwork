# 💨 Transaction Fees

Transaction Fees To protect the network from spam and [DDoS attacks](https://docs.phi.network/phi-wiki/glossary#d), transacting on PHI Smart Chain requires the payment of a [transaction fee](https://docs.phi.network/phi-wiki/glossary#t). This fee is paid in PHI, and can be broken down in two elements, as explained below.

#### The Base Fee <a href="#the-base-fee" id="the-base-fee"></a>

Transactions have an average fee of PHI 0.000000000000010007, Which In $USD Terms Is $0.00000001120784 Per Transaction and the network uses an algorithm to determine the base fee for each specific transaction based on the expected computing power required to process it. Factors that can directly influence the cost of a transaction - amongst others - are:

* If the transaction interacts, or not, with a smart contract;
* If there are too many other transactions being submitted at the same time;
* The type of asset you are transferring - [PHI20](../../glossary.md#p), [PHI721](../../glossary.md#p), etc;
* Built-in fees from the protocol or application you are using to submit the transaction;

The base fee has no upper bound and is always burned - or destroyed. So every time a user transacts on [PHI Smart Chain](broken-reference) the supply of PHI is reduced by a certain amount.

#### The Priority Fee <a href="#the-priority-fee" id="the-priority-fee"></a>

On top of the base fee, users are able to set a 'tip' for validators to have their transaction processed faster. This is called a 'Priority Fee' and is usually calculated automatically by most modern wallet providers, which will advise you on the optimal fee to set, given the current network state. With very few exceptions, the higher the priority fee, the faster a transaction will be processed. This fee is paid directly to the validators.

#### Other Fees <a href="#other-fees" id="other-fees"></a>

While using[ PHI Smart Chain,](broken-reference) users may also face other fees coming from the interaction with smart contracts, protocols, and platforms. While using any application deployed on PHI Smart Chain, users need to make sure they understand the fee structure of the given application before start transacting on or with it.

### Fees on Private Networks <a href="#fees-on-private-networks" id="fees-on-private-networks"></a>

​[Private networks](https://docs.phi.network/phi-wiki/glossary#p) based on the PHI Smart Chain protocol will work exactly the same way as they do in our public ledgers. The main difference is that by having full control over the network, private users can easily have access to native units of account to cover the usage fees, without never having to worry about them.
