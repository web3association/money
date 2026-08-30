# Division of responsibilities

A Web3 network can contain a native network coin and many user-created tokens. Although both can be fungible and transferable, they exist at different levels of the system.

The network coin is integrated into the protocol and can be connected to transaction processing, node compensation, consensus and network governance. Tokens operate on top of the protocol and can be designed for particular applications, assets and communities.

This distinction helps determine where different responsibilities should be placed. Functions essential to the survival of the entire network generally benefit from being assigned to the native coin and governed as simply as possible. Functions requiring experimentation or community-specific rules are generally more suitable for tokens.

Some responsibilities can be shared. Both network coins and tokens can preserve value, provide financial liquidity and act as collateral. The appropriate division depends on the scale of the responsibility, the consequences of failure and the amount of flexibility required.



## **Network operation**

Web3 networks require people or organisations to operate nodes. Node operators supply the hardware, storage, connectivity and ongoing technical work needed to verify transactions and maintain the distributed ledger.

The network must provide an incentive for enough independent operators to participate. If compensation is inadequate or unreliable, operators may stop maintaining their nodes, potentially weakening the availability and security of the network.

A network coin is purpose-built for this responsibility. Users or transaction sponsors create demand for the coin when they pay for network resources, and operators receive the coin as compensation for providing those resources.

This creates a circular relationship between network use and network operation. Demand for the network produces demand for the coin, while the coin funds the infrastructure needed to satisfy that demand.

Tokens are less suitable as the primary mechanism for node compensation. Their supply, value and governance may be controlled by separate communities whose interests do not necessarily align with the security of the network.

If node operators accepted many different tokens, the protocol would need a method for determining which tokens were valid and how much of each token represented adequate payment. The value of those tokens could change independently, and a token’s governing community could modify its supply or transfer rules.

A token could also collapse or be manipulated. If the network continued accepting it at an outdated value, a participant might use the token to obtain network resources cheaply or submit a large amount of unwanted activity.

Maintaining a protocol-level list of acceptable tokens would require continuing governance. The network would need to evaluate each token’s reliability, liquidity, monetary policy and security.

Allowing each node operator to choose which tokens to accept would create a different problem. Users might need to determine which nodes accepted a particular asset, while operators would need to set their own exchange rates. This would fragment transaction processing and complicate consensus.

A single native coin provides a common unit for compensating operators and pricing network resources. Operators remain free to exchange the coin for another asset after receiving it, and users can obtain the coin through wallet-level or application-level exchange mechanisms.

The core protocol therefore does not need to accept many independently governed tokens as direct substitutes for its native coin.



## **Paying for network usage**

Paying for network usage is closely connected to node compensation. A transaction consumes computation, storage, bandwidth and validation capacity, so the network needs a mechanism for allocating these resources.

Transaction fees are the most common mechanism. The user pays a quantity of the network coin when submitting a transaction, and some or all of that payment is directed towards node operators or the network treasury.

The fee also helps protect the network against transaction spam. If submitting transactions were entirely costless and no alternative restriction existed, a participant could attempt to consume large amounts of network capacity.

Using the native coin creates a consistent relationship between network resources and payment. The protocol does not need to assess the governance or reliability of every token created on the network.

This does not mean users must manually obtain and manage the network coin for every transaction. A wallet or application could exchange another asset into the required coin in the background. A separate participant could also sponsor a user’s transaction.

The underlying settlement can still occur in the network coin even when the user experiences the payment as occurring through another token.

The network benefits from keeping transaction fees as low as possible. Higher fees discourage valid activity and make competing networks more attractive. However, fees must remain sufficient to support node operation or prevent excessive resource consumption unless another source of network income performs those functions.



## **Network governance**

Web3 networks may need continuing decisions about protocol upgrades, technical parameters and treasury expenditure.

Governance is especially important when the network becomes widely used. Poor decisions can weaken security, make applications incompatible or create uncertainty about the network’s future rules.

The network coin can contribute to governance because it provides evidence of economic participation in the network. Coin holders, stakers and people paying fees or taxes have resources exposed to the consequences of network decisions.

