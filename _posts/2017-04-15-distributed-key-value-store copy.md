---
title: "Distributed Key Value Store"
layout: post
date: 2017-04-15 
tag:
 - distributed-systems
 - go
image: 
headerImage: false
projects: true
star: false
hidden: true # don't count this post in blog pagination
description: "A Distributed Key Value Store project written in Go"
category: project
author: nickrutigliano
externalLink: false
---

### What Does It Use?

- Go
- Azure

---

### Key Points

- 1st version of the distributed key value store with multi-node capabilities
- The store provided atomic all or nothing transactions, consistency across nodes and clients, and finally isolation of concurrent transactions
- This version uses 2 phase committing with key locking over the nodes and the client API to achieve this
- Tested across Azure data centers globally
- Implemented a malicious version that works to take over the system when a majority of nodes have been compromised at which point it begins to cancel real transactions from non-malicious nodes

#### [Check it out on Github!](https://www.github.com/rutigs/kvstore)
