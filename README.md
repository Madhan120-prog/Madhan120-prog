# Madhan Kumar Tammineni

**AI & Software Engineer · MS Computer Science @ University of Memphis**

[LinkedIn](https://www.linkedin.com/in/madhan-kumar-tammineni-4487a4197/) · [Portfolio](https://www.datascienceportfol.io/madhanktam) · madhant120@gmail.com

---

## About

I build production systems that put LLMs and retrieval to work, not just wrap an API and call it a feature. My background spans full-stack development (React, FastAPI, MongoDB), enterprise platforms (ServiceNow), and cloud infrastructure (AWS), and over the last year I've been doing hands-on AI engineering: retrieval-augmented generation, multi-agent orchestration, local/open-source model serving, and guardrails for AI-generated output.

I also run applied research on whether AI systems can actually be trusted — controlled experiments on LLM instruction-following and hallucination behavior, and a federated-learning defense against data/model poisoning (submitted to IEEE S&P 2026). That same habit of testing for where a system breaks, not just where it works, is why my RAG pipeline exists in the first place: I found a real bug where off-topic questions were pulling real patient records, and fixed it.

**Currently building**: a multi-agent university assistant (LangGraph) that answers student questions across housing, fees, registration, majors, and campus jobs — more on this soon as it comes together.

Looking for **AI Engineer / Software Engineer** roles at product companies building AI-integrated features, agentic systems, or developer tools. Also open to health-tech given my St. Jude background, but not exclusively focused there.

---

## Experience

**Software Engineering Intern — St. Jude Children's Research Hospital**
*Mar 2026 – Present*
- Built a full-stack web portal (React, Python, FastAPI) for gene therapy researchers to upload, explore, and analyze genomic integration site data
- Integrated Google DeepMind's AlphaGenome API for automated predictive analysis, replacing hours of manual review with an AI-driven pipeline
- Replaced static data tables with an interactive genome browser, automated hotspot detection, and dynamic charts

**Graduate Research Assistant — University of Memphis**
*Feb 2025 – Present*
- Running controlled experiments on LLM instruction-following and hallucination behavior across ChatGPT, Gemini, and Claude, targeting publication at ACL/EMNLP/AAAI
- Contributed to a Secure Federated Learning framework defending against data and model poisoning attacks — trained and benchmarked SVM, Random Forest, MLP, and CNN (AlexNet, GoogLeNet) models across IID/non-IID settings; findings submitted to IEEE S&P 2026
- Built Power BI dashboards transforming raw logs into structured KPIs, cutting manual tracking effort 30%

**ServiceNow Developer — Carelon Global Solutions**
*Sep 2023 – Jan 2025*
- Developed and configured ServiceNow applications, forms, and catalog items using Business Rules, Client Scripts, UI Policies, and Script Includes
- Automated low-priority ticket handling via server-side scripting and workflow rules, cutting ticket volume 25% and saving ~15% of analyst time
- Contributed to an internal AI initiative (Spark.AI) alongside core platform work

**Cloud & Data Engineering Intern — LTIMindtree**
*Jan 2023 – Aug 2023*
- Provisioned AWS resources (EC2, S3, IAM) using Terraform; configured CloudWatch monitoring and supported data ingestion POCs

---

## Featured Projects

### Integrated Patient Records & AI Clinical Decision Assistant
`React` `FastAPI` `MongoDB` `Gemini API` `ChromaDB` `sentence-transformers` `Ollama`

Full-stack system unifying 6 departments of multi-vendor patient data (MRI, X-Ray, ECG, CT, labs, treatment history) into a single timeline, with an AI clinical assistant answering natural-language questions across a patient's full record.

- RAG pipeline: local sentence-transformers embeddings + patient-scoped ChromaDB retrieval, running as a semantic fallback when keyword-based routing misses synonyms (e.g., "blood cell count" → WBC). Embeddings run locally — patient data never hits an external API for search.
- Found and fixed a real retrieval-floor bug in live testing: nearest-neighbor search has no built-in "nothing is relevant" case, so off-topic messages were retrieving real patient records. Added a cosine-distance relevance threshold to fix it.
- Multi-agent orchestration: hand-rolled specialist-per-department routing with a synthesizer pass for compound, multi-department questions.
- Local open-source vision inference: MedGemma via Ollama as an on-prem alternative to cloud-based image analysis.
- Guardrails: citation verification, confidence gating, and drug-dosage/diagnosis-language flags on AI-generated responses.
- Patient-ID filtering enforced at the database query level, not post-filtered — verified by a dedicated test, since retrieval that leaks across patients would be a real PHI exposure, not a cosmetic bug.

→ [repo link]

### Credit Risk Analytics — AMEX Dataset
`Python` `XGBoost` `SHAP`

Processed a 1.1M+ row, 190+ feature dataset with leakage-safe preprocessing; engineered customer-level temporal features and used SHAP to convert model predictions into actionable risk drivers.

→ [repo link]

### TigerSwap — University Peer-to-Peer Marketplace
`Next.js` `TypeScript` `Supabase`

Secure P2P trading marketplace with `@memphis.edu` domain authentication and integrated campus pickup scheduling.

→ [repo link]

### St. Jude BioHackathon (KIDS25) — Protein Structure Visualization
`AlphaFold` `R-Shiny`

Built an interactive visualization tool for protein structure prediction output, presented at St. Jude's KIDS25 hackathon.

→ [repo link]

---

## Additional Projects

- **StyleSphere E-Commerce Platform** — `MySQL` `Figma` — schema design and query optimization (+30% SQL efficiency), revenue/churn reporting, UI in Figma
- **Adaptive MFA Security Layer** — trust-score–based authentication model for adaptive multi-factor authentication

→ [repo links]

---

## Research

- **Secure Federated Learning against data/model poisoning** — benchmarked classical ML and CNN defenses across IID/non-IID settings. *Submitted, IEEE S&P 2026.*
- **LLM instruction-following and self-reported honesty** — testing whether ChatGPT, Gemini, and Claude comply with and honestly report on tool-disable instructions. *In progress, targeting ACL/EMNLP/AAAI.*
- **Aadhaar-Based Electronic Voting Machine Using Fingerprint Authentication** — *JUNI KHYAT Journal (UGC Care)*
- **Monitoring System for Preventing Unauthorized Credit Card Transactions** — *TIJER International Journal*

---

## Skills

**AI Engineering:** RAG system design · Vector search (ChromaDB) · sentence-transformers · Local/open-source model serving (Ollama) · Multi-agent orchestration · Prompt engineering · LLM guardrails & output verification · LLM evaluation methodology

**Languages & Frameworks:** Python · JavaScript · TypeScript · SQL · React · Next.js · FastAPI

**Applied ML:** scikit-learn · XGBoost · SHAP · PyTorch (CNN training — AlexNet, GoogLeNet)

**Infrastructure:** AWS (EC2, S3, IAM, CloudWatch) · Terraform · MongoDB · Linux · Git

**Platforms & Visualization:** ServiceNow · Power BI

---

## Education

**University of Memphis** — M.S. Computer Science, GPA: 3.5 · *Jan 2025 – Dec 2026*
Coursework: Machine Learning, AI, Cryptography, Operating Systems
Peter I. Neathery Fellowship · International Graduate Merit Scholarship

**Sreenidhi Institute of Science & Technology** — B.Tech, Electronics & Communication Engineering · *2019 – 2023*

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Madhan120-prog&theme=react-dark&hide_border=true" />
</p>
