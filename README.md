# `> whoami`

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│   CARLOS MARRÓN                                              │
│   Cybersecurity Engineer × Web3 Security Researcher          │
│                                                              │
│   Smart Contracts  •  DeFi  •  Blockchain Security  •  AI   │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

> **I break things before attackers do.**
> Finding real-world vulnerabilities across smart contracts, DeFi protocols, and blockchain infrastructure.

---

### `security.log`

```diff
+ 2 Critical vulnerabilities
+ $400K+ confirmed funds at risk
+ $4,118+ confirmed security earnings
+ 19 security findings
+ Findings across Immunefi · Code4rena · Sherlock
+ Building AI-powered audit agents

- trusting code without trying to break it
```

---

# `./findings`

> **Real vulnerabilities. Reproducible PoCs. Responsible disclosure.**

### ⏳ Pending Results / Rewards

> Findings still under review or without finalized rewards are **not counted in confirmed statistics or security earnings**.

| Program          | Platform | Findings                      | Status                |
| ---------------- | -------- | ----------------------------- | --------------------- |
| 🔥 **Firelight** | Immunefi | 🟠 `3× High` · 🟢 `2× Low`    | ⏳ **Pending Results** |
| ⚛️ **Quantus**   | Immunefi | 🟠 `3× High` · 🔵 `1× Medium` | ⏳ **Pending Results** |

---

### ✅ Confirmed Findings

| ID        | Platform       |        Severity | Impact                                     | Status            |     Reward |
| --------- | -------------- | --------------: | ------------------------------------------ | ----------------- | ---------: |
| `BBP-001` | Private Report | 🔴 **Critical** | ~$400K Funds at Risk                       | Confirmed · OOS   |          — |
| `BBP-002` | Private Report | 🔴 **Critical** | ~$16K Funds at Risk                        | ✅ Paid            | **$1,600** |
| `BBP-006` | Code4rena      |   🔵 **Medium** | Permanent DoS of Lending Market Onboarding | ✅ Paid            |   **$732** |
| `BBP-009` | Sherlock       |   🔵 **Medium** | Metric Security Finding                    | ✅ Paid            |     **$1** |
| `BBP-010` | Sherlock       |   🔵 **Medium** | Metric Security Finding                    | ✅ Paid            |     **$1** |
| `BBP-008` | Immunefi       |      🟢 **Low** | Unauthorized Gas Sponsorship               | ⏳ Pending Payment | **$1,000** |
| `BBP-003` | Immunefi       |      🟢 **Low** | Stale Migration Approval Logic             | ✅ Paid            |   **$340** |
| `BBP-004` | Sherlock       |      🟢 **Low** | Sponsorship Denial of Service              | ✅ Paid            |   **$187** |
| `BBP-005` | Immunefi       |      🟢 **Low** | Bond Freezing / Funds Locked               | ✅ Paid            |     **$7** |
| `BBP-007` | Immunefi       |   ⚪ **Insight** | Future Integration Fund Drain Risk         | ✅ Paid            |   **$250** |

---

### `findings.db`

| Severity         | ✅ Confirmed | ⏳ Pending |  Total |
| ---------------- | ----------: | --------: | -----: |
| 🔴 **Critical**  |       **2** |     **0** |  **2** |
| 🟠 **High**      |       **0** |     **6** |  **6** |
| 🔵 **Medium**    |       **3** |     **1** |  **4** |
| 🟢 **Low**       |       **4** |     **2** |  **6** |
| ⚪ **Insight**    |       **1** |     **0** |  **1** |
| **All Findings** |      **10** |     **9** | **19** |

| Metric                             |       Value |
| ---------------------------------- | ----------: |
| 💰 **Confirmed Security Earnings** | **$4,118+** |
| ⚠️ **Confirmed Funds at Risk**     |  **$400K+** |
| 🔎 **Confirmed Findings**          |      **10** |
| ⏳ **Pending Findings**             |       **9** |
| 📊 **Total Findings**              |      **19** |

```text
pending_queue/
├── firelight/
│   ├── HIGH
│   ├── HIGH
│   ├── HIGH
│   ├── LOW
│   └── LOW
│
└── quantus/
    ├── HIGH
    ├── HIGH
    ├── HIGH
    └── MEDIUM

9 findings pending final results / rewards...
```

---

# `./reports`

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

→ [View Report](https://code4rena.com/audits/2026-04-k2/submissions/S-108)

---

### 🔵 `BBP-009` — Medium · Sherlock

**Metric Security Finding · Paid**

→ [View Report](https://audits.sherlock.xyz/contests/1279/voting/1697)

---

### 🔵 `BBP-010` — Medium · Sherlock

**Metric Security Finding · Paid**

→ [View Report](https://audits.sherlock.xyz/contests/1279/voting/1698)

---

### 🟢 `BBP-008` — Low · Immunefi

**Unauthorized Gas Sponsorship · $1,000 Reward**

→ Write-up Coming Soon

---

### 🟢 `BBP-003` — Low · Immunefi

**Stale Migration Approval Logic · $340 Reward**

→ [View Report](https://reports.immunefi.com/folks-finance-staking-contracts/69794-sc-low-user-cannot-revoke-migration-approval-if-migrator-loses-migrator-role)

---

### 🟢 `BBP-004` — Low · Sherlock

**Sponsorship Denial of Service · $187 Reward**

→ [View Report](https://audits.sherlock.xyz/contests/1260/voting/703)

---

### 🟢 `BBP-005` — Low · Immunefi

**Bond Freezing / Funds Locked · $7 Reward**

→ [View Report](https://reports.immunefi.com/base/74357-sc-low-unresolvable-game-state-when-proof-threshold-2-and-deadline-is-missed-in-aggregateverif)

---

### ⚪ `BBP-007` — Security Contribution · Immunefi

**Future Integration Fund Drain Risk · $250 Reward**

→ [View OpenZeppelin PR](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/6667)

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

`Solidity` · `Foundry` · `EVM` · `Python` · `JavaScript/TypeScript` · `Docker` · `Git` · `Smart Contract Auditing` · `PoC Development`

---

## 👾 About Me

I'm **Carlos Marrón**, a final-year Cybersecurity Engineering student and Web3 security researcher.

I focus on finding **real-world vulnerabilities** in smart contracts, DeFi protocols, and blockchain infrastructure.

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

Right now, I'm also building **next-generation audit agents** designed to discover high-impact vulnerabilities at scale.

---

# `./responsible-disclosure`

Some reports are fully public, while others are partially redacted to avoid exposing private company information, vulnerable codebases, internal communications, or unresolved technical details.

For private or sensitive cases:

```text
[REDACTED] Company names
[REDACTED] Contract addresses
[REDACTED] Vulnerable codebases
[REDACTED] Internal communications
[REDACTED] Unresolved exploit paths
[REDACTED] Sensitive PoC details
```

The purpose of this repository is to demonstrate technical security research **without putting organizations, users, or funds at risk.**

> **Demonstrate the vulnerability. Protect the users.**

---

# `./contact`

```text
github   → @CarlosMarronBenito
linkedin → Carlos Marrón
```

[**GitHub → @CarlosMarronBenito**](https://github.com/CarlosMarronBenito)
[**LinkedIn → Carlos Marrón**](https://www.linkedin.com/in/carlos-marron-benito/)
