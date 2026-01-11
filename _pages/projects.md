---
title: "Projects"
permalink: /projects/
---

## [Precision Matrix Estimation using Preconditioned Conjugate Gradient with Regularization (Master's Thesis)](/assets/Masters_Degree_Thesis.pdf)

- Developed a methodology for precision matrix estimation in high-dimensional, singular settings where traditional inversion fails
- Applied Ledoit & Wolf regularization to ensure covariance matrix invertibility and Neumann series preconditioners to accelerate Preconditioned Conjugate Gradient (PCG) convergence
- Conducted theoretical analysis of convergence properties and empirical validation on synthetic and real-world datasets
- Focus areas: Numerical Linear Algebra, Convex Optimization, High-Dimensional Statistics

**Stack:** Python, NumPy, SciPy, Matplotlib

[View Thesis (PDF)](/assets/Masters_Degree_Thesis.pdf)

---

## [RAG Knowledge Base Assistant (Generative AI)](/projects/rag-knowledge-base/)

- Built a Retrieval-Augmented Generation (RAG) application to answer domain-specific questions over internal documentation
- Combines document ingestion, indexing, and a generative model
- Delivers contextual, source-grounded answers

**Stack:** Python, FastAPI, LangChain, ChromaDB, React, TypeScript, Docker

[View Details](/projects/rag-knowledge-base/) &#124; [GitHub](https://github.com/alejoba1097/knowledge-base-rag)

---

## Shipping Label OCR System (Computer Vision + NLP) — Tres Astronautas

- Built and iterated on an end-to-end OCR pipeline for shipping label extraction: segmentation, text detection, and token classification models (achieving 0.97+ precision)
- Developed FastAPI-based inference API with GPU/CPU support, health monitoring, and Kubernetes deployments on Azure
- Implemented image preprocessing pipelines (deskew, orientation correction, brightness/contrast) and integrated GPT-4o for OCR post-correction
- Managed ML lifecycle with DVC, CI/CD via Azure Pipelines, and continuous model retraining from production feedback

**Stack:** Python, PyTorch, Detectron2, Transformers, FastAPI, Docker, Azure, DVC, OpenCV

---

## Contact Center Analytics Platform (ETL + BI)

- Designed and implemented end-to-end ETL pipelines feeding Power BI dashboards for client operations
- Pulled data from core business applications and third-party APIs into Redshift/RDS
- Automated refreshes with Lambda and exposed clean, analytics-ready models to reporting teams
- Focus on reliability, traceability, and actionable KPIs for day-to-day decision-making

**Stack:** Python, SQL, AWS Lambda, Redshift, RDS, Power BI

---

## Agent Performance Monitoring App (Ops Case Study)

- Built an application to track agent performance using daily data exports (QlikSense and internal tools)
- Centralized KPIs like AHT, SLA, and quality scores
- Added alerting and simple visual summaries so supervisors could spot issues early and coach teams
- Result: more transparent performance management and fewer surprises at the end of the month

**Stack:** Python, SQL, QlikSense / BI, Agile workflows

---

## NLP & Big Data Pipeline (Master's Project)

- Developed an NLP pipeline to mine and classify large volumes of text
- Focused on preprocessing, feature engineering, and model training at scale
- Used Spark for distributed processing
- Experimented with multiple ML paradigms (supervised/unsupervised, evolutionary approaches) to improve accuracy and robustness on noisy, real-world data

**Stack:** Python, Spark, PySpark, scikit-learn, NLP

---

## Operational Insights Dashboard Suite

- Designed Power BI reports and dashboards for operations and client stakeholders
- Provided clear view of daily transactions, bottlenecks, and SLA compliance
- Combined raw operational data with business rules to surface only the metrics that mattered
- Made it easier to align teams around common targets

**Stack:** Power BI, SQL, Python, Data Modeling

