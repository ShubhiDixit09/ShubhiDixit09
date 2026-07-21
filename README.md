# Shubhi Dixit

Computer Science undergraduate at **Delhi Technological University (DTU)** passionate about **Artificial Intelligence, Distributed Systems, Competitive Programming, and Software Engineering**.

I enjoy solving algorithmic challenges, building intelligent systems, and applying AI to real-world problems through hands-on projects. I believe in learning by building and continuously exploring new technologies.

---

### Areas of Interest

**Artificial Intelligence & Machine Learning**
- Machine Learning
- Deep Learning
- Retrieval-Augmented Generation (RAG)
- Agentic AI
- Computer Vision

**Competitive Programming**
- Dynamic Programming
- Graph Algorithms
- Trees
- Binary Search
- Sliding Window
- Two Pointers
- Greedy Algorithms
  
---

## 🚀 Projects

### NyayaBot

NyayaBot is a **100% on-device, zero-cloud legal action engine** built for Track 1: AI for Legal Assistance at the Google "Build with Gemma" hackathon (AIMS-DTU), helping citizens navigate legal processes without sending private grievances to a cloud server. Built with a teammate.

**Key Features**

- Runs entirely on-device on **Gemma 4** via Ollama using Per-Layer Embeddings, keeping inference under 6GB VRAM with zero cloud dependency
- Hinglish processing engine that maps conversational, code-mixed input directly to statutory intent
- Vision notice parser that extracts fine, deadline, and issuing authority straight from a photographed legal notice — no OCR chain
- Hierarchical RAG pipeline over ChromaDB that retrieves the relevant Act before narrowing to the exact Section
- Custom guardrail layer (**ShieldAI**) enforcing citation verification and output safety checks to prevent hallucinated legal answers
- ReAct-loop workflow orchestrator coordinating 8 tools (statutory search, document drafting, citation verification) over a 13-table SQLite schema with SQL-level compare-and-swap concurrency and idempotency-key validation for atomic, conflict-safe case writes

**Tech Stack**

Python • TypeScript • React • Gemma 4 • Ollama • ChromaDB • SQLite

🔗 **Repository:** [Gemma-AIMS](https://github.com/ShubhiDixit09/Gemma-AIMS)

Status: 🏆 Built with Gemma — AIMS-DTU Hackathon (Track 1: AI for Legal Assistance)

---

### SkillForge

SkillForge is an extensible **Agentic AI runtime** that orchestrates specialized AI agents, memory, and external tools to autonomously execute complex workflows from natural-language instructions. It is designed as a foundation for intelligent automation across software systems, with an extensible architecture for future robotics and edge AI integration.

## Architecture

```text
                User
                  │
                  ▼
      Natural Language Request
                  │
                  ▼
        Agent Orchestrator
                  │
     ┌────────────┼────────────┐
     ▼            ▼            ▼
Planning      Memory       Vision
  Agent        Agent        Agent
     └────────────┼────────────┘
                  ▼
         Execution Agent
                  │
                  ▼
     Tool Registry & Adapters
                  │
 ┌─────────┬─────────┬─────────┬─────────┐
 │ Browser │ Files   │Terminal │ OpenCV │
 └─────────┴─────────┴─────────┴─────────┘
                  │
                  ▼
 Simulation & Robotics Adapters
```

## Key Features

- Multi-agent architecture comprising **Planning, Vision, Memory, and Execution** agents
- Natural-language task execution powered by Large Language Models (LLMs)
- Modular tool execution framework for Filesystem, Browser, Terminal, and external APIs
- Event-driven workflow orchestration with reusable AI skills
- Computer vision support using OpenCV
- Browser automation for autonomous web interactions
- Extensible adapter system for simulation and future robotics integration
- Distributed runtime designed for scalable agent orchestration


**Tech Stack**

Python • FastAPI • LangGraph • OpenCV • Docker • Git

### Planned Integrations

ROS2 • Gazebo • Playwright • PostgreSQL • Redis • YOLOv8

Status: 🚧 Active Development

---

### ChronoSync

ChronoSync is an intelligent timetable scheduling platform for universities that combines Genetic Algorithms and Greedy Optimization to automate timetable generation while satisfying scheduling constraints and maximizing resource utilization.

**Key Features**

- Multi-department timetable scheduling
- Faculty preference optimization
- Hybrid Genetic Algorithm + Greedy Optimization
- Automatic conflict detection and schedule regeneration
- Shared classroom and laboratory allocation
- Role-based dashboards for Admin, Teacher, and Student
- Designed for seamless ERP integration

## Tech Stack

React.js • Node.js • Express.js • MongoDB • Python • Genetic Algorithms • Greedy Optimization

🔗 **Repository:** [ChronoSync](https://github.com/ShubhiDixit09/ChronoSync)

---

## Tech Stack

### Languages

- C++
- Python
- JavaScript

### Frontend

- React.js
- HTML
- CSS

### Backend

- Node.js
- Express.js
- Fast API

### Database

- MongoDB

### Core CS

- Data Structures & Algorithms
- Object-Oriented Programming
- Operating Systems

### AI / ML

- LangGraph
- OpenCV

### Tools & Platforms

- Git
- GitHub
- Postman
- VS Code
- ROS2
- Arduino IDE

---

## Competitive Programming

I regularly practice Competitive Programming to strengthen problem-solving, algorithmic thinking, and the ability to design efficient algorithms under time constraints.
- **LeetCode:** **90+ Problems Solved**
- **Codeforces:** Newbie *(10+ Problems Solved)*

---

## 🏆 Achievements

- **99.08 Percentile** in JEE Main
- **Qualified JEE Advanced**
- **1st Place** – Guessapalooza, IEEE DTU INVICTUS Annual Technical Fest *(₹3,000 Cash Prize)*
- **2nd Place** – State-Level Mental Mathematics Competition *(₹10,500 Cash Prize)*
- **Rank 12** – MVPP Delhi State Scholarship Examination among **20,000+ participants** *(₹5,000 Scholarship)*

---

### 📚 Currently Working On

- Building **SkillForge**, an extensible multi-agent AI runtime for intelligent automation with future robotics support.
- Learning **Machine Learning, Deep Learning, Generative AI, RAG, and Multi-Agent AI** through hands-on projects.
- Exploring **ROS2, Computer Vision, LangGraph, and Snapdragon AI technologies** for intelligent autonomous systems.
- Strengthening problem-solving skills through Data Structures & Algorithms and Competitive Programming.

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/shubhi-dixit-dtu/)
- [LeetCode](https://leetcode.com/u/shubhi_dixit_09/)
- [Codeforces](https://codeforces.com/profile/shubhi.dixit.dtu)
