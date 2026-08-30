# Responsibilities, goals and constraints

The network coin is a mission-critical component when it is used to pay for network resources and compensate node operators. Its design can affect transaction processing, security, governance, financial activity and the long-term sustainability of the network.

Because these functions are connected, improving one property of the coin can weaken another. A policy that increases demand may strengthen network security but also encourage storage and concentration. A policy that strongly discourages storage may improve availability but reduce the coin’s value and make node compensation less reliable.

The network coin therefore needs a clearly defined set of responsibilities and design goals. It should perform the functions required for the network to operate while avoiding responsibilities that can be handled more safely and flexibly by tokens or applications.



## **Core responsibility: supporting network operation**

The network coin’s primary responsibility is to support the continuing operation of the network.

Users require computation, transaction processing, storage and other network resources. Node operators provide the hardware and operational effort needed to make those resources available.

The coin creates a common mechanism for transferring value between these participants. Users or transaction sponsors obtain the coin to pay for network activity, while node operators receive it as compensation.

This relationship allows the network to create an internal economy rather than depending entirely on external funding. Demand for the network creates demand for its coin, and the coin helps fund the infrastructure required to satisfy that demand.

The compensation mechanism must be reliable across changing levels of network activity. If operators cannot expect to recover their costs, they may leave. A decline in participation can weaken availability, decentralisation and security.

The network coin must therefore retain enough value and demand to support continuing node operation.



## **Paying for network resources**

The coin provides a common unit for pricing network resources.

A transaction consumes a quantity of computation, storage and bandwidth. A simple transfer may use fewer resources than a complex smart-contract transaction.

Using the network coin allows the protocol to express these costs through a single asset. Nodes can apply the same rules without assessing the value and governance of every token created on the network.

The network should aim to keep the cost of valid activity as low as possible. High fees discourage use and make competing networks more attractive. However, a transaction may still need to carry some cost or satisfy another restriction so that malicious participants cannot consume unlimited network resources.

The coin’s fee role therefore needs to balance access with protection against spam and denial-of-service activity.

Transaction fees do not necessarily need to provide all of the income required for node operation. Other network-level charges may supplement them. However, the coin remains the common asset through which the protocol accounts for resource use and distributes compensation.



## **Potential responsibility: supporting consensus**

The network coin may support the consensus mechanism, particularly in proof-of-stake networks.

Participants commit coins to demonstrate economic exposure to the network. The protocol can reward correct participation and impose losses for specified forms of misconduct.

This gives the coin a direct role in security. An attacker may need to acquire or control a substantial amount before gaining enough influence to disrupt consensus.

The effectiveness of this mechanism depends on the coin’s value and distribution. If the coin has very little demand, acquiring a large proportion may become comparatively inexpensive. If ownership is highly concentrated, a small number of participants may already possess substantial influence.

The coin’s economic design must therefore consider more than its market price. Security also depends on who controls the supply, how easily ownership can concentrate and how much of the coin is committed to consensus.

The network coin does not have to determine consensus influence in every design. A proof-of-work network uses computational resources as the direct basis of participation. Even then, the coin may remain important because it compensates operators and gives the rewards economic value.



## **Potential responsibility: supporting governance**

The network coin may also contribute to network governance.

Protocol upgrades, economic parameters and treasury expenditure may require collective decisions. Coin holdings, staking participation, fees or other coin-based contributions can provide evidence that a participant has an economic relationship with the network.

This can help address the Sybil-resistance problem. Creating many wallets does not automatically create additional coins or contributions.

However, coin-based governance also creates the risk of wealth-based control. Large holders may gain disproportionate influence, particularly if coin ownership becomes more concentrated over time.

The network should not assume that ownership alone is a complete measure of legitimate participation. Coin-based governance can form part of a wider decision process, but it must account for concentration, delegation and conflicts of interest.

Whatever governance mechanism is adopted, it should remain as simple and predictable as possible. A global network cannot efficiently subject every technical and economic decision to a complex process involving its entire population.

The coin’s role in governance should therefore be limited to responsibilities that genuinely require network-level coordination.



## **Secondary responsibility: financial liquidity**

The network coin can provide financial liquidity across the ecosystem.

Tokens need markets through which users can exchange one asset for another. If every token requires a separate direct market against every other token, liquidity becomes fragmented across a large number of pairings.

The network coin can act as a common intermediary. Tokens can maintain markets against the native coin, allowing users to exchange one token for the coin and then exchange the coin for another token.

This gives the network coin a productive secondary use and creates demand beyond the immediate payment of transaction fees.