Coin holdings or coin-based contributions can therefore be used to influence voting power. However, each approach involves trade-offs.

Governance based only on current holdings gives greater influence to participants who own more coins. This can help protect the network against large numbers of fake identities, but it may also concentrate decision-making power among wealthy holders.

Governance based on fees or taxes paid can recognise ongoing contribution rather than ownership alone. It may, however, favour participants who transact frequently or operate large businesses.

A one-person, one-vote system avoids directly connecting influence to wealth, but permissionless networks have difficulty establishing that each participant represents one distinct person. A single individual may create many wallets and appear to be many voters. This is commonly known as a Sybil attack.

No single method removes every governance problem. The important structural point is that network-level decisions should be handled through mechanisms connected to the network as a whole.

Tokens do not need to govern the underlying network. Each token can have its own governance process for decisions about its supply, transfer rules, treasury and intended use.

A community token might use one-person, one-vote governance if it has a reliable identity system. Another might base voting power on token holdings, contributions or membership. A token might also have fixed rules that require little or no continuing governance.

Separating token governance from network governance prevents every token community from becoming directly involved in maintaining the core protocol. Token communities can experiment with different arrangements without changing the rules used by every other application.



## **Monetary policy**

The network coin and tokens can both have monetary policies governing how their supply changes and whether holding balances incurs a cost.

However, the network coin’s policy affects the entire system. A change in supply can influence node compensation, network security, transaction fees, governance and the value of financial positions across the ecosystem.

This systemic importance limits the amount of experimentation that is appropriate at the network level. The coin’s policy should be predictable, robust and understandable to a global population of users and operators.

Tokens have more freedom because their monetary policies apply primarily to their own holders and communities. A token can use a fixed, expansionary, contractionary or elastic supply without requiring the underlying network to adopt the same approach.

A token community can also implement a carrying charge or token tax to simulate demurrage. If the policy fails, users can move to another token while continuing to use the same network.

The possibility of failure remains economically important for token holders, but it does not necessarily compromise transaction processing across the underlying network.



## **Medium of exchange**

Both network coins and fungible tokens can be accepted as payment for goods and services. However, the technical ability to transfer an asset does not automatically make it an effective medium of exchange.

A medium of exchange benefits from broad acceptance, sufficient liquidity and reasonably predictable purchasing power. People must be confident that they can receive the asset and later use it in another transaction.

National fiat currencies achieve acceptance partly through established financial infrastructure, taxation and legal-tender rules. Web3 networks create an environment in which users can also choose from multiple transferable digital assets.

This raises a central design question: should one globally adopted asset become the primary medium of exchange, or should multiple forms of money coexist?



## **The limitations of one global medium of exchange**

A single global medium of exchange may initially appear attractive. Users would not need to convert currencies when trading across communities, and prices could be expressed through a common unit.

However, a single global monetary system would create substantial governance complexity. Decisions about supply and other monetary parameters would affect a large and diverse population.

Different regions and communities can experience different economic conditions. One economy may be growing rapidly while another is contracting. A single supply policy cannot respond independently to both.

A supply increase intended to support one region could contribute to rising prices elsewhere. A contraction intended to restrain prices in one economy could worsen unemployment and falling demand in another.

A global currency would also create a significant point of dependence. If its governance or monetary mechanisms failed, every community relying on it as the principal medium of exchange would be affected.

Different communities may also want incompatible monetary properties. A country, city, online community and digital game may have different preferences concerning supply, governance, stability and demurrage.

A single implementation would struggle to satisfy every requirement while remaining simple enough to operate reliably.

Multiple monetary systems allow these responsibilities to be distributed. If one form of money fails, another can replace it. Communities can choose policies suited to their circumstances rather than depending on a single global decision process.



## **The network coin as a medium of exchange**

A widely adopted network coin may naturally be accepted as payment. Users recognise it, exchanges support it and participants need it for network activity.

These characteristics give it an advantage over newly created tokens. However, the network coin does not need to become the primary medium of exchange for all goods and services.

