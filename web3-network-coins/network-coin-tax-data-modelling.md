# Network coin tax data modelling

The following compares storable and demurrage based network coins. Storable coins means there would be no cost for holding the coin and leaving it idle in a wallet. Demurrage means there would be carrying costs in the form of a periodic tax.



## Comparing storable vs demurrage based network coins

Comparisons between storable and demurrage based network coins can help with understanding the implications of adopting a network coin tax within a Web3 network. The approaches being compared include:

* **Storable network coin with transaction fees to generate treasury income** - The network coin is storable and the base transaction fee is increased to generate ongoing income for the ecosystem treasury.
* **Storable network coin with only excess transaction fees generating treasury income** - The network coin is storable and the transaction fees are as low as possible. Only excess fees would be used as a form of treasury income that are above the compensation threshold for node operators.
* **Demurrage network coin (0.1% network coin tax)** - The network coin has a carrying cost in the form of a 0.1% network coin tax.
* **Demurrage network coin (1% network coin tax)** - The network coin has a carrying cost in the form of a 1% network coin tax.



The data model applies some example values to illustrate the difference between these approaches based on whether the user is storer, an active user or a combination of the two. The data modelling can be found here:

{% embed url="https://docs.google.com/spreadsheets/d/18uxCbSpag4xotIpxdNlbZk4fKwn_1rIwg65Pod3__xs/edit?gid=0#gid=0" %}

