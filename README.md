# ISO/IEC 27001:2022 — Applied ISMS Portfolio Project

**Author:** Swapnil Shingte, ISO/IEC 27001:2022 Lead Auditor 

## What this is

A self-directed project applying ISO/IEC 27001:2022 to a fictional mid-size IT services company — **Certus IT Solutions Pvt. Ltd.** — end to end: context and scope, risk assessment, Statement of Applicability, and a full internal audit report with real findings.

Built after repeated feedback (here, and from people already working in GRC) that a certification alone doesn't show you can *apply* the standard. This is that application.

## Why Certus IT Solutions

Modelled as a ~150-person IT managed services / software company — hybrid workforce, AWS/Azure cloud infrastructure, BFSI/healthcare clients. Close enough to real IT operations that every risk, control, and finding in this project reflects genuine day-to-day security/compliance work, not textbook scenarios.

## Contents

| File | What it is |
|---|---|
| `ISMS_Context_and_Scope.docx` | Clause 4.1–4.3 — internal/external issues, interested parties, ISMS scope, policy summary |
| `Risk_Register.xlsx` | Clause 6.1.2/6.1.3 — 18 risks, full likelihood/impact scoring, treatment decisions, residual risk, mapped to Annex A controls |
| `Statement_of_Applicability.xlsx` | Clause 6.1.3(d) — all 93 Annex A controls, applicability, justification, implementation status, 1 justified exclusion |
| `Internal_Audit_Report.docx` | Full first-party audit report — 1 major NC, 3 minor NCs, 2 OFIs, 5 sampled conformities, root-cause findings, follow-up plan |

See /TPRM folder for an extension covering vendor risk assessment — questionnaire, completed sample assessment, and policy.

## How the pieces connect

This isn't four disconnected documents — they trace through each other, the way a real ISMS does:

- Risk **R-01** (ransomware via phishing) → mapped to controls **8.7, 6.3, 8.16** in the risk register → those controls appear in the **SoA** → control **6.3** shows "Partially Implemented" in the SoA → that gap is the exact subject of **NC-02** in the audit report (incomplete awareness training)
- Risk **R-14** (unpatched legacy servers) → control **8.8** → SoA shows 8.8 "Partially Implemented" → **NC-03** (patch SLA not met) is the audit evidence behind that status
- The **major nonconformity (NC-01)** — overdue risk assessment — is itself a finding *about* the risk register's own currency, closing the loop

## What I can speak to from this

- Why a finding gets graded major vs minor (see NC-01 vs NC-02–04, and the reasoning for each)
- The difference between a control being *selected* (6.1.3) vs *implemented* (8.1) — and why that distinction changes which clause a nonconformity is raised against
- How to trace a risk from identification through to Annex A control selection through to audit evidence
- What a real audit finding looks like: criteria → evidence → finding statement, not just "this is wrong"

## Disclaimer

Certus IT Solutions Pvt. Ltd. is entirely fictional. This project does not represent, and is not derived from, the confidential information of any employer or client I have worked with.
