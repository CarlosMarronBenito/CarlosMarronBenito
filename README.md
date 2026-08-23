# `> whoami`

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   CARLOS MARRÓN                                              │
│   Cybersecurity Engineer × Web3 Security Researcher          │
│                                                              │
│   Smart Contracts  •  DeFi  •  Blockchain Security  •  AI    │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

> **I break things before attackers do.**
> Hunting real-world vulnerabilities across smart contracts, DeFi protocols and blockchain infrastructure.

---

### `security.log`

```diff
+ 2 Critical vulnerabilities
+ $400K+ confirmed funds at risk
+ $4,116+ total security earnings
+ Findings across Immunefi · Code4rena · Sherlock
+ Building AI-powered audit agents

- trusting code without trying to break it
```

---

# `./findings`

> **Real vulnerabilities. Reproducible PoCs. Responsible disclosure.**

### ⏳ Pending Results / Rewards

> Findings under review or without finalized rewards are **not counted in confirmed statistics or total earnings**.

| Program          | Platform | Findings                      | Status                |
| ---------------- | -------- | ----------------------------- | --------------------- |
| 🔥 **Firelight** | Immunefi | 🟠 `2× High` · 🟢 `1× Low`    | ⏳ **Pending Results** |
| ⚛️ **Quantus**   | Immunefi | 🟠 `3× High` · 🔵 `1× Medium` | ⏳ **Pending Results** |
| 📊 **Metric**    | Sherlock | 🔵 `2× Medium`                | ⏳ **Pending Results**  |

---

### ✅ Confirmed Findings

| ID        | Platform       |        Severity | Impact                                     | Status            |     Reward |
| --------- | -------------- | --------------: | ------------------------------------------ | ----------------- | ---------: |
| `BBP-001` | Private Report | 🔴 **Critical** | ~$400K Funds at Risk                       | Confirmed · OOS   |          — |
| `BBP-002` | Private Report | 🔴 **Critical** | ~$16K Funds at Risk                        | ✅ Paid            | **$1,600** |
| `BBP-006` | Code4rena      |   🔵 **Medium** | Permanent DoS of Lending Market Onboarding | ✅ Paid            |   **$732** |
| `BBP-008` | Immunefi       |      🟢 **Low** | Unauthorized Gas Sponsorship               | ⏳ Pending Payment | **$1,000** |
| `BBP-003` | Immunefi       |      🟢 **Low** | Stale Migration Approval Logic             | ✅ Paid            |   **$340** |
| `BBP-007` | Immunefi       |   ⚪ **Insight** | Future Integration Fund Drain Risk         | ✅ Paid            |   **$250** |
| `BBP-004` | Sherlock       |      🟢 **Low** | Sponsorship Denial of Service              | ✅ Paid            |   **$187** |
| `BBP-005` | Immunefi       |      🟢 **Low** | Bond Freezing / Funds Locked               | ✅ Paid            |     **$7** |

---

### `findings.db`

| Severity         | ✅ Confirmed | ⏳ Pending |  Total |
| ---------------- | ----------: | --------: | -----: |
| 🔴 **Critical**  |       **2** |     **0** |  **2** |
| 🟠 **High**      |       **0** |     **5** |  **5** |
| 🔵 **Medium**    |       **1** |     **3** |  **4** |
| 🟢 **Low**       |       **4** |     **1** |  **5** |
| ⚪ **Insight**    |       **1** |     **0** |  **1** |
| **All Findings** |       **8** |     **9** | **17** |

| Metric                         |       Value |
| ------------------------------ | ----------: |
| 💰 **Total Earnings**          | **$4,116+** |
| ⚠️ **Confirmed Funds at Risk** |  **$400K+** |

```text
pending_queue/
├── firelight/
│   ├── HIGH
│   ├── HIGH
│   └── LOW
│
├── quantus/
│   ├── HIGH
│   ├── HIGH
│   ├── HIGH
│   └── MEDIUM
│
└── metric/
    ├── MEDIUM
    └── MEDIUM

9 findings pending final results / rewards...
```

---

## `./reports`