Deep coin liquidity can also make the network easier to enter. A user holding a token can exchange it for the coin required to pay for network resources.

Financial liquidity is not as essential as node compensation, but it is strongly aligned with the purpose of a programmable digital-asset network. A network that supports efficient token exchange may attract more users, applications and assets.

The coin should not be spread across unnecessary financial incentives merely to create artificial demand. Its use should be encouraged where it directly improves the operation and usefulness of the network.



## **Secondary responsibility: contract collateral**

The network coin can also serve as collateral in agreements.

A participant may place coins into a smart contract as assurance that they will comply with specified conditions. If the participant breaches the agreement, some or all of the collateral may be transferred or removed.

The network coin is suitable for this use because it is widely recognised within the ecosystem and has demand connected to network operation.

Collateral can create longer-term demand because coins may remain committed for the duration of an agreement. It also places the coin into a productive role rather than leaving it idle in a wallet.

However, excessive collateral lock-up could reduce availability. The network still requires coins to remain accessible for fees, node compensation and other essential functions.

Tokens can complement the network coin as collateral, particularly when an agreement requires stable purchasing power or an asset connected to a specific community. The network coin does not need to satisfy every collateral requirement.



## **Goal: maintain high availability**

Anyone who needs to use the network must be able to obtain the network coin or have a transaction sponsor provide it on their behalf.

If large quantities are held idle for extended periods, the actively available supply decreases. Users may find the coin more expensive or difficult to obtain, and transaction costs may become less predictable.

A rising coin price does not automatically prevent network use. The protocol can price fees in very small units, and wallets can acquire only the amount required for a transaction. However, extreme scarcity and volatility can still create access problems.

High availability means more than a large total supply. Coins may technically exist while remaining concentrated in wallets that do not make them available for exchange, lending or payment.

The design should encourage coins to remain accessible through circulation, markets and appropriate financial protocols.

Availability must be balanced against security. Some coins will be committed to staking, collateral and long-term financial positions. These uses can support the network even though the coins are not immediately available for every transaction.

The objective is not to keep every coin moving continuously. It is to prevent excessive idle retention from restricting access to a resource required by all network users.



## **Goal: achieve balanced demand**

Demand for the network coin must be neither too weak nor excessively concentrated around passive holding.

If demand is too low, the coin’s value may decline. Node compensation becomes less attractive, and acquiring enough coins to influence consensus or governance may become less expensive.

Low demand can also reduce the value of treasury income. A treasury holding a large number of coins may be unable to fund substantial work if selling them places further pressure on an already weak market.

If demand is too high because holders expect rapid appreciation, people may accumulate the coin and leave it idle. This can reduce availability and concentrate ownership.

Demand based primarily on speculation can also be unstable. A coin may achieve a high price during periods of optimism and then experience a rapid decline when expectations change.

Balanced demand means that participants want the coin because it performs useful functions, but the advantages of holding it do not make indefinite accumulation the dominant strategy.

The coin should maintain enough long-term demand to support security, node operation and financial liquidity while preserving an incentive to use or make it available.



## **Goal: avoid excessive idle storage**

Idle coins provide little direct benefit to the network. They do not pay for transactions, provide liquidity, support agreements or compensate operators.

A holder may still contribute indirectly by demonstrating confidence in the network and supporting the coin’s market value. This can be helpful during the early development of a network when investment is needed and few productive uses exist.

As the ecosystem matures, the relative value of passive storage decreases. More users depend on access to the coin, and more applications can use it productively.

The design should therefore distinguish between holding that supports a network’s early development and prolonged accumulation that restricts access in a mature ecosystem.

A coin should be capable of preserving meaningful value without becoming an ideal instrument for indefinite idle storage. This is the central problem that demurrage is intended to address.



## **Goal: encourage productive use**

When participants do not need coins for immediate transactions, the network can encourage them to make those coins available for useful purposes.

They may provide liquidity for token exchange, lend coins to other users, commit them to consensus or use them as collateral.

Productive use does not mean that every financial activity benefits the network equally. A complicated protocol may lock coins without increasing their practical availability. An incentive can also be exploited by participants who create artificial transactions or assets merely to qualify for a reward.

The network should therefore prioritise use cases that provide clear and measurable benefits. Token exchange liquidity improves access to digital assets, single-asset lending can make coins available to borrowers and staking may support consensus.

Incentives should not distribute the coin across many financial protocols simply to create the appearance of activity. Doing so can fragment liquidity and introduce additional technical risks.



## **Goal: preserve decentralised ownership**

