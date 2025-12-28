# Awesome Move Security

> A curated list of Move language security resources organized by dialect: Sui Move and Aptos Move smart contract auditing, vulnerability research, and security best practices.

**Move** is a smart contract language originally developed by Meta (formerly Facebook) for the Diem blockchain, now powering Sui and Aptos. Unlike Solidity, Move features a resource-oriented programming model with built-in safety guarantees, yet security vulnerabilities remain possible.

---

## Table of Contents

- [SUI MOVE SECURITY](#sui-move-security)
  - [Sui-Specific Security Articles](#sui-specific-security-articles)
  - [Sui Security Tools](#sui-security-tools)
  - [Sui Public Audit Reports](#sui-public-audit-reports)
  - [Sui CTFs and Challenges](#sui-ctfs-and-challenges)
  - [Sui Security Training](#sui-security-training)
  - [Sui Exploits and Incidents](#sui-exploits-and-incidents)

- [APTOS MOVE SECURITY](#aptos-move-security)
  - [Aptos-Specific Security Articles](#aptos-specific-security-articles)
  - [Aptos Security Tools](#aptos-security-tools)
  - [Aptos Public Audit Reports](#aptos-public-audit-reports)
  - [Aptos CTFs and Challenges](#aptos-ctfs-and-challenges)
  - [Aptos Exploits and Incidents](#aptos-exploits-and-incidents)
  - [Aptos Bug Bounty Programs](#aptos-bug-bounty-programs)
  - [Aptos Security Documentation](#aptos-security-documentation)

- [GENERAL MOVE SECURITY](#general-move-security)
  - [General Move Security Articles](#general-move-security-articles)
  - [Cheatsheets and Quick References](#cheatsheets-and-quick-references)
  - [Security Audit Firms](#security-audit-firms)
  - [Cross-Platform Bug Bounty Programs](#cross-platform-bug-bounty-programs)

---

# SUI MOVE SECURITY

## Sui-Specific Security Articles

### Audit Technique Guides

| Title | Source | Link |
|-------|--------|------|
| Introduction to Auditing Sui Move Contracts | SlowMist | [Medium](https://slowmist.medium.com/slowmist-introduction-to-auditing-sui-move-contracts-da005149f6bc) |
| Sui Objects Security Principles and Best Practices | MoveBit | [Blog](https://www.movebit.xyz/blog/post/Sui-Objects-Security-Principles-and-Best-Practices.html) |
| Greater Ecosystem Security Through Audits | Sui Official | [Blog](https://blog.sui.io/security-audits-and-move-registry/) |

### Vulnerability Analysis

| Title | Source | Link |
|-------|--------|------|
| Is the Move Language Secure? Typus Permission-Validation Vulnerability | SlowMist | [Medium](https://slowmist.medium.com/is-the-move-language-secure-the-typus-permission-validation-vulnerability-755a5175f7c3) |
| Bluefin Vulnerabilities Explanation | MoveBit | [Blog](https://www.movebit.xyz/blog/post/Bluefin-vulnerabilities-explanation-1.html) |
| MoveBit Discovers Vulnerability in Sui Cross-Chain Protocol | MoveBit | [Blog](https://www.movebit.xyz/blog/post/MoveBit-Discovers-and-Helps-Fix-Vulnerability-in-Sui-Cross-Chain-Protocol-20241012.html) |

---

## Sui Security Tools

### Formal Verification

| Tool | Description | Link |
|------|-------------|------|
| **Sui Prover** | Formal verification tool by Asymptotic for mathematically verifying contract properties | [GitHub](https://github.com/asymptotic-code/sui-prover) |

### Fuzzing Tools

| Tool | Description | Link |
|------|-------------|------|
| **Sui Fuzzer** | FuzzingLabs fuzzing tool for Sui contracts | [GitHub](https://github.com/FuzzingLabs/sui-fuzzer) |

---

## Sui Public Audit Reports

| Protocol | Auditor(s) | Report Link |
|----------|-----------|-------------|
| **Cetus Protocol** | MoveBit | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20MoveBit.pdf) |
| **Cetus Protocol** | OtterSec | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20OtterSec.pdf) |
| **Cetus Protocol** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/CetusProtocol%20-%20Zellic%20Audit%20Report.pdf) |
| **Suilend** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Suilend%20-%20Zellic%20Audit%20Report.pdf) |
| **Bucket Protocol** | OtterSec, MoveBit | [GitHub](https://github.com/Bucket-Protocol/Audit) |
| **KriyaDEX** | MoveBit | [PDF](https://github.com/movebit/Sampled-Audit-Reports/blob/main/reports/KriyaDEX-Smart-Contract-Audit-Report.pdf) |
| **Streamflow (Sui)** | MoveBit | [PDF](http://movebit.xyz/reports/Streamflow-Final-Audit-Report.pdf) |
| **Chirp Network** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Chirp%20Network%20-%20Zellic%20Audit%20Report.pdf) |
| **Magma Finance** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Magma%20Finance%20-%20Zellic%20Audit%20Report.pdf) |
| **Garden Move Deploy** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Garden%20Move%20Deploy%20-%20Zellic%20Audit%20Report.pdf) |
| **Magna Airlock** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Magna%20Airlock%20-%20Zellic%20Audit%20Report.pdf) |
| **Sui AMM Swap** | MoveBit | [PDF](https://movebit.xyz/file/Sui-AMM-swap-Contracts-Audit-Report.pdf) |
| **Scallop Lend** | Zellic, OtterSec, MoveBit | [Docs](https://docs.scallop.io/protocol/auditing) |
| **Move and Sui Security Assessment** | Zellic | [PDF](https://github.com/sui-foundation/security-audits/blob/main/docs/Move%20and%20Sui%20Security%20Assessment%20-%20Zellic%20Audit%20Report.pdf) |

---

## Sui CTFs and Challenges

| Competition | Organizer | Link |
|-------------|-----------|------|
| **MoveCTF** | MoveBit, ChainFlag, OtterSec | [Website](https://movectf.movebit.xyz/) |
| **Sui Vietnam MoveCTF** | MoveBit | [Website](https://suictf.movebit.xyz/) |
| **MetaTrust Web3 Security CTF** | MetaTrust Labs, Mysten Labs | Various |
| **Numen Cyber CTF 2023** | Numen Cyber | [GitHub](https://github.com/numencyber/NumenCTF_2023) |

**Challenge Repositories:**

| Repository | Description | Link |
|------------|-------------|------|
| **MoveCTF-1st-Challenge** | First MoveCTF challenges | [GitHub](https://github.com/movectf/MoveCTF-1st-Challenge) |

**CTF Writeups:**

| Writeup | Competition | Link |
|---------|-------------|------|
| MoveCTF 2024 Writeup | MoveCTF | [Amber Group](https://ambergroup.medium.com/movectf-2024-writeup-f74784e020c4) |
| MetaTrust CTF Sui 2023 | MetaTrust | [leoq7](https://leoq7.com/2023/09/MetaTrust-CTF-Sui/) |
| Move CTF 2024 Writeup | MoveCTF | [ZAN](https://medium.com/@zan.top/move-ctf-2024-writeup-a9baa0c043e7) |
| Move CTF Writeup | MoveCTF 2022 | [GitHub](https://github.com/saruman9/move_ctf_writeup) |

---

## Sui Security Training

### Official Sui Resources

| Course | Link |
|--------|------|
| Sui Move Intro Course | [GitHub](https://github.com/sui-foundation/sui-move-intro-course) |
| Sui Object Model Workshop | [GitHub](https://github.com/sui-foundation/sui-object-model-workshop) |

### Third-Party Sui Training

| Course | Platform | Link |
|--------|----------|------|
| Move on Sui Bootcamp | Rise In | [Bootcamp](https://www.risein.com/bootcamps/move-on-sui-bootcamp) |
| Build on Sui Track | Metaschool | [Course](https://metaschool.so/sui) |
| Secure Your Sui Smart Contracts | QuillAudits | [Blog](https://www.quillaudits.com/blog/web3-security/secure-your-sui-smart-contracts) |

---

## Sui Exploits and Incidents

### Major Sui Exploits

#### Cetus Protocol Hack - May 2025
- **Amount Lost:** ~$223 million (largest Move ecosystem hack)
- **Amount Recovered:** $162 million frozen by validators
- **Root Cause:** Integer overflow in `checked_shlw` function within integer-mate library
- **Post-Mortems:**
  - [Rekt News Analysis](https://rekt.news/cetus-rekt)
  - [Dedaub Technical Analysis](https://dedaub.com/blog/the-cetus-amm-200m-hack-how-a-flawed-overflow-check-led-to-catastrophic-loss/)
  - [Halborn Explanation](https://www.halborn.com/blog/post/explained-the-cetus-hack-may-2025)
  - [Merkle Science Analysis](https://www.merklescience.com/blog/hack-track-how-a-shared-library-bug-triggered-the-223m-cetus-hack)
  - [Verichains Analysis](https://blog.verichains.io/p/cetus-protocol-hacked-analysis)
  - [Crypto News Coverage](https://crypto.news/cetus-protocol-hack-sui-exploit-full-breakdown/)
  - [CCN Coverage](https://www.ccn.com/news/crypto/sui-cetus-260m-exploit/)

---

# APTOS MOVE SECURITY

## Aptos-Specific Security Articles

### Audit Technique Guides

| Title | Source | Link |
|-------|--------|------|
| Move Security Guidelines | Aptos Official | [Docs](https://aptos.dev/build/smart-contracts/move-security-guidelines) |

### Vulnerability Analysis

| Title | Source | Link |
|-------|--------|------|
| Top 10 Aptos Move Bugs | Zellic | [Blog](https://www.zellic.io/blog/top-10-aptos-move-bugs) |
| Moving the Immovables: Lessons From Our Aptos Audit | CertiK | [Blog](https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit) |

---

## Aptos Security Tools

### Formal Verification

| Tool | Description | Link |
|------|-------------|------|
| **Move Prover** | Official formal verifier using Boogie and Z3 SMT solver for proving functional correctness | [GitHub](https://github.com/aptos-labs/aptos-core) |
| **Move Prover Resources** | CertiK guide on Move Prover quality assurance | [Blog](https://www.certik.com/resources/blog/1NygvVeqIwhbUk1U1q3vJF-the-move-prover-quality-assurance-of-formal-verification) |

### Static Analyzers and Linters

| Tool | Description | Link |
|------|-------------|------|
| **Aptos Move Lint** | Built-in linter with security checks for unsafe operations, signer leaks, infinite recursion | [Docs](https://aptos.dev/build/smart-contracts/linter) |
| **aptos-move-analyzer** | Language server with security-focused linting | [GitHub](https://github.com/movebit/aptos-move-analyzer) |
| **aptos-move-analyzer (VSCode)** | VSCode extension supporting Move V1 and V2 | [Marketplace](https://marketplace.visualstudio.com/items?itemName=MoveBit.aptos-move-analyzer) |
| **MoveBit MoveScanner** | Web-based security scanner for Aptos contracts | [Website](https://www.movebit.xyz/MoveScanner) |

### Fuzzing Tools

| Tool | Description | Link |
|------|-------------|------|
| **Move-Smith** | Source-code level fuzzer for Move compilers and VM | [GitHub](https://github.com/aptos-labs/move-smith) |

---

## Aptos Public Audit Reports

| Protocol | Auditor(s) | Report Link |
|----------|-----------|-------------|
| **Cetus Protocol (Aptos)** | MoveBit | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20MoveBit.pdf) |
| **Cetus Protocol (Aptos)** | OtterSec | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20OtterSec.pdf) |
| **Liquidswap (Pontem)** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Pontem%20Liquidswap%20-%20Zellic%20Audit%20Report.pdf) |
| **Liquidswap Formal Verification** | MoveBit | [Blog](https://pontem.network/posts/liquidswap-passes-formal-verification-by-movebit---heres-what-it-means) |
| **Thala Labs MOD** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Thala%20Labs%20Move%20Dollar%20-%20Zellic%20Audit%20Report.pdf) |
| **Econia** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Econia%20-%20Zellic%20Audit%20Report.pdf) |
| **Echelon** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Echelon%20-%20Zellic%20Audit%20Report%20(January).pdf) |
| **Tortuga Liquid Staking** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Tortuga%20Liquid%20Staking%20-%20Zellic%20Audit%20Report.pdf) |
| **Laminar Markets** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Laminar%20-%20Zellic%20Audit%20Report.pdf) |
| **MSafe** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/MSafe%20-%20Zellic%20Audit%20Report.pdf) |
| **PancakeSwap Aptos** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/PancakeSwap%20Aptos%20-%20Zellic%20Audit%20Report.pdf) |
| **PancakeSwap Move** | SlowMist | [PDF](https://github.com/slowmist/Knowledge-Base/blob/master/open-report-V2/smart-contract/SlowMist%20Audit%20Report%20-%20PancakeSwap_MOVE_en-us.pdf) |
| **Wormhole Aptos** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Wormhole%20Aptos%20-%20Zellic%20Audit%20Report.pdf) |
| **LayerZero OFT** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/LayerZero%20OFT%20Wrapper%20Audit%20(January%2019th%202023)%20-%20Zellic%20Audit%20Report.pdf) |
| **Cellana** | MoveBit | [PDF](https://movebit.xyz/reports/Cellana-Smart-Contract-Final-Audit-Report.pdf) |
| **Streamflow (Aptos)** | MoveBit | [PDF](https://movebit.xyz/reports/Streamflow-Aptos-Final-Audit-Report.pdf) |
| **Kanalabs Aggregator** | MoveBit | [PDF](https://movebit.xyz/reports/Kanalabs-aggregator-Smart-Contract-Final-Audit-Report.pdf) |
| **Amnis Finance** | MoveBit, Verichains | [Docs](https://docs.amnis.finance/security-audits) |

---

## Aptos CTFs and Challenges

| Competition | Organizer | Link |
|-------------|-----------|------|
| **CTF MOVEment** | MoveBit, Aptos Foundation | [Website](https://ctfmovement.movebit.xyz/) |
| **Aptos Code Collision CTF** | Aptos Foundation | [CTFtime](https://ctftime.org/event/2433/) |
| **Aave V3 Aptos CTF** | Aave | $100K rewards |

**Challenge Repositories:**

| Repository | Description | Link |
|------------|-------------|------|
| **ctfmovement challenges** | Official CTF MOVEment repos | [GitHub](https://github.com/movebit) |

**CTF Writeups:**

| Writeup | Competition | Link |
|---------|-------------|------|
| MOVEment CTF 2022 Writeup | CTF MOVEment | [Amber Group](https://ambergroup.medium.com/movement-ctf-2022-writeup-4904ff8a82e) |
| CTF Movement Aptos 2022 | CTF MOVEment | [leoq7](https://leoq7.com/2022/12/CTF-Movement-Aptos/) |
| CTFMovement-3 Challenge | CTF MOVEment | [Coinsbench](https://coinsbench.com/draining-tokens-from-a-dex-in-the-movebit-ctfmovement-3-challenge-a-solution-walkthrough-37d8ed737821) |

---

## Aptos Exploits and Incidents

### Major Aptos Exploits

#### Thala Labs Hack - November 2024
- **Amount Lost:** $25.5 million
- **Amount Recovered:** 100% (after $300K bounty negotiation)
- **Root Cause:** Missing validation in v1 farming contract `unstake_max` function
- **Post-Mortems:**
  - [Thala Official Post-Mortem](https://thalalabs.medium.com/thala-nov-15-post-mortem-5aea82bb3916)
  - [Halborn Analysis](https://www.halborn.com/blog/post/explained-the-thala-hack-november-2024)
  - [QuillAudits Analysis](https://www.quillaudits.com/blog/hack-analysis/thala-defi-hack-analysis)

### Critical Aptos Bug Bounty Disclosures

| Vulnerability | Bounty | Impact | Post-Mortem |
|---------------|--------|--------|-------------|
| Wormhole Bridge Aptos | Undisclosed | $5M at risk via unauthorized calls | [Cointelegraph](https://cointelegraph.com/news/certik-discovered-5-million-security-flaw-wormhole-bridge-aptos) |
| Aptos MoveVM Integer Overflow | Undisclosed | Full network DoS potential | [CyberExpress](https://thecyberexpress.com/critical-vulnerability-in-aptos-movevm-patched/) |

---

## Aptos Bug Bounty Programs

### Aptos Layer 1 Programs

| Program | Max Reward | Link |
|---------|------------|------|
| Aptos Labs Bug Bounty | Variable | [GitHub](https://github.com/aptos-labs/aptos-core/security) |
| Aptos Petra Wallet | $100,000 | [Immunefi](https://immunefi.com/bug-bounty/aptos-petra-wallet/) |

### Aptos Protocol Programs

| Program | Max Reward | Link |
|---------|------------|------|
| Econia | $100,000 | [Immunefi](https://immunefi.com/bug-bounty/econia/information/) |
| Liquidswap | $500,000 | [Immunefi](https://immunefi.com/bug-bounty/liquidswap/information/) |

---

## Aptos Security Documentation

| Resource | Link |
|----------|------|
| Move Security Guidelines | [Docs](https://aptos.dev/build/smart-contracts/move-security-guidelines) |
| Aptos Cryptography Docs | [Docs](https://aptos.dev/build/smart-contracts/cryptography) |
| Aptos Rust Secure Coding | [GitHub](https://github.com/aptos-labs/aptos-core/blob/main/RUST_SECURE_CODING.md) |
| Securing the Aptos Framework | [Medium](https://medium.com/aptoslabs/securing-the-aptos-framework-through-formal-verification-14124d1ed660) |
| Securing Move (Aptos Labs & OtterSec) | [Medium](https://medium.com/aptoslabs/securing-move-f81099f5e08c) |
| Aptos Discord | [Discord](https://discord.com/invite/aptosnetwork) |
| Aptos Telegram | [Telegram](https://t.me/aptos) |

---

# GENERAL MOVE SECURITY

## General Move Security Articles

### Audit Technique Guides

| Title | Source | Link |
|-------|--------|------|
| An Auditor's Introduction to Move | OtterSec | [Blog](https://osec.io/blog/2022-09-06-move-introduction) |
| Top Move Smart Contract Auditing Services 2025 | FailSafe | [Article](https://getfailsafe.com/top-move-smart-contract-auditing-companies-services-in-2025/) |

### Vulnerability Analysis

| Title | Source | Link |
|-------|--------|------|
| The Billion Dollar Move Bug | Zellic | [Blog](https://www.zellic.io/blog/the-billion-dollar-move-bug) |
| Move Fast and Break Things: Move Security Part 1 | Zellic | [Blog](https://www.zellic.io/blog/move-fast-and-break-things-pt-1) |
| Move Fast and Break Things: Move Security Part 2 | Zellic | [Blog](https://www.zellic.io/blog/move-fast-break-things-move-security-part-2) |

### Security Best Practices

| Title | Source | Link |
|-------|--------|------|
| Security Analysis of the Move Language | Numen Cyber | [Blog](https://www.numencyber.com/security-analysis-of-the-move-language-game-changer-of-smart-contracts/) |
| What Makes Move Safe? (MoveCon Panel) | Pontem Network | [Blog](https://pontem.network/posts/what-makes-move-safe) |
| Why Move is the Future of Secure Smart Contract Development | Zokyo | [Medium](https://medium.com/zokyo-io/why-move-is-the-future-of-secure-smart-contract-development-7a219e37e00b) |
| Securing Smart Contracts: A Dev's Guide Part I | Movement Labs | [Blog](https://blog.movementlabs.xyz/article/securing-smart-contracts-a-devs-guide-part-i) |
| Move101: Why is Move a Safer Smart Contract Language? | Starcoin | [Medium](https://starcoin.medium.com/move101-why-is-move-a-safer-smart-contract-language-8aef721ada84) |

### SharkTeam Move Security Series

| Article | Link |
|---------|------|
| Logic Verification Vulnerability | [Medium](https://medium.com/@sharkteam/a-vulnerability-perspective-analysis-of-move-language-security-logic-verification-vulnerability-dfd7a5cafb03) |
| Proposal Attack Analysis | [Medium](https://medium.com/@sharkteam/move-language-security-analysis-and-contract-audit-points-proposal-attack-4adaeae2028f) |
| Contract Upgrade Vulnerability | [Medium](https://medium.com/@sharkteam/move-language-security-analysis-and-contract-audit-contract-upgrade-vulnerability-79ec80dce744) |

---

## Cheatsheets and Quick References

| Resource | Platform | Link |
|----------|----------|------|
| Sui Move Security Cheatsheet | Sui | [GitHub](https://github.com/darshan-06/Sui-Move-cheat-sheet/blob/main/sui_move_security_cheatsheet.md) |
| Move Audit Resources | General | [GitHub](https://github.com/0xriazaka/Move-Audit-Resources) |
| Zellic Findings Database | General | [Website](https://reports.zellic.io/findings) |

### Audit Report Repositories

| Repository | Description | Link |
|------------|-------------|------|
| MoveBit Sampled Audit Reports | Multi-platform audit reports | [GitHub](https://github.com/movebit/Sampled-Audit-Reports) |
| Zellic Publications | Multi-platform audit reports | [GitHub](https://github.com/Zellic/publications) |
| Sui Foundation Security Audits | Sui-specific audits | [GitHub](https://github.com/sui-foundation/security-audits) |
| SlowMist Knowledge Base | Multi-platform reports | [GitHub](https://github.com/slowmist/Knowledge-Base) |

---

## Security Audit Firms

### Primary Move Ecosystem Auditors

| Firm | Specialty | Platforms | Website |
|------|-----------|-----------|---------|
| **Monethic** | Smart contract security audits and blockchain security services | Sui, Aptos, Solana, EVM | [monethic.com](https://monethic.com) |
| **MoveBit** | Formal verification pioneer, CTF host, first Move security company | Sui, Aptos | [movebit.xyz](https://www.movebit.xyz) |
| **OtterSec** | Deep manual reviews, Move Prover expertise, Sui Foundation partner | Sui, Aptos | [osec.io](https://osec.io) |
| **Zellic** | Critical vulnerability research, Move bytecode expertise | Sui, Aptos | [zellic.io](https://www.zellic.io) |

### Additional Auditors with Move Capabilities

| Firm | Notable Work | Website |
|------|--------------|---------|
| **CertiK** | Aptos Core audit, Hamster Wheel discovery | [certik.com](https://www.certik.com) |
| **Halborn** | Sui security audits, Pontem Wallet | [halborn.com](https://www.halborn.com) |
| **SlowMist** | PancakeSwap Move audit, audit guides | [slowmist.com](https://www.slowmist.com) |
| **Blaize.Security** | Full-stack Sui defenses | [security.blaize.tech](https://security.blaize.tech) |
| **Certora** | Hybrid audit reports with formal verification | [certora.com](https://www.certora.com) |
| **Hacken** | Move smart contract audits | [hacken.io](https://hacken.io) |
| **Verichains** | Cetus analysis, Amnis Finance audit | [verichains.io](https://verichains.io) |
| **QuillAudits** | Security audits and analysis | [quillaudits.com](https://www.quillaudits.com) |

---

## Cross-Platform Bug Bounty Programs

| Program | Platform | Max Reward | Link |
|---------|----------|------------|------|
| Wormhole | Both | 20,000,000 W | [Immunefi](https://immunefi.com/bug-bounty/wormhole/) |
| Movement Labs Attackathon | Movement | $400,000 | [Immunefi](https://immunefi.com/audit-competition/movement-labs-attackathon/information/) |

---

## Contributing

This resource is maintained to help the Move security community. To contribute:

1. Submit audit reports, tools, or resources via pull request
2. Report broken links or outdated information
3. Share CTF writeups and security research
4. Ensure proper categorization (Sui Move vs Aptos Move vs General)

---

## Disclaimer

This compilation is for educational and research purposes only. Links are provided for reference and do not constitute endorsement. Always verify information independently and conduct your own security assessments. Security vulnerabilities should be reported through official bug bounty channels, not exploited.

---

*Last updated: December 2025*
