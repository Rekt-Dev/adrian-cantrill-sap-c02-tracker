# Adrian Cantrill SAP-C02 — Per-Lesson Study Tracker

A standalone HTML tracker for every lesson in [Adrian Cantrill's AWS Solutions Architect Professional course](https://learn.cantrill.io/).

**No install. No account. Open the file in your browser.**

---

## What it does

- Every lesson tagged: `Watch` / `Fast (1.75x)` / `Skip` / `Supplement` / `Demo-Skip`  
- Tailored for someone with a strong infra background (CKA/CKS, 30yr IT) — skips what you already know
- Checkbox per lesson, progress bar, filter by action type
- **Gap analysis for post-2021 AWS services** — the course was built in 2020/2021 and SAP-C02 tests newer services

## The gap analysis

Every link on a lesson is tagged:

| Tag | Meaning |
|-----|---------|
| 🔴 `OUTDATED` | Adrian's content is wrong or stale — you **must** read the link |
| 🟠 `GAP` | Service not in the course at all — read before the exam |
| 🔵 `EXTRA` | Adrian's lesson is fine — link is bonus depth |

## Post-2021 gaps covered (not in Adrianx27s course)

- IAM Identity Center (renamed from AWS SSO)
- AWS Control Tower
- AWS Network Firewall
- Aurora Serverless v2 (completely different from v1)
- RDS Proxy
- AWS Backup
- Amazon Macie v2
- Amazon Detective
- AWS Fault Injection Simulator
- EventBridge Pipes
- Lambda SnapStart
- S3 Object Lambda
- EC2 Image Builder
- AWS App Runner
- AWS Transfer Family
- AWS Resilience Hub
- OpenSearch Service (renamed from Elasticsearch)
- CloudFront OAC (replaced OAI)
- Inspector v2 (completely rewritten)
- WAFv2 (replaced WAFv1)
- MGN / DRS (replaced CloudEndure)
- Cost Anomaly Detection
- Savings Plans
- ...and more

## Usage

1. Download `adrian_per_lesson_tracker.html`
2. Open it in any browser
3. Check off lessons as you go — progress saves in localStorage

---

Built by [Rekt-Dev](https://github.com/Rekt-Dev) while studying for SAP-C02.