If it assumed that responsibility, the coin would face pressure to maintain stable purchasing power across the global economy. Its supply policy would need to respond to changes in demand arising from many countries, applications and financial markets.

This would add complexity to an asset already responsible for supporting the network’s operation. Changes intended to improve its performance as money could affect node compensation, consensus or governance.

The network coin is a mission-critical component. Its core policy benefits from simplicity, predictability and resistance to manipulation. Assigning it responsibility for managing the monetary conditions of every community would create unnecessary risk.

It can still be used as payment when participants choose to accept it. The distinction is that it does not need to be designed or governed as the sole global medium of exchange.



## **Tokens as mediums of exchange**

Tokens are more suitable for creating community-specific monetary systems.

A country could issue token-based money and govern it according to national economic conditions. A town, online community or digital game could create a different token reflecting its own requirements.

The token’s supply and other monetary rules could be adapted without changing the underlying network coin. Governance can occur at the scale of the community rather than across the network’s entire global population.

This does not guarantee that token money will be stable or well governed. A token may lose acceptance, experience excessive supply changes or become controlled by a small group.

However, the failure of one token creates an opportunity for another to emerge. The underlying network can continue supporting exchange while users migrate between monetary systems.

Tokens therefore create an open and competitive environment for mediums of exchange. Different implementations can coexist, and users can decide which assets they are willing to accept.



## **Store of value**

Both the network coin and tokens can function as stores of value. Their effectiveness depends on their ability to preserve purchasing power and maintain demand over time.

The network coin may be attractive because it is connected to the continuing use of the network. If the network remains widely adopted, demand for transaction processing and other protocol functions can support demand for the coin.

This can make the network coin a relatively prominent asset within its ecosystem. It may also make excessive storage more likely, particularly if holders expect continuing price appreciation or receive low-risk returns from staking and financial protocols.

A token can also preserve value. A stablecoin may track a fiat currency, a commodity-backed token may represent a claim on a physical asset and a community currency may use its own supply policy.

Tokens face more direct competition. A user can move into another token if it offers more desirable monetary properties or stronger backing.

Demurrage can be applied to either type of asset to discourage prolonged idle retention. The monetary unit can preserve meaningful purchasing power while the balance incurs a carrying cost.

For the network coin, preventing excessive concentration may be particularly important because large holders may influence consensus or governance. At the same time, the coin needs enough demand and value to maintain network security.

The network must therefore balance value preservation against low-cost storability. The coin should remain desirable enough to support operation and security but not so easy to accumulate that ownership and influence continuously concentrate.

Tokens can adopt different balances according to the needs of their communities. One token may prioritise stable purchasing power, another may impose stronger demurrage and another may remain highly storable.

The network provides the infrastructure within which these different policies compete.



## **Financial liquidity**

Financial liquidity refers to the availability of assets for exchange, lending and borrowing. Deep liquidity allows participants to trade larger amounts with less effect on market prices.

Both network coins and tokens can provide financial liquidity. They can be deposited in exchange protocols, lent to borrowers or used as collateral.

A digital asset network benefits from efficient markets. Users are more likely to create, hold and exchange assets on a network when they can move between those assets quickly and at low cost.

Liquidity becomes fragmented when every token needs a separate direct market against every other token. If a network contains a large number of tokens, the possible number of pairings becomes difficult to support with deep liquidity.

A common intermediary asset can reduce this fragmentation. Instead of maintaining a deep direct market between every pair of tokens, each token can be paired with the common asset.

A user exchanging one token for another can first move into the common asset and then into the desired token.



## **The network coin as global exchange liquidity**

The network coin is a natural candidate for becoming a prominent liquidity pairing. It is already recognised across the network and has continuing demand through network usage.

If many tokens maintain markets against the network coin, liquidity can become concentrated into a smaller number of useful pairings. This can reduce slippage and make token exchange more efficient.

The network coin’s protocol-level position may also make it more predictable than an individual token. It cannot be abandoned without affecting the network itself, while an application-specific token can be replaced more easily.

This does not mean the network coin must become the only liquidity asset. Stablecoins and other widely adopted tokens may also provide deep markets. The objective is to avoid unnecessary fragmentation rather than prohibit alternative pairings.

