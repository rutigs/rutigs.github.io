---
title: "What's a Cryptocurrency?"
layout: post
date: 2017-10-04
headerImage: false
tag:
- distributed-systems
- blockchain
- cryptocurrency
star: false
category: blog
author: nickrutigliano
description: A description of cryptocurrency
---

## Intro

I was recently tasked with the assignment to explain something deeply technical in nature to someone from a non-technical background or an area of study different from my own. Given my recent interests in cryptocurrencies and the somewhat recent fork of Bitcoin I chose _cryptocurrency_.

It is worth noting that I ignore the blockchain in my explanation that follows. While hugely important it's not something I felt was important to both a bystander of the ecosystem and a non-technical reader to understand how these currencies operate at entry level.

##### Briefing

A cryptocurrency is a digital currency that is designed to work as a unit of exchange using cryptography to provide security of transactions as well as the creation of additional units. Cryptocurrencies began to become popular in 2009 with the creation of the Bitcoin, a cryptocurrency currently valued at $3624.57 USD as of September 22.

##### What (Modern) Cryptocurrencies Are Not

Crytocurrencies have existed before Bitcoin but these were ones that were not **decentralized**. This is an important distinction and one that explains its recent popularity despite digital currencies having existed for two decades before it. Simply put, the currency being decentralized, means there is no governing bodies, federal oversight, or single point of operation. The system is run by all the members who participate within its protocols.  If it were to be operated by a corporate or governmental entity, it would largely be the same as the digital currency provided through your modern financial systems like debit and credit as these entity hold sole responsibility for your money and your access to it; cryptocurrencies are entirely controlled by its users. It is suffice to say that cryptocurrency operations happen from at a peer-to-peer level while traditional currencies operate with an organization as the middle man between you and whoever you are exchanging with when using interac or credit.

##### How are the transactions secure?

Transactions with cryptocurrencies require you to hold sole ownership of your private key(s). It is easy to think of a private key as a combination of personal ID and a password. This gives you the ability to both verify your identity and protect your security. To understand the process of how these keys are used in transactions you first need to understand public key cryptography.

In a public key cryptographic system each user has two keys: a public one and a private one.  Each user keeps their private key to themselves and shares their public key to all the other users of the system. These keys are created in such a way, that when used in mathematical functions for encrypting and decrypting messages, the private key can decrypt messages encrypted with the public key. An example can be shown as such:

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Public_key_encryption.svg/525px-Public_key_encryption.svg.png)

Putting this all together we get a system of secure transactions within a cryptocurrencies ecosystem. When Bob wishes to send Alice some money he encrypts the transaction with Alice's public key, and upon receiving the transaction Alice uses her private key to decrypt and receive it. It is this use of public-private key cryptography that guarantees if someone were to send you money, only you would be able to receive it.

It is important to note that this process of public key encryption and private key decryption is not bi-directional, which means cryptocurrency transactions are refundable or reversible.

##### Who or what makes units of cryptocurrencies?

With a computer and the right software, any member of the system is capable of creating or more properly put, being rewarded with units of the currency. The units are created as follows. When a series of transactions is broadcasted they must be proven and verified before being integrated into the ledger or the history of all the transactions. Members race to prove the transaction cryptographically and upon  the success of doing so, are rewarded a quantity of currency by the system. It is this cryptographic proof-of-work that is often referred to as the process of mining.  While verifying a transaction that is proved is easy, the act of proving is computationally expensive and time-consuming and provides financial incentive to all members of the system to help ensure the integrity and history of system.

##### What are some other key differences with traditional currencies?

**Wallet**: Cryptocurrencies operate with a digital wallet. Unlike your physical wallet, your digital wallet does not technically store your money anywhere. Instead what you store are the secure private keys that are used to access your wallet address and sign transactions verifying your identity. By having these private keys you can access all the transactions to and from your wallet and reconstruct your balance and proceed to make and receive transactions. 

**Fraud: **The currencies cannot be counterfeited or reversed by the sender as it is not possible with the use of public key cryptography mentioned above. Whereas traditional systems such as PayPal or credit card charge-backs are prone to this.

**Open Access: **Everyone in the world who has access to the internet has access to cryptocurrencies. This  provides a currency free of exchange rates and accessible to use at the international level with no problems.

Sources:

Cryptocurrency. (2017, September 19). Retrieved September 22, 2017, from https://en.wikipedia.org/wiki/Cryptocurrency

Buy/Sell Digital Currency. (n.d.). Retrieved September 22, 2017, from https://www.coinbase.com/

Nakamoto, S. (n.d.). *Bitcoin: A Peer-to-Peer Electronic Cash System*[PDF]. Www.bitcoin.org. https://bitcoin.org/bitcoin.pdf

Rosic, A. (2016, November 22). 7 Incredible Benefits Of Cryptocurrency. Retrieved September 22, 2017, from http://www.huffingtonpost.com/ameer-rosic-/7-incredible-benefits-of-_1_b_13160110.html