Source: [https://docs.google.com/spreadsheets/d/18uxCbSpag4xotIpxdNlbZk4fKwn\_1rIwg65Pod3\_\_xs](https://docs.google.com/spreadsheets/d/18uxCbSpag4xotIpxdNlbZk4fKwn_1rIwg65Pod3__xs)



**Key takeaways**

* **Storable networks are great for savers and bad for active users -** The most important users for a Web3 network are those that actually use the network and generate economic activity. Those that just store the network coin are generating no activity and are limiting other people's access to the network coin. A storable network coin means that people that hold coins idle will pay nothing towards supporting the network. Only active users will pay for fees that support the network. Active users are unfairly punished with a larger financial burden as the fees to maintain the network are only split across those that are actively using the network and not those that are storing the network coin and not creating transactions.
* **Generating treasury income with added transaction fees punishes active users** - If treasury income is generated through active users this is a form punishment for active users as they become the only users that are paying towards the treasury. Storers of the network coin wouldn’t need to contribute towards the treasury. This approach leads to the worst outcome for active users as it is the most expensive approach for them to use the network regularly. This creates an incentive to use other networks where the transaction fees are lower. A storable network that only generates treasury income from excess transaction fees somewhat solves this problem however now the income potential for the treasury would be drastically reduced as transaction fees would be reduced as much as possible.
*   **Storable networks could have transaction fees that are nearly as cheap as demurrage networks** - If node operators were paid a predictable or fixed amount based on performance both storable networks and demurrage networks could reduce their fees once this threshold of compensation has been reached.

    With storable networks it is more difficult to lower transaction fees as low as possible as node operators rely on the income generated from transactions. This means the network needs to predict how many transactions it will receive to reduce the fees accordingly to make sure the node operators are only compensated what is necessary. Alternatively it means using a single fee amount that could have been reduced due to the excess income that was generated beyond the intended compensation amount. Storable networks will likely need to introduce a buffer so that node operators are always sufficiently compensated otherwise this could create a systemic risk for the network. Node operators also rely on the price stability of the network coin as if the price drops the same number of transactions produce a lower total amount, which might not be enough to incentivise ongoing operation.

    Network coin taxes on the other hand don't rely on transaction volume which makes the income more predictable. They do however rely on price stability of the network coin. Overall this should mean that network coin taxes provide more reliable income for node operators than transaction fees. The transaction fees can be reduced to the absolute minimum and this can remain there in perpetuity. The only increase in fee that is commonly required is one that prevents transaction spammers. Demurrage networks should be able to more reliably keep transaction fees as cheap as possible. The other benefit of the network coin tax approach is it spreads the cost of paying for node operators across the entire network of people whom hold the network coin rather than just the active users who are transacting.
*   **Network coin tax networks will need sufficient incentives or achieve network effects that can maintain a meaningful network coin tax -** A network with a network coin tax could be easily duplicated and the network coin tax could be reduced to only pay for node operation. When these networks mature there will likely be less development effort required to improve and maintain the network. This situation creates an opportunity to reduce the network coin tax or for other networks to duplicate the network and reduce it.

    This could make it difficult to keep the network coin tax above the cost of operating the network unless an additional incentives are added to generate ongoing demand for the network coin. Alternatively network effects could be sufficient to result in people not leaving the network due to the difficulties in getting everyone to migrate elsewhere.



## Modelling coin dispersion and investment returns

Another valuable thing to understand is the implications of demurrage for the holders of the network coin and whether they will generate a return on investment as well as how the coin could disperse over time based on different input variables.

Holders that generate a return on investment from simply holding the network coin is undesirable as this represents a form of unearned income. However it can be difficult to accurately record and understand the increasing and decreasing amount of network activity that leads to changes in the demand for the network coin. Maintaining stable prices with the network coin would be inherently difficult in a global network where the economic activity can become increasingly complex over time.

Either adopting a fixed supply for simplicity or being conservative with any network coin supply increases can be a desirable approach to prevent inflation. However this means that deflation and coin price appreciation are fairly likely. This unearned income is undesirable however coin price appreciation does generate demand for the network coin. And the network can easily capture some or all of this unearned income through a network coin tax. Demurrage acts as a counter weight to the store of value function. During the growth phases of the network it could be an acceptable trade off to give people a higher return on investment to encourage more investment into the network. Web3 networks fiercely compete for capital so two things that can be compelling for these networks are high growth rates and returns on investment for holders to increase the amount of capital invested.

To model how the network coin tax could impact the network and the user we can model some of the following key input variables:

* I**nitial amount of coins held** - The starting number of network coins that someone is holding.
* **Coin starting price** - The value of the network coin at the beginning.
* **Annual price appreciation** - The percentage rate in which the coin's price increases each year. This will happen due to global network growth and adoption or due to economic growth in the network that results in more demand for the network coin.
* **Annual average yield** - The average amount of yield that can be generated per year by depositing the network coin as financial liquidity. This would be relevant for token exchange liquidity pairings using the network coin and how much return can be generated each year. Not all liquidity pairs would generate the same yield. Commonly the riskier pairs might have less liquidity due to volatility or uncertainty in the token, this can result in higher returns for suppliers of liquidity when there is demand for the tokens.
* **Network coin tax rate** - The annual network coin tax rate. This is the total percentage of coins that will be taken each year due to the taxation.



The model can help with exploring what the trends are for total coins held and total value of the remaining coins held over time. It is also useful to understand what the cost would be to purchase the coins again that have been taken away due to the network coin tax. The data modelling can be found here:

{% embed url="https://docs.google.com/spreadsheets/d/1M6G4NXRzf_ECmqUrcjCrB5RITkoSHTgsB55l8L3w6ZY/edit?usp=sharing" %}

Source: [https://docs.google.com/spreadsheets/d/1M6G4NXRzf\_ECmqUrcjCrB5RITkoSHTgsB55l8L3w6ZY/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1M6G4NXRzf_ECmqUrcjCrB5RITkoSHTgsB55l8L3w6ZY/edit?usp=sharing)



Disclaimer - The data model doesn’t accurately simulate the gain and losses each year as the yield generated would be calculated based on the amount of deposited liquidity at each point in time. For simplicity we deducted the network coin tax amount off first and then calculated the yield. In reality the yield generated would be higher as the amount deposited would gradually go down over time. This model is just a simple example that helps to illustrate the key data inputs to consider when designing a demurrage based Web3 network.



**Key takeaways**

* **Coin dispersion occurs when network coin tax is above the yield generated** - Coin dispersion is desirable as it helps to improve network coins decentralisation over time, which can help with increasing security and preventing coin ownership concentration. If on average people lose coins from depositing it as financial liquidity they will gradually lose coins over time. This could be problematic if there was no coin price appreciation as it would mean people are deciding to optionally participate in something where they are actively losing some nominal amount of money. However due to coin price appreciation, the loss in coin ownership does not mean the holder won’t see a positive return on investment in terms of purchasing power.
* **Positive increases in ownership can still be possible** - Most people would lose coins over time due to the network coin tax being above the average yield they can generate. However some people will deposit their liquidity into pairings that are more profitable and this might mean they increase their coin ownership for a number of years. This isn’t necessarily concerning for coin ownership concentration as the holders of the network coin could be taking on high levels of risk to generate that return on investment. The liquidity pairing would require a sufficiently high enough demand to generate a higher than average profit so they would still be making a valuable contribution to the financial market.
* **Coin price appreciation makes it harder to sustain coins held** - The higher the price increases the more expensive it becomes to purchase back the coins that have been taxed. Coin price appreciation can help with increasing the inevitability that people start to lose coins over time due to the cost of trying to maintain their original coin holdings. For smaller amounts it could be easy for people to increase their position, however at a larger scale this becomes much more difficult due to the proportional total price increases. And this is where demurrage becomes most important, to increase the difficulty of larger holders being able to perpetually increase their position.
* **High coin price appreciation could result in a need for supply increases** - Fast coin price appreciation is not desirable as it can make the network coin less effective as financial liquidity. It would not be compelling to use the network coin as financial liquidity if it is more profitable to just buy and hold the coin instead. Expansionary supply changes could help with slowing down any price increases. It will be difficult to know the exact amount that needs to be added to the supply to achieve truly stable prices. Instead it might make sense to be conservative and allow for a small amount of ongoing coin price appreciation in these situations so that the supply changes don’t cause inflation. If accurate tools and mechanisms emerge that can maintain stable prices then these could be considered however they would need to be mission critical solutions with high reliability. In the short term, Web3 network could accept some coin price appreciation and capture some or all of the unearned income through a network coin tax.
