<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=25&pause=1000&color=00C2FF&center=true&vCenter=true&width=650&lines=AI+%26+Software+Engineer;RAG+%2B+Multi-Agent+Systems;Full-Stack+%C2%B7+Python+%C2%B7+React+%C2%B7+LLMs" alt="Typing Animation" />
</p>

<h1 align="center">Hi there <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">, I'm Madhan Kumar Tammineni</h1>
<h3 align="center">AI & Software Engineer · MS in Computer Science @ University of Memphis</h3>

---

## 🔗 Connect with Me

[![Portfolio](https://img.shields.io/badge/Portfolio-8A2BE2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.datascienceportfol.io/madhanktam)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madhan-kumar-tammineni-4487a4197/)
![Email](https://img.shields.io/badge/Email-madhant120@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)

---

## 👨‍💻 About Me

 I build production systems that put LLMs and retrieval to work and not just wrap an API and call it a feature.
 Hands-on with **RAG pipelines, multi-agent orchestration, local/open-source model serving, and LLM guardrails**, on top of a full-stack + cloud foundation (React, FastAPI, MongoDB, AWS).
 I also run applied research on whether AI systems can actually be trusted LLM hallucination/instruction-following experiments, and a federated-learning defense against poisoning attacks (submitted to IEEE S&P 2026).
currently building a multi-agent university assistant with **LangGraph** and  more soon.
Looking for **AI Engineer / Software Engineer** roles at product companies. Also open to health-tech given my St. Jude background, but not exclusively focused there.

---

## 💼 Experience

**Software Engineering Intern – St. Jude Children's Research Hospital**
📅 Mar 2026 – Present
- Built a full-stack web portal (React, FastAPI) for gene therapy researchers to analyze genomic integration site data
- Integrated Google DeepMind's **AlphaGenome API** for automated predictive analysis, replacing hours of manual review
- Built an interactive genome browser with automated hotspot detection and dynamic charts

**Graduate Research Assistant – University of Memphis**
📅 Feb 2025 – Present
- Running controlled experiments on **LLM instruction-following and hallucination behavior** across ChatGPT, Gemini, and Claude
- Contributed to a **Secure Federated Learning** framework defending against data/model poisoning attacks
- Built Power BI dashboards transforming raw logs into structured KPIs, cutting manual tracking effort **30%**

**Software Engineer – Carelon Global Solutions(Elevance Health)**
📅 Sep 2023 – Jan 2025
- Developed ServiceNow applications, forms, and catalog items using Business Rules, Client Scripts, and Script Includes
- Automated low-priority ticket handling, cutting ticket volume **25%** and saving ~15% of analyst time
- Contributed to an internal AI initiative (Spark.AI) alongside core platform work

**Software Engineer– LTIMindtree**
📅 Feb 2022 – July 2023
- Automated AWS infra deployment with **Terraform**; configured S3 + IAM policies and CloudWatch monitoring

---

## 🚀 Featured Projects

- 🏥 **Integrated Patient Records & AI Clinical Decision Assistant** | `React` `FastAPI` `MongoDB` `Gemini API` `ChromaDB`
  - Core of the project is data integration, not AI. Six hospital departments run on six genuinely different storage technologies (SQLite, JSON files, dbm key-value, shelve object store, CSV flat file), deliberately isolated to        mirror how real hospital vendor systems never share a database.
  - A Master Patient Index (MongoDB) unifies all six under one canonical patient ID, the same pattern real EHR platforms use for interoperability (Epic, IHE PIX/PDQ).
  - Every department is reachable only through a gateway module with a uniform contract (lookup, translate, query, normalize), so the rest of the app treats all six departments identically regardless of what's underneath.
  - AI clinical assistant layered on top of the unified data: patient-scoped RAG (ChromaDB, local embeddings) as a fallback to keyword routing, hand-rolled multi-agent orchestration for multi-department questions, and guardrails for citation checks and dosage/diagnosis-language flags.
  - Found and fixed a real retrieval-floor bug in live testing where off-topic questions were pulling real patient records; added a relevance threshold to fix it.

- 💳 **Credit Risk Analytics (AMEX Dataset)** | `Python` `XGBoost` `SHAP`
  - Processed a 1.1M+ row, 190+ feature dataset with leakage-safe preprocessing
  - Used SHAP to convert model predictions into actionable, explainable risk drivers

- 🔁 **TigerSwap — University P2P Marketplace** | `Next.js` `TypeScript` `Supabase`
  - Secure trading marketplace with `@memphis.edu` domain auth and campus pickup scheduling

- 🧬 **St. Jude BioHackathon (KIDS25)** | `AlphaFold` `R-Shiny`
  - Interactive protein structure visualization tool, presented at St. Jude's KIDS25 hackathon

- 🛒 **StyleSphere E-Commerce Platform** | `MySQL` `Figma`
  - Schema design + query optimization boosting SQL efficiency **30%**; revenue/churn reports with Figma UI

- 🔐 **Adaptive MFA Security Layer**
  - Trust-score–based authentication model for adaptive multi-factor authentication

---

## 🔬 Research & Publications

- **Secure Federated Learning against data/model poisoning** — benchmarked SVM, Random Forest, MLP, and CNN (AlexNet, GoogLeNet) defenses across IID/non-IID settings. *Submitted, IEEE S&P 2026.*
- **LLM instruction-following and self-reported honesty** — testing ChatGPT, Gemini, and Claude on tool-disable instruction compliance. *In progress, targeting ACL/EMNLP/AAAI.*
- 🗳️ **Aadhaar-Based Electronic Voting Machine (Fingerprint Auth)** — Python + Arduino. Published in *JUNI KHYAT Journal (UGC Care)*
- 💳 **Monitoring System for Preventing Unauthorized Credit Card Transactions** — Logistic Regression + AdaBoost, 92% accuracy on 100k+ transactions. Published in *TIJER International Journal*

---

## 🛠️ Skills

### 💻 Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![ServiceNow](https://img.shields.io/badge/ServiceNow-1BB55C?style=for-the-badge&logo=servicenow&logoColor=white)

### 🤖 AI Engineering
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logo=databricks&logoColor=white)
![HuggingFace](https://img.shields.io/badge/sentence--transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Systems-4B5563?style=for-the-badge)
![MultiAgent](https://img.shields.io/badge/Multi--Agent_Orchestration-4B5563?style=for-the-badge)
![Guardrails](https://img.shields.io/badge/LLM_Guardrails_%26_Eval-4B5563?style=for-the-badge)

### 📊 Applied ML
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-4B5563?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-4B5563?style=for-the-badge)

### ☁️ Infrastructure & Visualization
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 🎓 Education

- 🎓 **University of Memphis** (Jan 2025 – Expected Dec 2026)
  *MS in Computer Science, GPA: 3.5/4.0*
  Coursework: ML, AI, Cryptography, OS
  **Awards:** Peter I. Neathery Fellowship 🏅 | International Graduate Merit Scholarship 🎖️

- 🎓 **Sreenidhi Institute of Science & Technology (JNTU-H)** (2019 – 2023)
  *B.Tech in Electronics & Communication, GPA: 8.44/10*
  Govt. Scholarship Awardee

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Madhan120-prog&theme=react-dark&hide_border=true" />
</p>

---
