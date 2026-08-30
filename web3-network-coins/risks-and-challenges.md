# Risks and challenges

Demurrage introduces a number of risks as well as opportunities. A poorly designed carrying charge can reduce demand, discourage early investment, create avoidance behaviour and increase the power of the treasury.

The programmable nature of Web3 makes demurrage easier to implement consistently, but it also makes it easier for users to move immediately into alternative assets. A network cannot assume that participants will continue holding a charged coin when uncharged tokens and competing networks are readily available.

The rate, exemptions, productive-use reductions and treasury process therefore require careful design. Some risks can be reduced, but not every challenge has a proven solution.



## **Difficulty attracting initial capital**

Early-stage Web3 networks compete for capital, developers, applications and liquidity.

Investors may prefer a storable coin because they can retain the entire nominal balance while benefiting from potential appreciation and staking rewards.

A network imposing demurrage from launch may appear less attractive, particularly when few productive uses exist. Holders pay the charge without having access to mature exchange, lending or collateral protocols.

This can worsen the usual early-network coordination problem. Developers may not build without users, while users may not join without applications.

One response is to delay demurrage during the genesis phase or introduce it at a very low initial rate. The genesis allocation can fund early development while investment demand supports the coin’s value.

The charge can increase gradually as applications, liquidity and productive uses become available.

This approach reduces the initial barrier but allows early ownership concentration to develop. The initial allocation and staking policy must therefore account for the possibility that large early holders retain substantial long-term influence.



## **Reduced demand and persistent sell pressure**

A network coin charge encourages holders to exchange the coin for assets without the same cost.

Node operators, treasury recipients and users receiving the coin may sell it immediately. Wallets can automate this conversion.

Persistent selling can suppress the price and weaken confidence. Lower value then affects node compensation, consensus security and treasury purchasing power.

Productive-use reductions can create longer-term demand, but they must compensate for demurrage and the risks of participating.

If the network has little utility or weak financial markets, incentives may be insufficient. A high carrying charge cannot substitute for genuine demand.

The network must be prepared to reduce the rate when evidence shows that it is undermining the coin’s operational role.



## **Too much demand can remain possible**

Demurrage does not guarantee that storage will become unattractive.

If the coin appreciates faster than the carrying charge, holders may continue receiving a positive return from inactivity. Staking and lending yields can increase that return.

A network experiencing rapid adoption may therefore retain the concentration problems associated with storable money even after introducing demurrage.

The charge can be increased, but frequent adjustments reduce predictability. Expanding the supply may moderate appreciation but introduces dilution and governance complexity.

The network must evaluate the net return from holding rather than assuming that any positive demurrage rate is sufficient.



## **Sustaining a rate above low-risk yields**

A mature dispersion policy may require the effective carrying charge to exceed the return available from low-risk staking and lending.

Maintaining this relationship is difficult. Financial yields change with borrowing demand, transaction activity and market conditions.

If yields rise temporarily, increasing the demurrage rate immediately may be unnecessary and destabilising. If yields remain higher for long periods, large balances can continue growing.

The network must decide which activities qualify as low risk and how their returns should be measured. Different protocols offer different risks, and advertised yields do not always reflect losses, illiquidity or smart-contract exposure.

A moving average across established activities may provide context, but any automatic formula can be manipulated.

The relationship between demurrage and yield might therefore be more suitable as a governance consideration than as a simple mechanical rule.



## **Competition from lower-charge networks**

Web3 software is commonly open source. A competing community can copy much of a successful network and launch a version with a lower carrying charge.

Individual holders may prefer the cheaper network because they retain more of their coin balance.

This competitive pressure may make it difficult to sustain demurrage above the minimum required for operation, especially after the original network has matured and its technical development costs have declined.

Network effects provide one response. Deep liquidity, applications, users and trusted infrastructure cannot be reproduced as quickly as software.

The original network can also justify the charge by using treasury income effectively. Participants may accept a higher cost when it produces better security, lower transaction fees and useful public infrastructure.

However, network effects should not be treated as permanent protection. Interoperability and automated wallets can reduce migration costs.

The sustainable rate is constrained by the value users receive relative to competing networks.



## **Difficulty distinguishing productive use**

Reduced rates require the network to determine which positions provide genuine value.

A user may create an unused token, pair it with network coins and claim a liquidity reduction. They may generate artificial transactions to make the market appear active.

