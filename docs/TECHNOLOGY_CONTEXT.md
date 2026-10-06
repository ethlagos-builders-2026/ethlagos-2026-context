# Technology Context

This document explains the technologies explicitly mentioned by ETH Lagos.

## ERC-8004: Trustless Agents

Status on the Ethereum EIP site: Draft ERC.

Purpose:
Discover agents and establish trust through reputation and validation.

The proposal defines three main registries:

### Identity Registry
Provides a portable onchain agent identifier.

### Reputation Registry
Provides a standard interface for feedback signals about agents.

### Validation Registry
Provides hooks for independent validation of agent work.

Important:
ERC-8004 does not itself define agent payments.

Source:
https://eips.ethereum.org/EIPS/eip-8004

---

## ERC-4337: Account Abstraction

ERC-4337 provides account abstraction without requiring a consensus-layer protocol change.

Key components include:

### Smart Contract Account
An account whose authorization/validation logic can be programmable.

### UserOperation
A pseudo-transaction object submitted by users.

### Bundler
Collects UserOperations and submits them through the EntryPoint contract.

### EntryPoint
The shared contract through which ERC-4337 operations are validated and executed.

### Paymaster
A contract that can pay transaction fees on behalf of the user, subject to its own rules.

Source:
https://eips.ethereum.org/EIPS/eip-4337

---

## L2s

Layer 2 networks execute activity away from Ethereum mainnet while inheriting or connecting back to Ethereum security and settlement.

ETH Lagos explicitly mentions:
- rollups
- the Superchain
- affordable rails
- low-cost execution for humans and agents

Partners also include several major L2 ecosystems.

---

## Paymasters / Gasless UX

In ERC-4337, a paymaster can sponsor transaction fees for a user.

This can enable applications where:
- a new user does not need ETH before their first action
- an application subsidizes gas
- a user pays fees through a different commercial model

A paymaster does not mean transactions have zero cost. It changes who pays and under what policy.

---

## Intents

The ETH Lagos UX theme mentions intents.

An intent expresses the outcome a user wants rather than forcing the user to manually construct every low-level blockchain action.

Typical design goal:
"Do X for me" instead of "choose network, approve token, select router, set gas, sign multiple transactions."

---

## RWAs

RWA means Real-World Asset.

In this event context, the important phrase is "off-chain Nigerian assets."

The challenge is not limited to token creation. A serious RWA system normally needs a clear relationship between:
- the real-world asset/obligation
- verification
- onchain representation
- ownership or claim
- settlement/redemption
- failure/default assumptions

---

## ZK / Zero-Knowledge

Zero-knowledge proofs allow a party to prove a statement without revealing all of the underlying information.

ETH Lagos mentions ZK in:
- identity
- privacy tools
- decentralized society

Potential uses include:
- proving eligibility without revealing full identity
- proving possession of a credential
- selective disclosure
- privacy-preserving community participation

---

## Quadratic Funding

Quadratic funding is a public-goods funding mechanism designed to increase the influence of broad community support rather than only large individual contributions.

ETH Lagos includes it under the Cypherpunk Lagos theme.

## Main event source

https://ethlagos.ng/
