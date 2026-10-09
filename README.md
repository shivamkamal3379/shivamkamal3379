# Hi, I'm Shivam Kamal

**AI/ML Engineer | LLM Agents, RAG & Computer Vision**

I ship production AI: LLM agents (LangChain, LangGraph), RAG pipelines and real-time computer vision, with 2+ years of hands-on experience. Based in Mohali, India.

**Open to full-time roles** as an AI/ML Engineer, GenAI Engineer or Agentic AI Engineer. Remote (India or worldwide), or on-site/hybrid in the Tricity (Chandigarh, Mohali, Panchkula).

[LinkedIn](https://www.linkedin.com/in/shivamkamal3379) | [Email](mailto:shivamkamal3379@gmail.com)

---

## What I've built

Most of my client work is under NDA, so names are withheld and those repos are private. Here is what the systems actually do.

### Agentic assistant for a productivity app
- Handles 23 intents end to end: tasks, calendar, goals, finances, email drafting and onboarding
- Two-model design: a small fast model detects intent, a larger model executes
- Code-level guardrail: the model cannot say "done" or "saved" until the backend confirms the action
- Mandatory user confirmation before any data-changing action, and numbered choices on ambiguous requests
- Stack: LangGraph, Mistral, FastAPI, Redis, LangSmith

### Legal research search over 1.43 lakh+ Supreme Court judgments
- Hybrid search: keyword matching for exact identifiers (section numbers, citations) plus semantic search for meaning
- Query rewriting, statute mapping, result fusion and reranking
- Ingestion pipeline with OCR fallback, deduplication and automated headnote validation
- Citation guardrails restrict answers to official court text

### Privacy-first contact search agent
- Natural-language search over a personal network, with two-layer retrieval and reranking
- Citation guardrails so the agent never invents a contact
- Voice input (Whisper), spoken responses (TTS) and business card OCR
- Stack: Python, FastAPI, Qdrant, GPT-4o, Docker

### Client-intelligence platform for an agency
- Reads client chats and call transcripts, gives each client a status with a stated reason, and flags neglected accounts and risks
- Runs fully locally for data privacy

### Real-time ANPR (number plate recognition)
- YOLOv8 detection, OpenCV preprocessing and OCR on live video streams
- 92% detection accuracy, using super-resolution, noise reduction and burst-frame capture

### Research: RAFI (Real-Artifact Injection)
- A training method for more robust deep learning in gastrointestinal endoscopy classification
- Independent research paper in preparation for arXiv / peer review

---

## Tech stack

| Area | Tools |
|---|---|
| LLMs and agents | LangChain, LangGraph, LangSmith, MCP servers, OpenAI, Mistral, prompt engineering |
| RAG and search | Pinecone, Qdrant, ChromaDB, FAISS, hybrid search, reranking |
| Computer vision | YOLOv8, OpenCV, EasyOCR, PyTorch |
| Backend | Python, FastAPI, Node.js, REST APIs, MongoDB, MySQL, Redis |
| Deployment | Docker, Git, GitHub |
| Frontend | React, Next.js, Tailwind CSS |

## Public repos

- [agentic-ai-handbook_Langgraph](https://github.com/shivamkamal3379/agentic-ai-handbook_Langgraph): LangGraph agentic AI handbook (Jupyter notebooks)
- [Car-Plate-Detection](https://github.com/shivamkamal3379/Car-Plate-Detection): number plate detection (Jupyter notebook)
- [Inventory-X](https://github.com/shivamkamal3379/Inventory-X): web app for managing and renting inventory, with real-time availability and automated cost calculation
- [Prompt-Wars-Antiquity-Platform](https://github.com/shivamkamal3379/Prompt-Wars-Antiquity-Platform): carbon footprint awareness platform built for PromptWars Virtual

## Education and mentoring

- BCA, Punjabi University, Patiala (2023 - 2026)
- I mentor aspiring AI/ML engineers on Topmate: roadmaps, project reviews and mock interviews

## Contact

Hiring for an AI/ML role, or building something with LLM agents? I'd be glad to talk.

- Email: shivamkamal3379@gmail.com
- LinkedIn: [linkedin.com/in/shivamkamal3379](https://www.linkedin.com/in/shivamkamal3379)
