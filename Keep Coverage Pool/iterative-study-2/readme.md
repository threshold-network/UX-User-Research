![Cover_2](https://user-images.githubusercontent.com/40768736/191755553-802e5caf-fb6f-4cc7-8895-ea12ed6e1a7a.png)

* 🐱 User Researcher: Sasha Tanase
* 👓 Observers: Liz Shinn, Sasha Tanase, Michal, Rafal, Doug von Kohorn
* 🚀 Status -  Finished
---
# 🌐 Overview
The idea of the Usability Tests is to uncover what is intuitive and what is not in our layouts as well as uncovering what information is missing and what is confusing. 
We will have 2 distinct tasks that will be designed to test:
* the deposit flow
* the withdraw flow
* the timeline visual explanation of the protocol

We will also talk to KEEP users but also non-KEEP users.

## 🎯 Study Goals
In previous studies we have discovered that:
* the entire flow was extremely complex and users did not entirely understand it.
* most of the important information was ignored and the users would only read it when panic hit.
In this study we want to find:
* if the timeline display helps users understand how the protocol works
* discover worst friction points
* measure error rate
* task success
* task time
* learnability
* post task - SEQ

### 💬 Methodology
We are going to talk to X people both KEEP and non-Keep users to find out if the Deposit flows and Withdraw flows are intuitive and easily understandable. Also we are aiming to test if the new timeline display of the protocol helps users understand easier. 
* Define the user profile we want to talk to - people with some DeFi experience
* Design a screener for the recruiting announcement - screener
* Schedule interviews - 45 min 
* Topics - 
  * Blockchain knowledge - self assessed
  * Actively staking behaviour - needs, missing features.
  * 
  * Deposit Flow Walkthrough
  * Exit Flow Walkthrough
* Document
* Analyze
* Report

Link for Ropsten - https://dashboard.test.keep.network/coverage-pools/how-it-works

### ⏲ Pre-test Preparation

In the invitation e-mail we will ask the participants to send us their ETH address they are going to use for the test. 
We will send each participant:
* 22,000 Ropsten KEEP 
* 0.2 Ropsten ETH
* a visual tutorial 
Visual Tutorial

Tutorial that will be sent to participants can be found here - https://bit.ly/3ze520j

## 📊 Metrics to measure

Object
Deposit Flow - Task
“Deposit an amount of tokens in the pool.”
Average Rating - 5.8

Why it didn’t score 7? Reasons stated by the participants:
* Not enough information about the risks

* Users did not clearly understand what the covpools do 

* The documentation link was not in the modal

* The missing exchange rate of KEEP/covKEEP 

* Links to github, links to source code missing, where was the contract deployed

* The modals disappear in the process

Object
Learnability - Task  
“Please tell me what where the steps mentioned in the overview timeline?”
Average Rating - S - Success

We wanted to test if the users were remembering easier the protocol timeline if they were helped by a visual support we provided in the modals.
6 out of 8 users remembered all the steps including the time periods. There was also a partial success - where one users could not remember the last step and a Failure - which seems to be more like an outlier, because the participant did not pay attention to anything and did not read anything during the test.
Learnability was tested during the whole Usability Test and we can safely say that users tend to learn quite easily how the product works. This is supported by the fact that the Average ratings. Most of the users rate the tasks lower at the beginning, and in time, they get used to the process and rate higher the second task.

Object
Withdraw - Task  
“Withdraw an amount of tokens”
Average Rating - 6.2 
Why it didn’t score 7? Reasons stated by the participants:
* We are not telling the users upfront that the process involves two transactions and we are not giving them any gas estimates
* We do not provide our users with some alerting/reminder system to help them remember when the cooldown period is over 8/8 ask for this
* The KEEP/covKEEP Exchange Rate doesn’t have decimals and it’s just an estimate
* The percentage of the pool doesn’t have decimals
* Dumbed down risk listing
* Most of the users complaining that our dApp is breaking the pattern in which the user grants max spanding to the contract and this way they are saved gas. 
* Modals are closing when the Metamask is triggered and users get lost in the process

# 📕 Report

[Report](./Keep%20Iterative%20User%20Research%20-%20Coverage%20Pools%20Usability%20Testing%20Round%202%20github.pdf)
