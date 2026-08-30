# How Web3 networks operate

A Web3 network is a digital system in which multiple participants maintain and update a shared ledger according to a common set of rules. Instead of placing the authoritative record under the control of a single bank, company or database administrator, the network distributes responsibility across node operators running compatible software.

The network receives transactions from users, verifies whether those transactions follow its rules, agrees on their order and records the resulting changes in the shared ledger. Programmable networks can also execute smart contracts and maintain tokens created through those contracts.

The reliability of the system depends on the network’s ability to keep these different participants in agreement, reject invalid activity and provide sufficient incentives for people to continue operating the required infrastructure.



## **The distributed ledger**

A ledger is a record of ownership, balances and transactions. Banks maintain ledgers recording the balances and obligations associated with their customers’ accounts. A Web3 network also maintains a ledger, but copies of that ledger are stored and updated by multiple network participants.

The ledger records the current state of the network. This state may include coin balances, token balances, deployed smart contracts and information stored by applications.

When a valid transaction is accepted, the state changes. A transfer from Alice to Bob reduces the balance controlled by Alice and increases the balance controlled by Bob. A transaction involving a smart contract may produce a more complex change, such as exchanging tokens, depositing collateral or updating information within an application.

The ledger provides a shared reference that allows participants to determine which transactions have occurred and which assets are controlled by each address.

Because multiple nodes maintain the ledger, no single copy should be treated independently as authoritative. The network’s consensus process determines which version of the ledger is accepted as the current state.



## **Transactions**

A transaction is an instruction submitted to the network. It asks the network to make a particular change to its recorded state.

A transaction may transfer a network coin, transfer a token, execute a smart contract or update information associated with an application. The available transaction types depend on the functionality supported by the network.

Alice begins a transaction through her wallet. The wallet prepares the necessary information, including the destination, the asset being transferred and the amount. Alice then authorises the instruction using the cryptographic credentials associated with her address.

The authorised transaction is transmitted to the network. Nodes inspect it to determine whether it complies with the protocol’s rules. They may check whether Alice has authority over the relevant assets, whether her balance is sufficient and whether the transaction has already been submitted or completed.

If the transaction is valid, it can be included in the ledger. If it violates the network’s rules, nodes reject it.

The network does not need to understand why Alice is making the transaction or whether she considers it economically beneficial. Its responsibility is to determine whether the instruction is technically valid under the protocol.



## **Wallets and authorisation**

A wallet is the software through which a user interacts with a Web3 network. It allows the user to inspect assets, prepare transactions and provide the cryptographic authorisation required to control an address.

The wallet does not necessarily contain the digital assets themselves. The assets exist as records within the network’s state. The wallet manages the credentials that allow the user to instruct the network to transfer or use those assets.

This differs from a conventional bank account. A bank maintains an account connected to a customer’s legal identity and decides whether to process instructions involving that account. A Web3 network generally evaluates whether a transaction is authorised by the cryptographic credentials controlling the relevant address.

The underlying protocol may not know the legal identity of the person operating the wallet. Applications built on the network can still introduce identity requirements, but these are distinct from the basic mechanism used to authorise a transaction.

Direct wallet control gives users greater independence from account providers. It also transfers more responsibility to them. If credentials are lost or exposed, there may be no central institution capable of restoring access or reversing an unauthorised transaction.



## **Node operators**

A node is a computer running software that participates in the Web3 network. The person or organisation responsible for it is a node operator.

Nodes receive transactions, apply the network’s validation rules and maintain information about the ledger. Depending on the network’s design, nodes may also participate directly in determining which transactions are added and in what order.

Node operators contribute hardware, storage, computing capacity, internet connectivity and operational effort. A network intended for continuous global use requires nodes to remain available and synchronised.

If only one organisation operated all the nodes, the system would retain a central point of control. That organisation could alter the ledger, block access or change the rules. Web3 networks attempt to distribute node operation across independent participants so that no single operator controls the entire system.

The number of nodes alone does not determine the extent of decentralisation. It also matters who controls them, how influence is distributed and whether ordinary participants can independently verify the ledger.



## **Full nodes and verification**

Some nodes independently verify transactions and the state of the ledger. They apply the network’s rules rather than simply trusting information supplied by another participant.

Independent verification makes it more difficult for an operator to introduce invalid transactions or change balances arbitrarily. Other nodes will reject activity that does not comply with the agreed protocol.

A user does not necessarily need to operate a full node to interact with the network. Wallets may obtain information through nodes operated by other people or through service providers. This is more convenient but introduces some dependence on the provider supplying the information.

The network remains most verifiable when users and organisations have a practical ability to run their own nodes. If node operation becomes excessively expensive or technically difficult, verification may become concentrated among a smaller number of organisations.



## **Consensus**

Consensus is the process through which network participants agree on the accepted state of the distributed ledger.

Different nodes can receive transactions at different times. Two transactions may conflict, or a malicious participant may attempt to spend the same asset more than once. The network therefore requires a process for deciding which transactions are accepted and in what order.

