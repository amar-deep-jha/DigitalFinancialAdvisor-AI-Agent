
# FinSaathi AI – Digital Financial Literacy Assistant

This repository documents the capstone project **FinSaathi AI**, developed during the **IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies**. The internship was a collaborative initiative by the **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild**.

The goal of this project is to make financial literacy **accessible, personalized, and secure**, helping users understand digital finance tools like UPI, avoid online scams, and manage personal budgets through the power of AI.

## 📝 Table of Contents
- [Intern Details](#intern-details)
- [About the Internship](#about-the-internship)
- [Project: FinSaathi AI – Digital Financial Literacy Assistant](#project-finsaathi-ai--digital-financial-literacy-assistant)
  - [Problem Statement](#problem-statement)
  - [Solution Overview](#solution-overview)
- [⚙️ Technology Stack](#️-technology-stack)
- [🚀 Project Workflow](#-project-workflow)
- [📊 Results](#-results)
- [📁 Repository Contents](#-repository-contents)

## 👨‍💻 Intern Details
- **Name:** Amar Deep Jha
- **Institute:** [Krishna Institute of Technology Kanpur Nagar](https://kgikanpur.in/)
- **Duration:** 4 Weeks (15th July 2025 to 7th August 2025)

## 📖 About the Internship
This internship provided practical exposure to AI and Cloud technologies using IBM’s platforms and tools. Over four weeks, participants gained skills through weekly sessions, cloud labs, and final project development.

**Curriculum Summary:**
- Week 1: IBM Cloud intro, AI foundations, cloud services
- Week 2: Data analytics, Cloud EDA, hands-on labs
- Week 3-4: Agentic AI labs, watsonx.ai, Retrieval-Augmented Generation (RAG), Granite LLMs

## 💡 Project: FinSaathi AI – Digital Financial Literacy Assistant

### Problem Statement
Millions of people are unfamiliar with digital financial tools like UPI, secure banking, and online fraud protection. The lack of awareness results in financial vulnerability and missed opportunities for safe digital transactions.

### Solution Overview
FinSaathi AI is an AI-powered assistant built using IBM watsonx.ai and Granite models. It uses RAG (Retrieval-Augmented Generation) to retrieve reliable financial education content and answer user queries in multiple languages. It covers:
- UPI usage and safety
- Online scam awareness
- Budgeting and saving strategies
- Interest rates and digital wallets

## ⚙️ Technology Stack
- **Cloud Platform:** IBM Cloud Lite
- **AI Model:** IBM Granite (e.g., granite-13b-instruct-v2)
- **Interface:** IBM watsonx.ai Studio
- **RAG Framework:** Vector index with file-based knowledge base
- **Languages:** Python, Markdown, IBM YAML assets

## 🚀 Project Workflow
1. Researched problem area and finalized scope (Digital Financial Literacy).
2. Collected documents from reliable sources (RBI, NPCI, Banks).
3. Uploaded files into watsonx.ai Knowledge Base.
4. Configured vector index and deployed retrieval pipeline.
5. Tested user queries in English and Hindi.
6. Deployed the AI Agent and validated its multilingual response capabilities.

## 📊 Results
FinSaathi AI successfully answered diverse financial questions using RAG + Granite LLM. The project empowers users with digital financial knowledge in an easy and interactive format.

<img src="https://github.com/user-attachments/assets/Screenshot (116).png" alt="Demo Screenshot 1" />
<img src="https://github.com/user-attachments/assets/Screenshot (117).png" alt="Demo Screenshot 2" />

## 📁 Repository Contents
- `FinSaathi_Agent_Notebook.ipynb`: Agent development notebook inside watsonx.ai
- `README.md`: This file
- `RBI_UPI_User_Guide.docx`: Knowledge base document for UPI education
- `Financial_Fraud_Awareness_Brochure.docx`: Educational content on online frauds
- `Online_Banking_Dos_and_Donts.pdf`: Guidelines on safe banking practices
- `Bilingual_Banking_Glossary.txt`: Glossary of terms in Hindi & English
