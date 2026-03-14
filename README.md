# 🚀 VC Nexus

**The Automated Due Diligence & Trust Score Engine for Venture Capital.**

## 📖 Overview
VC Nexus is a Compound AI System designed to automate the grueling process of startup due diligence. Instead of analysts spending weeks cross-referencing pitch decks, this platform ingests a startup's data room and deploys specialized AI agents to verify claims against real-world data, scan code for vulnerabilities, and gauge public sentiment—culminating in a deterministic, math-based **Trust Score**.

## ✨ Core Features
* **Document Parsing:** Extracts stated ARR, headcount, and legal clauses from uploaded Pitch Decks, Cap Tables, and Legal PDFs.
* **Factual Verification:** Cross-references stated founder claims against live B2B firmographic databases to catch discrepancies.
* **Technical Risk Assessment:** Scans GitHub repos and Software Bill of Materials (SBOMs) for vulnerabilities and malicious open-source licenses.
* **Real-Time Audit Log:** Streams asynchronous agent tasks to the frontend so VCs can watch the investigation live via a terminal-style UI.
* **Interactive Data Room:** A conversational AI interface allowing VCs to chat directly with the generated diligence report and raw documents.

## 🛠️ The Tech Stack
* **Framework:** Next.js & Tailwind CSS
* **AI Reasoning Engine:** Gemini 1.5 Pro
* **Document Ingestion:** LlamaParse
* **Company Data & Enrichment:** Apollo.io API
* **Web Scraping & Sentiment:** Tavily API
* **Security & SBOM Scanning:** Safedep
* **Real-Time UI Streaming:** Pusher
* **Conversational UI:** Vercel AI SDK
* **Zero-Trust Secrets Vault:** Infisical
