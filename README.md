# AI-Agentic-Design-Patterns-AutoGen
# 🤖 AI Agentic Design Patterns with AutoGen

> **Course Projects** | DeepLearning.AI — *AI Agentic Design Patterns with AutoGen*

A hands-on collection of Jupyter notebooks exploring core **agentic AI design patterns** using [Microsoft AutoGen](https://github.com/microsoft/autogen) — a framework for building multi-agent LLM applications. Each notebook corresponds to a key lesson from the course, demonstrating a distinct pattern of agent collaboration and tool use.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Projects](#projects)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Course Reference](#course-reference)

---

## Overview

This repository contains project notebooks from the **"AI Agentic Design Patterns with AutoGen"** course by DeepLearning.AI. The projects cover fundamental patterns in agentic AI systems — from simple two-agent reflection loops to multi-agent planning pipelines with tool use — all built using the AutoGen framework.

Each notebook is self-contained and demonstrates a real-world agentic workflow.

---

## Projects

### 1. 🪞 Reflection and Blogpost Writing
**File:** `Reflection_and_Blogpost_Writing (1).ipynb`

Implements the **Reflection Pattern** — one of the foundational agentic design patterns. A writer agent generates a blog post, while a critic/reviewer agent reflects on the output and provides feedback. The writer iterates based on that feedback, resulting in a polished final article.

**Key Concepts:**
- Reflection agentic pattern
- Two-agent conversation loop (Writer ↔ Critic)
- Iterative self-improvement via feedback

---

### 2. 🛠️ Tool Use and Conversational Chess
**File:** `Tool_Use_and_Conversational_Chess (1).ipynb`

Demonstrates the **Tool Use Pattern**, where agents are equipped with external tools (functions) to extend their capabilities beyond language. Applied to a chess game, agents use tools to validate and execute moves, maintaining game state across turns.

**Key Concepts:**
- Tool use / function calling in AutoGen
- Human-in-the-loop agent interaction
- Stateful conversational agents

---

### 3. 📋 Sequential Chats and Customer Onboarding
**File:** `Sequential_Chats_and_Customer_Onboarding (2).ipynb`

Showcases the **Sequential Chat Pattern** — chaining multiple two-agent conversations in a pipeline. Applied to a customer onboarding scenario, each step in the sequence collects or processes specific information before passing context to the next stage.

**Key Concepts:**
- Sequential chaining of multi-agent conversations
- Context carryover between conversation stages
- Practical pipeline design for business workflows

---

### 4. 📈 Planning and Stock Report Generation
**File:** `Planning_and_Stock_Report_Generation.ipynb`

Implements the **Planning Pattern** using a group of specialized agents. A planner agent coordinates sub-agents (researcher, analyst, writer) to gather stock data, analyze it, and produce a comprehensive stock report — simulating a real-world financial analysis pipeline.

**Key Concepts:**
- Planning / orchestration agentic pattern
- GroupChat with multiple specialized agents
- Web-augmented data retrieval and report generation

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent framework |
| [OpenAI GPT-4 / GPT-3.5](https://platform.openai.com) | Underlying LLM |
| Jupyter Notebook | Interactive development |
| Python 3.10+ | Runtime |

---

## Getting Started

### Prerequisites

```bash
pip install pyautogen openai
```

### Setup

1. Clone the repository:
```bash
git clone https://github.com/AirAbhiii/AI-Agentic-Design-Patterns-AutoGen.git
cd AI-Agentic-Design-Patterns-AutoGen
```

2. Set your OpenAI API key:
```python
import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"
```

3. Open any notebook in Jupyter and run the cells:
```bash
jupyter notebook
```

---

## Agentic Design Patterns Covered

```
┌─────────────────────────────────────────────────────┐
│           Agentic Design Patterns                   │
├──────────────────┬──────────────────────────────────┤
│  Reflection      │  Blogpost Writing                │
│  Tool Use        │  Conversational Chess            │
│  Sequential Chat │  Customer Onboarding             │
│  Planning        │  Stock Report Generation         │
└──────────────────┴──────────────────────────────────┘
```

---

## Course Reference

📖 **Course:** [AI Agentic Design Patterns with AutoGen](https://www.deeplearning.ai/short-courses/ai-agentic-design-patterns-with-autogen/)
🏫 **Platform:** DeepLearning.AI
🔧 **Framework:** Microsoft AutoGen

---


---

⭐ If you found this helpful, consider starring the repo!
