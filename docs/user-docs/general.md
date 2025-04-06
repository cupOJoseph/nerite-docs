---
sidebar_position: 1
---

# General

What is Nerite?
Nerite is a decentralized borrowing protocol that lets users deposit ETH, LSTs, and ARB as collateral, and mint the stablecoin USDN at an interest rate depositors choose. Nerite is based on Liquity v2.

There are several main use-cases:

- Borrow USDN to access capital without having to sell your tokens
- 1-click multiply exposure to collateral assets
- Earn yield by depositing USDN in the stability pool or farming elsewhere
- Stake NERI to direct PIL and earn rewards
- Stream USDN as a subscription, salary, grant, or any other kind of payment

Nerite is built using the Liquity V2 codebase. Check out their docs [here](https://docs.liquity.org/).

What are the differences to Liquity V1?
Some things stay the same:

- Immutability
- Decentralization
- Rigorous security
- Redemption of stablecoins for underlying collateral maintains the $1.00 peg

However, Liquity has innovated on multiple fronts:

- User-set interest rates – more control over your borrowing cost.
- New collateral types - ETH, LSTs, and ARB
- Improved redemption mechanism (lowest borrowing rate is redeemed first, always increasing yield of USDN with each redemption)
- Troves are now transferable as ERC-721 tokens
- Improved capital efficiency

What other differences are there between Liquity V2 and Nerite?
- Additional collateral types. Nerite supports: ETH, rETH, wstETH, sfrxETH, weETH, pufETH, tETH, tBTC, COMP, and ARB (all on the Arbitrum network).
- Streaming: USDN can be streamed at any rate using [Superfluid](https://www.superfluid.finance/). Pay anyone every second.
- ARB deposited in the protocol can be delegated by Nerite governance.
- Additional security features to allow for the other features, like debt limits.

Does Nerite have governance?
Nerite is subject to minimal governance which is solely tasked with distributing Protocol Liquidity Incentives (PIL), directing 25% of the protocol's revenue to external initiatives, delegating ARB, and updating collateral debt limits.

The core protocol can never be upgraded, by governance or otherwise. Similarly, there is no governance control over the stablecoin or any collateral assets.