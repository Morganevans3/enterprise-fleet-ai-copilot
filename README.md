# Enterprise Fleet Operations & AI Copilot Platform

## Overview
An end-to-end MLOps and Generative AI pipeline engineered on Databricks to optimize commercial vessel operations. This project features a scalable Medallion data architecture, predictive machine learning models for fleet management, and a LangChain-powered Retrieval-Augmented Generation (RAG) copilot to assist operators with technical documentation.

## Technical Stack
* **Cloud & Data Processing:** Databricks, PySpark, Delta Lake
* **Machine Learning & MLOps:** Scikit-Learn, MLflow, SHAP
* **Generative AI:** LangChain, ChromaDB, HuggingFace

## Key Features
* **Scalable Data Architecture:** Engineered a robust Medallion pipeline using PySpark and Delta Lake to ingest and transform complex fleet telemetry data.
* **Predictive Modeling & Registry:** Developed a Random Forest classifier managed through MLflow's model registry to ensure reproducible, version-controlled machine learning deployments.
* **AI Copilot Integration:** Architected a context-aware RAG application using LangChain and ChromaDB, allowing users to query technical vessel documentation via natural language.
