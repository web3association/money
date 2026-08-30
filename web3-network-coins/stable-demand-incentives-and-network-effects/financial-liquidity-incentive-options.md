# Financial liquidity incentive options

A financial liquidity incentive can create longer-term demand for a network coin that carries a periodic charge.

Rather than rewarding passive storage, the network can reduce the charge when holders make their coins available for functions that benefit other participants. This can increase demand while improving the operation of the network’s financial markets.

Many decentralised financial protocols can use the network coin. However, the existence of a possible use does not mean that it should receive a network-level incentive.

Each reduction forgoes demurrage income and directs part of the coin supply towards a particular activity. Incentives should therefore be concentrated on functions that provide clear ecosystem-wide benefits.



## **Financial liquidity objectives**

Financial liquidity incentives should satisfy several objectives:

* **Create longer-term demand** - The incentive should give participants a reason to maintain exposure to the network coin over longer periods. Lock-up or commitment periods can make demand more durable. Coins deposited for a few minutes provide less stability than coins committed for several months. Longer commitments can also reduce the speed at which liquidity leaves during periods of market stress. However, excessive lock-ups can make the coin difficult to obtain and prevent holders from responding to changing risks.
* **Increase the utility of the network coin** - The incentive should support functions that make the coin and network more useful. Locking coins without providing a service may increase measured demand, but it does not necessarily improve network operation. A productive position should contribute liquidity, availability, security or another identifiable benefit. The question is not whether a financial application can use the network coin. It is whether that application is sufficiently important to justify preferential treatment from the protocol.
* **Strengthen network effects** - The incentivised use should become more valuable as participation increases. Financial markets create a strong example. Deeper liquidity reduces slippage, attracts users and makes it easier for additional participants to supply liquidity. A competing network may copy the software, but it cannot immediately reproduce an established market’s liquidity. This can create a durable network effect based on genuine utility rather than artificial restrictions.
* **Make the coin easier to obtain** - Everyone using the network may need access to the coin for fees or other protocol-level resources. An incentive should therefore make coins more available rather than merely removing them from circulation. Positions that allow users to exchange or borrow coins are generally more useful than arrangements that lock coins without making them accessible.
* **Avoid automatic wealth concentration** - A charge reduction should compensate a participant for providing a useful function or accepting risk. It should not create a guaranteed positive return that allows existing holders to compound their ownership indefinitely. The incentive must account for the demurrage reduction, income received from the financial protocol, lock-up restrictions, market and smart-contract risks and the opportunity cost of alternative uses.
* **Resist manipulation** - Eligibility should depend on the function provided rather than the technical appearance of a position. If any smart contract qualifies, participants can create contracts that merely store coins. If every token pairing qualifies, participants can create tokens and inactive markets they control. Raw volume and wallet counts do not solve the problem because trades and addresses can be generated artificially. The protocol must distinguish genuine availability and economic activity from nominal deposits designed only to obtain the lower charge.
* **Avoid excessive fragmentation** - Spreading incentives across many financial protocols divides the available coin supply. If every exchange, lending market, stablecoin, derivative and synthetic-asset protocol receives an incentive, each market may remain shallow. Governance and implementation also become more complex. A focused incentive structure is easier to understand, evaluate and maintain.



## **Network coin charge reductions**

A reduction in the network-coin charge is a direct way to encourage financial liquidity.

Suppose idle balances are charged 5 per cent annually while coins deposited into recognised liquidity positions are charged 2 per cent. The participant saves three percentage points by making the coins available.

The participant may also earn fees from the application. Their total outcome depends on:

* The value of the charge reduction
* Protocol fee income
* Changes in the coin’s market value
* Changes in the value of any paired assets
* Smart-contract and liquidity risks
* The duration of the commitment

This approach does not require the protocol to create additional coins. Instead, the network forgoes some demurrage income in exchange for a productive contribution.

The full rate represents the cost of leaving the coin inactive, while reduced rates recognise productive uses.



## **Token exchange liquidity**

Token exchange protocols allow users to swap digital assets.

A network supporting many tokens benefits from deep and efficient markets between them. The native coin can serve as a common pairing, reducing the need for every token to maintain a direct market against every other token.

A user exchanging token A for token B could first exchange token A for the network coin and then exchange the network coin for token B.