A network coin may influence consensus and governance, so the distribution of ownership affects the distribution of power.

If holders can earn a low-risk return that consistently exceeds the costs of holding the coin, large balances can grow automatically. Participants already possessing substantial amounts can receive more coins without making an equivalent new contribution.

Compounding can increase concentration over time, especially when smaller holders must spend part of their balances while larger holders can reinvest their returns.

Concentrated ownership can allow a small number of participants to influence transaction processing, governance and treasury decisions. It can also reduce confidence that the network is meaningfully decentralised.

The coin’s design should make indefinite concentration more difficult. This does not require every participant to hold the same amount. Differences can result from labour, investment, risk and contribution.

The objective is to avoid a structural mechanism through which existing ownership automatically becomes increasingly dominant without corresponding productive activity.

Coin dispersion can improve security by distributing economic influence across more participants. It can also increase access by making more of the supply available to people providing goods, services and labour.



## **Goal: sustain the network economy**

The network needs enough income to compensate node operators, maintain infrastructure, correct security problems and fund necessary development.

A genesis allocation can finance early activity, but it is finite. Once it has been distributed or spent, the network requires another source of income.

Transaction fees create one source, but their reliability depends on network activity. Income declines when transaction volume falls, even though operators and developers may still need to maintain the system.

Increasing transaction fees to fund a treasury can discourage the very activity the network is intended to support. Active users bear the cost, while people holding coins without transacting make no direct contribution.

A sustainable economy requires a funding mechanism that remains reliable across changing levels of transaction activity. It should distribute costs in a way that aligns with the benefits participants receive from the network.

The resulting income must also be used effectively. A large treasury does not guarantee useful development. Poor allocation can waste resources, create political conflict and encourage participants to capture the funding process.

The sustainability of the network therefore depends on both revenue collection and responsible expenditure.



## **Goal: maintain a predictable and reliable coin**

Users and operators need to understand the rules governing the network coin.

Frequent or discretionary changes to its supply, fees and economic functions can create uncertainty. Participants may be unwilling to hold, use or accept a coin if they cannot predict how its rules will change.

The coin is particularly sensitive because it can affect every application on the network. A token community can change its own asset without directly modifying other tokens. A network-coin change applies across the shared infrastructure.

The coin’s implementation should therefore minimise unnecessary parameters and governance decisions. Automated rules can improve predictability when they are understandable and resistant to manipulation.

Automation does not automatically make a system safe. A rule depending on unreliable or easily manipulated data can fail without human intervention. Complex algorithms may also behave unpredictably under conditions their designers did not anticipate.

Simplicity is therefore an important security property. A simpler policy can be easier to inspect, maintain and explain to a global population.



## **Goal: protect network security**

The network coin’s market value can affect the cost of attacking the network.

In a proof-of-stake system, a higher coin value generally makes it more expensive to acquire a large stake. In coin-based governance, it increases the cost of purchasing voting influence.

However, a high price is not sufficient if ownership is concentrated or if coins can be borrowed temporarily for an attack. Security depends on distribution, liquidity, staking participation and the rules governing influence.

A design intended to increase circulation must not accidentally weaken security by making the coin undesirable to hold under all circumstances. If no one wants longer-term exposure to the coin, its price and the reliability of operator compensation may decline.

The network must distinguish between productive commitment and idle storage. Coins used in consensus, liquidity and collateral positions can support the network even when they remain under one participant’s ownership.

Security therefore requires balanced incentives. The coin must remain valuable enough to protect the network while avoiding a structure that steadily concentrates control.



## **Goal: maintain moderate price stability**

The network coin does not need perfectly stable purchasing power to perform its core functions. Fees can be adjusted, and the coin can be divided into small units.

Nevertheless, extreme volatility can create operational and financial problems.

If the coin appreciates rapidly, borrowers must repay increasingly valuable units, token markets require frequent rebalancing and users may delay spending because they expect further appreciation.

If the coin loses value rapidly, operator compensation and treasury income become less reliable. Participants may exchange the coin immediately after receiving it, increasing sell pressure.

Moderate stability can improve the coin’s usefulness as financial liquidity and collateral. It can also make network costs more predictable.

Achieving stable prices at a global scale is difficult. Demand is influenced by network adoption, application activity, speculation and external economic conditions.

A highly responsive supply system might require external data and complex governance, creating risks for the network. A simple policy may be more reliable but permit larger price changes.

Price stability is therefore a goal that must be balanced against simplicity and security. Gradual changes may be acceptable if avoiding them would require a fragile or manipulable mechanism.



