<div align="center">

<a href="https://github.com/jdh847"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3200&pause=1000&color=E8630A&center=true&vCenter=true&multiline=true&repeat=true&width=760&height=100&lines=Rust+systems+%7C+Cryptographic+infrastructure;Bitcoin+anchoring+%7C+BFT+consensus+%7C+Regulated+finance" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yitebeier-aikebaier)
[![Nexum Ledger](https://img.shields.io/badge/nexumledger.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.nexumledger.com)
[![IACR ePrint](https://img.shields.io/badge/IACR_ePrint_2026%2F1109-C4302B?style=for-the-badge)](https://eprint.iacr.org/2026/1109)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jsjjd3690@gmail.com)

</div>

---

### About me

I build cryptographic audit infrastructure for regulated finance, in Rust.

Founder and lead engineer at **Nexum Ledger Ltd** (London, Companies House 17001897): an
append-only evidence engine for SRA-regulated law firms. Client data is encrypted with
AES-256-GCM, the Merkle tree is built over ciphertext rather than plaintext, and SHA-256
roots are anchored to **Bitcoin via OpenTimestamps**, so retention and erasure can be proven
to a regulator without the ledger ever holding recoverable client content.

Two things here you can verify without taking my word for it:

- **[IACR ePrint 2026/1109](https://eprint.iacr.org/2026/1109)** &middot; *SoK: Cryptographic
  Erasure on Public Ledgers: Application Layer Architectures, Key Lifecycle Adversaries,
  and GDPR Art. 17 Equivalence*
- **[Sealmark](https://github.com/jdh847/sealmark)** &middot; published in the
  [official Obsidian community plugin store](https://obsidian.md/plugins?id=sealmark).
  Private proof of existence for notes: hash locally, anchor to Bitcoin, verify offline.
  Your content never leaves your machine, only a hash is published.

**MSc Finance**, University of St Andrews. Based in London.
UK Graduate Route, no sponsorship required.

---

### What I work on

**Cryptographic infrastructure** &middot; append-only hash-chained audit stores, AES-256-GCM
envelope encryption, key-destruction erasure semantics, ciphertext Merkle trees, SHA-256
anchoring to Bitcoin via OpenTimestamps, GDPR Art. 17 evidence

**Consensus and distributed systems** &middot; Byzantine fault tolerance (PBFT, HotStuff, Raft),
fault injection, safety invariants under partition, throughput and latency benchmarking

**Production Rust** &middot; tokio, axum, sqlx, PostgreSQL, constant-time verification on webhook
boundaries, CI gates that actually block, deployment on bare VPS with GitHub Actions

**Quantitative finance** &middot; multi-factor alpha, HRP portfolio construction, regime-aware
volatility scaling, walk-forward and survivorship-free backtesting across US, China A-share
and Japan equities

**Financial econometrics** &middot; GARCH/EGARCH/GJR-GARCH, Fama-French factor models, VaR/CVaR,
Monte Carlo, cointegration, regime switching

---

### Featured projects

<div align="center">

<a href="https://github.com/jdh847/quant-engine-rs">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jdh847&repo=quant-engine-rs&theme=github_dark&hide_border=true&border_radius=8" />
</a>
<a href="https://github.com/jdh847/bft-consensus-bench">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jdh847&repo=bft-consensus-bench&theme=github_dark&hide_border=true&border_radius=8" />
</a>
<br/>
<a href="https://github.com/jdh847/sealmark">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jdh847&repo=sealmark&theme=github_dark&hide_border=true&border_radius=8" />
</a>
<a href="https://github.com/jdh847/javascript-opentimestamps">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=jdh847&repo=javascript-opentimestamps&theme=github_dark&hide_border=true&border_radius=8" />
</a>

</div>

---

### Tech stack

<div align="center">

**Languages**

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Rust ecosystem**

![Tokio](https://img.shields.io/badge/Tokio-232323?style=flat-square&logo=rust&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white)
![SQLx](https://img.shields.io/badge/SQLx-4479A1?style=flat-square&logo=rust&logoColor=white)
![Serde](https://img.shields.io/badge/Serde-E8630A?style=flat-square&logo=rust&logoColor=white)

**Cryptography and ledgers**

![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=flat-square&logo=bitcoin&logoColor=white)
![OpenTimestamps](https://img.shields.io/badge/OpenTimestamps-232323?style=flat-square)
![AES--256--GCM](https://img.shields.io/badge/AES--256--GCM-232323?style=flat-square)
![Merkle](https://img.shields.io/badge/Merkle_trees-232323?style=flat-square)

**Quant and ML**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-232323?style=flat-square)

**Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

### GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jdh847&show_icons=true&theme=github_dark&hide_border=true&border_radius=8&count_private=true&include_all_commits=true" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jdh847&layout=compact&theme=github_dark&hide_border=true&border_radius=8&langs_count=6" height="170" />

</div>

---

<div align="center">

<sub>Open to engineering roles in the UK, Ireland and the Netherlands.<br/>
Rust systems &middot; cryptographic infrastructure &middot; distributed systems &middot; quantitative finance</sub>

</div>
