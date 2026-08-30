# Recommended demurrage implementation

The recommended initial design is a fixed-supply network coin with a periodic percentage charge on balances. Collected coins are transferred to the network treasury and returned to circulation through node compensation and approved expenditure. Selected uses that directly support the network receive reduced rates.

This should be treated as an initial monetary design rather than a permanent configuration. Rates and incentives should begin conservatively and change only in response to sustained evidence.



### **Core mechanism**

Demurrage should be expressed as an annual percentage rate and accrue over time in smaller increments. The protocol may settle accrued charges periodically or when a balance is accessed, provided that both methods produce the same predictable economic result.

The charge should:

* Apply proportionately to the amount held and the time for which it is held
* Apply to balances in both wallets and smart contracts
* Follow the balance when coins are moved so that transfers between controlled addresses cannot reset accrued liability
* Use a public formula that wallets, applications and long-term contracts can calculate independently
* Preserve the fungibility of the coin by applying to balances rather than creating coins with different expiry dates

No organisation or address category should receive an automatic exemption. Any reduced rate should result from a verifiable network function rather than the identity of the holder or the type of account used.



### **Treasury collection and initial supply**

Collected coins should be transferred to the network treasury rather than burned. The treasury should spend them back into circulation, keeping the total coin supply initially fixed.

Treasury expenditure should be prioritised as follows:

1. Essential node operation and network security
2. Protocol maintenance, security reviews and shared infrastructure
3. Development and other ecosystem work
4. Wider public goods, if sufficient funding and legitimate governance exist

Node compensation should reflect measurable work and resources, such as availability, validation, storage and reliability. Demurrage income should not be redistributed to holders in proportion to their balances.

Funding should normally be released against milestones or observable contributions. If the treasury persistently collects more than it can allocate productively, the demurrage rate should be reconsidered rather than allowing a large inactive treasury balance to accumulate.



### **Base and reduced rates**

The protocol should establish:

* A **base rate** for ordinary wallet and contract balances
* **Reduced rates** for positions that provide defined network benefits

The initial qualifying uses should be limited to:

* Consensus staking
* Token exchange liquidity
* Single-asset lending of the network coin
* Network coins committed as genuine contract collateral

Reduced rates should not normally be zero. Qualifying positions may also generate staking rewards, lending income or exchange fees; the combined outcome should not create a low-risk mechanism through which large holders can compound their ownership indefinitely.

The difference between the base and reduced rates should be meaningful but not so large that users are effectively compelled to enter financial protocols. A participant should remain able to retain a directly accessible balance and pay the base rate.



### **Qualification rules**

Eligibility should depend on the economic function performed rather than on depositing coins into a particular contract.

Qualifying rules should consider:

* The amount and duration of the commitment
* Whether the coins are genuinely available to other users
* Liquidity depth or borrowing utilisation where relevant
* Withdrawal conditions and reliability
* Distribution across independent providers
* Resistance to artificial markets, transactions and self-dealing

Raw transaction volume or wallet counts should not independently determine eligibility because both can be manipulated.

Token exchange and single-asset lending reductions should initially be broadly comparable. This allows participants to choose according to the contribution and risk involved rather than directing activity towards whichever category receives the largest subsidy.

Where one position performs several functions, reductions should not be added together automatically. The applicable rate should reflect the underlying contribution, subject to a defined minimum rate.

Multi-asset lending, stablecoin issuance, collateralised debt positions, derivatives and synthetic assets may use the network coin, but should not initially receive protocol-level reductions. Additional categories should be introduced only when they demonstrate a direct, broadly shared and verifiable network benefit.



### **Transaction fees**

Demurrage income should provide the base funding for network operation, transaction fees can still be used for resource allocation and spam prevention.

Fees should be set near the minimum required to prevent excessive resource consumption. They should not be expected to fund the entire operating budget. If another reliable and inclusive anti-spam mechanism becomes available, fees may be reduced further.



### **Initial rate and rollout**

Demurrage may be absent or minimal during genesis while the network attracts participants, establishes liquidity and develops qualifying uses.

A modest base rate should be introduced during the growth phase using:

* Advance notice
* A published implementation schedule
* Conservative initial base and reduced rates
* A defined maximum adjustment within each governance period
* Sufficient transition time for wallets, contracts and financial positions

As the network matures, the rate may be adjusted in relation to low-risk staking and lending returns. If dispersion remains an objective, passive or low-risk positions should not consistently provide a net return that increases their share of the coin supply.

Transitions should depend on network conditions rather than fixed dates. Relevant conditions include application use, liquidity, staking participation, node decentralisation, ownership distribution and the treasury’s ability to use collected income effectively.



### **Governance and adjustment**

Rate changes should be infrequent, gradual and predictable.

The governance framework should specify:

* Who can propose and approve a change or which of changes are automated
* The indicators used to evaluate proposals
* The permitted range for the base and reduced rates
* The maximum size of an adjustment
* The required notice and implementation period
* A more demanding process for changing the permitted range itself

Founding entities may have limited authority during the earliest phase, but that authority should be transparent and transferred progressively to decentralised governance.

Published indicators should inform decisions rather than change rates automatically. Automatic adjustment should not be introduced until the network has reliable, manipulation-resistant data and sufficient operational evidence.



### **Monitoring**

The network should assess the implementation using longer-term trends in:

* Idle and active balances
* Coin ownership distribution
* Staking participation and concentration
* Exchange-liquidity depth, duration and distribution
* Lending supply and utilisation
* Use of the coin as contract collateral
* Node participation and operating costs
* Treasury income, expenditure and recipient concentration
* Optional demand for the coin
* Long-term appreciation and market volatility

No single measure should trigger a policy change. Adjustments should reflect sustained conditions across several indicators.



### **Supply-policy review**

The total supply should remain fixed initially. Persistent appreciation should first be evaluated against the effective demurrage rate and its effect on passive holding.

A modest and predictable expansionary policy should be considered only if appreciation persistently disrupts network-coin access, lending, liquidity or collateral use. Elastic supply should not be introduced unless its inputs and adjustment mechanisms are sufficiently reliable for a mission-critical protocol.



### **Initial configuration**

The initial recommended implementation therefore consists of:

* A fixed network-coin supply.
* An annualised demurrage rate that would be introduced when the genesis funding allocation is near depletion or when the ecosystem is showing signs of meaningful growth.
* Equal application of demurrage to wallet and smart-contract balances.
* Network coin taxes used as an income source for the ecosystem treasury.
* A base demurrage rate for ordinary balances and reduced but non-zero rates for staking, token exchange liquidity, single-asset lending and contract collateral use cases.
* Incentivised use cases could be stacked together to achieve multiple rate reductions but even combined these should always have an ongoing demurrage charge.
* Treasury that prioritises node operation costs and then it would help with funding essential network development and maintenance.
* Transaction fees would be minimised and only be used for the purpose of resource allocation and spam prevention.
* Demurrage rates would initially be very conservative and be governed through bounded, gradual and well communicated changes.
* Monitored data sources would be used to influence any demurrage rate, incentive mechanism or the supply policy related changes.

This configuration provides a practical starting point that can be implemented and evaluated without making the network’s monetary system dependent on unnecessary complexity.
