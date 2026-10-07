<div align="center">

# ☁️ AWS SAA-C03 Advanced Notebook

**A hand-written-style, colour-coded study notebook for the AWS Certified Solutions Architect – Associate (SAA-C03) exam.**
Architecture decisions · exam traps · service-selection cheat sheets — all in one self-contained HTML file.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-000000?logo=vercel&logoColor=white)](https://aws-saa-c03-advanced-notebook-l25wdv9s7.vercel.app/)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)
![Exam](https://img.shields.io/badge/Exam-SAA--C03-FF9900?logo=amazonaws&logoColor=white)
![Format](https://img.shields.io/badge/Format-Single%20HTML-blue)

[**🌐 Open the notebook**](https://aws-saa-c03-advanced-notebook-l25wdv9s7.vercel.app/) · [Report an issue](../../issues)

</div>

---

## 📖 About

This notebook is the "next level" companion to the foundational SAA-C03 topics (EC2, EBS, EFS, S3, Lambda, ECS/EKS, RDS, DynamoDB, Aurora, Redshift, ELB, ASG, CloudWatch).
It does not re-teach the basics. It focuses on what separates a pass from a fail: **choosing between two answers that both look right**.

Every scenario is approached with *The Architect's 10 Questions* — Security, Availability, Scalability, Performance, Fault tolerance, Cost, Ops overhead, Durability, RTO/RPO, Future growth — and then resolved by the single **deciding word** in the question stem (*most cost-effective*, *least operational overhead*, *most secure*, *lowest latency*…).

## ✨ Features

- **15 structured parts + a "night-before" must-know page** mapped to the four exam domains
- **~21,000 words**, **77 comparison tables**, **28 inline SVG diagrams** and **38 annotated architecture slides**
- **Colour-coded highlighting** — yellow = core fact, pink = trap, green = best answer, blue = question keyword, orange = number to remember, violet = newer/renamed service
- **Callout boxes** — ⚠️ exam traps, 🔎 "see this → think this" clues, 🧠 memory tricks, 🏗️ worked architectures, ⚖️ slides-vs-current-AWS notes
- **Print-ready** — one click on **⬇ Save as PDF** produces an A4 notebook with ruled paper and margins
- **Zero dependencies** — fonts and images are embedded; works offline

## 🎯 Exam domains covered

| Domain | Weight | What it really tests |
|---|---|---|
| D1 – Secure architectures | 30% | IAM logic, encryption/KMS, network isolation, private access, governance |
| D2 – Resilient architectures | 26% | Multi-AZ / Multi-Region, decoupling, DR strategy, failover |
| D3 – High-performing architectures | 24% | Right service for the access pattern, caching, scaling, edge |
| D4 – Cost-optimized architectures | 20% | Pricing models, storage tiers, data transfer, serverless vs servers |

## 🗂️ Contents

| Part | Topic | Domains |
|---|---|---|
| ✦ | How to use this notebook | – |
| P1 | Security, Identity & Governance | D1 |
| P2 | Networking — VPC, Hybrid, DNS & Edge | D1 D2 D3 |
| P3 | Storage — S3 advanced, FSx, hybrid storage | D2 D3 D4 |
| P4 | Compute — pricing depth, placement, containers vs serverless | D3 D4 |
| P5 | Databases — replicas, Aurora, DynamoDB deep, purpose-built | D2 D3 |
| P6 | Load Balancing & Scaling — the nuances | D2 D3 |
| P7 | Application Integration — SQS, SNS, EventBridge, MQ, Kinesis | D2 D3 |
| P8 | Serverless & Microservices — Lambda, API Gateway, Step Functions | D2 D3 D4 |
| P9 | Monitoring, Management & IaC | D1 D2 D4 |
| P10 | Migration & Data Transfer | D2 D4 |
| P11 | Analytics & ML awareness | D3 D4 |
| P12 | Disaster Recovery & Resilience | D2 |
| P13 | Architecture Patterns (worked examples) | D1–D4 |
| P14 | Service-Selection Cheat Sheets | – |
| P15 | Final Exam Traps + 🔥 Must-Know | – |

## 🚀 Usage

**Online:** open the [live site](https://YOUR-PROJECT.vercel.app).

**Locally:** it is a single file, so no build step is needed.

```bash
git clone https://github.com/imaniketrajput/aws-saa-c03-advanced-notebook.git
cd aws-saa-c03-advanced-notebook
# just open index.html in any modern browser
```

**Export as PDF:** click **⬇ Save as PDF** (top-right) → choose *Save as PDF* → keep *Background graphics* on, paper size **A4**, margins **Default/None**.

## 🧩 Deployment

Deployed on [Vercel](https://vercel.com) as a static site. No framework, no build command, and the output directory is the repo root (`index.html`).

## 📁 Repository structure

```
.
├── index.html   # the complete notebook (fonts, styles, diagrams embedded)
├── README.md
├── LICENSE      # CC BY-NC-ND 4.0
└── NOTICE.md    # copyright + third-party content notice
```

## ⚠️ Disclaimer

This is an independent study resource. It is **not affiliated with, endorsed by, or sponsored by Amazon Web Services**. AWS services, features and pricing change often — always verify against the official [AWS documentation](https://docs.aws.amazon.com/) and the current [SAA-C03 exam guide](https://aws.amazon.com/certification/certified-solutions-architect-associate/).

## 📜 License & copyright

© 2026 **Aniket Singh Rajput**. Original content is licensed under
[**Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International**](LICENSE).
You may share it with credit, for non-commercial use, without modification.

Embedded AWS slide images and AWS trademarks belong to Amazon Web Services and are **not** covered by this licence — see [NOTICE.md](NOTICE.md).

## 👤 Author

**Aniket Singh Rajput** — [@imaniketrajput](https://github.com/imaniketrajput)

If this helped you pass, give the repo a ⭐
