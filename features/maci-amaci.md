---
title: MACI and aMACI
parent: Features
nav_order: 4
---

# **MACI**

Minimal Anti-Collusion Infrastructure (MACI) is a pioneering governance technology developed by the Ethereum community that is used in decision making processes to conceal the identities and voting choices of participants. This prevents collusion and coercion from affecting voting, which has been a key challenge facing decentralized governance in the past.

At DoraHacks, we have adapted MACI for our on-platform community voting and judging mechanisms. Eligible voters have their wallet addresses added to a whitelist and are allocated **voice credits** used to cast their votes. The number of voice credits given is determined by the organizer, and is customisable to reflect voting power of each participant.

Once a wallet is connected to the Vota MACI system, the address is hidden within a smart contract and the user can see their **voice credit** allocation and voting options in a simple, easy-to-use interface. Participants simply choose the options to vote for and specify how many credits to allocate to each one. DoraHacks has a MACI system built on **Dora Vota**, a Cosmos appchain, and gas fees are automatically covered by the integrated **gas station**.

Projects on EVM-compatible chains can also choose to use MACI on their own blockchains. The process is similar to MACI on Dora Vota, but in this case participants are required to purchase and stake some DORA tokens on the Ethereum network in order to receive vcDORA to cast their votes. vcDORA received from staking has no value and cannot be traded, as it is linked to the user's wallet address. The requirement to stake DORA is an anti-sybil mechanism, which prevents bots from taking part in MACI voting.

# **a-MACI**

Anonymous-MACI builds on the privacy of participants enabled by MACI, but adds another layer of anonymity by hiding their identities from the organizers themselves. This system is useful when collusion between organizers and participants is a concern, as with a-MACI it’s also impossible for voters to prove how they voted after the round closes.
