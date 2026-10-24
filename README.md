# `> whoami`

# Carlos Marrón

**Cybersecurity Engineer × Web3 Security Researcher**  
`Smart Contracts` · `DeFi` · `Blockchain Security` · `AI-Powered Auditing`

> **I break things before attackers do.**  
> Real-world vulnerabilities. Reproducible PoCs. Responsible disclosure.

[![GitHub](https://img.shields.io/badge/GitHub-CarlosMarronBenito-181717?style=flat-square&logo=github)](https://github.com/CarlosMarronBenito)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Marr%C3%B3n-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/carlos-marron-benito/)
[![Immunefi](https://img.shields.io/badge/Immunefi-CarlosMB-5B3DF5?style=flat-square)](https://immunefi.com/profile/CarlosMB/)
![Aero Top 6](https://img.shields.io/badge/Aero%20%2F%20Sherlock-Top%206-7C3AED?style=flat-square)

---

## `./security.log`

| **≈ $6,758** | **31** | **2 Critical** | **Top 6** |
| :---: | :---: | :---: | :---: |
| Total paid rewards | Tracked findings | Confirmed reports | Aero / Sherlock |

```diff
+ $400K+ at risk in my highest-impact confirmed disclosure
+ 30 findings within rewarded reports and competitions
+ 1 additional confirmed Critical (out of scope, unpaid)
+ Competitions and reports across Sherlock, Immunefi & Code4rena
+ Building autonomous audit agents for scalable vulnerability discovery
- trusting protocol assumptions without testing them
```

**Scope and counting:** This is a curated record of finalized findings, **not every submission or audit I've performed**. The 31 tracked reports comprise **30 in rewarded results** and **one separate confirmed, out-of-scope Critical**. Some contest findings are accepted duplicates or informational reports, not unique vulnerability discoveries or individually paid bounties.

## `./track-record`

**Ordered by reward (highest first), with the exceptional $400K-at-risk disclosure highlighted first.** Aero's individual reward is intentionally hidden, but is included in total earnings.

| Program / report | Confirmed result & impact | Reward / status |
| :--- | :--- | ---: |
| 🔴 **Private security disclosure** · `BBP-001` | **Critical · ~$400,000 funds at risk** — largest single confirmed exposure · [Redacted report](./reports/BBP-001-redacted-critical.pdf) | **Confirmed · OOS · Unpaid** |
| 🏆 **Aero / MetaDEX03** · Sherlock | **Top 6 · 2 Medium · 8 Low · 2 Info** · Aerodrome / Velodrome · [Contest guide](https://github.com/dromos-labs/metadex-public/blob/main/audits/sherlock-contest-auditor-guide.md) · [Public audit report](https://github.com/dromos-labs/metadex-public/blob/main/audits/reports/SherlockContest.pdf) | 🔒 **REDACTED · Paid** |
| 🔴 **Private security disclosure** · `BBP-002` | **Critical · ~$16,000 funds at risk** · [Public disclosure](https://www.linkedin.com/feed/update/urn:li:activity:7388469541724524544/) | **$1,600** |
| 🟢 **Immunefi · Private report** · `BBP-008` | **Low · Unauthorized gas sponsorship** · Public write-up pending | **$1,000** |
| 🔵 **K2 · Code4rena** · `BBP-006` | **Medium · M-04: permanent reserve-ID exhaustion / onboarding DoS** · Credited as **CarlosMB**, also found by other wardens · [Official K2 report](https://code4rena.com/reports/2026-04-k2) · [Submission S-108¹](https://code4rena.com/audits/2026-04-k2/submissions/S-108) | **$732** |
| 🟢 **Folks Finance: Staking Contracts · Immunefi** · `BBP-003` | **Low · #69794: user cannot revoke migration approval after migrator role revocation** · [Official report](https://reports.immunefi.com/folks-finance-staking-contracts/69794-sc-low-user-cannot-revoke-migration-approval-if-migrator-loses-migrator-role) | **$340** |
| ⚛️ **Quantus · Immunefi** | **#17 · 3 High + 1 Medium** · 2 original / 2 accepted duplicates · [Official leaderboard](https://immunefi.com/audit-competition/audit-comp-quantus/leaderboard/) | **$330** |
| ⚪ **OpenZeppelin paymaster · Immunefi** · `BBP-007` | **Insight · Effective-prefund mismatch and future integration risk** · [Related upstream fix: OpenZeppelin PR #6667](https://github.com/OpenZeppelin/openzeppelin-contracts/pull/6667) | **$250** |
| 🟢 **Sherlock · Sponsorship DoS report** · `BBP-004` | **Low · Sponsorship denial of service** · [Sherlock voting reference #703](https://audits.sherlock.xyz/contests/1260/voting/703) | **$187** |
| 🔥 **Firelight · Immunefi** | **#24 · 3 High + 2 Low** · 5 accepted duplicates · [Official leaderboard](https://immunefi.com/audit-competition/audit-comp-firelight-1/leaderboard/) | **$33** |
| 🟢 **Base Azul · Immunefi** · `BBP-005` | **Low · #74357: unresolvable dispute-game state with bond funds locked** · [Official report](https://reports.immunefi.com/base/74357-sc-low-unresolvable-game-state-when-proof-threshold-2-and-deadline-is-missed-in-aggregateverif) | **$7** |
| 🔵 **Metric · Sherlock** · `BBP-009` | **Medium · Metric security finding** · [Sherlock voting reference #1697](https://audits.sherlock.xyz/contests/1279/voting/1697) | **$1** |
| 🔵 **Metric · Sherlock** · `BBP-010` | **Medium · Metric security finding** · [Sherlock voting reference #1698](https://audits.sherlock.xyz/contests/1279/voting/1698) | **$1** |

¹ The individual Code4rena submission page may require login; its **M-04** finding and CarlosMB attribution appear in the public K2 final report.

**Identifier note:** `BBP-001` through `BBP-010` are **my portfolio's internal tracking labels**, not report IDs issued by Immunefi, Code4rena, or Sherlock. Where public platform IDs exist, they appear separately as **#69794**, **#74357**, **M-04**, **S-108**, or a Sherlock voting reference. The OpenZeppelin PR is an **upstream maintainer-authored fix**, linked as related technical evidence rather than a PR authored by me. The private-report amounts and unpublished case descriptions reflect my own disclosures.

**Earnings:** `≈ $6,758` is the sum of paid rewards, including Aero's **REDACTED** prize. This public total is approximate in presentation; rewards for private reports and contest outcomes are not independently displayed on every linked platform.

**Severity breakdown:** `2 Critical` · `6 High` · `6 Medium` · `14 Low` · `3 Informational / Insight` = **31** tracked findings. Exactly one Critical (`BBP-001`) is confirmed but not rewarded. Accepted duplicates remain explicitly differentiated from original discoveries.

---

## `./research`

I'm a final-year **Cybersecurity Engineering** student and **Web3 security researcher** focused on vulnerabilities with tangible technical or economic impact: stolen or frozen funds, broken authorization, protocol insolvency, denial of service, and economic manipulation.

I also build **AI-assisted, autonomous smart contract audit agents**, with an emphasis on scalable vulnerability discovery and reproducible proofs of concept.

```yaml
research:
  - smart-contract-security
  - defi-and-economic-exploits
  - blockchain-infrastructure
  - reproducible-proof-of-concepts

building:
  - autonomous-audit-agents
  - scalable-vulnerability-discovery
  - ai-powered-security-research

methodology:
  - understand-the-system
  - identify-the-assumptions
  - break-the-assumptions
  - validate-the-impact
  - disclose-responsibly

toolbox:
  - Solidity / Foundry / EVM
  - Python / JavaScript / TypeScript
  - Docker / Git
```

> **What assumption does this protocol make that I can break?**

---

## `./responsible-disclosure`

I publish reproducible research while protecting users and organizations. Private reports may be redacted to avoid exposing company information, vulnerable deployments, internal communications, unresolved attack paths, or sensitive PoC details.

> **Demonstrate the vulnerability. Protect the users.**

**Contact:** [GitHub](https://github.com/CarlosMarronBenito) · [LinkedIn](https://www.linkedin.com/in/carlos-marron-benito/) · [Immunefi (@CarlosMB)](https://immunefi.com/profile/CarlosMB/)
