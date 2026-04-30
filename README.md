# Agents-On-chain
# 🤖 Agents on Chain — 30 Days: Basics to Advanced

> *A structured 30-day LinkedIn series by a Solidity developer learning to build, secure, and ship AI agents on blockchain.*

## 🧭 What is this?

Most AI agent content is either too Web2 or too surface-level.

This series is built **from a Solidity developer's perspective** — every concept is bridged from something you already know as a blockchain dev. If you've written smart contracts, you're closer to building on-chain agents than you think.

**35 posts. 5 weeks. 1 working DeFi Guardian agent shipped at the end.**


## 🗺️ The Bridge — What You Already Know Maps Directly to Agents

| Solidity Concept | Agent Equivalent |
|---|---|
| Smart contract | Agent's on-chain executor — same Solidity, new trigger |
| Reentrancy guard | Circuit breaker that pauses an agent acting anomalously |
| Access control (roles) | Session keys — who can tell the agent what to do |
| Events & logs | Agent's sensory input — how it reads on-chain state |
| Proxy pattern | Smart account — upgradeable wallet for the agent |
| Security audit | Agent security review — prompt injection + access control |

---

## 🗓️ Series Roadmap

```
You know Solidity → Week 1–2: Agent Basics → Week 3: The Bridge → Week 4: Build Patterns → Week 5: Ship DeFi Guardian
```

---

## 📅 Week-by-Week Breakdown

### Week 1 — What even is an AI agent?
> Apr 26 – May 2 · For blockchain devs who don't know agents yet

| Day | Topic | Format | Post |
|-----|-------|--------|------|
| D1 | I finished 100 days of Solidity. Here's why my next series is about AI agents | Explainer | [🔗]() |
| D2 | LLM vs AI Agent: one answers questions, the other takes actions | Visual | [🔗]() |
| D3 | The 4 parts of every AI agent: Perception · Memory · Reasoning · Action | Explainer | [🔗]() |
| D4 | ReAct loop in plain English: how an agent thinks before it acts | Visual | [🔗]() |
| D5 | Your first LangChain agent in Python: 20 lines that perceive, decide, and act | Code | [🔗]() |
| D6 | 🔥 ChatGPT is not an agent. Here's why that distinction matters | Hot take | [🔗]() |
| D7 | Week 1 recap: 7 things I learned about agents as a Solidity developer | Build log | [🔗]() |

---

### Week 2 — Why agents need blockchains
> May 3 – May 9 · The problem with autonomous money

| Day | Topic | Format | Post |
|-----|-------|--------|------|
| D8  | What happens when your AI agent needs to pay for something? | Explainer | [🔗]() |
| D9  | EOA wallets were built for humans — here's every way they fail for agents | Visual | [🔗]() |
| D10 | The moment I realised agents and smart contracts need each other | Hot take | [🔗]() |
| D11 | ERC-4337: the standard that turns a smart contract into an agent's wallet | Explainer | [🔗]() |
| D12 | UserOperation struct decoded — every field, every purpose | Code | [🔗]() |
| D13 | Coinbase Agentic Wallets: how a $100B company solved the agent money problem | Case study | [🔗]() |
| D14 | Week 2 build: I deployed a minimal ERC-4337 smart account on Base Sepolia | Build log | [🔗]() |

---

### Week 3 — Building the bridge (hands-on)
> May 10 – May 16 · Session keys, Bundlers, Paymasters, Chainlink

| Day | Topic | Format | Post |
|-----|-------|--------|------|
| D15 | Session keys: giving your agent a $10/day limit instead of your whole wallet | Explainer | [🔗]() |
| D16 | Implementing a spending-capped session key with ZeroDev Kernel — full code | Code | [🔗]() |
| D17 | Paymasters: a protocol can pay your agent's gas so it never needs ETH | Explainer | [🔗]() |
| D18 | Chainlink Functions: how a smart contract calls an AI model and gets the answer on-chain | Explainer | [🔗]() |
| D19 | Chainlink Functions request + fulfillment — end-to-end Solidity code | Code | [🔗]() |
| D20 | x402: the protocol that lets agents pay for APIs with stablecoins | Case study | [🔗]() |
| D21 | Week 3 build: agent reads Aave health factor + sends alert. 80 lines | Build log | [🔗]() |

---

### Week 4 — Real world agent patterns
> May 17 – May 23 · Liquidation · Governance · Treasury · Identity

| Day | Topic | Format | Post |
|-----|-------|--------|------|
| D22 | The liquidation agent: observe → reason → trigger → verify | Explainer | [🔗]() |
| D23 | Liquidation agent contract: health check + session key trigger — Solidity | Code | [🔗]() |
| D24 | I built the liquidation agent. Here's what worked, broke, and surprised me | Build log | [🔗]() |
| D25 | DAO governance agent: parsing proposal calldata to flag protocol risks | Explainer | [🔗]() |
| D26 | 🔥 AI agent swarms will manipulate DeFi protocols within 12 months | Hot take | [🔗]() |
| D27 | World ID + AgentKit: ZK proof that a human is behind your agent | Case study | [🔗]() |
| D28  | Week 4 recap: 4 agent patterns every Solidity dev should know | Visual | [🔗]() |

---

### Week 5 — Agent security + final build reveal
> May 24 – May 30 · Your Solidity background is your edge here

| Day | Topic | Format | Post |
|-----|-------|--------|------|
| D29 | Prompt injection on-chain: how an attacker poisons your agent through event data | Explainer | [🔗]() |
| D30 | I ran a prompt injection attack on my own agent. Every step + the fix | Case study | [🔗]() |
| D31 | Circuit breaker pattern: pausing an agent acting outside its rules — Solidity | Code | [🔗]() |
| D32 | Agent security checklist: 8 things to audit before deploying an on-chain agent | Visual | [🔗]() |
| D33 | 🔥 Agent auditing will be bigger than smart contract auditing by 2027 | Hot take | [🔗]() |
| D34 | DeFi Guardian build sprint: session keys + Chainlink + LangChain in one agent | Build log | [🔗]() |
| D35 | 30 days. 1 working DeFi agent. GitHub + demo + what I'd do differently | Build log | [🔗]() |

---

## 📁 Repo Structure

```
agents-on-chain-30days/
├── README.md
├── week-1/
│   ├── day-01.md
│   └── ...
├── week-2/
├── week-3/
├── week-4/
├── week-5/
├── code/
│   ├── session-key.sol
│   ├── chainlink-functions.sol
│   ├── circuit-breaker.sol
│   ├── liquidation-agent.sol
│   └── langchain-agent.py
└── resources.md
```

---

## 🛠️ Tech Stack Used in Builds

- **Solidity** — smart contracts, session keys, circuit breakers
- **Python + LangChain** — agent reasoning and orchestration
- **ERC-4337** — smart account / account abstraction
- **ZeroDev Kernel** — session key implementation
- **Chainlink Functions** — on-chain AI oracle calls
- **Base Sepolia** — testnet for all deployments
- **Aave** — health factor monitoring in Week 3 build

---

## 🔗 Connect

If you're a Solidity dev curious about agents — follow the series on LinkedIn. Every post is written to build on the last one.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Matimand-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/YOUR_HANDLE)

---

*This repo is a live archive — updated daily as posts go live.*