The consensus mechanism coordinates this decision. It enables nodes to converge on a shared transaction history even when some participants are unavailable, unreliable or malicious.

A functioning consensus mechanism must make it difficult for an individual participant to rewrite the ledger or cause conflicting versions to remain accepted. Once sufficient agreement has been reached, users can treat a transaction as confirmed according to the security assumptions of the network.

The consensus process does not imply that every node communicates directly with every other node about each transaction. The exact method varies between networks. The common objective is to establish a shared state that independent participants can verify.



## **Preventing conflicting transactions**

Digital information can ordinarily be copied. Without a shared ledger, Alice could attempt to send the same digital asset to both Bob and Charlie.

The network prevents this by evaluating each transaction against the accepted ledger state. Once Alice’s transfer to Bob has been included, the state records that Alice no longer controls the transferred amount. A later attempt to transfer the same amount to Charlie will be rejected if her remaining balance is insufficient.

The ordering of transactions is therefore important. The consensus mechanism establishes which valid transaction occurred first and ensures that nodes apply later transactions to the resulting state.

This ability to maintain scarcity and consistent ownership records is one of the principal functions of a distributed ledger.



## **Malicious and unreliable participants**

A Web3 network cannot assume that every participant will behave honestly. Some nodes may disconnect, fail to update their software or submit invalid information. Others may attempt to censor transactions, manipulate the ledger or gain an unfair financial advantage.

The protocol must continue operating even when some participants are unreliable. Nodes should be able to reject invalid transactions by applying the network’s publicly defined rules.

An individual operator may be able to delay a transaction when responsible for a particular part of the processing sequence, but another operator may subsequently include it. Persistent censorship generally requires control or coordination across a sufficiently influential portion of the network.

The amount of influence required depends on the consensus mechanism. If control becomes concentrated, the network may become more vulnerable to censorship, ledger manipulation and governance capture.

Decentralisation is therefore not simply an organisational preference. It is part of the network’s security model.



## **Incentivising node operation**

Operating a node requires resources. Participants may need to purchase hardware, maintain servers, provide storage and bandwidth, monitor software and respond to technical problems.

A globally available network cannot ordinarily assume that enough people will provide these resources indefinitely without compensation. It needs an economic mechanism that rewards the participants responsible for maintaining its operation.

Web3 networks commonly use a native network coin for this purpose. The network can distribute coins to eligible node operators or direct fees paid by users towards them.

This creates a circular economic relationship. Users demand network resources when they submit transactions, while node operators provide the infrastructure required to process and store those transactions. The network coin transfers value between the users and operators.

The reward mechanism must provide enough compensation to sustain reliable operation without imposing unnecessary costs on users. If rewards are insufficient, node operators may stop participating. If they are excessive, users may pay more than is necessary and use an alternative network.



## **Paying for network usage**

Networks commonly require users to pay a fee when submitting transactions. The fee compensates node operators and helps prevent a user from consuming unlimited network resources.

Without any cost or alternative restriction, a malicious participant could submit a large number of transactions and attempt to overwhelm the network. Even a very small fee can make sustained spam more expensive.

Transaction fees may vary according to the amount of computation or storage required. A simple coin transfer may use fewer resources than a complex smart-contract transaction.

The fee is commonly paid with the native network coin. This produces continuing demand for the coin because users need it to access the network.

However, a network benefits from keeping transaction costs low. High fees can discourage valid activity and cause users or applications to migrate to competing networks. The fee must therefore balance access, node compensation and protection against excessive resource consumption.

Later pages will examine whether other forms of income, including a periodic charge on network-coin balances, could subsidise node operation and reduce dependence on transaction fees.



## **The network coin**

The network coin is the native fungible asset associated with the network protocol. Unlike a token created through a smart contract, it is normally integrated directly into the network’s operation.

Its responsibilities may include paying transaction fees, compensating node operators, participating in the consensus mechanism and influencing governance. The exact combination varies between networks.

In a proof-of-stake system, participants may commit or stake network coins as part of the consensus process. The value placed at risk gives them an incentive to follow the protocol. A participant that acts maliciously may lose some or all of the committed amount, depending on the design.

In a proof-of-work system, operators compete by contributing computational resources. The network coin is used to reward successful participation and may also transfer transaction fees to the operators processing activity.

The network coin is therefore more than an application-specific digital asset. It can be part of the economic infrastructure that keeps the ledger operational and secure.



## **Smart contracts**

A smart contract is a program deployed on a Web3 network. It contains instructions that the network executes when users submit relevant transactions.

A smart contract can receive, hold and transfer digital assets according to predefined rules. It can support arrangements such as exchanges, loans, collateral deposits, collective treasuries and other agreements.

The term “contract” does not necessarily mean that every program is a legal contract. It describes software that automatically applies programmed conditions within the network.

