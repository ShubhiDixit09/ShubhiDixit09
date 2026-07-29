# Shubhi Dixit

Computer Science undergraduate at **Delhi Technological University (DTU)**, passionate about **Artificial Intelligence, Distributed Systems, Competitive Programming, and Software Engineering**.

I enjoy solving algorithmic challenges, building intelligent systems, and applying AI to real-world problems through hands-on projects. I believe in learning by building and continuously exploring new technologies.

---

# Featured Projects

I enjoy building systems where AI and algorithms produce real, verifiable outcomes—not just text responses. These projects explore agentic execution, privacy-aware AI, and combinatorial optimisation through complete frontend–backend applications.

---

## [SkillForge](https://github.com/ShubhiDixit09/SkillForge-updated) — Agentic AI Runtime

> A software-first runtime that converts natural-language goals into planned, permissioned, and verified software actions.

<p align="center">
  <img src="https://raw.githubusercontent.com/ShubhiDixit09/SkillForge-updated/main/skillforge-dashboard.png" alt="SkillForge execution dashboard" width="75%">
</p>

**Workflow:**  
`Next.js Dashboard → FastAPI → LangGraph Orchestrator → Specialised Agents → Bounded Tools → Verification → SQLite + Live SSE Events`

- Models each task as a stateful **plan → execute → verify** workflow instead of returning a single chatbot response.
- Routes steps across planning, coding, file, memory, execution, and verification roles through central agent and tool registries.
- Executes workspace inspection, safe file reads, Git status, memory search, and allow-listed test commands through a permissioned executor.
- Prevents path traversal and unrestricted shell access using workspace boundaries, command allow-lists, timeouts, and output limits.
- Streams persisted workflow events to the dashboard using **Server-Sent Events**, making every step, failure, and result observable.
- Works in deterministic zero-key mode, with optional local **Gemma through Ollama** for evidence-grounded final synthesis.
- Redesigned from an initially hardware-dependent robotics system into an environment-independent runtime; ROS2, Gazebo, and physical devices remain future adapters.

<details>
<summary><b>View architecture</b></summary>

```mermaid
flowchart LR
    U["Natural-language goal"] --> UI["Next.js UI"]
    UI --> API["FastAPI"]
    API --> LG["LangGraph"]
    LG --> AG["Specialised agents"]
    AG --> EX["Policy-bound executor"]
    EX --> TL["Files · Git · Tests · Memory"]
    TL --> VR["Verification"]
    VR --> UI
