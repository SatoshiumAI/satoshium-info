# ⚡ Layer-2 Basics — Explained

“Layer 2” means building on top of Bitcoin without changing Bitcoin’s core rules.

The goal is simple:

Keep the base layer conservative and verifiable  
while enabling faster payments and expanded capabilities above it.

---

## 🔎 The Simple Definition

A Layer-2 system allows people to transact faster or cheaper than the base layer while still relying on Bitcoin for final settlement.

Think:

- **Layer 1 (Bitcoin)** → security, neutrality, verification
- **Layer 2** → speed, flexibility, usability

Layer 2 does not replace Bitcoin.

It builds on Bitcoin.

---

## 🧱 Why Layer 2 Exists

Bitcoin intentionally limits block space so anyone can verify the network independently.

This preserves decentralization.

However, it also means:

the entire world cannot transact directly on-chain every day.

Layering solves this tradeoff.

Instead of changing Bitcoin’s rules, additional activity moves to higher layers.

Bitcoin stays stable while usage scales.

---

## ⚖️ Settlement vs Payments (The Key Split)

The simplest mental model:

**Layer 1**

Final settlement and global truth

**Layer 2**

Speed and everyday activity

This mirrors how large financial systems already work:

activity happens continuously  
settlement happens periodically

L2 is activity.  
L1 is finality.

---

## 🧩 Common Layer-2 Types

Layer 2 is a category, not a single system.

Examples include:

**Lightning Network**

Designed for instant payments using channels and liquidity.

**Sidechains**

Separate blockchain environments with pegged BTC and additional features.

**Federated systems**

Fast and simple systems operated by trusted groups.

**Rollup-style approaches**

Emerging methods that batch activity and settle proofs back to Bitcoin.

Each approach trades decentralization, speed, privacy, and trust differently.

---

## ⚠️ Trust Models (What Can Go Wrong)

Leaving the base layer introduces new assumptions.

Key risks include:

- operator risk (control by intermediaries)
- bridge risk (moving BTC between systems)
- custody risk (who holds keys)
- complexity risk (harder verification)

Bitcoin reduces trust.

Layer 2 often reintroduces some trust.

The goal is understanding where that trust exists.

---

## 🔐 Custody on Layer 2

Custody remains the most important question:

Who can move the bitcoin?

Two common models:

**Self-custodial Layer 2**

You control keys, but setup may be more complex.

**Custodial Layer 2**

Simpler experience, but a provider controls funds.

Satoshium guideline:

Keep long-term savings on Layer 1 cold storage.  
Use Layer 2 as a spending layer.

---

## 🧭 How to Evaluate a Layer-2 System

Before using any L2, ask:

- Do you control the keys?
- Can you exit independently back to Layer 1?
- Who operates the system?
- What is enforced by Bitcoin vs enforced by people?
- Has it survived real stress events?
- What is the intended use case?
- Are you using it for spending or saving?

If the trust model is unclear, keep balances small.

---

## ❓ Quick FAQ

**Is Lightning a Layer 2?**

Yes. It is the most widely used Bitcoin Layer-2 for instant payments.

**Does Layer 2 change Bitcoin?**

No. True Layer-2 systems operate without modifying Bitcoin’s base rules.

**Is Layer 2 always safe?**

Safety depends on the trust model and custody structure.

**What’s the best setup for most people?**

Cold storage on Layer 1 for savings  
Layer 2 for everyday spending

---

Layer: Education Layer  
Track: Bitcoin  
Section: Lightning Network  
Classification: Foundational Scaling Concept Page  
Namespace: satoshium-info  
Status: Active  
Role: Introduces Layer-2 scaling as the framework for understanding Lightning and future Bitcoin infrastructure
