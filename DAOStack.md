---
title: "DAOStack"
tags: ["permanent-notes", "blockchain", "dao", "technology" ,"organization" ]
date: 2021-05-12 23:33:00
source: "https://medium.com/daostack/an-explanation-of-daostack-in-fairly-simple-terms-1956e26b374"
---

DAOStack is an Open Source stack to make it easier to create [[DAO - Decentralized Autonomous Organizations|DAO]] organizations.

## Layers

- Infrastructure: Smart contracts on Ethereum
- Arc: library of modules for building the back ends of DAO
- ArcGraph:  Caching layer that fetches, stores, and organizes information from the blockchain, enabling fast load times.
- Application Layer
	1. DAO Interaction Apps(used participate in their organization’s governance)
	2. DAO Creation Apps(make it easy to deploy a customized DAO)

## GEN

GEN is the cryptocurrency used in DAOStack. It can be used to vote for/against a proposal - this will influence if the proposal rises to the organizational collective. If the a proposal passes, the voters who voted for it will get more GEN - if not, they'll lose their GEN.

## Holographic consensus

A smaller part of the whole (a small group of voters) can be made to effectively represent the whole (all the voters), allowing DAOs to make fast decisions while maintaining value-alignment.

## Reputation

A score assigned to each user that represents that user’s voter power. Each DAO has a ledger of Reputation scores - Reputation cannot be directly transferred from peer to peer. It is distributed through the passing of proposals inside the DAO.