Without a common pairing, the number of possible markets increases rapidly as more tokens are introduced. Liquidity becomes fragmented across many pairings, making each individual market shallower.

Using the network coin as a common intermediary can:

* Reduce liquidity fragmentation
* Lower slippage
* Make larger exchanges possible
* Make tokens easier to access
* Make the network coin easier to obtain for fees
* Increase the usefulness of issuing tokens on the network

A demurrage reduction can encourage holders to supply coins to these markets. Lock-up incentives can create longer-term liquidity and reduce sudden withdrawals.

Token exchange liquidity is closely aligned with the purpose of a digital asset network because it improves the creation, access and exchange of assets hosted by that network.



**Token exchange network effects**

Liquidity produces a reinforcing network effect.

Deeper markets offer better exchange prices. Better prices attract more users and token issuers. Increased activity can generate more fee income and attract further liquidity providers.

A competing network can reproduce the exchange protocol but cannot immediately reproduce the liquidity already committed to the market.

The network coin strengthens this effect when it becomes a common pairing. Its liquidity makes token markets more efficient, while the presence of more token markets increases the usefulness of acquiring and supplying the coin.



**Risks of token exchange incentives**

Providing exchange liquidity requires the holder to pair the network coin with another asset.

If the paired token loses most of its value, the liquidity provider may end up holding more of the failed token and fewer network coins. The position may also experience losses when the relative prices of the two assets change substantially.

The incentive therefore requires participants to accept risks beyond merely holding the network coin.

Some participants may avoid exchange liquidity because they do not want exposure to another token. Others may attempt to avoid this risk by creating a token they control and pairing it with their own network coins.

Such a position may qualify technically while providing little genuine value. If no one uses the market, the coins are not meaningfully supporting token exchange.

Requiring transaction volume does not fully solve the problem because the participant can generate artificial trades. Requirements based on the number of wallets can be manipulated through multiple addresses.

Protocol fees provide a natural reason to favour genuine markets, but the value of a network-level charge reduction may still make inactive pairings worthwhile.

The network should therefore avoid relying exclusively on token exchange liquidity. Holders should have another way to make their coins available without taking direct exposure to a second asset.



## **Single-asset lending and borrowing**

A single-asset lending protocol allows participants to lend the network coin and other participants to borrow the same asset.

Lenders make coins available without pairing them with another token. They may receive fees from borrowers as well as a reduction in demurrage.

Borrowers gain access to the network coin for transaction fees, exchange liquidity or other productive uses. This can make the coin easier to obtain without requiring existing holders to sell their positions.

Because the deposited and borrowed asset is the same, the protocol does not need an external price oracle to determine the relative value of two different assets. A decline in the coin’s value relative to fiat money or tokens affects both sides of the loan equally.

This avoids the cross-asset liquidation risk found in multi-asset lending. Interest accrual and loan conditions can be measured directly in the network coin. This can provide a simpler way to make the network coin available than lending arrangements that depend on external asset prices.



**Complementing token exchange liquidity**

Single-asset lending addresses an important limitation of token exchange incentives.

Holders willing to accept exposure to another token can provide exchange liquidity and earn market fees. More cautious holders can lend the network coin without directly acquiring another asset.

This reduces the incentive to create artificial tokens merely to qualify for a lower charge. If the reduction is comparable across both uses, a participant can use the lending protocol instead of constructing an inactive token pairing.

The two functions are complementary:

* Token exchange improves markets for hosted assets
* Single-asset lending improves the availability of the native coin
* Both create optional, longer-term demand
* Both provide a service to other network users



**Balancing exchange and lending incentives**

The relative size of the incentives matters.

If token exchange liquidity receives a substantially larger reduction, participants may create artificial tokens and markets to obtain the better rate without accepting genuine token risk.

If single-asset lending receives a much larger reduction, too much of the available supply may move away from token exchange. Token markets may then remain shallow even when lending liquidity is abundant.

Applying comparable reductions can reduce this distortion. Participants can choose according to genuine preferences and risk tolerance rather than differences in network treatment.

The network may still want especially deep token exchange liquidity because of its importance to hosted asset markets. Any additional incentive should be designed so that fake pairings and artificial volume cannot obtain it cheaply.

