# Demurrage implementation approaches

Demurrage can be implemented in several ways within a Web3 network. Each approach attempts to increase the cost of leaving the network coin idle, but they differ in how directly they impose that cost and how they affect users, applications, the coin supply and the network treasury.

The principal approaches considered here are coin expiry, incentives for active use and a periodic charge on network coin balances.

A suitable implementation should be predictable, difficult to avoid and simple enough to operate as part of a mission-critical network. It should apply consistently across wallets and smart contracts, preserve the fungibility of the coin and avoid creating unnecessary complexity for ordinary transactions.

The implementation must also determine what happens to any coins collected. They could be removed from supply or transferred to a network treasury and returned to circulation through node compensation, development funding and other expenditure.



## **Coin expiry**

A coin-expiry system would make network coins unusable after a specified date or period. Holders would therefore need to spend or exchange them before they expired.

Although this creates a strong incentive against indefinite storage, it would undermine fungibility. Coins with different expiry dates would not be economically equivalent: a coin expiring tomorrow would be less useful than one valid for another year. Participants might reject coins near expiry or accept them only at a discount.

Wallets, exchanges and smart contracts would also need to track different coin vintages. Lending, collateral and liquidity protocols would have to account for balances that could expire while held in a contract. Long-term agreements would become more difficult because a nominal quantity of coins might not remain usable for the duration of the agreement.

Expiry could also concentrate activity around fixed deadlines. Holders would attempt to dispose of coins as expiry approached, while recipients would become increasingly reluctant to accept them. This could produce periodic transaction surges and unstable pricing rather than continuous circulation.

Allowing holders to renew expiring coins for a charge would reduce these problems, but would effectively recreate periodic demurrage through a more complicated process. Automatic renewal would resemble a direct balance charge, while manual renewal would impose unnecessary administrative work.

Coin expiry therefore adds substantial complexity while weakening the coin’s usefulness as a common unit of exchange, liquidity and collateral. A gradual charge on balances can impose a carrying cost without creating multiple time-dependent classes of coin.



## **Incentivised activity**

Instead of charging idle balances, the network could reward participants for transactions, consensus participation, liquidity provision or other productive uses.

These incentives may support useful network functions, but they do not directly make idle storage costly. A holder can ignore the available rewards and retain the full nominal balance. The effect is therefore an opportunity cost rather than demurrage.

Rewards also require funding. They must come from new issuance, transaction fees or treasury reserves. New issuance dilutes holders, fee-funded rewards place costs on active users, and fixed treasury allocations are eventually depleted.

Activity related rewards can also encourage manipulation. Participants may transfer coins between wallets, create artificial transaction volume or establish unused liquidity positions solely to qualify for payments. Preventing this requires additional eligibility rules, monitoring and governance.

More targeted incentives, such as benefits for consensus participation or supplying established liquidity markets, may be harder to manipulate and can complement demurrage. However, the network must still decide which activities qualify and how their contribution should be measured.

Incentivised activity is therefore better used as a supporting mechanism than as the primary implementation of demurrage. In particular, productive positions could receive a reduced demurrage rate rather than newly issued rewards. This encourages useful activity while preserving a direct and consistent cost for retaining the network coin.



## **Periodic network coin tax**

A direct approach is to apply a recurring percentage charge to network coin balances. This can be described as a network coin tax or balance-based demurrage.

Suppose the annual rate is 3 per cent. A wallet maintaining an average balance of one thousand coins would pay approximately thirty coins over the year. A wallet maintaining one million coins would pay approximately thirty thousand.

The charge could be collected in small amounts at regular intervals. The annual rate would describe the total expected charge, while the protocol would apply the corresponding portion daily or at another defined frequency.

The monetary unit would not expire. Every coin would remain interchangeable with every other coin, and applications would not need to distinguish between different vintages.

Holding the balance would incur a cost, but the individual units would continue to function consistently.



**Proportional treatment**

A percentage based charge treats balances proportionately. Every holder is subject to the same rate, while the nominal amount collected increases with the size of the balance.

This makes large positions more expensive to maintain in absolute terms. A participant attempting to preserve a substantial balance must acquire enough additional coins to offset the continuing charge.

The proportional approach avoids setting an arbitrary nominal fee. A fixed charge would affect a small wallet much more heavily than a large one and could eventually consume the entire balance.

A percentage charge scales automatically with the amount held.

The system could still introduce different rates for different forms of use, but the underlying calculation would remain proportional to the balance or position.



**Applying the charge to wallets and smart contracts**