Using the network coin as a common liquidity asset creates additional demand and gives idle coins a productive use. However, it can also make the wider financial system more dependent on the coin’s reliability.

If many tokens are paired primarily against the network coin, rapid changes in its value can require markets to rebalance and may produce losses for liquidity providers. The network coin therefore benefits from some degree of price stability even if it is not the principal medium of exchange.



## **Tokens as local financial liquidity**

Token-based money can perform a similar function within a particular community.

A national or local token might be paired with assets most relevant to that economy. An online-game currency could provide liquidity for items and services used within the game.

These local markets do not need to depend exclusively on the network coin. Community tokens can provide a unit of exchange and liquidity suited to their own applications.

The network coin can facilitate exchange across the wider ecosystem, while tokens support deeper local markets. The two roles are complementary rather than mutually exclusive.



## **Contract collateral**

Collateral is an asset committed to an agreement as protection against non-performance. If a participant breaks the agreement, some or all of the collateral may be transferred or removed according to the applicable rules.

Web3 networks can use smart contracts to hold and manage collateral. This can increase confidence between participants who do not know or fully trust one another.

For example, Alice and Bob may enter an agreement involving the sale of a good or the provision of a service. One or both parties can place collateral into a smart contract. If the agreement is completed, the collateral is returned. If a dispute occurs, it may be used as compensation after the relevant conditions or mediation process has been applied.

Collateral can also support participation in digital applications. A platform may require users to place value at risk before performing actions that could harm other participants. The possibility of losing collateral creates a financial deterrent against misconduct.

This can be particularly useful in a permissionless environment where the legal identity or history of a participant is not fully known.



## **The network coin as contract collateral**

The network coin is a strong candidate for collateral because it is widely recognised within the network and has continuing protocol-level demand.

Using it as collateral creates an additional source of long-term demand. It also gives holders a productive use for coins that might otherwise remain idle.

The same network coins might support more than one function. A financial position containing the network coin could potentially provide exchange liquidity while also serving as evidence of collateral for another agreement, depending on the design and risk controls.

The network must avoid over-incentivising collateral use to the point that large amounts of the coin become inaccessible. Users still need the coin for network activity, and excessive lock-up could reduce its availability.

Collateral incentives should therefore support productive use without encouraging a small number of participants to control an excessive share of the coin.



## **Tokens as contract collateral**

Tokens can also be used as collateral. Their suitability depends on their liquidity, stability, governance and expected demand.

A stable token may be useful when the agreement requires predictable purchasing power. A token representing a specific asset may be appropriate when that asset is directly connected to the contract.

Tokens can complement the network coin when collateral requirements exceed the amount of native coin participants are willing or able to commit.

Using tokens can also reduce pressure to accumulate the network coin solely for collateral purposes. This helps preserve its availability for transaction fees and other network-level responsibilities.

However, token collateral introduces additional risks. A token may lose value, its smart contract may fail or its governing community may change its rules. Agreements accepting token collateral must account for those possibilities.



## **Responsibility and the consequences of failure**

The appropriate division of responsibilities depends partly on what happens when an asset or mechanism fails.

A failure involving network operation, consensus or node compensation can affect every application. These responsibilities should therefore be handled through assets and rules governed at the network level.

A failure involving a community medium of exchange may be serious for that community, but it does not necessarily need to compromise the shared ledger. Tokens allow this monetary risk to remain separated from the underlying infrastructure.

Financial liquidity and collateral lie between these two levels. Both the network coin and tokens can perform these functions, but the risk created by each asset must be understood.

The network coin offers broad recognition and protocol-level demand, while tokens offer flexibility and context-specific design.

This produces a general division of responsibilities. The network coin is most directly suited to paying for and supporting network operation, and it may contribute to network governance. Tokens are more suited to community-specific mediums of exchange and monetary policies. Both can preserve value, provide liquidity and act as collateral, although the network coin may serve as a common liquidity asset across the wider ecosystem.

This division allows the underlying network to remain relatively simple while supporting monetary and financial experimentation above it.
