---
title: "Distributed Blockchain Key Value Store"
layout: post
date: 2017-04-30 
tag:
 - distributed-systems
 - blockchain
 - go
image: 
headerImage: false
projects: true
star: true
hidden: true # don't count this post in blog pagination
description: "A Distributed Blockchain Key Value Store project written in Go"
category: project
author: nickrutigliano
externalLink: false
---

### What Does It Use?

- Go
- Blockchain
- Azure

---

### Key Points

- 2nd version of the distributed key value store with multi-node capabilities
- The store provided atomic all or nothing transactions, consistency across nodes and clients, and finally isolation of concurrent transactions
- This version used blockchain style proof-of-work SHA256 hashing to verify transactions in a blockchain across all nodes
- Tested across Azure data centers globally
- Implemented a malicious version that works to take over the system when a majority of nodes have been compromised at which point it begins to cancel real transactions from non-malicious nodes

#### [Check it out on Github!](https://www.github.com/rutigs/blockchain-kvstore)
