# Syed Ahmed Basharat Ali (Basharat)

**Data scientist and analytics engineer in New York City.** I work on payments, fraud, settlement and reconciliation data, metric definitions and semantic layers, experimentation and causal inference, and LLM evaluation.

**Open to roles:** Data Scientist, Analytics Engineer, Senior Data Analyst, Business Operations / Strategy & Operations, Strategic Finance analytics, in New York or remote in the US.

[basharat.net](https://www.basharat.net) · [LinkedIn](https://linkedin.com/in/sa-basharat-ali) · sabasharat.ali@gmail.com

---

## Experience

- **Graduate Assistant, AI Implementation, Mercy University** (New York, Dec 2025 to present). University-wide Ethical AI Faculty Toolkit and GenAI literacy curriculum for 5,000+ students.
- **Freelance Data Science & AI Consultant** (own consulting practice). Through it I was the CEO's data person at Rime, a Saudi edge-AI retail camera startup: traced an 80% upstream data loss across a 150-device fleet, stabilized a 137 GB PostgreSQL backbone failing 8-hour Airbyte syncs, and shipped an 11-model dbt migration across a multi-tenant Snowflake warehouse with 50+ client schemas. Also built a bilingual Arabic/English AI assistant on OpenAI function calling for a grocery-delivery startup.
- **Data Scientist, Geidea** (Riyadh, Aug 2023 to Jan 2025), Saudi Arabia's largest payments processor. Promoted from Business Analyst within 6 months; member of the executive strategy team. Real-time anomaly detection on 1M+ daily payment transactions; merchant churn and revenue forecasting that informed a tiered retention strategy, cutting merchant churn from 35% to about 10% on a $5M+ portfolio; segmentation of 40,000+ merchants by MCC, interchange and chargeback behavior; settlement and onboarding data models covering 400,000+ POS terminals; automated collections pipelines contributing to $8M+ in additional annual profit; FinOps reconciliation and SLA reporting across 5+ teams.
- **Senior Data Consultant, EY** (Karachi, Jan 2022 to Jun 2023). Founding member of EY Pakistan's Business Consulting data team. Analytics, predictive modeling, audit automation and C-suite dashboards for GSK and National Foods; internal reporting layer for EY Pakistan leadership.
- **Data Analyst, Proxima AI** (Karachi, May 2021 to Jan 2022).

**Education:** M.S. Business Analytics, Mercy University (GPA 4.0, Aug 2026; founder and president of the Data & AI Club). B.S. Computer Science, University of Karachi.

---

## Public work (each runs locally with the Python standard library)

| Repository | What it shows |
|---|---|
| [ledger-integrity](https://github.com/sa-basharat-ali/ledger-integrity) | Reconciliation for agentic payments. Daily totals see the net error, not the gross: netting hid $32,732 (46%) of $71,570. A retry with a regenerated idempotency key was caught 0 of 53 times and was 93% of undetected dollar-hours. |
| [marketplace-payout-reconciliation](https://github.com/sa-basharat-ali/marketplace-payout-reconciliation) | 122,810 orders across three money records. Daily-total checks fire on 31 of 31 days of a clean book; a fee computed on tax passes every reconciliation until fees are recomputed from policy. |
| [merchant-freeze-economics](https://github.com/sa-basharat-ali/merchant-freeze-economics) | Pricing a merchant freeze against the fraud it prevents across 60,000 merchants. A 98%-recall policy loses $9.1M versus freezing nobody; cutting review time from 3 days to 1 is worth more than a two-point AUC gain. |
| [fraud-queue-economics](https://github.com/sa-basharat-ali/fraud-queue-economics) | Expected-value triage for a fraud review queue. Alert recall falls 85.1% to 80.0% while dollar recall rises 76.8% to 93.0% at 54% lower cost. |
| [llm-judge-validation](https://github.com/sa-basharat-ali/llm-judge-validation) | Validating an LLM judge against human labels. It overstates quality by 5.2 points overall and 19.4 in one category; its own confidence interval contains the truth 0% of the time. |
| [semantic-layer-trust-harness](https://github.com/sa-basharat-ali/semantic-layer-trust-harness) | Auditing a semantic layer against independent ground truth. 40 of 90 queries (44%) have no single correct answer until an allocation rule is declared. |
| [ai-spend-intelligence](https://github.com/sa-basharat-ali/ai-spend-intelligence) | AI spend from a raw card feed: 231 descriptors resolved to 15 vendors, seat vs usage billing classified, and metered spend shown to be uncallable before about day 12 of the month. |
| [fleet-silent-failure-detection](https://github.com/sa-basharat-ali/fleet-silent-failure-detection) | Silent-failure detection for a 314-device capture fleet. Row counts catch 18 of 43 failures; content checks catch 43 of 43. |
| [on-time-delivery-causal](https://github.com/sa-basharat-ali/on-time-delivery-causal) | Causal study on 101,684 orders. The definition of "on time" flips the effect on repeat purchase from -0.38 to +0.51 points. |

---

## Tools

Python, SQL, R, dbt, Snowflake, PostgreSQL, Oracle, Airflow, Airbyte, Talend, Tableau, Power BI, Metabase, scikit-learn, XGBoost, CatBoost, PyTorch, ARIMA, causal inference, OpenAI and Anthropic APIs, RAG, MCP, Claude Code, Cursor, AWS, Docker, GitHub Actions.
