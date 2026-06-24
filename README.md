# 🏥 Healthcare Claims Assistance Platform
## Multi-Agent AI System

An intelligent Multi-Agent AI system for healthcare 
insurance claims processing.

## 🎯 What It Does
- Automatically routes insurance questions to 
  specialized AI agents
- Coverage Verification Agent — answers what's covered
- Claims Status Agent — guides claim filing process
- RAG pipeline ensures accurate document-grounded answers
- Zero hallucination — all answers from real policy docs

## 🏗️ Architecture
User Question → Supervisor Agent (LangGraph)
                      ↓              ↓
              Coverage Agent    Claims Agent
                      ↓              ↓
               RAG Pipeline (FAISS + Groq LLM)
                      ↓
              Real Insurance Policy Documents

## 🛠️ Tech Stack
- LangChain — RAG pipeline
- LangGraph — Multi-agent orchestration
- FAISS — Vector database
- Groq LLM (llama-3.3-70b) — Language model
- PyPDF — Document processing
- SentenceTransformers — Embeddings

## 📊 Project Stats
- 3 Insurance policy PDFs processed
- 68 pages of real insurance documents
- 378 document chunks in vector database
- 2 specialized AI agents
- Intelligent supervisor routing

## 🚀 How to Run
1. Open Healthcare_projectipynb.ipynb in Google Colab
2. Get free API key from console.groq.com
3. Add your GROQ_API_KEY in Cell 2
4. Run all cells in order

## 📋 Sample Questions
- "Is cataract surgery covered?"
- "What is the waiting period for pre-existing diseases?"
- "How do I file a reimbursement claim?"
- "What documents needed for hospitalization claim?"
- "Is there co-payment for senior citizens?"

## 📸 Screenshots

### Coverage Agent in Action
![Coverage Agent](Screenshot%202026-06-24%20173050.png)

### LangGraph Architecture
![Architecture](Screenshot%202026-06-24%20173258.png)

### Final Test Results
![Final Test](Screenshot%202026-06-24%20173453.png)

## 👩‍💻 Built By
Kavitha K — Generative AI Engineer
