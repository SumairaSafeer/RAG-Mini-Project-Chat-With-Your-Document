# RAG Mini-Project: Chat With Your Own Document
**NeuroFive Solutions — Generative AI & Prompt Engineering Internship**
**Submitted by:** Sumaira Safeer

![Status](https://img.shields.io/badge/status-complete-brightgreen) ![Type](https://img.shields.io/badge/type-RAG-blue) ![Tool](https://img.shields.io/badge/tool-NotebookLM-orange)

---

## 📌 Objective
Build a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows an AI to answer questions using a private document, instead of relying solely on its training data and to evaluate how grounding affects accuracy and trustworthiness.

---

## 📄 Document Used
- **`CoT_Persona_Prompting_Comparison.docx`**  a Prompt Engineering report covering Chain-of-Thought and Persona prompting techniques.

---

## 🛠️ Approach Chosen
**No-Code + Code Hybrid**
| Approach | Tool | Notes |
|---|---|---|
| Primary | Google NotebookLM | Free, fast, no setup required. |
| Alternative | LangChain + OpenAI / Grok / Llama | For developers who need a custom, code-based pipeline. |

---

## 🔄 RAG Pipeline Built (NotebookLM)
1. Went to [notebooklm.google.com](https://notebooklm.google.com)
2. Created a new notebook named **"CoT Persona Prompting Report"**
3. Uploaded the source document (PDF version).
4. NotebookLM automatically handled chunking, embeddings, and vector search behind the scenes.

---

## ❓ Questions Asked (Grounding Test)
| # | Question | Result |
|---|----------|--------|
| 1 | What is the correct price of the ball? | ✅ Correct ($0.05), with full algebra shown. |
| 2 | Who is the author and what is the context? | ✅ Correct: Sumaira Safeer, NeuroFive internship. |
| 3 | Difference between Run 1 and Run 2? | ✅ Detailed and accurate explanation. |
| 4 | What persona was used, and why? | ✅ Good explanation of the "expert accountant" persona. |
| 5 | Why does plain prompting fail? | ✅ Accurate analysis |
| 6 | Are other techniques planned? (hallucination test) | ✅ Correctly responded "Not mentioned" |

**Key Finding:** No major hallucinations occurred — answers were grounded, consistent, and verifiable against the source document.

---

## 📊 Summary
- **Tool used:** Google NotebookLM (RAG)
- **Result:** Grounding the model with a private document significantly improved answer quality, accuracy, and trustworthiness compared to a plain LLM with no retrieval step.
- **Conclusion:** RAG is highly effective for building "chat with your documents" applications. It enables LLMs to reason over private or domain-specific data they were never trained on, while reducing hallucination risk.

---

## 📁 Files Included
```
RAG-Mini-Project/
├── RAG_Mini_Project_Chat_With_Your_Own_Document.pdf   # Full write-up
└── demo_video.mp4                                      # Screen recording of NotebookLM Q&A
```

---

## 💡 Skills Demonstrated
- Retrieval-Augmented Generation (RAG) fundamentals.
- Document embeddings and vector search.
- Grounded AI response evaluation.
- Hallucination testing and verification.

---

## 👩‍💻 Author
**Sumaira Safeer**
Computer Engineer

**Internship:** NeuroFive Solutions: Generative AI & Prompt Engineering

**LinkedIn:** [linkedin.com/in/sumaira-safeer-948804418](https://www.linkedin.com/in/sumaira-safeer-948804418/)
**GitHub:** [github.com/SumairaSafeer](https://github.com/SumairaSafeer)
