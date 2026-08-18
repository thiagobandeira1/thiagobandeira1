# Hi, I'm Thiago Bandeira 👋

**AI/ML Engineer & Healthcare Operations Leader — Miami, FL**

I build production AI systems inside the healthcare operation I run. As Director of
Operations & Innovation at a value-based care organization, I lead a full-risk
Medicare panel of 4,000+ members (4.5+ Stars, 3 consecutive years) — and I
personally design, ship, and maintain the ML models, LLM applications, and
analytics platforms behind those results.

- 🎓 M.S. Data Science & Artificial Intelligence — Florida International University
- 📜 AWS Certified Machine Learning Engineer
- 📄 Published research: interpretable 30-day readmission prediction on MIMIC-IV

## What I'm working on

- 🤖 **LLM systems in live clinical workflows** — an AI phone operator handling
  real patient calls end-to-end, and AI-assisted HCC risk-adjustment coding
  (LLM APIs, MCP integrations, LangChain)
- 📊 **Value-based care analytics** — HEDIS/Stars performance, HCC/RAF risk
  adjustment, and claims analytics (~150K claim lines/month)
- 🏥 **Utilization reduction that holds up** — programs behind a 41% avoidable-ER
  reduction and a 34% panel-deficit turnaround

## Main projects

| Project | What it does | Stack | Outcome |
|---|---|---|---|
| [HCC Coding Assistant](https://github.com/thiagobandeira1/HCC-Coding-Assistant) | RAG + agent over 8,019 HCC-mapped ICD-10 codes: clinical language → validated codes → CMS-HCC V28 category → RAF estimate, with all math in deterministic tools | LangChain 1.x, OpenAI, LangGraph memory | Every answer grounded in 2026 CMS reference data — zero codes from LLM memory |
| [Readmission Risk API](https://github.com/thiagobandeira1/readmission-risk-api) | FastAPI service predicting 30-day readmission risk for Medicare patients, with per-patient SHAP explanations | XGBoost, FastAPI, SHAP, Docker | AUROC 0.797 on 67 RFE-selected features |
| [Medicare 30-Day Readmission (MIMIC-IV)](https://github.com/thiagobandeira1/Medicare-30day-Readmission-MIMIC-IV) | Reproducible readmission-prediction pipeline with a peer-review-grade no-leakage protocol | Python, gradient boosting, MIMIC-IV v3.1 | FIU capstone refactored for publication |
| [Avoidable ED Visits Intervention](https://github.com/thiagobandeira1/Avoidable-ED-Visits-Primary-Care-Intervention) | Data-driven intervention targeting avoidable emergency department visits in a Medicare Advantage population | NYU-EDA algorithm, Python, operational workflow design | 15,000+ ED claims analyzed; $2M+ avoidable-visit savings identified |
| Codex HCC *(private/production)* | End-to-end HCC extraction from medical records: OCR → rules + LLM arbiter → evidence scoring → RAF | Python, Azure Document Intelligence, OpenAI, FastAPI | Precision +8.8pp across 11 tuning iterations at ~97% HCC recall |
| VBC Financial Dashboard *(private/production)* | HIPAA-compliant value-based care performance platform: claims, quality, and financial analytics | React, TypeScript, Supabase/PostgreSQL, Cloudflare Zero Trust, CI/CD | Runs the monthly P&L for a full-risk Medicare operation |

## Skills

**Languages:** Python · SQL · R · TypeScript
**ML:** XGBoost · LightGBM · scikit-learn · SHAP · feature engineering · model evaluation
**LLM & GenAI:** LangChain · RAG · agentic workflows · tool calling · MCP · OpenAI / Azure OpenAI APIs
**Data:** PostgreSQL · Supabase · pandas · Spark/PySpark · Delta Lake · Databricks · Power BI
**Engineering:** FastAPI · Flask · Docker · Git/GitHub · CI/CD · React
**Cloud:** AWS (ML certified) · Azure (Document Intelligence, OpenAI)
**Healthcare:** CMS-HCC V28 / RAF · HEDIS / Stars · FHIR R4 · claims analytics · Medicare Advantage / full-risk VBC

## What I want to build next

- Agentic AI for clinical documentation and risk-adjustment review
- Real-time quality-gap closure systems that plug into care-team workflows
- ML that survives contact with production healthcare data — messy OCR, sparse labels, and all

## Contact

📧 thiagobatistanb@gmail.com