The charge would need to apply across the network rather than only to ordinary user wallets.

If smart contract balances were exempt, holders could deposit coins into a simple contract and avoid the charge without making the coins available for productive use.

Applying demurrage to both wallets and contracts reduces this form of avoidance. Coins remain subject to the carrying cost regardless of whether they are held directly or through an application.

The network may decide that particular productive positions qualify for a reduced rate. This should be an explicit incentive rather than an accidental exemption.

For example, coins committed to consensus or made available through recognised liquidity protocols might incur a lower rate than coins held in an inactive wallet.

The difference would reflect the function being performed. It would not mean that smart contracts generally escape the charge.



**Frequency of collection**

The charge can be collected annually, monthly, daily or through another schedule.

Infrequent collection creates noticeable adjustment dates. Holders may move coins shortly before the charge is applied and return them afterwards if the system calculates liability only at a single moment.

A large annual deduction may also cause sudden changes in balances, markets and application positions.

Frequent collection makes each individual charge smaller and produces a more continuous incentive. A daily or similarly regular adjustment reduces the importance of any single collection event.

The network must still determine how to calculate the charge efficiently. Continuously updating every balance could create unnecessary computational work.

The implementation could calculate accumulated demurrage when a wallet or contract is next accessed, while ensuring that the economic result corresponds to the time for which the balance was held.

Whatever mechanism is used, users should be able to predict the charge from the published annual rate.



**Transferring collected coins to the treasury**

Coins collected through demurrage can be transferred to a network treasury.

This keeps the total supply unchanged. The coins move from private balances into a collectively governed account and can later return to circulation through expenditure.

The treasury can use the income to compensate node operators, maintain the protocol, fund development and support other approved initiatives.

Because the charge applies to the existing supply, the amount of coin income is more predictable than revenue based entirely on transaction volume.

The treasury must avoid becoming a permanent store of inactive coins. If collected balances accumulate without being spent, the network has merely moved inactivity from private wallets into a public account.

Demurrage income should therefore be connected to a funding process capable of returning coins to circulation through useful expenditure.



**Removing collected coins from supply**

The network could instead burn the collected coins, permanently removing them from circulation.

This would reduce the total supply over time. Remaining coins might appreciate if demand remained stable, partially offsetting the cost of demurrage for existing holders.

A persistent reduction in supply could also increase the incentive to hold the remaining coins, working against the objective of encouraging circulation.

Burning does not provide income for node operation or development. The network would continue needing transaction fees, new issuance or external funding.

The choice between treasury transfer and burning therefore has significant consequences. Treasury transfer preserves supply and funds network activity, while burning creates a contractionary supply policy.

For a system intended to combine demurrage with sustainable network funding, treasury transfer is the more directly aligned approach.



**Predictability**

A network coin charge can be defined through a published annual rate and a clear collection schedule.

Users can estimate the cost of maintaining a balance and compare it with the expected benefits of liquidity, staking, lending and other uses.

Applications can incorporate the charge into their calculations. A lending protocol can account for the rate when determining expected returns, while a collateral agreement can anticipate the gradual adjustment in the underlying balance.

Predictability does not require the rate to remain unchanged forever. The network may allow governance or an automated mechanism to adjust it.

However, frequent or unexpected changes would weaken confidence. Participants need time to respond, and long-term agreements require some certainty about future costs.

A simple and stable rate is easier to understand, while a variable rate can respond more closely to changing demand and economic growth. This trade-off is considered in later pages.



## **Comparing the approaches**

Coin expiry produces a strong incentive but weakens fungibility and creates complex time-dependent values. Wallets, exchanges and contracts would need to distinguish between coins approaching different expiry dates.

Incentivised activity preserves balances but does not directly remove low-cost storability. It requires a funding source and can encourage artificial behaviour.

A periodic network coin charge, or a network coin tax, addresses the holding incentive directly. It preserves one consistent monetary unit, treats balances proportionately and can generate predictable treasury income.

The direct charge can also incorporate the useful part of the incentivised-activity approach by reducing the rate for selected productive positions.

For these reasons, a periodic balance charge, or a network coin tax, is the most promising of the three approaches. It provides the clearest implementation of demurrage while remaining compatible with different supply policies and financial uses.

However, selecting the mechanism does not determine the correct rate. A high charge can encourage circulation and generate income, but it can also weaken demand for the coin. A low charge may preserve demand while failing to prevent concentration.

The implementation must therefore be considered alongside the broader problem of stable network coin demand, which is examined on the following page.
