# ⚡ Channels, Liquidity & Routing — Explained

If Lightning is “instant Bitcoin,” then:

- **channels** are the rails
- **liquidity** is the fuel
- **routing** is the navigation layer

Understanding these three concepts explains why some Lightning payments succeed instantly — and why others fail.

---

## 🔎 The Simple Explanation

Lightning moves value through pre-funded connections between participants.

These connections are called **channels**.

- **Channels** hold balances between peers
- **Liquidity** determines how much can move in each direction
- **Routing** links channels together across the network

Lightning works when there is a route with enough liquidity to carry a payment end-to-end.

---

## 🧱 What a Lightning Channel Really Is

A Lightning channel is a shared balance between two participants anchored by a Bitcoin on-chain transaction.

Inside the channel:

- balances update instantly
- transactions occur off-chain
- settlement happens later on-chain

Lifecycle of a channel:

1. **Open** — bitcoin is committed to a shared structure
2. **Use** — balances shift between participants
3. **Close** — final balances settle back to Bitcoin

A helpful mental model:

A channel works like a running tab that settles only when opened or closed.

---

## 💧 Liquidity: Inbound vs Outbound

Liquidity determines whether payments succeed.

It is not simply “how much bitcoin you have.”

It is **where the bitcoin sits inside the channel**.

Two types exist:

**Outbound liquidity**

How much you can send.

**Inbound liquidity**

How much you can receive.

Sending consumes outbound liquidity.  
Receiving consumes inbound liquidity.

Balances shift back and forth over time as payments occur.

---

## 🛰️ Routing: How Payments Find a Path

Lightning payments can travel across multiple nodes.

This means:

- you do not need a direct channel with the recipient
- payments hop across intermediate nodes
- each hop must have sufficient liquidity
- wallets automatically select routes based on availability and cost

Routing is what allows Lightning to scale as a network rather than remain a set of isolated connections.

---

## 🚦 Why Payments Succeed or Fail

Most Lightning payment failures are not technical bugs.

They are liquidity or topology issues.

Common causes include:

- insufficient liquidity somewhere along the route
- temporary node unavailability
- routing fees exceeding acceptable thresholds
- payment size exceeding available channel capacity

A useful analogy:

Lightning behaves like traffic. Sometimes a different route, smaller payment, or retry solves the issue.

---

## 💸 Fees: Why Routes Cost Money

Routing nodes may charge small forwarding fees.

These incentives encourage nodes to:

- provide liquidity
- remain online
- maintain reliable connectivity

Two common fee types:

**Base fee**

A fixed forwarding cost

**Rate fee**

A small percentage based on payment size

Reliable routing is supported by a functioning fee market.

---

## 🧭 Practical Tips for Beginners

If your goal is mostly sending payments:

- use wallets that manage liquidity automatically
- maintain outbound liquidity
- start with smaller transactions while learning

If your goal is receiving reliably:

- ensure inbound liquidity exists
- connect to well-positioned peers
- keep nodes online if self-hosting

Balanced liquidity improves reliability in both directions.

---

## ❓ Quick FAQ

**Do I need to run a Lightning node?**

No. Many wallets manage channels automatically.

**Why can I send but not receive?**

You likely have outbound liquidity but little inbound liquidity.

**Why can I receive but not send?**

Your outbound liquidity is low.

**Is Lightning always instant?**

When a route exists with sufficient liquidity, payments are typically near-instant.

**What explains most real-world Lightning behavior?**

Channels + liquidity + routing together explain nearly everything users experience.

---

Layer: Education Layer  
Track: Bitcoin  
Section: Lightning Network  
Classification: Core Infrastructure Concept Page  
Namespace: satoshium-info  
Status: Active  
Role: Explains how Lightning payment topology and liquidity determine success or failure
