# NovaSmart AI Governance Lab — Complete Audit Record & Scorecard

Executive AI Governance, Security, and Observability Audit Record for **NovaSmart AI Agent Estate** (GCP Project: `qwiklabs-gcp-02-acabb26a218f`).

## 📄 Key Repository Documents

- [novasmart_governance_lab_record.docx](novasmart_governance_lab_record.docx) — Executive Word Document Report (Modules 0–5)
- [command_output.txt](command_output.txt) — Complete CLI Commands & Output Log
- [scorecard/governance_scorecard.html](scorecard/governance_scorecard.html) — Interactive Executive Live Scorecard

## 📁 Repository Structure

```
.
├── novasmart_governance_lab_record.docx   # Executive Word Document Report
├── command_output.txt                     # Full CLI Commands & Output Log
├── evidence/                              # Verified Module Proof Files (m0..m5)
│   ├── m0/ ...
│   ├── m1/ ...
│   ├── m2/ ...
│   ├── m3/ ...
│   ├── m4/ ...
│   └── m5/ ...
├── scorecard/                             # HTML Live Scorecard Dashboard
│   ├── governance_scorecard.html
│   └── novasmart_governance_scorecard_state.json
├── m5_local_scaffold/                     # Module 5 Evaluation Scaffold
│   ├── price_match_agent.py
│   ├── tougher_eval_dataset.csv
│   └── hardened_local_eval_results.json
└── *.yaml / *.json                        # IAM, IAP CEL, and Gateway Specs
```

## 🛡️ Covered Modules & Controls

1. **Module 0**: Estate Visibility & Discovery (`agents-cli`, GCP project readiness).
2. **Module 1**: Identity & Data Least Privilege (Service account splitting, fine-grained IAM).
3. **Module 2**: Inbound & Outbound Perimeter Controls (Egress gateway attachment, A2A inbound policy, BigQuery MCP CEL expression).
4. **Module 3**: Ingress Model Armor Screening (`nvst-jailbreak-template` creation, Reasoning Engine attachment, HTTP 403 refusal).
5. **Module 4**: Distributed Tracing & Behavioral Observability (`auto_instrumentation` enablement, A2A trace context propagation).
6. **Module 5**: Continuous Quality Evaluation & Decision (Seed eval, 8-scenario tougher eval, local prompt security fix `git diff`, SEAM breakdown, governance dataset rules).
