# Awesome Move Security

> A curated list of Move language security resources organized by dialect: Sui Move and Aptos Move smart contract auditing, vulnerability research, and security best practices.

**Move** is a smart contract language originally developed by Meta (formerly Facebook) for the Diem blockchain, now powering Sui and Aptos. Unlike Solidity, Move features a resource-oriented programming model with built-in safety guarantees, yet security vulnerabilities remain possible.

---

## Table of Contents

- [SUI MOVE SECURITY](#sui-move-security)
  - [Sui Security Articles](#sui-specific-security-articles)
  - [Sui Public Audit Reports](#sui-public-audit-reports)
  - [Sui Exploits and Incidents](#sui-exploits-and-incidents)
  - [Sui CTFs and Challenges](#sui-ctfs-and-challenges)

- [APTOS MOVE SECURITY](#aptos-move-security)
  - [Aptos Security Articles](#aptos-specific-security-articles)
  - [Aptos Public Audit Reports](#aptos-public-audit-reports)
  - [Aptos Exploits and Incidents](#aptos-exploits-and-incidents)
  - [Aptos CTFs and Challenges](#aptos-ctfs-and-challenges)

- [GENERAL MOVE SECURITY](#general-move-security)
  - [General Move Security Articles](#general-move-security-articles)
  - [Cheatsheets and Quick References](#cheatsheets-and-quick-references)
  - [Security Audit Firms](#security-audit-firms)

---

# SUI MOVE SECURITY

## Sui Security Articles

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| SlowMist guide introducing how to audit Sui Move smart contracts            | https://slowmist.medium.com/slowmist-introduction-to-auditing-sui-move-contracts-da005149f6bc |
| MoveBit article explaining Sui object security principles and best practices| https://www.movebit.xyz/blog/post/Sui-Objects-Security-Principles-and-Best-Practices.html |
| Official Sui blog post on improving ecosystem security through audits        | https://blog.sui.io/security-audits-and-move-registry/ |
| SlowMist analysis of a Move language permission-validation vulnerability    | https://slowmist.medium.com/is-the-move-language-secure-the-typus-permission-validation-vulnerability-755a5175f7c3 |
| MoveBit explanation of vulnerabilities discovered in Bluefin                | https://www.movebit.xyz/blog/post/Bluefin-vulnerabilities-explanation-1.html |
| MoveBit writeup on discovering and fixing a Sui cross-chain vulnerability   | https://www.movebit.xyz/blog/post/MoveBit-Discovers-and-Helps-Fix-Vulnerability-in-Sui-Cross-Chain-Protocol-20241012.html |



---

## Sui Public Audit Reports

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Cetus Protocol audited by MoveBit                                           | https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20MoveBit.pdf |
| Cetus Protocol audited by OtterSec                                          | https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Sui%20Audit%20Report%20by%20OtterSec.pdf |
| Cetus Protocol audited by Zellic                                            | https://github.com/Zellic/publications/blob/master/CetusProtocol%20-%20Zellic%20Audit%20Report.pdf |
| Suilend audited by Zellic                                                   | https://github.com/Zellic/publications/blob/master/Suilend%20-%20Zellic%20Audit%20Report.pdf |
| Bucket Protocol audited by OtterSec and MoveBit                             | https://github.com/Bucket-Protocol/Audit |
| KriyaDEX audited by MoveBit                                                 | https://github.com/movebit/Sampled-Audit-Reports/blob/main/reports/KriyaDEX-Smart-Contract-Audit-Report.pdf |
| Streamflow on Sui audited by MoveBit                                        | http://movebit.xyz/reports/Streamflow-Final-Audit-Report.pdf |
| Chirp Network audited by Zellic                                             | https://github.com/Zellic/publications/blob/master/Chirp%20Network%20-%20Zellic%20Audit%20Report.pdf |
| Magma Finance audited by Zellic                                             | https://github.com/Zellic/publications/blob/master/Magma%20Finance%20-%20Zellic%20Audit%20Report.pdf |
| Garden Move Deploy audited by Zellic                                        | https://github.com/Zellic/publications/blob/master/Garden%20Move%20Deploy%20-%20Zellic%20Audit%20Report.pdf |
| Magna Airlock audited by Zellic                                             | https://github.com/Zellic/publications/blob/master/Magna%20Airlock%20-%20Zellic%20Audit%20Report.pdf |
| Sui AMM Swap audited by MoveBit                                             | https://movebit.xyz/file/Sui-AMM-swap-Contracts-Audit-Report.pdf |
| Scallop Lend audited by Zellic, OtterSec, and MoveBit                       | https://docs.scallop.io/protocol/auditing |
| Move and Sui security assessment audited by Zellic                          | https://github.com/sui-foundation/security-audits/blob/main/docs/Move%20and%20Sui%20Security%20Assessment%20-%20Zellic%20Audit%20Report.pdf |

---

## Sui Exploits and Incidents

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Rekt News overview explaining the Cetus Protocol hack and its impact        | https://rekt.news/cetus-rekt |
| Dedaub technical breakdown of the integer overflow root cause               | https://dedaub.com/blog/the-cetus-amm-200m-hack-how-a-flawed-overflow-check-led-to-catastrophic-loss/ |
| Halborn explanation of how the Cetus exploit occurred on Sui                | https://www.halborn.com/blog/post/explained-the-cetus-hack-may-2025 |
| Merkle Science analysis of the shared library vulnerability                 | https://www.merklescience.com/blog/hack-track-how-a-shared-library-bug-triggered-the-223m-cetus-hack |
| Verichains technical analysis of the Cetus Protocol exploit                 | https://blog.verichains.io/p/cetus-protocol-hacked-analysis |
| Crypto.News coverage summarizing the Cetus Sui exploit                      | https://crypto.news/cetus-protocol-hack-sui-exploit-full-breakdown/ |
| CCN news coverage reporting details of the Cetus exploit                    | https://www.ccn.com/news/crypto/sui-cetus-260m-exploit/ |


---

## Sui CTFs and Challenges

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Official MoveCTF competition focused on Move smart contract security        | https://movectf.movebit.xyz/ |
| Sui-focused MoveCTF organized by MoveBit Vietnam community                  | https://suictf.movebit.xyz/ |
| 2023 blockchain security CTF by Numen Cyber with Move-related challenges    | https://github.com/numencyber/NumenCTF_2023 |
| Repository containing the first official MoveCTF challenge set              | https://github.com/movectf/MoveCTF-1st-Challenge |
| Detailed writeup and solutions for MoveCTF 2024 challenges                  | https://ambergroup.medium.com/movectf-2024-writeup-f74784e020c4 |
| Writeup covering MetaTrust Sui CTF 2023 challenge solutions                 | https://leoq7.com/2023/09/MetaTrust-CTF-Sui/ |
| Independent MoveCTF 2024 writeup with technical breakdowns                  | https://medium.com/@zan.top/move-ctf-2024-writeup-a9baa0c043e7 |
| Community writeups and solutions for the 2022 Move CTF                      | https://github.com/saruman9/move_ctf_writeup |

---

# APTOS MOVE SECURITY

## Aptos Security Articles

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Official Aptos documentation outlining Move smart contract security rules   | https://aptos.dev/build/smart-contracts/move-security-guidelines |
| Monethic deep dive into Move vulnerabilities in storage and access control  | https://medium.com/@monethic/move-demistyfied-part-3-vulnerabilities-in-storage-and-access-control-checks-8634cc1d114d |
| Monethic explanation of structs, storage, and capabilities in Move          | https://medium.com/@monethic/move-demystified-part-2-structs-storage-and-cap-abilities-a60bf6b0b399 |
| Monethic introduction to Aptos Move with a HelloWorld module walkthrough   | https://medium.com/@monethic/aptos-move-demystified-part-1-helloworld-module-873090be5fa4 |
| Zellic overview of the most common Aptos Move vulnerabilities               | https://www.zellic.io/blog/top-10-aptos-move-bugs |
| CertiK audit lessons learned from securing an Aptos protocol                | https://www.certik.com/resources/blog/moving-the-immovables-lessons-learned-from-our-aptos-smart-contract-audit |
| Monethic explains Move Prover usage               | https://medium.com/@monethic/getting-started-with-move-prover-for-aptos-01923d5a1d0f |


## Aptos Public Audit Reports

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Cetus Protocol on Aptos audited by MoveBit                                  | https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20MoveBit.pdf |
| Cetus Protocol on Aptos audited by OtterSec                                 | https://github.com/CetusProtocol/Audit/blob/main/Cetus%20Aptos%20Audit%20Report%20by%20OtterSec.pdf |
| Pontem Liquidswap audited by Zellic                                         | https://github.com/Zellic/publications/blob/master/Pontem%20Liquidswap%20-%20Zellic%20Audit%20Report.pdf |
| Liquidswap formal verification conducted by MoveBit                         | https://pontem.network/posts/liquidswap-passes-formal-verification-by-movebit---heres-what-it-means |
| Thala Labs Move Dollar audited by Zellic                                    | https://github.com/Zellic/publications/blob/master/Thala%20Labs%20Move%20Dollar%20-%20Zellic%20Audit%20Report.pdf |
| Econia protocol audited by Zellic                                           | https://github.com/Zellic/publications/blob/master/Econia%20-%20Zellic%20Audit%20Report.pdf |
| Echelon protocol audited by Zellic                                          | https://github.com/Zellic/publications/blob/master/Echelon%20-%20Zellic%20Audit%20Report%20(January).pdf |
| Tortuga liquid staking audited by Zellic                                    | https://github.com/Zellic/publications/blob/master/Tortuga%20Liquid%20Staking%20-%20Zellic%20Audit%20Report.pdf |
| Laminar Markets audited by Zellic                                           | https://github.com/Zellic/publications/blob/master/Laminar%20-%20Zellic%20Audit%20Report.pdf |
| MSafe wallet audited by Zellic                                              | https://github.com/Zellic/publications/blob/master/MSafe%20-%20Zellic%20Audit%20Report.pdf |
| PancakeSwap on Aptos audited by Zellic                                      | https://github.com/Zellic/publications/blob/master/PancakeSwap%20Aptos%20-%20Zellic%20Audit%20Report.pdf |
| PancakeSwap Move implementation audited by SlowMist                         | https://github.com/slowmist/Knowledge-Base/blob/master/open-report-V2/smart-contract/SlowMist%20Audit%20Report%20-%20PancakeSwap_MOVE_en-us.pdf |
| Wormhole bridge on Aptos audited by Zellic                                  | https://github.com/Zellic/publications/blob/master/Wormhole%20Aptos%20-%20Zellic%20Audit%20Report.pdf |
| LayerZero OFT wrapper audited by Zellic                                     | https://github.com/Zellic/publications/blob/master/LayerZero%20OFT%20Wrapper%20Audit%20(January%2019th%202023)%20-%20Zellic%20Audit%20Report.pdf |
| Cellana protocol audited by MoveBit                                         | https://movebit.xyz/reports/Cellana-Smart-Contract-Final-Audit-Report.pdf |
| Streamflow on Aptos audited by MoveBit                                      | https://movebit.xyz/reports/Streamflow-Aptos-Final-Audit-Report.pdf |
| Kanalabs aggregator audited by MoveBit                                      | https://movebit.xyz/reports/Kanalabs-aggregator-Smart-Contract-Final-Audit-Report.pdf |
| Amnis Finance audited by MoveBit and Verichains                             | https://docs.amnis.finance/security-audits |


---

## Aptos CTFs and Challenges

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Official CTF MOVEment competition by MoveBit and Aptos Foundation           | https://ctfmovement.movebit.xyz/ |
| Aptos Code Collision CTF hosted by the Aptos Foundation                     | https://ctftime.org/event/2433/ |
| Aave V3 CTF focused on Aptos with significant rewards                       | $100K rewards |
| Official CTF MOVEment challenge repositories                                | https://github.com/movebit |
| Amber Group writeup for CTF MOVEment 2022                                   | https://ambergroup.medium.com/movement-ctf-2022-writeup-4904ff8a82e |
| Community writeup for CTF MOVEment Aptos 2022                               | https://leoq7.com/2022/12/CTF-Movement-Aptos/ |
| Coinsbench walkthrough of a CTF MOVEment challenge                          | https://coinsbench.com/draining-tokens-from-a-dex-in-the-movebit-ctfmovement-3-challenge-a-solution-walkthrough-37d8ed737821 |
|

---

## Aptos Exploits and Incidents

| Description                                                                 | Link |
|-----------------------------------------------------------------------------|------|
| Thala Labs official post-mortem explaining the November 2024 exploit        | https://thalalabs.medium.com/thala-nov-15-post-mortem-5aea82bb3916 |
| Halborn technical analysis of the Thala Labs hack                           | https://www.halborn.com/blog/post/explained-the-thala-hack-november-2024 |
| QuillAudits breakdown of the Thala DeFi exploit                              | https://www.quillaudits.com/blog/hack-analysis/thala-defi-hack-analysis |
| Cointelegraph report on Wormhole Aptos vulnerability disclosure             | https://cointelegraph.com/news/certik-discovered-5-million-security-flaw-wormhole-bridge-aptos |
| CyberExpress coverage of a critical Aptos MoveVM integer overflow bug       | https://thecyberexpress.com/critical-vulnerability-in-aptos-movevm-patched/ |


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

### Well known Move Ecosystem Auditors

| Firm | Specialty | Platforms | Website |
|------|-----------|-----------|---------|
| **Monethic** | Smart contract security audits and blockchain security services | Sui, Aptos, Solana, EVM | [monethic.com](https://monethic.com) |
| **MoveBit** | Formal verification pioneer, CTF host, first Move security company | Sui, Aptos | [movebit.xyz](https://www.movebit.xyz) |
| **OtterSec** | Deep manual reviews, Move Prover expertise, Sui Foundation partner | Sui, Aptos | [osec.io](https://osec.io) |
| **Zellic** | Critical vulnerability research, Move bytecode expertise | Sui, Aptos | [zellic.io](https://www.zellic.io) |


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
