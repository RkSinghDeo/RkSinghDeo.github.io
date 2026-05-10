---
title: "Services"
description: "Fixed-scope AWS data engineering engagements. You know what you're getting and when."
---

All engagements include: CDK IaC (reproducible, version-controlled infrastructure), CI/CD pipeline, CloudWatch monitoring dashboard, and a 30-minute handoff call with your team.

---

## AWS FinOps Audit

**You're paying too much. You don't know exactly where.**

I instrument your Lambda functions and Glue jobs, run Power Tuning, pull 90 days of Cost Explorer data into Athena, and deliver a prioritized list of right-sizing changes — ranked by ROI.

**What you get:**
- Itemized right-sizing report for every Lambda function and Glue job
- Estimated annual savings per change (so you can decide what to implement)
- Nightly automated cost monitoring (CDK-deployed, runs forever)
- Self-service Streamlit dashboard connected to Athena
- AI-generated weekly FinOps summary (Claude 3.5 Sonnet)

**Typical outcome:** 20–35% reduction in monthly compute spend.  
**Timeline:** 1 week  
**Starting at:** $1,500

---

## Serverless ETL Pipeline

**Your data needs to arrive reliably, every time, without waking anyone up.**

I design and build a fully serverless ETL pipeline from your source to your target — Lambda, Glue, SQS, Airflow (MWAA), or Step Functions depending on your use case. Includes data quality gates and alerting.

**What you get:**
- End-to-end pipeline from source to target (S3, Redshift, DynamoDB, or RDS)
- Data quality validation layer (record count, null rates, referential integrity)
- Slack/email alerting on failure with one-click replay
- CloudWatch dashboard with SLA metrics
- CDK stack and CI/CD pipeline for your team to maintain

**Typical outcome:** >99.5% pipeline reliability, <30min data freshness.  
**Timeline:** 2–3 weeks  
**Starting at:** $3,500

---

## Data Lakehouse Build

**You have S3 data. Your analysts can't query it reliably.**

I migrate your existing S3 data lake to Apache Iceberg with a medallion architecture (Bronze/Silver/Gold). Schema evolution, ACID transactions, and 60–90% faster Athena queries — without rewriting your downstream dashboards.

**What you get:**
- Iceberg table migration (Bronze/Silver/Gold layers) with zero downtime cutover
- PySpark Glue jobs with MERGE INTO CDC, deduplication, and data quality checks
- Athena workgroup configured for cost control and performance
- Optional: dbt models on Redshift Serverless for business-logic marts
- CDK IaC for the full lakehouse stack

**Typical outcome:** 50–90% reduction in Athena costs, 60% faster queries, schema changes in seconds.  
**Timeline:** 3–4 weeks  
**Starting at:** $5,000

---

## AI Data Agent (Bedrock)

**Your business users want to ask questions. Your analysts are a bottleneck.**

I build an Amazon Bedrock Agent with an Athena action group — business users ask natural-language questions, the agent generates and executes SQL against your Gold layer, and returns plain-English answers.

**What you get:**
- Bedrock Agent (Claude 3.5 Sonnet) wired to your Athena/Iceberg Gold layer
- Input validation and data governance pre-processing hook
- OpenAPI-defined action group (run_sql · list_tables · describe_table)
- Read-only safety layer — no DML possible through the agent
- CDK deployment with scoped IAM roles

**Typical outcome:** Analysts freed from ad-hoc query requests. Business stakeholders self-serve within 2 hours of training.  
**Timeline:** 1–2 weeks (requires existing Gold layer)  
**Starting at:** $2,500

---

## Not sure which fits?

[Get in touch](/contact/) — I'll review your current setup and tell you exactly where the highest-ROI work is. No sales pitch.