## **Goal: create useful network effects**

Web3 networks compete for users, applications, developers, assets and financial liquidity.

Because the software is commonly open source, a competing network can copy successful technical features. Long-term advantage may therefore depend more heavily on adoption, security, governance and network effects.

The network coin can contribute to these effects when it supports functions that become more useful as participation grows.

Financial liquidity is a strong example. A network with deep token markets can offer lower slippage and easier access to assets. New users benefit from existing liquidity, while their own participation makes the markets more useful for others.

The coin can serve as a common liquidity asset and connect the markets for many different tokens. If this role becomes established at scale, a new network may find it difficult to reproduce the same market depth immediately.

Other network effects may arise from applications, users and stored data, but open standards and interoperability can make these easier to migrate.

The network should encourage network effects that improve real usefulness rather than relying on artificial barriers to exit. Users should remain because the network provides efficient and reliable services, not because their assets or data are deliberately trapped.



## **Constraint: global scale**

A successful Web3 network may serve users across many countries and economic environments.

This scale makes governance and economic management more difficult. A policy that benefits one group may impose costs on another, and reaching agreement can require substantial time.

The network coin cannot be adjusted as if it were a small community currency. Changes can affect global financial markets, applications and node operators.

The coin therefore benefits from assigning community-specific responsibilities elsewhere. Tokens can handle monetary policies intended for particular countries, regions and online communities.

The network coin can remain focused on the shared infrastructure used by all of them.



## **Constraint: open competition**

No user is permanently required to remain on one Web3 network. Competing networks can offer lower fees, different governance and more attractive economic policies.

A network that imposes excessive costs on coin holders may encourage them to move elsewhere. A competing network can copy the underlying software and reduce those costs.

This limits how far the network can rely on taxation or other charges without providing corresponding value.

Network effects may reduce the speed of migration, but they do not eliminate competition. Wallets, bridges and other interoperability tools can make it easier to use several networks.

The network-coin policy must therefore remain economically competitive. Charges should be justified by improvements in security, availability, infrastructure or ecosystem funding.



## **Constraint: coexistence with tokens and external assets**

Users can hold many assets on the network. If the network coin becomes expensive to retain, they can exchange it for a token or external asset and reacquire the coin only when required.

Digital exchange can occur rapidly and may be automated by wallets. A carrying charge can therefore produce sell pressure more quickly than it would in a physical monetary system.

The network coin cannot assume that users will hold it simply because they need it occasionally for fees. It requires continuing reasons for longer-term demand, such as staking, liquidity and collateral.

At the same time, the network should not make tokens artificially unattractive merely to strengthen demand for the native coin. A network that restricts token choice can be outcompeted by one offering greater flexibility.

The network coin must succeed through its own usefulness and economic design.



## **Constraint: the coin should not become the sole global medium of exchange**

The network coin can be accepted as payment, but it does not need to become the primary medium of exchange for every community using the network.

Attempting to maintain stable monetary conditions for the entire global economy would add substantial responsibility. Countries and communities experience different growth rates, price changes and financial conditions.

A single policy could not respond independently to each environment. Adjustments intended to benefit one economy might harm another.

Tokens allow communities to create their own mediums of exchange while using the same underlying ledger. They can choose different supply policies, governance structures and approaches to demurrage.

This division reduces the burden on the network coin. It can focus on operating and securing the shared infrastructure rather than governing every community’s monetary system.

The concession is not that the network coin cannot function as money. It can be exchanged, held and accepted as payment. The point is that becoming the sole or principal global medium of exchange should not be treated as one of its necessary responsibilities.



## **Balancing the design goals**

The network coin must balance availability, demand, security, decentralisation, sustainability and predictability.

Increasing demand can strengthen the coin’s value but encourage storage. Increasing circulation can improve availability but weaken longer-term demand if users immediately exchange the coin for other assets.

Locking coins into staking or collateral can support security and financial activity but reduce the amount immediately available for transactions. Increasing the supply can improve availability but dilute existing holders and weaken the coin’s value.

A simple fixed policy can improve predictability but may not respond to changes in network demand. An adaptive policy can pursue greater stability but introduce governance, data and security risks.

There is no single parameter that resolves all of these tensions. The design must establish priorities.

The first priority is the continuing operation and security of the network. The second is maintaining access to the coin for users. Secondary financial functions should support these priorities rather than compromise them.

Demurrage becomes relevant because it directly addresses one side of the balancing problem: the ability to retain the network coin indefinitely at little or no cost.
