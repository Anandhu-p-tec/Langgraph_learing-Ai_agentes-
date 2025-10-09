# LangGraph Learning — AI Agents

A learning repository demonstrating the fundamentals of **Agentic AI** using **LangGraph** — a graph-based framework for structuring intelligent agents.  
This project evolves step-by-step from basic graph construction to creating fully functional agents capable of reasoning, decision-making, and tool use.

---

## 🧠 Project Overview

This repository is designed as a **hands-on exploration** of how agentic systems can be represented using graph-based logic.

Each module incrementally introduces a new concept:
- From **simple graph creation**
- To **conditional branching**
- To **tool integration and autonomous decision-making**

The final modules demonstrate a complete **AI agent pipeline** — capable of perceiving input, reasoning through graph structures, and taking action via tool calls.

---

## 🎯 Goals & Learning Objectives

**Main Goal:**  
To understand and showcase how graph-based reasoning frameworks like LangGraph can be used to **build, visualize, and execute agentic AI systems**.

**Learning Outcomes:**
- Learn how to represent reasoning and control flow as graph nodes and edges.
- Understand how agents can make **conditional decisions** within structured graphs.
- Implement **tool-based actions** that extend agent capabilities.
- Observe **agentic behavior** — perception → reasoning → action.
- Appreciate the **transparency, modularity, and interpretability** of graph-driven AI.

---
## 🧩 Repository Structure
```
Langgraph_learning-AI_agents/
├── 1_simple_graph.ipynb
├── 2_graph_with_condition.ipynb
├── 3_chat_bot.ipynb
├── 4_tool_call.ipynb
├── 5_tool_call_agent.ipynb
├── main.py
├── pyproject.toml
├── .python-version
├── .gitignore
└── README.md
```

---

## 📘 Module Explanations

### 1️⃣ `1_simple_graph.ipynb`
**Purpose:**  
Introduces the foundation of LangGraph — creating simple nodes and edges to represent sequential tasks.

**Demonstrates:**
- How to define graph structures.
- Simple node execution and traversal.
- Flow representation without conditional logic.

**Learning Focus:**  
Understanding graph-based thinking and how execution can move across connected nodes.

---

### 2️⃣ `2_graph_with_condition.ipynb`
**Purpose:**  
Adds **conditional branching** to the graph, introducing decision points.

**Demonstrates:**
- Nodes with **conditional edges**.
- How control flow changes based on input or state.
- Representation of “if-else” logic in graph format.

**Learning Focus:**  
How decision-making and branching logic are embedded into agentic systems.

---

### 3️⃣ `3_chat_bot.ipynb`
**Purpose:**  
Implements a **graph-based conversational flow**, simulating how a chatbot can navigate dialogue states.

**Demonstrates:**
- Nodes as dialogue states.
- Conditional branching based on user input.
- Managing conversation context via graph transitions.

**Learning Focus:**  
Understanding **dialogue management** and contextual flow within a graph structure.

---

### 4️⃣ `4_tool_call.ipynb`
**Purpose:**  
Introduces **tool integration**, allowing the agent to perform actions or fetch data via external APIs or functions.

**Demonstrates:**
- How to embed “tool nodes” in graphs.
- Executing function calls during traversal.
- Using tool outputs to decide next steps.

**Learning Focus:**  
Bridging graph logic with external capabilities — the foundation of **agentic behavior**.

---

### 5️⃣ `5_tool_call_agent.ipynb`
**Purpose:**  
Combines all prior concepts to build a **fully functioning agent** using LangGraph.

**Demonstrates:**
- Graph-based reasoning and planning.
- Integration of multiple tools.
- Conditional and iterative decision-making.
- Handling success, failure, and fallback paths.

**Learning Focus:**  
Creating **autonomous, reasoning-driven agents** — where graphs define the agent’s mind and tools define its actions.

---

### ⚙️ `main.py`
**Purpose:**  
Runs or connects multiple graph modules for end-to-end execution.

**Demonstrates:**
- How to instantiate and execute a LangGraph-based agent.
- Running different modules or test scenarios.
- Serving as the entry point for experimentation.

---

## 🧩 Characteristics of Agentic AI with LangGraph

| Characteristic | Description |
|----------------|-------------|
| **Modularity** | Each node or subgraph represents a distinct skill or reasoning unit. |
| **Transparency** | Every decision and transition is visible and traceable through the graph. |
| **Reusability** | Graph components (nodes, edges) can be recombined to form new agents. |
| **Dynamic Behavior** | Agents adapt their flow based on real-time input or tool results. |
| **Declarative Reasoning** | Logic is expressed as connections and conditions rather than procedural code. |
| **Agent Loop** | The flow naturally follows: **Perceive → Reason → Act → Update**. |

---

## 🚀 How to Run

1. **Clone the repository**
   ```
   git clone https://github.com/Anandhu-p-tec/Langgraph_learing-Ai_agentes-.git
   cd Langgraph_learing-Ai_agentes-
2. Set up environment
  ```
  pip install -r requirements.txt
  # or, if using poetry
  poetry install
```
3. Run Jupyter notebooks
   ```
   Open each .ipynb in sequence to follow the learning flow.
   ```
4. Execute the main script
   ```
   python main.py
   ```
### Summary of Learning
Through this project, you learn to:

Structure AI behavior as a graph of reasoning steps.

Connect actions and decisions into a coherent agentic flow.

Integrate tools and conditional logic for real-world adaptability.

Build interpretable and modular agents — the core of Agentic AI design.

Author: Anandhu P

Goal: To demonstrate a deep understanding of Agentic AI principles using LangGraph through structured, incremental learning.
   
   





## 🧩 Repository Structure

