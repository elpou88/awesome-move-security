# Awesome Move Security

> A curated list of Move language security resources for Sui Move and Aptos Move smart contract auditing, vulnerability research, and security best practices.

**Move** is a smart contract language originally developed by Meta (formerly Facebook) for the Diem blockchain, now powering Sui and Aptos. Unlike Solidity, Move features a resource-oriented programming model with built-in safety guarantees, yet security vulnerabilities remain possible—making specialized security knowledge essential.

---

## Table of Contents

- [Blogs and Security Articles](#blogs-and-security-articles)
  - [Audit Technique Guides](#audit-technique-guides)
  - [Vulnerability Analysis](#vulnerability-analysis)
  - [Security Best Practices](#security-best-practices)
  - [Sui vs Aptos Security Differences](#sui-vs-aptos-security-differences)
- [Formal Verification Resources](#formal-verification-resources)
- [Security Tools and Scanners](#security-tools-and-scanners)
  - [Formal Verification Tools](#formal-verification-tools)
  - [Static Analyzers and Linters](#static-analyzers-and-linters)
  - [Fuzzing Tools](#fuzzing-tools)
  - [IDE Plugins with Security Features](#ide-plugins-with-security-features)
- [Public Audit Reports](#public-audit-reports)
  - [Sui Ecosystem Audits](#sui-ecosystem-audits)
  - [Aptos Ecosystem Audits](#aptos-ecosystem-audits)
  - [Layer 1 Protocol Audits](#layer-1-protocol-audits)
- [CTFs and Security Challenges](#ctfs-and-security-challenges)
  - [Major CTF Competitions](#major-ctf-competitions)
  - [CTF Challenge Repositories](#ctf-challenge-repositories)
  - [CTF Writeups](#ctf-writeups)
- [Security Training and Courses](#security-training-and-courses)
- [Real-Life Exploits and Post-Mortems](#real-life-exploits-and-post-mortems)
  - [Major Exploits](#major-exploits)
  - [Critical Bug Bounty Disclosures](#critical-bug-bounty-disclosures)
- [Cheatsheets and Quick References](#cheatsheets-and-quick-references)
- [Bug Bounty Programs](#bug-bounty-programs)
- [Security Communities and Researchers](#security-communities-and-researchers)
- [Security Audit Firms](#security-audit-firms)

---

## Blogs and Security Articles

### Audit Technique Guides

| Title | Platform | Source |
|-------|----------|--------|
| [Introduction to Auditing Sui Move Contracts](https://slowmist.medium.com/slowmist-introduction-to-auditing-sui-move-contracts-da005149f6bc) | Sui | SlowMist |
| [Move Security Guidelines](https://aptos.dev/build/smart-contracts/move-security-guidelines) | Aptos | Aptos Official |
| [Sui Objects Security Principles and Best Practices](https://www.movebit.xyz/blog/post/Sui-Objects-Security-Principles-and-Best-Practices.html) | Sui | MoveBit |
| [An Auditor's Introduction to Move](https://osec.io/blog/2022-09-06-move-introduction) | General | OtterSec |
| [Top Move Smart Contract Auditing Services 2025](https://getfailsafe.com/top-move-smart-contract-auditing-companies-services-in-2025/) | General | FailSafe |
| [Greater Ecosystem Security Through Audits](https://blog.sui.io/security-audits-and-move-registry/) | Sui | Sui Blog |

### Vulnerability Analysis

| Title | Platform | Source |
|-------|----------|--------|
| [The Billion Dollar Move Bug](https://www.zellic.io/blog/the-billion-dollar-move-bug) | General | Zellic |
| [Top 10 Aptos Move Bugs](https://www.zellic.io/blog/top-10-aptos-move-bugs) | Aptos | Zellic |
| [Move Fast and Break Things: Move Security Part 1](https://www.zellic.io/blog/move-fast-and-break-things-pt-1) | General | Zellic |
| [Move Fast and Break Things: Move Security Part 2](https://www.zellic.io/blog/move-fast-break-things-move-security-part-2) | General | Zellic |
| [Moving the Immovables: Lessons From Our Aptos Audit](https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit) | Aptos | CertiK |
| [Is the Move Language Secure? Typus Permission-Validation Vulnerability](https://slowmist.medium.com/is-the-move-language-secure-the-typus-permission-validation-vulnerability-755a5175f7c3) | Sui | SlowMist |
| [Bluefin Vulnerabilities Explanation](https://www.movebit.xyz/blog/post/Bluefin-vulnerabilities-explanation-1.html) | Sui | MoveBit |
| [MoveBit Discovers Vulnerability in Sui Cross-Chain Protocol](https://www.movebit.xyz/blog/post/MoveBit-Discovers-and-Helps-Fix-Vulnerability-in-Sui-Cross-Chain-Protocol-20241012.html) | Sui | MoveBit |
| [A Systematic Classification of Vulnerabilities in MoveEVM](https://arxiv.org/html/2505.19047v1) | General | Academic |
| [Analyzing Four Types of Critical Security Vulnerabilities in Move](https://link.springer.com/article/10.1007/s10586-025-05439-1) | General | Academic |

### Security Best Practices

| Title | Platform | Source |
|-------|----------|--------|
| [Security Analysis of the Move Language](https://www.numencyber.com/security-analysis-of-the-move-language-game-changer-of-smart-contracts/) | General | Numen Cyber |
| [What Makes Move Safe? (MoveCon Panel)](https://pontem.network/posts/what-makes-move-safe) | General | Pontem Network |
| [Why Move is the Future of Secure Smart Contract Development](https://medium.com/zokyo-io/why-move-is-the-future-of-secure-smart-contract-development-7a219e37e00b) | General | Zokyo |
| [Securing Smart Contracts: A Dev's Guide Part I](https://blog.movementlabs.xyz/article/securing-smart-contracts-a-devs-guide-part-i) | General | Movement Labs |
| [Securing Move](https://medium.com/aptoslabs/securing-move-f81099f5e08c) | Aptos | Aptos Labs & OtterSec |
| [Move101: Why is Move a Safer Smart Contract Language?](https://starcoin.medium.com/move101-why-is-move-a-safer-smart-contract-language-8aef721ada84) | General | Starcoin |

### SharkTeam Move Security Series

- [Logic Verification Vulnerability](https://medium.com/@sharkteam/a-vulnerability-perspective-analysis-of-move-language-security-logic-verification-vulnerability-dfd7a5cafb03)
- [Proposal Attack Analysis](https://medium.com/@sharkteam/move-language-security-analysis-and-contract-audit-points-proposal-attack-4adaeae2028f)
- [Contract Upgrade Vulnerability](https://medium.com/@sharkteam/move-language-security-analysis-and-contract-audit-contract-upgrade-vulnerability-79ec80dce744)

### Sui vs Aptos Security Differences

| Title | Source |
|-------|--------|
| [Aptos vs. Sui: Detailed Blockchain Guide](https://blaize.tech/article-type/overview/aptos-vs-sui-blockchain-a-detailed-guide/) | Blaize |
| [Aptos vs Sui Research Report](https://www.thetie.io/insights/research/aptos-vs-sui/) | The Tie Research |
| [Move Twins: Sui and Aptos Comparison](https://medium.com/ybbcapital/move-twins-how-sui-and-aptos-are-challenging-the-blockchain-landscape-648c89eeb740) | YBB Capital |
| [Aptos vs. Sui vs. Movement Compared](https://www.dwf-labs.com/research/460-aptos-vs-sui-vs-movement-move-blockchains-compared) | DWF Labs |
| [Sui vs. Aptos: How Are These Blockchains Different?](https://www.bankless.com/sui-vs-aptos) | Bankless |

---

## Formal Verification Resources

| Title | Platform | Source |
|-------|----------|--------|
| [Fast and Reliable Formal Verification with Move Prover](https://arxiv.org/abs/2110.08362) | General | Academic (TACAS 2022) |
| [Formal Verification, Move Language, and Move Prover](https://www.certik.com/resources/blog/2wSOZ3mC55AB6CYol6Q2rP-formal-verification-the-move-language-and-the-move-prover) | General | CertiK |
| [Move Prover Quality Assurance](https://www.certik.com/resources/blog/1NygvVeqIwhbUk1U1q3vJF-the-move-prover-quality-assurance-of-formal-verification) | Aptos | CertiK |
| [Sui Prover: Bringing Formal Verification to Sui](https://blog.sui.io/asymptotic-move-prover-formal-verification/) | Sui | Sui Blog |
| [Securing Aptos Framework Through Formal Verification](https://medium.com/aptoslabs/securing-the-aptos-framework-through-formal-verification-14124d1ed660) | Aptos | Aptos Labs |
| [The ABC of Formal Verification with Move](https://medium.com/@seyyedaliayati/the-abc-of-formal-verification-with-move-906ac1b2aaa0) | General | Medium |
| [Liquidswap Passes Formal Verification by MoveBit](https://pontem.network/posts/liquidswap-passes-formal-verification-by-movebit---heres-what-it-means) | Aptos | Pontem |

---

## Security Tools and Scanners

### Formal Verification Tools

| Tool | Platform | Description | Link |
|------|----------|-------------|------|
| **Move Prover** | Aptos | Official formal verifier using Boogie and Z3 SMT solver for proving functional correctness | [GitHub](https://github.com/aptos-labs/aptos-core) |
| **Sui Prover** | Sui | Formal verification tool by Asymptotic for mathematically verifying contract properties | [GitHub](https://github.com/asymptotic-code/sui-prover) |

### Static Analyzers and Linters

| Tool | Platform | Description | Link |
|------|----------|-------------|------|
| **Aptos Move Lint** | Aptos | Built-in linter with security checks for unsafe operations, signer leaks, infinite recursion | [Docs](https://aptos.dev/build/smart-contracts/linter) |
| **Move Bytecode Verifier** | Both | Core VM component enforcing type, resource, and memory safety | [GitHub](https://github.com/move-language/move) |
| **sui-move-analyzer** | Sui | VSCode extension with diagnostics and MSL support | [GitHub](https://github.com/movebit/sui-move-analyzer) |
| **aptos-move-analyzer** | Aptos | Language server with security-focused linting | [GitHub](https://github.com/movebit/aptos-move-analyzer) |
| **MoveBit MoveScanner** | Both | Web-based security scanner | [Website](https://www.movebit.xyz/MoveScanner) |

### Fuzzing Tools

| Tool | Platform | Description | Link |
|------|----------|-------------|------|
| **ItyFuzz** | Sui (WIP) | Hybrid bytecode-level fuzzer combining symbolic execution with fuzzing | [GitHub](https://github.com/fuzzland/ityfuzz) |
| **Move-Smith** | Aptos | Source-code level fuzzer for Move compilers and VM | [GitHub](https://github.com/aptos-labs/move-smith) |
| **Sui Fuzzer** | Sui | FuzzingLabs fuzzing tool for Sui contracts | [GitHub](https://github.com/FuzzingLabs/sui-fuzzer) |
| **move-fuzzer** | Both | Work-in-progress module fuzzer from FuzzLand | [GitHub](https://github.com/fuzzland/move-fuzzer) |

### IDE Plugins with Security Features

| Tool | Platform | Description | Link |
|------|----------|-------------|------|
| **sui-move-analyzer** | Sui | VSCode extension with real-time diagnostics | [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=MoveBit.sui-move-analyzer) |
| **aptos-move-analyzer** | Aptos | VSCode extension supporting Move V1 and V2 | [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=MoveBit.aptos-move-analyzer) |
| **move-mode** | Both | Emacs major mode with LSP support | [GitHub](https://github.com/amnn/move-mode) |
| **Move Web IDE** | Both | Browser-based IDE for Move development | [Website](https://www.movebit.xyz/MoveWebIDE) |

### Security Libraries

| Library | Platform | Description | Link |
|---------|----------|-------------|------|
| **Movemate** | Both | Security-focused module building blocks for governance, math, data structures | [GitHub](https://github.com/pentagonxyz/movemate) |

---

## Public Audit Reports

### Sui Ecosystem Audits

| Protocol | Auditor | Report Link |
|----------|---------|-------------|
| **Cetus Protocol** | MoveBit | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20MoveBit.pdf) |
| **Cetus Protocol** | OtterSec | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20OtterSec.pdf) |
| **Cetus Protocol** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/CetusProtocol%20-%20Zellic%20Audit%20Report.pdf) |
| **Suilend** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Suilend%20-%20Zellic%20Audit%20Report.pdf) |
| **Bucket Protocol** | OtterSec, MoveBit | [GitHub](https://github.com/Bucket-Protocol/Audit) |
| **KriyaDEX** | MoveBit | [PDF](https://github.com/movebit/Sampled-Audit-Reports/blob/main/reports/KriyaDEX-Smart-Contract-Audit-Report.pdf) |
| **Streamflow** | MoveBit | [PDF](http://movebit.xyz/reports/Streamflow-Final-Audit-Report.pdf) |
| **Chirp Network** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Chirp%20Network%20-%20Zellic%20Audit%20Report.pdf) |
| **Magma Finance** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Magma%20Finance%20-%20Zellic%20Audit%20Report.pdf) |
| **Garden Move Deploy** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Garden%20Move%20Deploy%20-%20Zellic%20Audit%20Report.pdf) |
| **Magna Airlock** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Magna%20Airlock%20-%20Zellic%20Audit%20Report.pdf) |
| **Sui AMM Swap** | MoveBit | [PDF](https://movebit.xyz/file/Sui-AMM-swap-Contracts-Audit-Report.pdf) |
| **Scallop Lend** | Zellic, OtterSec, MoveBit | [Docs](https://docs.scallop.io/protocol/auditing) |

### Aptos Ecosystem Audits

| Protocol | Auditor | Report Link |
|----------|---------|-------------|
| **Cetus Protocol** | MoveBit | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20MoveBit.pdf) |
| **Cetus Protocol** | OtterSec | [PDF](https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20OtterSec.pdf) |
| **Liquidswap (Pontem)** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Pontem%20Liquidswap%20-%20Zellic%20Audit%20Report.pdf) |
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
| **Streamflow Aptos** | MoveBit | [PDF](https://movebit.xyz/reports/Streamflow-Aptos-Final-Audit-Report.pdf) |
| **Kanalabs Aggregator** | MoveBit | [PDF](https://movebit.xyz/reports/Kanalabs-aggregator-Smart-Contract-Final-Audit-Report.pdf) |
| **Amnis Finance** | MoveBit, Verichains | [Docs](https://docs.amnis.finance/security-audits) |

### Layer 1 Protocol Audits

| Protocol | Auditor | Report Link |
|----------|---------|-------------|
| **Move and Sui Security Assessment** | Zellic | [PDF](https://github.com/sui-foundation/security-audits/blob/main/docs/Move%20and%20Sui%20Security%20Assessment%20-%20Zellic%20Audit%20Report.pdf) |
| **Initia** | Zellic | [PDF](https://github.com/Zellic/publications/blob/master/Initia%20-%20Zellic%20Audit%20Report.pdf) |

### Audit Report Repositories

- [MoveBit Sampled Audit Reports](https://github.com/movebit/Sampled-Audit-Reports)
- [Zellic Publications](https://github.com/Zellic/publications)
- [Sui Foundation Security Audits](https://github.com/sui-foundation/security-audits)
- [SlowMist Knowledge Base](https://github.com/slowmist/Knowledge-Base)

---

## CTFs and Security Challenges

### Major CTF Competitions

| Competition | Platform | Organizer | Link |
|-------------|----------|-----------|------|
| **MoveCTF** | Sui | MoveBit, ChainFlag, OtterSec | [Website](https://movectf.movebit.xyz/) |
| **CTF MOVEment** | Aptos | MoveBit, Aptos Foundation | [Website](https://ctfmovement.movebit.xyz/) |
| **Sui Vietnam MoveCTF** | Sui | MoveBit | [Website](https://suictf.movebit.xyz/) |
| **Aptos Code Collision CTF** | Aptos | Aptos Foundation | [CTFtime](https://ctftime.org/event/2433/) |
| **MetaTrust Web3 Security CTF** | Sui | MetaTrust Labs, Mysten Labs | Various |
| **Numen Cyber CTF 2023** | Sui | Numen Cyber | [GitHub](https://github.com/numencyber/NumenCTF_2023) |
| **justCTF 2024** | Move | justCTF | Various |
| **Aave V3 Aptos CTF** | Aptos | Aave | $100K rewards |

### CTF Challenge Repositories

| Repository | Platform | Description | Link |
|------------|----------|-------------|------|
| **MoveCTF-1st-Challenge** | Sui | First MoveCTF challenges | [GitHub](https://github.com/movectf/MoveCTF-1st-Challenge) |
| **ctf-blockchain** | Multi | 200+ blockchain CTF challenges including Move | [GitHub](https://github.com/minaminao/ctf-blockchain) |
| **blocksec-ctfs** | Multi | Curated CTF competition index | [GitHub](https://github.com/blockthreat/blocksec-ctfs) |
| **ctfmovement challenges** | Aptos | Official CTF MOVEment repos | [GitHub](https://github.com/movebit) |

### CTF Writeups

| Writeup | Competition | Link |
|---------|-------------|------|
| MoveCTF 2024 Writeup | MoveCTF | [Amber Group](https://ambergroup.medium.com/movectf-2024-writeup-f74784e020c4) |
| MOVEment CTF 2022 Writeup | CTF MOVEment | [Amber Group](https://ambergroup.medium.com/movement-ctf-2022-writeup-4904ff8a82e) |
| CTF Movement Aptos 2022 | CTF MOVEment | [leoq7](https://leoq7.com/2022/12/CTF-Movement-Aptos/) |
| MetaTrust CTF Sui 2023 | MetaTrust | [leoq7](https://leoq7.com/2023/09/MetaTrust-CTF-Sui/) |
| Move CTF 2024 Writeup | MoveCTF | [ZAN](https://medium.com/@zan.top/move-ctf-2024-writeup-a9baa0c043e7) |
| CTFMovement-3 Challenge | CTF MOVEment | [Coinsbench](https://coinsbench.com/draining-tokens-from-a-dex-in-the-movebit-ctfmovement-3-challenge-a-solution-walkthrough-37d8ed737821) |
| Move CTF Writeup | MoveCTF 2022 | [GitHub](https://github.com/saruman9/move_ctf_writeup) |

---

## Security Training and Courses

### Official Resources

| Course | Platform | Link |
|--------|----------|------|
| Move Security Guidelines | Aptos | [Docs](https://aptos.dev/build/smart-contracts/move-security-guidelines) |
| Sui Move Intro Course | Sui | [GitHub](https://github.com/sui-foundation/sui-move-intro-course) |
| Sui Object Model Workshop | Sui | [GitHub](https://github.com/sui-foundation/sui-object-model-workshop) |
| Aptos Move Tutorial | Aptos | [GitHub](https://github.com/aptos-labs/aptos-core/tree/main/aptos-move/move-examples/move-tutorial) |

### Third-Party Training

| Course | Platform | Link |
|--------|----------|------|
| Move on Sui Bootcamp | Sui | [Rise In](https://www.risein.com/bootcamps/move-on-sui-bootcamp) |
| Build on Sui Track | Sui | [Metaschool](https://metaschool.so/sui) |
| Aptos Move by Example | Aptos | [GitBook](https://move-developers-dao.gitbook.io/aptos-move-by-example) |
| Pontem Aptos Tutorial | Aptos | [Docs](https://docs.pontem.network/03.-tutorials/aptos-tutorial) |
| Secure Your Sui Smart Contracts | Sui | [QuillAudits](https://www.quillaudits.com/blog/web3-security/secure-your-sui-smart-contracts) |

---

## Real-Life Exploits and Post-Mortems

### Major Exploits

#### Cetus Protocol Hack (Sui) - May 2025
- **Amount Lost:** ~$223 million (largest Move ecosystem hack)
- **Amount Recovered:** $162 million frozen by validators
- **Root Cause:** Integer overflow in `checked_shlw` function within integer-mate library
- **Post-Mortems:**
  - [Rekt News](https://rekt.news/cetus-rekt)
  - [Dedaub Analysis](https://dedaub.com/blog/the-cetus-amm-200m-hack-how-a-flawed-overflow-check-led-to-catastrophic-loss/)
  - [Halborn Explanation](https://www.halborn.com/blog/post/explained-the-cetus-hack-may-2025)
  - [Merkle Science Analysis](https://www.merklescience.com/blog/hack-track-how-a-shared-library-bug-triggered-the-223m-cetus-hack)
  - [Verichains Analysis](https://blog.verichains.io/p/cetus-protocol-hacked-analysis)

#### Thala Labs Hack (Aptos) - November 2024
- **Amount Lost:** $25.5 million
- **Amount Recovered:** 100% (after $300K bounty negotiation)
- **Root Cause:** Missing validation in v1 farming contract `unstake_max` function
- **Post-Mortems:**
  - [Thala Official Post-Mortem](https://thalalabs.medium.com/thala-nov-15-post-mortem-5aea82bb3916)
  - [Halborn Analysis](https://www.halborn.com/blog/post/explained-the-thala-hack-november-2024)
  - [QuillAudits Analysis](https://www.quillaudits.com/blog/hack-analysis/thala-defi-hack-analysis)

#### Shared Vulnerability Impact (Post-Cetus)
Multiple Sui protocols silently patched the same overflow bug:
- **Kriya DEX:** $10M TVL at risk
- **FlowX Finance:** $4.6M TVL at risk
- **Turbos Finance:** $10.3M TVL with vulnerable code present

### Critical Bug Bounty Disclosures

| Vulnerability | Platform | Bounty | Impact | Post-Mortem |
|---------------|----------|--------|--------|-------------|
| Sui "Hamster Wheel" Attack | Sui | $500,000 | Network shutdown via infinite loop | [CertiK](https://certik.medium.com/unraveling-the-hamsterwheel-how-certik-caught-a-critical-bug-in-sui-aeff568bcb95) |
| Sui Narwhal Network Shutdown | Sui | $50,000 | Temporary network DoS via OOM | [Immunefi](https://immunefi.com/blog/bug-fix-reviews/sui-network-shutdown/) |
| Wormhole Bridge Aptos | Aptos | Undisclosed | $5M at risk via unauthorized calls | [Cointelegraph](https://cointelegraph.com/news/certik-discovered-5-million-security-flaw-wormhole-bridge-aptos) |
| Aptos MoveVM Integer Overflow | Aptos | Undisclosed | Full network DoS potential | [CyberExpress](https://thecyberexpress.com/critical-vulnerability-in-aptos-movevm-patched/) |

---

## Cheatsheets and Quick References

| Resource | Platform | Link |
|----------|----------|------|
| Sui Move Security Cheatsheet | Sui | [GitHub](https://github.com/darshan-06/Sui-Move-cheat-sheet/blob/main/sui_move_security_cheatsheet.md) |
| Move Audit Resources | General | [GitHub](https://github.com/0xriazaka/Move-Audit-Resources) |
| Zellic Findings Database | General | [Website](https://reports.zellic.io/findings) |

### Common Move Vulnerability Patterns

1. **Object Ownership Verification** - Failing to verify signer owns `Object<T>`
2. **Abilities Mismanagement** - Improper use of `key`, `store`, `copy`, `drop`
3. **Resource Misuse** - Improper handling of non-drop resources
4. **Randomness Abuse** - Unsafe public functions calling randomness APIs
5. **Global Storage Access** - Improper access to shared objects
6. **Type Safety Issues** - Move type confusion bugs
7. **Integer Overflow in Bit Shifts** - Intentionally allowed unlike other operations
8. **Flash Loan Logic Errors** - Vulnerabilities in DeFi protocol implementations
9. **Phantom Type Parameter Misuse** - Improper generic type handling
10. **Shared Library Vulnerabilities** - Copy-pasted code creating systemic risk

---

## Bug Bounty Programs

### Layer 1 Programs

| Program | Platform | Max Reward | Link |
|---------|----------|------------|------|
| Sui Bug Bounty | Sui | $1,000,000 | [HackenProof](https://hackenproof.com/programs/sui-protocol) |
| Sui Foundation x Immunefi | Sui | Variable | [Website](https://sui.io/bug-bounty-program) |
| Aptos Labs Bug Bounty | Aptos | Variable | [GitHub](https://github.com/aptos-labs/aptos-core/security) |
| Aptos Petra Wallet | Aptos | $100,000 | [Immunefi](https://immunefi.com/bug-bounty/aptos-petra-wallet/) |
| Movement Labs Attackathon | Movement | $400,000 | [Immunefi](https://immunefi.com/audit-competition/movement-labs-attackathon/information/) |

### Protocol Programs

| Program | Platform | Max Reward | Link |
|---------|----------|------------|------|
| Econia | Aptos | $100,000 | [Immunefi](https://immunefi.com/bug-bounty/econia/information/) |
| Liquidswap | Aptos | $500,000 | [Immunefi](https://immunefi.com/bug-bounty/liquidswap/information/) |
| DeepBook | Sui | $100,000 | [Sui Forums](https://forums.sui.io/t/the-deepbook-bug-bounty-program-is-officially-live/46047) |
| Wormhole | Both | 20,000,000 W | [Immunefi](https://immunefi.com/bug-bounty/wormhole/) |

---

## Security Communities and Researchers

### Official Communities

| Community | Platform | Link |
|-----------|----------|------|
| Sui Discord | Sui | [Discord](https://discord.com/invite/sui) |
| Aptos Discord | Aptos | [Discord](https://discord.com/invite/aptosnetwork) |
| Aptos Telegram | Aptos | [Telegram](https://t.me/aptos) |
| Sui Developer Forum | Sui | [Forum](https://forums.sui.io) |

### Security Documentation

| Resource | Platform | Link |
|----------|----------|------|
| Sui Security Architecture | Sui | [Docs](https://docs.sui.io/concepts/sui-architecture/sui-security) |
| Sui Whitepaper | Sui | [PDF](https://docs.sui.io/paper/sui.pdf) |
| Sui Cryptography Docs | Sui | [Docs](https://docs.sui.io/concepts/cryptography) |
| Sui Research Papers | Sui | [Docs](https://docs.sui.io/concepts/research-papers) |
| Aptos Move Security Guidelines | Aptos | [Docs](https://aptos.dev/build/smart-contracts/move-security-guidelines) |
| Aptos Cryptography Docs | Aptos | [Docs](https://aptos.dev/build/smart-contracts/cryptography) |
| Aptos Rust Secure Coding | Aptos | [GitHub](https://github.com/aptos-labs/aptos-core/blob/main/RUST_SECURE_CODING.md) |
| MystenLabs Security Policy | Sui | [GitHub](https://github.com/MystenLabs/sui/blob/main/SECURITY.md) |

---

## Security Audit Firms

### Primary Move Ecosystem Auditors

| Firm | Specialty | Platforms | Website |
|------|-----------|-----------|---------|
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

## Key Statistics

| Metric | Value |
|--------|-------|
| **Total Confirmed Losses (Exploits)** | ~$248.5M+ |
| **Largest Single Exploit** | Cetus ($223M) |
| **Total Recovered** | ~$187.5M |
| **Bug Bounties Paid (Known)** | $850,000+ |
| **Protocols Affected by Shared Vulnerability** | 4+ |

---

## Contributing

This resource is maintained to help the Move security community. To contribute:

1. Submit audit reports, tools, or resources via pull request
2. Report broken links or outdated information
3. Share CTF writeups and security research

---

## Disclaimer

This compilation is for educational and research purposes only. Links are provided for reference and do not constitute endorsement. Always verify information independently and conduct your own security assessments. Security vulnerabilities should be reported through official bug bounty channels, not exploited.

---

*Last updated: December 2025*
