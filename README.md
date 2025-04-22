# Strategic AI Insights

**Author:** Deokjin choi  
**Goal:** To explore how AI and data-driven approaches can power technology strategy and competitive insights.

## Purpose

This repository is where I share my thoughts, experiments, and discoveries on how AI and data-driven approaches can help us ask better questions,find meaningful answers, and generate strategic insights. The focus is on **problem discovery, solution design, and strategic foresight** with the belief that good questions, supported by data and clear reasoning,can lead to better decisions and impactful strategies.

## Key Themes

1. **AI-powered problem discovery and solution design for technology strategy**  
   → Applying machine learning and NLP to identify critical challenges, propose solutions, and support strategic decision-making.

2. **Competitive intelligence through multi-source analysis**  
   → Integrating patents, research papers, earnings reports, and market data to understand competitor strategies and technology trends.

3. **Technology forecasting and roadmap planning (MOT perspective)**  
   → Leveraging data-driven methods to support technology prediction, scenario planning, and future-oriented strategy building.

## Strategy Flow Overview
<pre>
┌───────────────────────────────────────────────┐
│   External Signals                            │
│   (Patents, Market Data, Earnings Calls, etc.)│
│   → Web Crawling, Patent DB, RAG, Embeddings  │
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│   Problem Discovery                          │
│   (What is the right question?)              │
│   → LLM-based summarization, Topic Modeling  │
│   → Clustering, Keyword Extraction, Prompting│
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│   Data Analysis & AI Exploration             │
│   (How to explore the solution?)             │
│   → Sentence Embeddings, FAISS, Few-shot     │
│   → Clustering (HDBSCAN / KMeans), UMAP      │
│   → LLM-guided similarity, Prompt-based Eval│
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│   Insight Generation                         │
│   (What do we learn from the results?)       │
│   → LLM-based summarization, Difference Gen  │
│   → Similarity Explanation, MECE Structuring │
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│   Strategy Formulation                       │
│   (How does this connect to strategy?)       │
│   → Competitive Differentiation, Forecasting │
│   → Scenario Planning, LLM-based Scenario Gen│
└───────────────────────┬───────────────────────┘
                        │
                        ▼
┌───────────────────────────────────────────────┐
│   Communication & Delivery                   │
│   (How to communicate the findings?)         │
│   → Visualizations (Plotly, Streamlit, etc.) │
│   → Executive Summary by LLM or Manual Write │
└───────────────────────────────────────────────┘
</pre>

## Repository Structure

1. theory/ → Conceptual frameworks and strategic methodologies
2. case_studies/ → Analysis of real-world competitive scenarios
3. code/ → Experiments, scripts, and notebooks