Suppose Alice and Bob want to exchange two digital assets. Instead of trusting one participant to transfer first, they can place their assets into a smart contract. The contract completes the exchange when both required deposits have been received.

The network’s nodes execute the same contract rules and agree on the resulting state. Neither participant needs to control the ledger or operate a central database.

Automation can reduce the need for an intermediary to administer the agreement. However, it transfers importance to the program’s design. If the code contains an error or fails to account for a particular situation, the network may still execute it as written.



## **Deterministic execution**

Nodes need to reach the same result when executing a smart contract. If identical instructions produced different outcomes on different nodes, the participants could not agree on the ledger state.

Smart contracts are therefore designed to operate according to rules that nodes can reproduce and verify. The transaction and current state determine the resulting state.

Information that exists outside the network cannot automatically be treated as part of this shared calculation. If a contract depends on an external price, event or real-world condition, a mechanism is needed to introduce that information.

These mechanisms are commonly known as oracles. They can make external data available to smart contracts, but they also introduce another source of dependence and risk. If the supplied information is inaccurate or manipulated, the contract may execute an unintended action.

For this reason, network-level systems benefit from minimising unnecessary reliance on external information, particularly when a failure could affect the operation or security of the entire network.



## **Tokens**

Programmable Web3 networks often allow for the creation of tokens. A token is an asset represented through rules and records maintained on the network.

Tokens may be fungible, meaning each unit is interchangeable with another unit of the same type. They may also represent distinct assets whose individual identity matters.

A fungible token can represent money, a commodity claim, ownership, membership or another divisible form of value. The token’s contract or parameters define how balances are recorded, whether new units can be created and under what conditions units can be transferred or removed.

Tokens inherit the transaction processing and security environment of the underlying network, but they do not necessarily inherit the network coin’s monetary policy or governance. Each token can have its own rules and controlling community.

A token can fail or lose demand without causing the underlying network to stop operating. This separation allows communities to experiment with different assets while the network continues maintaining the shared ledger.



## **Network operation and application activity**

It is useful to distinguish the core network from the applications operating on it.

The core network maintains the ledger, validates transactions, executes supported instructions and provides the security required for participants to agree on the state.

Applications use this infrastructure for particular purposes. A token exchange may help users swap assets, a lending protocol may coordinate loans and a community application may manage memberships or contributions.

A failure in an application can harm its users without necessarily compromising the whole network. By contrast, a failure in the consensus mechanism, native coin incentives or core protocol can affect every application relying on the system.

The network therefore benefits from keeping its core responsibilities as simple and reliable as possible. Functionality that does not need to be implemented at the network level can be handled by applications and smart contracts.

This separation reduces the number of mechanisms that must be treated as mission-critical components of the network.



## **Governance and protocol changes**

Web3 networks may need to change over time. Developers may identify software defects, security improvements, performance changes or new functionality.

Because multiple independent node operators run the protocol, an update cannot always be deployed by changing one central server. Operators need to adopt compatible software and agree, formally or informally, on the rules they will follow.

Some networks use explicit governance processes in which participants vote on proposed changes. The network coin may determine or contribute to voting power. Other networks rely more heavily on discussion between developers, node operators, users and application providers.

If participants adopt incompatible rules, the network can split into separate versions. Each version may maintain its own ledger and community from the point of separation.

Governance is therefore connected to both technical coordination and economic incentives. Participants must decide which changes preserve the network’s security, reliability and usefulness.

A globally adopted network faces particular governance challenges. Large populations make collective decisions slower and more complex, while delegating control to a small group can reintroduce concentrated power.

For this reason, the protocol benefits from predictable rules and from limiting the number of parameters that require continuing human intervention.



## **Open-source software**

Many Web3 networks make their software publicly available. Open-source code allows participants to inspect the protocol, run their own nodes and verify the rules being applied.

Public code can improve transparency, but it does not guarantee that every user will understand or review the implementation. Most users still depend on developers, auditors and service providers to identify technical problems.

Open-source software also makes it easier for another community to copy and modify a network. Competing networks can adopt successful technical improvements without developing every component from the beginning.

This reduces the extent to which technology alone can create a permanent competitive advantage. Economic incentives, governance, security, application adoption and network effects become important in determining which networks retain users over time.



## **Permissionlessness and decentralisation**

Permissionlessness and decentralisation are related but distinct characteristics.

A network is permissionless when participants can ordinarily create wallets, submit valid transactions or operate nodes without receiving approval from a central administrator.

A network is decentralised when control over transaction processing, validation, governance and other important functions is distributed across independent participants.

A network can be open to users while still having concentrated node operation or governance. It can also have many operators while practical access depends on a small number of interfaces or service providers.

Evaluating a Web3 network therefore requires more than counting nodes or observing that anyone can create a wallet. It requires considering where control, infrastructure and economic influence are concentrated.

The network coin and tokens play different roles within this structure. The coin is generally tied to operation and access, while tokens are created on top of the network for application-specific and community-specific purposes.
