# RAG Mini-Project — Chat With Your Own Document

**NeuroFive Solutions — Generative AI & Prompt Engineering Internship**  
**Submitted by: Sumaira Safeer**

---

## 📌 Objective
Build a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows an AI to answer questions using a private document instead of relying only on its training data.

---

## 📄 Document Used
- **CoT_Persona_Prompting_Comparison.docx** (Prompt Engineering report on Chain-of-Thought + Persona techniques).

---

## 🛠️ Approach Chosen
**No-Code + Code Hybrid**
- **Primary Tool**: Google NotebookLM (Free & Powerful).
- **Alternative**: LangChain + OpenAI / Grok / Llama (for developers).

---

## 🔄 RAG Pipeline Built (NotebookLM)
1. Went to [notebooklm.google.com](https://notebooklm.google.com)
2. Created a new Notebook named **"CoT Persona Prompting Report"**
3. Uploaded the document (PDF version).
4. NotebookLM automatically handled chunking, embeddings, and vector search.

---

## ❓ Questions Asked (Test Grounding)

| # | Question | Result |
|---|----------|--------|
| 1 | What is the correct price of the ball? | ✅ Correct ($0.05) with full algebra |
| 2 | Who is the author and context? | ✅ Correct (Sumaira Safeer + NeuroFive Internship) |
| 3 | Difference between Run 1 and Run 2? | ✅ Detailed and accurate explanation |
| 4 | What persona was used and why? | ✅ Good explanation of "expert accountant" |
| 5 | Why does plain prompting fail? | ✅ Accurate analysis |
| 6 | Other techniques planned? (Hallucination test) | ✅ Correctly said "Not mentioned" |

**Key Finding**: No major hallucinations occurred. Answers were grounded and verifiable.

---

## 📊 Summary
**Tool Used**: Google NotebookLM (RAG)  
**Result**: Grounding the model with my own document significantly improved answer quality, accuracy, and trustworthiness compared to a plain LLM.

**Conclusion**: RAG is extremely effective for building "chat with your documents" applications. It allows LLMs to use private or domain-specific data they were never trained on.

---

## 📁 Files Included
- `RAG Mini-Project — Chat With Your Own Document.pdf`.
- Demo Video (Screen recording of NotebookLM Q&A).

---

**Made by Sumaira Safeer**  
Computer Engineer

---

*This project demonstrates practical understanding of Retrieval-Augmented Generation (RAG), embeddings, and grounded AI responses.*