### 🔴 `BBP-001` — Critical

**~$400,000 in Funds at Risk**

Private responsible disclosure. Confirmed vulnerability, but considered out of scope.

→ [Redacted Report](./reports/BBP-001-redacted-critical.pdf)

---

### 🔴 `BBP-002` — Critical

**~$16,000 in Funds at Risk · $1,600 Reward**

→ [Public Disclosure](https://www.linkedin.com/feed/update/urn:li:activity:7388469541724524544/)

---

### 🔵 `BBP-006` — Medium · Code4rena

**Permanent DoS of Lending Market Onboarding · $732 Reward**

→ Disclosure Pending

---

### 🟢 `BBP-008` — Low · Immunefi

**Unauthorized Gas Sponsorship · $1,000 Reward**

→ Write-up Coming Soon

---

### 🟢 `BBP-003` — Low · Immunefi

**Stale Migration Approval Logic · $340 Reward**

→ [View Report](https://reports.immunefi.com/folks-finance-staking-contracts/69794-sc-low-user-cannot-revoke-migration-approval-if-migrator-loses-migrator-role)

---

### ⚪ `BBP-007` — Security Contribution · Immunefi

**Future Integration Fund Drain Risk · $250 Reward**

→ [View OpenZeppelin PR](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/6667)

---

### 🟢 `BBP-004` — Low · Sherlock

**Sponsorship Denial of Service · $187 Reward**

→ [View Report](https://audits.sherlock.xyz/contests/1260/voting/703)

---

### 🟢 `BBP-005` — Low · Immunefi

**Bond Freezing / Funds Locked · $7 Reward**

→ [View Report](https://reports.immunefi.com/base/74357-sc-low-unresolvable-game-state-when-proof-threshold-2-and-deadline-is-missed-in-aggregateverif)

---

# `./research`

### ⚡ Current Focus

```yaml
research:
  - smart-contract-security
  - defi-vulnerability-research
  - blockchain-infrastructure
  - real-world-exploitation

building:
  - autonomous-audit-agents
  - scalable-vulnerability-discovery
  - ai-powered-security-research

methodology:
  - understand-the-system
  - identify-the-assumptions
  - break-the-assumptions
  - build-the-poc
  - responsibly-disclose
```

---

### 🔧 `/toolbox`

`Solidity` · `Foundry` · `EVM` · `Python` · `JavaScript` · `Git` · `DeFi` · `PoC Development`

---

## 👾 About Me

I'm **Carlos Marrón**, a 20-year-old cybersecurity engineer and Web3 security researcher.

I focus on finding **real-world vulnerabilities** in smart contracts, DeFi protocols and blockchain infrastructure — especially across protocols and dApps I personally use.

My research focuses on vulnerabilities capable of producing meaningful impact:

```text
→ Funds stolen
→ Funds frozen
→ Broken authorization
→ Protocol insolvency
→ Denial of Service
→ Economic manipulation
→ Broken protocol assumptions
```

A large part of my work revolves around taking complex systems and asking one question:

> ### **What assumption does this protocol make that I can break?**

Right now, I'm also building **next-generation audit agents** designed to search for live critical vulnerabilities at scale.

---

# `./responsible-disclosure`

Some reports are fully public, while others are partially redacted to avoid exposing private company information, vulnerable codebases, internal communications or unresolved technical details.

For private or sensitive cases:

```text
[REDACTED] Company names
[REDACTED] Contract addresses
[REDACTED] Vulnerable codebases
[REDACTED] Internal communications
[REDACTED] Unresolved exploit paths
[REDACTED] Sensitive PoC details
```

The purpose of this repository is to demonstrate technical security research **without putting organizations, users or funds at risk.**

> **Demonstrate the vulnerability. Protect the users.**

---

# `./contact`

```text
github   → @CarlosMarronBenito
linkedin → Carlos Marrón
```

[**GitHub → @CarlosMarronBenito**](https://github.com/CarlosMarronBenito)
[**LinkedIn → Carlos Marrón**](https://www.linkedin.com/in/carlos-marron-benito/)
