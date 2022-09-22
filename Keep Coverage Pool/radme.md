![Cover](https://user-images.githubusercontent.com/40768736/191750576-25dd94f3-4521-4e28-ba87-d9cd892b0dac.png)
# 🐱‍💻 Description of the project

A coverage pool is a flexible new money lego that can be used as a back-stop or "buyer of last resort" in on-chain financial systems. 
The Coverage Pool feature set will initially rolled out to whitelisted Keep supporters & community members. Eventually DeFi power users( I think we should avoid this term from now on, tends to lead us astray), specifically liquidity providers and underwriters for other protocols, will be best suited for the Coverage Pool product. 

## 🧍User Stories by feature

* Coverage Pool Deposit/Withdrawal
  * Underwriters can connect their wallet or input their Ethereum address to view their current deposits
  * Underwriters can deposit KEEP whitelisted by the Coverage Pool
  * Underwriters can remove their KEEP from the Coverage Pool after a fixed withdraw period of 21 days
  * Underwriters earn KEEP as a reward for being an underwriter

## 🎯 Design Goals

Distill technical complexity into a very user friendly and easy to use product. The Coverage Pool is a very complex feature that destined to rewards underwriters, users who are willing to put their tokens in the pool to secure the network. 

Points we needed to address due to high complexity:

* helping users understand how to protocol works - the protocol has a very long period in which the users wait for their tokens to be unlocked and then a very short period in which they can claim the tokens. - we had to come up with a timeline type of information visualization for them to understand better. This visualization is repeated every step so they do not forget.
  
* An Information page put together very well that helps users understand what a coverage pool is and how it works.

* Preventing error modals - due to a high risk we had to make sure we have enough steps/modals in which users are presented upfront which are their risks, and give them the option to quit.

* Due to the fact that the period between the activation of the withdrawal and the claiming token window is very long - 21 days - we made sure we help the users avoid forgetting so we have given them the option to Add to calendar and also made the decision to add in the overview page of the dashboard the Pending withdrawal modal so whenever they come to the dashboard they could see how long will it take until they need to claim the tokens.

# 💻 Table of Contents
1. [Iterative User Study 1](https://github.com/threshold-network/UX-User-Research/tree/main/Keep%20Coverage%20Pool/iterative-study-round-1)
2. [Iterative User Study 2](https://github.com/threshold-network/UX-User-Research/tree/main/Keep%20Coverage%20Pool/iterative-study-2)