The objective is not to force all network coins into one protocol. It is to maintain sufficient liquidity across the most useful functions without unnecessarily fragmenting the supply.



**Liquidity positions as collateral**

A token exchange liquidity position could potentially serve as collateral for borrowing.

The value of the collateral can be based partly on the amount of network coin recoverable from the position. If liquidation becomes necessary, the paired token can be exchanged and the resulting network coins used to settle the obligation.

This allows one position to support token exchange while also enabling additional financial activity.

However, changes in relative prices can reduce the number of network coins recoverable from the pairing. Market depth may also be insufficient to sell the paired asset without substantial slippage.

A borrower therefore cannot safely use the full nominal value of the liquidity position. The protocol would require:

* Conservative collateral limits
* Adequate market depth
* Liquidation margins
* Reliable valuation of the underlying position
* Protection against manipulated or illiquid token markets

If a network can incentivise a more productive usage of the network coin it is incentivised to implement that solution. This might involve using the network coin in multiple use cases such as collateral for general contract use and within multiple financial protocols like token exchange and single-asset lending and borrowing.



## **Multi-asset lending and borrowing**

A multi-asset lending protocol allows users to deposit one asset and borrow another.

This gives participants access to liquidity without selling their original holdings. A user can retain exposure to the network coin while borrowing a stablecoin or another token.

The difficulty is valuation. The protocol must determine the relative prices of the collateral and borrowed asset so it can liquidate a position before the collateral becomes insufficient.

Tokens may trade on several networks and exchanges at different prices. Lending protocols commonly rely on oracles to aggregate this information.

Oracle failure or manipulation can:

* Trigger incorrect liquidations
* Prevent necessary liquidations
* Overvalue collateral
* Allow borrowers to withdraw more network coins than their collateral is worth
* Create losses for lenders

These risks may be acceptable for participants who voluntarily use an application. They are less suitable as dependencies within the core network’s economic design.

The network coin can still be used by multi-asset lending applications without receiving special treatment. Because of its complexity and reliance on external information, multi-asset lending is less compelling as a target for network-level charge reductions than single-asset lending.



## **Stablecoin collateral**

The network coin can be locked as collateral for issuing a stablecoin.

This creates demand because participants must acquire and deposit the coin before minting the stable asset.

However, the network would need to determine which stablecoin systems qualify for a demurrage reduction. Without restrictions, participants could create a token, deposit their network coins and retain the entire resulting stablecoin supply themselves.

The coins would appear to support a financial application without necessarily providing useful liquidity or monetary activity.

Maintaining an approved list introduces governance complexity. The network would need to evaluate:

* Collateral requirements
* Price oracles
* Liquidation mechanisms
* Governance arrangements
* Redemption processes
* The reliability and adoption of each stablecoin

Stablecoin collateral also locks network coins that might otherwise be available for fees, exchange or lending.

Collateralised stablecoins can be valuable applications, but they do not need privileged treatment at the network level. Their relationship to network access is less direct than token exchange or single-asset lending.



## **Collateralised debt positions**

Collateralised debt position protocols allow users to lock assets in return for newly created tokens or credit.

The network coin could serve as collateral, creating longer-term demand. However, the same qualification problem arises as with stablecoins.

Participants can create assets with little genuine use merely to obtain the charge reduction. The newly created tokens are not guaranteed to circulate or support productive activity.

The network coins may also become unavailable for fees, token exchange or lending.

These protocols can operate voluntarily without receiving a network-level incentive. Their usefulness should be demonstrated through user demand rather than assumed by the core protocol.



## **Derivatives**

Derivative protocols allow participants to gain or hedge exposure to asset-price movements through futures, options and perpetual arrangements.

The network coin may be used as margin or collateral, creating demand for it. However, derivatives are not essential to the basic operation of a digital-asset network.

Many tokens and stable assets can provide collateral for these markets. The network does not need to privilege the native coin in every financial application.

Derivative positions can also introduce:

* Leverage
* Liquidation risk
* Oracle dependencies
* Market manipulation risks
* Contagion between financial protocols

These risks are more appropriately managed at the application level

Participants remain free to use the network coin in derivative protocols, but derivatives are less compelling as a target for protocol-level charge reductions.



## **Synthetic assets**