A smart contract may claim to provide collateral while allowing the owner to withdraw coins immediately. A lending protocol may display a large deposit even though no borrower can practically access it.

The network can impose qualification rules, lock-up periods and recognised protocol lists, but these introduce governance complexity and favour established applications.

Overly broad incentives are easy to exploit. Overly narrow incentives centralise decision-making and may exclude valuable new protocols.

The safest approach is to support a small number of functions with clearly observable benefits, but even these require continuing evaluation.



## **Avoidance through wrappers and contracts**

If the carrying charge does not apply consistently, users will structure holdings to avoid it.

Coins can be deposited into contracts, represented through derivative claims or moved between wallets. A participant may retain the economic benefit of ownership without appearing to hold the underlying balance directly.

Applying demurrage to the underlying coins prevents many simple forms of avoidance. A wrapper can transfer the cost to the claim holders, but it cannot eliminate the charge on the deposited balance.

Problems remain when exemptions and reduced rates exist. Participants may design contracts that satisfy the technical requirements without performing the intended economic function.

Every exception creates a potential avoidance route. The implementation should therefore favour reductions based on measurable contribution where possible rather than categorical exemptions.



## **Technical complexity**

A recurring network-wide balance charge affects wallets, smart contracts, exchanges, lending protocols and accounting systems.

Applications need to understand how balances change over time. A contract expecting to hold a fixed number of coins may become underfunded if it does not account for demurrage.

Continuous updates to every balance could also create substantial computation and storage requirements. Lazy calculation at the time of access can reduce this burden but makes implementation more complex.

Rounding becomes significant for very small balances. The protocol must ensure that repeated calculations do not create inconsistent results or unfairly consume small holdings.

Any defect in the native coin’s accounting can affect the entire network. The mechanism therefore requires extensive testing and a simple, auditable formula.



## **Smart-contract compatibility**

Existing contracts may assume that a deposited coin balance remains nominally unchanged unless a transaction occurs.

Demurrage breaks this assumption. Collateral, liquidity and escrow positions need to account for the gradual charge.

If demurrage is introduced after a network has already developed a large application ecosystem, some contracts may become incompatible or insolvent.

This creates a strong argument for defining the mechanism early, even if the initial rate is zero or very low. Applications can then be designed around the possibility of later activation.

A mature network introducing demurrage retrospectively would need a careful migration process and sufficient notice.



## **Treasury accumulation**

Transferring collected coins to the treasury preserves the total supply, but the treasury may become one of the largest holders.

If expenditure remains below income, an increasing proportion of the supply moves into a collectively governed account. This reduces circulation and concentrates economic power.

The treasury should therefore operate under a spending or allocation process capable of returning income to the ecosystem.

Reducing the rate is preferable to collecting coins that cannot be used effectively.

Treasury balances may still need reserves for emergencies and long-term commitments. The objective is not to spend immediately without planning, but to avoid indefinite accumulation without a defined purpose.



## **Treasury capture**

A large recurring treasury creates an incentive to manipulate governance and funding decisions.

Participants may purchase voting power, coordinate delegations or create projects designed primarily to extract funding.

If the same organisation receives repeated grants, it can accumulate coins and increase its influence over future decisions. This can create a self-reinforcing cycle of funding and control.

Founding entities may initially moderate the process, but permanent control by founders conflicts with decentralisation.

Funding can be released gradually against milestones, and payments can be made directly to contributors and suppliers rather than through unnecessary large lump sums.

These measures reduce risk but do not eliminate political competition over treasury resources.



## **Funding-process effectiveness**

Demurrage income is only advantageous when the treasury uses it effectively.

A high rate combined with poor expenditure imposes a cost on holders without producing corresponding value. Users and capital may move to another network.

Evaluating impact is difficult. Infrastructure and research may provide benefits that appear only after several years, while short-term market growth may reflect unrelated speculation.

The funding process needs transparent objectives and methods for reviewing completed work. It should also be able to stop initiatives that fail to deliver.

The sustainable demurrage rate is partly limited by the treasury’s demonstrated capacity to allocate income.



## **Governance of the demurrage rate**

The rate affects every holder and application, so control over it represents substantial economic power.

Large holders are likely to prefer lower rates, while treasury recipients may support higher rates. Node operators may favour enough income to guarantee compensation, and active users may prefer lower transaction fees funded through the charge.

