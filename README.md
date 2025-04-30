# 📚 Book Writing AI Agent

An intelligent, multi-agent system to autonomously **plan, write, edit, fact-check, and publish** a complete book using the **CrewAI framework** and **Groq's LLaMA-3-70B model**. This AI pipeline mimics the collaborative process of human authors, editors, and publishers to streamline creative book development.


---

##  Project Overview

This project leverages multiple specialized AI agents, each assigned a distinct role in the book creation pipeline:

- **Planning Agent**: Outlines the concept, characters, and story world.
- **Writing Agent**: Drafts each chapter based on the structured plan.
- **Editing Agent**: Refines grammar, coherence, and clarity.
- **Fact-Checking Agent**: Ensures all facts and real-world references are accurate.
- **Publishing Agent**: Formats the manuscript and prepares it for final release.

All agents work **sequentially** using the `CrewAI` orchestrator to simulate a real-world publishing team.

---

##  Tech Stack

- **Python**
- **[CrewAI](https://github.com/joaomdmoura/crewAI)** — Multi-agent workflow framework
- **[Langchain-Groq](https://pypi.org/project/langchain-groq/)** — LLaMA 3 integration via Groq API
- **Groq LLaMA-3-70B** — High-performance LLM for creativity and reasoning
---
##  How It Works

1. **Planning Agent**: Generates a story outline with characters and setting.
2. **Writing Agent**: Writes chapters (1000+ words each).
3. **Editing Agent**: Edits chapters for flow, grammar, and style.
4. **Fact-Checking Agent**: Verifies real-world references.
5. **Publishing Agent**: Produces the final formatted manuscript.

Each task runs in sequence and contributes to a comprehensive output.

##  Requirements

```
crewai
langchain
langchain_groq
numpy
```

