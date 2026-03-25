# 🟠 How Bitcoin Works

Bitcoin is not an application.

It is a global network of independent computers enforcing shared rules about money.

These rules allow value to move without banks or central operators.

---

## 📌 One-Sentence Summary

Bitcoin works because thousands of independent nodes enforce the same rules while miners perform proof-of-work to secure transaction history.

---

## 🧱 The Five Core Parts of Bitcoin

Bitcoin operates through five interacting components:

wallets  
transactions  
the mempool  
blocks  
miners and nodes  

Together they maintain a shared ledger anyone can verify.

---

## 🔑 Keys, Addresses, and Ownership

Bitcoin ownership is controlled by cryptographic keys.

Private key  
authorizes spending

Public key  
verifies signatures

Address  
receives payments

If you control the private keys, you control the bitcoin.

Wallets store keys, not coins.

---

## 🔄 Transactions and the Mempool

When sending bitcoin, a wallet creates a transaction that:

references existing outputs you control  
creates new outputs for recipients  
includes a fee  
is signed with your private key  

Valid transactions enter the **mempool**, a waiting area shared across nodes.

Miners select transactions from the mempool to include in blocks.

Fees influence confirmation priority when demand increases.

---

## 📦 Blocks and Confirmations

Transactions are grouped into blocks.

Each block links to the previous block, forming the blockchain.

Confirmation depth represents security:

1 confirmation  
transaction included in a block

multiple confirmations  
increasing difficulty of reversal

Rewriting deeper blocks becomes progressively harder.

---

## ⛏️ Mining and Proof-of-Work

Mining secures Bitcoin’s transaction history.

Miners compete to find valid hashes that satisfy the network target.

The first valid block is broadcast to the network.

Nodes verify the block before accepting it.

Proof-of-work prevents cheap rewriting of history by making attacks expensive.

---

## 🖥️ Nodes and Consensus

Nodes enforce Bitcoin’s rules independently.

They verify:

transaction signatures  
block validity  
supply rules  
double-spend prevention  

Miners propose blocks.

Nodes decide whether those blocks are valid.

Consensus emerges from rule enforcement across many independent nodes.

---

## 💸 Fees and Finality

Bitcoin block space is limited.

Transaction fees help prioritize inclusion.

Higher fees typically confirm faster during congestion.

Finality increases with confirmation depth.

For fast, low-cost payments, Layer-2 systems like the Lightning Network are often used.

---

## 📉 Fixed Supply and Issuance Schedule

Bitcoin supply is capped at:

21,000,000 BTC

New coins enter circulation through block rewards.

Approximately every four years:

the block reward halves

This slows issuance over time.

Mining difficulty adjusts automatically to maintain a steady block rhythm.

---

## ⚠️ What Can Go Wrong

Most risks occur at the user level.

Examples include:

losing private keys  
sending to incorrect addresses  
falling for scams  
keeping funds on exchanges  

Protocol-level attacks are extremely difficult because nodes reject invalid blocks.

Bitcoin itself is not easily altered without broad consensus.

---

## 🧭 How This Page Fits the Education Layer

This page prepares readers to understand:

Proof-of-Work security  
node verification  
self-custody responsibility  
transaction finality  
Layer-2 scaling systems  

It connects Bitcoin’s architecture to practical usage and security expectations.

---

Layer: Education Layer  
Track: Bitcoin  
Section: Foundations  
Classification: Protocol Mechanics Primer  
Namespace: satoshium-info  
Status: Active  
Role: Explains the operational structure of Bitcoin including transactions, blocks, mining, nodes, supply rules, and confirmation security
