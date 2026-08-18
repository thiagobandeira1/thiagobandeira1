# Hi, I'm Thiago Bandeira 👋

**AI/ML Engineer & Healthcare Operations Leader, Miami, FL**

I build production AI systems inside the healthcare operation I run. As Director of
Operations & Innovation at a value-based care organization serving 14,000+ patients,
I lead a full-risk Medicare panel of 4,000+ members (4.5+ Stars, 3 consecutive years)
and personally design, ship, and maintain the ML models, LLM applications, and
analytics platforms behind those results: a 34% panel-deficit turnaround, a 41%
reduction in avoidable ER visits and admissions, and $50K+ in recovered revenue
through Python/SQL automation.

- 🎓 M.S. Data Science & Artificial Intelligence, Florida International University (GPA 4.0/4.0)
- 📜 AWS Certified Machine Learning Engineer (Associate)
- 🌎 Trilingual: English, Portuguese, Spanish

## What I'm working on

- 🤖 **LLM systems in live clinical workflows**: an AI phone operator handling real
  patient calls end-to-end (3CX + RAG, human-in-the-loop escalation), and AI-assisted
  HCC risk-adjustment coding (LLM APIs, MCP integrations, LangChain)
- 📊 **Value-based care analytics**: HEDIS/Stars performance, HCC/RAF risk adjustment,
  and claims analytics processing ~150K claim lines per month
- 🏥 **Utilization reduction that holds up**: hospitalization-risk prediction feeding
  proactive CCM/TCM outreach, cutting avoidable readmissions 10 to 15%
- 👥 **Leading 80+ clinical and administrative staff** (10 providers, 13 departments)
  with SOP standardization and real-time KPI platforms

## Main projects

| Project | What it does | Stack | Outcome |
|---|---|---|---|
| [HCC Coding Assistant](https://github.com/thiagobandeira1/HCC-Coding-Assistant) | RAG + agent over 8,019 HCC-mapped ICD-10 codes: clinical language to validated codes, CMS-HCC V28 category, and RAF estimate, with all math in deterministic tools | LangChain 1.x, OpenAI, LangGraph memory | Every answer grounded in 2026 CMS reference data, zero codes from LLM memory |
| [Readmission Risk API](https://github.com/thiagobandeira1/readmission-risk-api) | FastAPI service predicting 30-day readmission risk for Medicare patients, with per-patient SHAP explanations | XGBoost, FastAPI, SHAP, Docker | AUROC 0.797 on 67 RFE-selected features |
| [Medicare 30-Day Readmission (MIMIC-IV)](https://github.com/thiagobandeira1/Medicare-30day-Readmission-MIMIC-IV) | Reproducible readmission-prediction pipeline with a peer-review-grade no-leakage protocol | Python, gradient boosting, MIMIC-IV v3.1 | FIU capstone refactored for publication |
| [Avoidable ED Visits Intervention](https://github.com/thiagobandeira1/Avoidable-ED-Visits-Primary-Care-Intervention) | Data-driven intervention targeting avoidable emergency department visits in a Medicare Advantage population | NYU-EDA algorithm, Python, operational workflow design | 15,000+ ED claims analyzed, 40% avoidable, $2M+ in annual savings opportunities identified |
| VBC Financial Dashboard *(private/production)* | HIPAA-conscious value-based care platform: claims from 3 insurance plans, real-time EHR data via FHIR R4 over SMART Backend Services, anomaly detection with Critical/High/Medium severity scoring, and per-patient surplus/deficit analytics | React, TypeScript, Supabase/PostgreSQL, Cloudflare Zero Trust, CI/CD | Closes the 1-to-2-month visibility gap claims files leave; zero-trust with MFA, row-level security on PHI, and append-only audit logs |
| Codex HCC *(private/production)* | Multi-agent HCC extraction from medical records: a review agent surfaces candidate conditions, an independent validation agent verifies each against documented evidence | Python, Azure Document Intelligence, OpenAI, FastAPI | Precision +8.8pp across 11 tuning iterations at ~97% HCC recall |
| AI Phone Operator *(private/production)* | Voice agent fielding inbound patient calls: answers routine questions grounded in a curated clinic knowledge base, triages, and escalates clinical or sensitive calls to humans | 3CX, RAG over LLM APIs, knowledge base | Cut front-desk call volume and wait times with reliable after-hours coverage |
| KPI & Performance Tracking App *(private/production)* | Web app for SOP adherence, training reinforcement, and real-time staff performance tracking across clinical and administrative workflows | Web dashboards, KPI analytics | Drives targeted coaching and continuous improvement across 13 departments |

## Research & publications

- Bandeira, T., Gonzalez, A., Poellabauer, C., Mondal, A.M. *Predicting 30-Day Hospital
  Readmission in Medicare Patients: An Interpretable Gradient-Boosting Model on MIMIC-IV
  v3.1.* M.S. Capstone, Florida International University.
- Bandeira, T. *Using the NYU ED Algorithm and Admission-Hour Patterns to Reduce Avoidable
  ED Visits: A Primary-Care Perspective* (2025). [SSRN](https://ssrn.com/abstract=5340590)

## Skills

**Languages:** Python · SQL · R · TypeScript
**ML:** XGBoost · LightGBM · scikit-learn · SHAP · model calibration · feature engineering · survival/time-to-event analysis · NLP
**LLM & GenAI:** LangChain · RAG with vector databases · agentic workflows · tool calling · MCP · prompt engineering · OpenAI & Anthropic Claude APIs
**Data:** PostgreSQL · Supabase · pandas · Spark/PySpark · Delta Lake · Databricks · Power BI · Tableau
**Engineering:** FastAPI · Flask · Docker · Git/GitHub · CI/CD (branch-per-environment) · React
**Cloud:** AWS (ML certified) · Azure (Document Intelligence, OpenAI, Cognitive Services) · Cloudflare
**Healthcare:** CMS-HCC V28 / RAF · HEDIS / Stars · HL7 & FHIR R4 / EHR interoperability · claims analytics · Medicare Advantage / full-risk VBC

## What I want to build next

- Agentic AI for clinical documentation and risk-adjustment review
- Real-time quality-gap closure systems that plug into care-team workflows
- ML that survives contact with production healthcare data: messy OCR, sparse labels, and all

## Contact

📧 thiagobatistanb@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/thiago-bandeira-ai)
