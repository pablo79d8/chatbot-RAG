# 🤖 Bachelor's Thesis: AI Chatbot with Retrieval-Augmented Generation (RAG) for Programming Education

> **Note:** The full thesis and documentation are written in Spanish.  
> _Nota: El trabajo y la documentación están redactados en español._

This repository contains the main outcomes of my Bachelor's Thesis at the University of Valladolid, focused on developing an intelligent chatbot optimized for the "Fundamentals of Programming" course. The project combines modern AI techniques, natural language processing, and robust software engineering to address real educational needs for both students and instructors.

## 📚 Project Overview

- **Goal:**  
  To design and implement a web-based conversational agent capable of answering student questions, providing contextual feedback on programming assignments, and assisting instructors—leveraging the power of Retrieval-Augmented Generation (RAG).

- **Target Users:**  
  - *Students*: Receive precise, course-aligned answers, guidance on code quality, and error explanations.
  - *Instructors*: Manage course materials, update chatbot context, and review student interactions.

- **Key Features:**
  - Integration of a local Large Language Model (LLM) with RAG to generate contextualized answers based on up-to-date course documentation.
  - Seamless integration with Moodle (via LTI) for authentication, user role management, and resource synchronization.
  - Two distinct user interfaces: tailored for students and for instructors.
  - Autonomous file management: upload, update, and retrieval of PDF course materials.
  - Feedback and evaluation system to assess answer quality and user satisfaction.
  - Persistent storage of user queries, chat history, and metadata.

## 🏗️ System Architecture

- **Backend:**  
  - Developed in Python using Flask for API endpoints and logic.
  - RAG pipeline implemented with LangChain, HuggingFace embeddings, and Ollama for running LLMs locally.
  - ChromaDB (vector database) for semantic search and retrieval of course materials.
  - PostgreSQL for relational data storage (users, chats, documents, feedback).
  - LTI standard for secure Moodle integration.

- **Frontend:**  
  - Built with Gradio for fast, interactive web interfaces.
  - Dynamic interface adapts based on user role (student/teacher).

- **Deployment:**  
  - Fully local solution (privacy-preserving), designed for scalability and future integration with other courses.

## 🛠️ Technologies Used

- **Python** (Flask, Gradio, LangChain)
- **Ollama** (local LLM serving)
- **ChromaDB** (vector database)
- **HuggingFace** (embeddings/models)
- **PostgreSQL** (+ pgvector extension)
- **Moodle LTI** (Learning Tools Interoperability)
- **Visual Studio Code**, **Astah UML** (for code and design)

## ✅ Evaluation & Results

- Conducted both technical testing (parameter tuning for retrieval thresholds, performance benchmarks) and real user evaluations (students and teachers).
- Used standard instruments: System Usability Scale (SUS), Net Promoter Score (NPS), NASA-TLX for cognitive workload, plus open-ended feedback.
- Results showed high usability and perceived value in both teaching and learning contexts, with clear improvements over generic AI chatbots.

## 🌟 Impact

This project demonstrates how advanced AI and NLP methods (RAG, LLMs) can be tailored to create practical, domain-specific solutions for education. The architecture is modular and scalable, making it adaptable for other courses or institutions.


## 🖼️ Screenshots

**Chatbot tab view:**

![Chatbot Tab](https://github.com/user-attachments/assets/e8858597-2ffa-47b9-958e-fd9069b5a3cb)

**File manager tab view:**

![File Manager Tab](https://github.com/user-attachments/assets/52589994-4ddd-44fb-9ca1-f8f93e64e332)



