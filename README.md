# bounty-journal — Zenith (aka Yannix)

Infra security researcher (BR) focused on Broken Access Control + exposure monitoring.

## ✅ Validated
- **ProfileGrid <=6.0.0.2 IDOR** — Patchstack (Credits: Zenith) — Unauth friends-only disclosure + forced-friendship chain — `Status: Validated, CVE pending` — `reports-sanitized/profilegrid-6.0.0.2/`
- **BR B2B Program (BOLA High, ID->CNPJ chain)** — BugPay, Status: Under review, details under embargo
- **BR SaaS Analytics Program (JWT session Medium CWE-613)** — BugPay, under embargo

## 🛠️ Stack
Nmap, BloodHound, Redflower (own recon tooling), Burp (Repeater), Python recon (curl_cffi), crt.sh watch, local Ollama (privacy-first: cloud for ideas, local for data).

## 📡 Monitor
`bounty-feed:` Multi-source monitor (Bugcrowd, HackerOne, Intigriti + own EU/BR sources) with infra filter + ROI.

## 🧪 Labs (proven coverage, no false positives)
- `labs/pms-3.0.9/` — coverage with no eligible finding (tested locally, no false positive) — (discount/checkout/stripe with t*.json)
- `labs/top-10-4.4.3/` — coverage with no eligible finding (tested locally) — (Contributor-only injection)
- `labs/csv-2.4.17/` — coverage with no eligible finding (tested locally) — (create_users only)
- `labs/forminator-1.57.2/` — coverage with no eligible finding (tested locally) — (600k end-to-end)
- `labs/kwayy-5.2/` — coverage with no eligible finding (tested locally) — (hardened)

## 📬 Contact
- GitHub: zenith-sec
- Discord: yannix_dex
- Yogosha: Strike Force candidate (waiting list)
- Rule: testing only with authorization/scope or localhost. No OOS, no mass scraping, no prod without permission.

> Bird of Hermes: eating my wings to make me tame — power with restraint.