An automated rule avoids some political discretion but requires reliable data. Manipulated inputs can cause inappropriate changes.

Community voting provides legitimacy but may be captured by concentrated coin ownership. Delegating the decision to a committee creates expertise but centralises authority.

Rate limits, advance notice and gradual implementation can reduce the consequences of a poor decision. They do not resolve the underlying question of who should control the policy.



## **Rate volatility**

Frequent rate changes make the coin difficult to use in long-term agreements.

A lender, borrower or collateral provider needs to estimate the future balance after demurrage. Unexpected increases can change the economics of an existing position.

Participants may also speculate around governance decisions, buying before expected reductions or selling before increases.

The rate should therefore respond to persistent conditions rather than short-term market movements.

A stable range with infrequent adjustments is more compatible with a predictable global asset than a continuously changing rate.



## **Unequal practical access to reductions**

The base percentage may be formally equal while users have unequal ability to reduce it.

Wealthier and more technically sophisticated participants can access staking, liquidity and lending protocols. Small holders may leave coins in ordinary wallets because the available yield does not justify transaction costs or complexity.

If productive positions receive substantial reductions, ordinary users may pay a higher effective rate than institutions managing large balances.

Wallets can help by simplifying access, such as by making single-asset lending an easy to use option.



## **Liquidity lock-up risk**

Lock-up periods create durable demand and strengthen network effects, but they reduce flexibility.

Participants cannot withdraw coins quickly during market stress. They may experience losses or be unable to meet other obligations.

Large unlock events can also create delayed volatility. If many positions expire at the same time, substantial selling may occur.

Lock-up schedules should be distributed rather than concentrated around a few dates. Users should also understand the conditions before committing their coins.

The network should not treat reduced liquidity as an advantage in every circumstance. Availability for transaction use remains one of the principal goals.



## **Price and supply interactions**

Demurrage can interact with fixed, expansionary and contractionary supply policies in unexpected ways.

Under a fixed supply, strong growth may produce appreciation that offsets the charge. Under expansion, users may experience both dilution and demurrage. Under contraction, scarcity can strengthen storage incentives.

The network may respond by adjusting several parameters at once, making it difficult to determine which change produced an outcome.

Beginning with a fixed supply and conservative carrying charge reduces the number of interacting variables.

Any later supply change should be introduced separately and evaluated over a sufficiently long period.



## **Public understanding and acceptance**

Demurrage is unfamiliar to most users. People are accustomed to seeing the same nominal balance remain in an account unless they spend it.

A balance that declines automatically may be perceived as confiscation or a technical defect, even when its purchasing power remains stable.

The term “tax” may also create resistance, particularly when no government administers the network.

Clear wallet interfaces are essential. Users should be able to see the annual rate, the amount charged and the destination of the collected coins.

They also need to understand the distinction between demurrage and inflation. The number of units may decline even when each unit retains purchasing power.

Education cannot overcome an implementation that provides little value. Acceptance ultimately depends on whether users experience reliable operation, low fees and useful treasury expenditure.



## **Business acceptance**

Businesses may hesitate to accept a coin that incurs an ongoing charge.

They need to account for demurrage when pricing goods, managing working capital and holding revenue.

Automated conversion can reduce exposure. A business can accept the coin and exchange it for a preferred token or asset immediately.

This flexibility also limits long-term demand for the network coin. If every recipient converts at once, the price may remain under pressure.

The coin does not need to become the primary business medium of exchange. Tokens can perform that role while the network coin remains focused on infrastructure, liquidity and collateral.



## **Regulatory and accounting uncertainty**

A recurring network-level charge may be treated differently across jurisdictions.

Authorities may view it as a tax, protocol fee, transfer or reduction in asset quantity. The classification can affect accounting and legal obligations.

Different countries may also restrict particular financial incentives or require service providers to identify users.

The network protocol may remain permissionless, but wallets, exchanges and businesses can face local requirements.

Regulatory variation creates costs and can influence where liquidity and node operation are located.



## **Experimental uncertainty**

There have been relatively few large-scale demurrage systems, and none provide complete evidence for a globally adopted programmable network coin.

User behaviour may differ from theoretical expectations. Automated trading, token competition and cross-network interoperability can produce effects not present in earlier monetary experiments.

The network should introduce the mechanism gradually, publish data and remain capable of reducing or modifying the rate.

A conservative and reversible progression is safer than assuming the final design is known before substantial real-world use.
