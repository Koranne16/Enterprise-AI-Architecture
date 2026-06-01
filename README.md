# Enterprise AI Architecture, FinOps & LLMOps Portfolio

**Nikhil R. Koranne | Director of Engineering & Sr. TPM**

This repository contains Architecture Decision Records (ADRs) and system design frameworks focused on solving the primary bottlenecks in enterprise AI adoption: **Compute Cost, Relational Data Accuracy, and Strict Data Governance.**

## The Executive Mandate
Enterprise AI is transitioning from proof-of-concept to production. The focus must shift from basic AI enablement to **AI FinOps**—architecting systems that aggressively reduce API OpEx, eliminate SaaS vendor sprawl, and protect proprietary data.

## Core Architecture Artifacts

### 1. Cost & Infrastructure Optimization
*   **[AI FinOps Strategy: Local Containerization vs. Managed APIs](01_AI_FinOps_Docker_vs_Managed_API.md)**
    *   *Focus:* Utilizing Docker Desktop volumes and cloud-synced storage architectures to eliminate managed AI subscription fees while maintaining enterprise backup integrity.

### 2. Complex Business Data Retrieval
*   **[Relational Data Mapping: GraphRAG Execution](02_ADR_GraphRAG_vs_VectorRAG.md)**
    *   *Focus:* Shifting from simple semantic similarity to Knowledge Graphs for complex operational workflows (e.g., mapping multi-unit LLC portfolios, floor plans, and financial ledgers).

### 3. Model Governance & Security
*   **[Semantic Routing & RLS Data Governance](03_Semantic_Routing_and_RLS.md)**
    *   *Focus:* Optimizing inference latency by routing complex tasks to Claude while securing vector databases (pgvector) using strict SQL Row-Level Security (RLS) to prevent internal data leakage.
