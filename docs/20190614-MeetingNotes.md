# Venue June 14, 2019 Meeting Notes

  * [Vision Statement](#vision-statement)
  * [Defining Bounty](#defining-bounty)
  * [Why The Bounty Program](#why-the-bounty-program)
  * [Scope](#scope)
  * [Actors:](#actors)
  * [Constraints](#constraints)
  * [Functions Of A Bounty Program](#functions-of-a-bounty-program)
  * [Task Relationship](#task-relationship)
  * [Use Cases](#use-cases)
  * [2 Types Of Bounties](#2-types-of-bounties)
  * [Stable Coin](#stable-coin)
  * [Things To Look At](#things-to-look-at)

## Vision Statement 
Venue is a bounty program.

In broader terms, Venue is an escrow service that will be able to manage the transaction between two parties in which goods and/or services can be exchanged.

## Defining Bounty

Bounty is a small task that manages escrow, is verified, and renumerates.

## Why The Bounty Program

A way to decentralize your employer.... Greg quote... Fosters the emergent Gig economy.

## Scope

Venue should be bigger than Volentix. Anyone should be able to use the platform, even outside the Volentix ecosystem.

## Actors:
 - Contractee: Client. The one posting the bounty.
 - Contractor: The one doing the work.
 - Approver: Can be the contractee or 3rd party.
 - Arbitrator: In case of dispute
 - Operator: The individual running Venue

## Constraints

1. In order to gain mass market adoption, Venue will be web based in prioriety over Verto integration.
2. Before Venue is built, the economics and business strategy must be finalized.
3. The sytems backend must remain independant from its front end.
4. The system architecture must be decentralized

## Functions Of A Bounty Program

  - **Profiles:** Ways for users to manage their personas online
  - **Create Tasks:** Ability for contractors to create tasks.
  - **Escrow:** Hold the contractees stable coin allocated for the task.
  - **Payment:** Pay the Contractor upon proof of work.
  - **Integrate:** Must integrate with many platforms such as facebook and twitter
  - **Find Tasks:** Contractors must be able to find and discover tasks for their skill.
  - **Rating:** A transparent, simple, rating system must be created for both contractors and contractees. Someing very simple like the Uber rating system.
  - **Arbitration:** In cases where there is a dispute, a service of arbitration must be architected as a first class solution.

## Task Relationship

Tasks can be one to one or one to many. For example, a development work unit may be assigned to one person to complete. However, actions like sign up for Volentix or download Verto can be applied to the communittee at large. In the case of the later, the contractee can create one task and any number of contractors can fullfill the task in parallel.

## Use Cases

- Download Verto
- Fix a bug
- Write a blog
- Test software
- Mow the lawn
- Paint the house

Note that the last 2 are a bit toungue in cheek, however, they must remain in the teams conciousness as third party entrepreneurs will be able to use Venue as an escrow platform. This allows unknown entrepreneurs the freedom to create their own business models without impediment or restriction on the underlying protocol.

## 2 Types Of Bounties

1. Automated: Things like downloading Verto. Would require bots... potential marketplace for resale of bots.
2. Verified: Needs a human intervention. For example, pull requests, documenation updates, security bugs, etc.


## Stable Coin

Based on the experience of other platforms, it is suggested that bounties are bound to stable coins. As we will be using VDex under the hood, this should be a fairly trivial pattern.

## Things To Look At

Sourcecred: https://github.com/sourcecred/sourcecred