Synthetic-asset protocols use collateral to replicate the value of stocks, commodities and other assets.

The network coin can be locked to support these positions. This may increase measured demand, but it can also reduce the amount available to network users.

Synthetic assets depend on external price information and liquidation systems. Oracle or market failures can place deposited collateral at risk.

As with derivatives, these applications can use the network coin without receiving special incentives. Their role is less directly connected to the core objective of creating efficient markets for assets already hosted on the network.



## **Concentrating financial incentives**

A network-level incentive should be reserved for uses that provide clear benefits to the whole ecosystem.

Token exchange liquidity improves the markets through which hosted assets are exchanged. Single-asset lending makes the native coin available without requiring lenders to accept direct exposure to another token or requiring the protocol to compare external asset prices.

These functions are complementary and closely aligned with network access.

Stablecoins, collateralised debt positions, derivatives, synthetic assets and multi-asset lending may all be useful applications. However, spreading charge reductions across them can divide the supply and make every market shallower.

A focused incentive structure is:

* Easier to govern
* Easier for participants to understand
* Easier to evaluate
* Less likely to fragment liquidity
* Less dependent on approved application lists and external oracles
* More likely to create a strong network effect around a small number of important markets



## **Implementation considerations**

Even the most compelling options require careful implementation.

**Qualification rules**

The network must identify eligible positions without treating every contract deposit as productive activity.

Possible considerations include:

* Whether users can actually exchange or borrow the deposited coins
* The duration of the commitment
* The depth and accessibility of the liquidity
* Whether control is distributed among independent participants
* Whether a position serves genuine third-party demand
* Whether the application can prevent immediate withdrawal after receiving the reduction

No individual measure is manipulation-proof. Qualification may need several conditions and periodic review.



**Lock-up periods**

Longer commitments provide more durable liquidity and stronger evidence of sustained demand.

However, rigid lock-ups increase participant risk and may make the coin less available during changing market conditions. The network may instead use graduated reductions, with longer commitments receiving somewhat greater benefits.

Any difference must remain small enough to avoid encouraging artificial lock-ups that provide little practical availability.



**Protocol neutrality**

The network should ideally recognise a function rather than permanently favouring one application.

For example, eligibility could depend on providing accessible single-asset lending rather than using a particular named lending protocol.

Functional rules make competition possible while reducing dependence on an approved provider. However, they are more difficult to verify and may expand the network’s technical responsibilities.



**Predictability**

Participants need to understand the likely value of the charge reduction before committing coins.

Frequent changes can destabilise liquidity and cause participants to move between protocols in response to each adjustment.

A relatively stable incentive structure with infrequent, well-signalled changes is more predictable than a continuously changing system.



**Monitoring results**

The network should examine whether incentives produce genuine benefits rather than relying only on nominal deposits.

Relevant indicators may include:

* Liquidity depth
* Duration of deposits
* Distribution among providers
* Borrowing utilisation
* Withdrawal reliability
* Slippage for ordinary exchanges
* The proportion of supply committed over longer periods
* Dependence on a small number of protocols or participants

Raw transaction counts and volume should remain supporting information because both can be manipulated.



## Most compelling liquidity incentive mechanisms

The purpose of a financial liquidity incentive is not simply to lock network coins. It is to create longer-term demand while making the coin and network more useful.

The strongest options are token exchange liquidity and single-asset lending.

Token exchange liquidity:

* Improves markets for hosted tokens
* Reduces slippage and liquidity fragmentation
* Makes the network coin easier to acquire
* Supports the coin as a common market pairing
* Creates a strong liquidity-based network effect
* Incentivises participants to accept exposure to another trusted fungible asset

Single-asset lending:

* Makes network coins available to borrowers
* Does not require lenders to pair the coin with another asset
* Mechanism doesn’t rely on external price oracles
* Provides an alternative for holders unwilling to accept token-pairing liquidity risks

Multi-asset lending, stablecoins, collateralised debt positions, derivatives and synthetic assets may all use the network coin voluntarily. However, they are less compelling targets for network-level incentives because they introduce greater complexity, external dependencies, qualification problems or weaker ecosystem benefits.

A focused incentive structure can direct longer-term demand towards functions that make the coin more available, improve token markets and strengthen financial network effects without unnecessarily fragmenting liquidity.
