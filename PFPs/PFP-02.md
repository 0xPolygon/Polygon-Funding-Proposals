| PFP               | Title                           | Description          | Author                        | Discussion | Status | Type                                     | Date                  |
|-------------------|---------------------------------|----------------------|-------------------------------|------------|--------|------------------------------------------|-----------------------|
| 2 | Community Treasury Board  | Describes the Polygon Community Treasury Board | Mateusz Rzeszowski, Justice Conder, Bojana Tomic, Mihailo Bjelic | [Forum](https://forum.polygon.technology/t/pfp-2-community-treasury-board/13760)  | Continuous | Informational | 2024-04-11
---

# PFP-2: Community Treasury Board


## Abstract

This proposal introduces the Community Treasury Board (CTB) as an independent governance body responsible for managing the Community Treasury. This includes but isn’t limited to, creating a Community Treasury strategy and post-season impact reports, approving grants and expenses, and managing a budget.


## Specification

The CTB is an independent body responsible for shepherding the Polygon Community Treasury. It should comprise thought leaders and experts in ecosystem growth and grant operations. Members must be familiar with ecosystem trends and opportunities and able to formulate a compelling thesis to support their strategic decisions. 


### CTB Qualifications

Among others, the following qualifications are needed:



1. Value Alignment with the Polygon vision and Wider Ethereum and Web3 Values— CTB members should be aligned with Polygon, follow Ethereum’s ethos, and be aligned with general Web3 values, such as decentralization, self-sovereignty, and unconstrained access to the Internet of Value. 
2. Ecosystem Growth Expertise— CTB will be critical in guiding both early seasons to success via strategy-setting and working on the framework's evolution towards more efficient and decentralized growth strategies. 
3. Specific Field Expertise—CTB members will ultimately assess the value of individual projects and allocators to the development of the Polygon ecosystem. As such, they need to possess the skills necessary to assess these efforts well or delegate them to other collaborators they deem qualified.
4. Community Expertise—The Polygon ecosystem is at a pivotal moment as it builds a strong community ready to advance it even further. Prospective CTB members need to be able to leverage this effort as an opportunity for long-term ecosystem growth. 
5. Operational Expertise—Operating the CT is a significant undertaking that requires CTB members to have operational expertise to spin up large programs. 


### CTB Responsibilities

The Community Treasury Board will be able to determine its procedures to address the following responsibilities.


#### Strategy Setting

Before a funding cycle starts, CTB prepares and publishes a strategy document. The document sets out a framework for project funding categories, subcategories, and the eligibility of each funding track in the upcoming season. 

Pre-cycle preparation is accomplished when the CTB produces a final strategy delineating the above-described allocations. This strategy is published transparently.


#### Track Selection

This proposal distinguishes two tracks, which the CTB may employ as needed on a per-season basis by including in the strategy document.

**Direct Funding Track**

The direct funding track facilitates submissions from individual projects to the CTB. All prospective grantees will require CTB approval to receive funding from the CT, following a process laid out by the CTB.

**Grant Allocator track**

The Grant Allocator track relies on specialized entities facilitating the distribution of allocated funds to grantees. Similarly to individual projects, prospective Grant Allocators will follow a process laid out by the Community Treasury Board.


#### Expenditure Approval

At all times, the CTB is responsible for reviewing applications from all tracks and approving all expenditures from the Community Treasury, assisted by the Polygon Village Grants team as needed. The Village Grants team may propose funding proposals, but CTB approval is always final and necessary.


#### Post-Cycle Reporting 

Post-cycle, the CTB is responsible for producing a transparency report capturing the decisions, expenses, and the total impact across all participating Grant Allocators. The transparency report may summarize the decisions around individual projects funded within the season, and any learnings from the season.


### Allocation - Technical Flow

In the current phase, the Polygon Village Grants team will assist with Community Treasury operations, aggregating approved applications and the preparation of corresponding on-chain transactions. A set of on-chain mechanisms is proposed to facilitate the flow of funds. 

The address of the current interim SAFE contract, introduced in [PIP-17](https://github.com/maticnetwork/Polygon-Improvement-Proposals/blob/main/PIPs/PIP-17.md) and to which Community Treasury emissions stream to, is `0x2ff25495d77f380d5F65B95F103181aE8b1cf898`.

A new governance contract (Aragon) is proposed that will govern the Community Treasury.

A non-upgradeable OpenZeppelin ERC20Votes will be used as a voting token held by two SAFE contracts. Transfers, Approvals and Delegation will be disabled and tokens will be distributed upon contract deployment. Two roles are furthermore distinguished, Proposer and Executor.

- 50.00000001 tokens will be distributed to the Proposer SAFE (`0x2ff25495d77f380d5F65B95F103181aE8b1cf898`) wallet operated by Polygon Labs,
- 49.99999999 tokens will be distributed to the Executor ⅗ consensus multisig wallet (`0xb7b02DbC9D054A8BA90b2172B4f8d2D79aC7d3a0`) operated by the Community Treasury Board.  

The Proposer is responsible for proposal creation, with 50 votes being the requirement. 

Once a proposal has been created, both the PROPOSER and EXECUTOR's `yes` votes are necessary to execute a proposal, with 100 votes being the required consensus.

The above setup ensures that while Polygon Labs may assist the Community Treasury Board with day-to-day administrative and other non-managerial operations, it may not execute any transactions, including the distribution of funds, without the CTB's on-chain approval. 

### Compensation to Initial CTB Members

Each of the initial CTB members will receive a monthly payment equal to $5,000 USD, payable in POL, from the Community Treasury, calculated using the [Coingecko Historical POL Close Price](https://www.coingecko.com/en/coins/polygon-ecosystem-token/historical_data) as of the last day of each month (or a pro-rata portion thereof for any partial month service).


## Copyright

All copyrights and related rights in this work are waived under CC0 1.0 Universal.
