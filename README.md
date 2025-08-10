# SmartSDLC – AI-Enhanced Software Development Lifecycle

SmartSDLC is a full-stack, AI-powered platform that reimagines the traditional Software Development Lifecycle (SDLC) by automating key stages using advanced Natural Language Processing (NLP) and state-of-the-art Generative AI models.

SmartSDLC isn't just a tool — it's an intelligent ecosystem enabling teams to instantly convert unstructured requirements into user stories, source code, test cases, and documentation. This automation minimizes manual effort, increases accuracy, and accelerates the software delivery pipeline.

---

## ✨ Key Features / Scenarios

### 1. Requirement Upload & Classification

- **Upload unstructured requirement PDFs**
- Backend extracts content (with PyMuPDF) and uses IBM Watsonx Granite-20B to classify sentences by SDLC phase: _Requirements, Design, Development, Testing, Deployment_.
- Outputs structured user stories, clearly grouped and displayed in the frontend for traceability and planning.

### 2. AI Code Generator

- **Input natural language requirements or user stories**
- AI generates relevant, production-grade code (multiple languages supported).
- Clean, syntax-highlighted code output; accelerates prototyping and reduces boilerplate.

### 3. Bug Fixer

- **Submit buggy code snippets** (Python, JavaScript, etc.)
- AI analyzes for syntax & logic errors and returns corrected, optimized code.
- Enables fast, automated debugging directly in the browser.

### 4. Test Case Generator

- **Generate test cases from code or requirements**
- AI produces robust unit tests (e.g., `unittest` or `pytest` style), ensuring consistent test coverage and reducing manual QA effort.

### 5. Code Summarizer

- **Upload any code snippet**
- AI generates human-readable explanations and documentation, aiding onboarding and long-term knowledge management of codebases.

### 6. Floating AI Chatbot Assistant

- **Real-time conversational assistance throughout the platform**
- Integrated with LangChain for intelligent context-aware support (e.g., “How do I write a unit test?”).
- Intuitive chat UI for interactive help on SDLC best practices and tool usage.

---

## 🚀 How It Works

1. **Frontend:** 
   - User-friendly web interface for uploads, prompts, and direct interaction.
   - Organized output grouping by SDLC phase; live syntax highlighting; integrated AI chat.

2. **Backend:** 
   - Python FastAPI server.
   - Orchestrates file parsing, prompt processing, and external AI model interactions (IBM Watsonx Granite-20B, LangChain).
   - Handles all automation and logic for classification, code/content generation, bug fixing, etc.

3. **AI Models:**
   - **IBM Watsonx Granite-20B**: For NLP-based classification, code, bug fixing, summaries.
   - **LangChain**: For conversational AI and context-aware chat support.

---

## 📦 Tech Stack

- **Frontend:** React, HTML, CSS
- **Backend:** Python, FastAPI
- **AI/ML:** IBM Watsonx APIs, LangChain, PyMuPDF, OpenAI-compatible endpoints
- **Testing:** unittest, pytest

---



