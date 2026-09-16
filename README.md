# 🌌 DevCodex: The AI-First Knowledge Engine

Welcome to **DevCodex**—the open-source core of a revolutionary, ever-evolving knowledge graph designed to bridge the gap between human engineering wisdom and AI agent execution. 

We are building a world where your AI agents don't just "guess" architectural patterns or security rules; they **know** them. DevCodex is designed to augment reasoning by feeding AI agents crisp, high-signal nodes and typed edges, completely transforming how software is built, scaled, and secured globally.

---

## 🚀 The Vision: A World Connected by Structured Wisdom

Software engineering knowledge is currently trapped in walls of prose, scattered docs, and tribal knowledge. DevCodex changes the paradigm. We map knowledge into an actionable **Graph**:
- **For Humans:** A clear, interactive map of patterns, security mandates, and architectural decisions.
- **For AI Agents:** A precise, traversable graph (`graph/nodes.jsonl`) that agents read to instantly understand the *rules*, *principles*, and *context* of a project before writing a single line of code.

Imagine dropping an AI agent into any codebase and having it instantly align with the world's best engineering practices, securely and flawlessly. That is the world DevCodex is building.

## 🏗️ What is Open Source (Public) vs. Commercial?

We are aggressively committed to building a transparent, powerful open-source foundation. To ensure DevCodex empowers the entire world while remaining sustainable, we have clearly delineated the open-source machinery from the proprietary intelligence.

### 🟢 What is Public (This Repository - The Core Engine)
This repository contains the **DevCodex Core / Engine**. It is the open-source machinery that makes the magic happen. It will **never** be artificially limited. It includes:
1. **The Graph Schema & Specification:** The core rules and typed edges (e.g., `part-of`, `implements`, `depends-on`) that define how knowledge is connected.
2. **Local Curation Mechanics:** The tooling for projects to pull in knowledge and maintain a `.devcodex.lock` (curated subset of nodes).
3. **Agent Interaction Protocols:** Standardized guidelines (like our `AGENTS.md`) teaching any LLM or AI agent exactly how to traverse and utilize a DevCodex graph.
4. **Local Retrieval & Parsing:** Open-source tools for querying, rendering (Mermaid/HTML), and mutating the local knowledge graph.

### 🔒 What remains Proprietary (Main DevCodex Intelligence)
The commercial value and proprietary layer reside purely in the **Data**, not the machinery:
1. **The Canonical Knowledge Graph (`graph/nodes.jsonl`):** The massive, continuously curated database of security rules, production patterns, and architecture decisions.
2. **Deep Documentation (`docs/`):** The elaborative prose that backs up the nodes in the canonical graph.
3. **Managed Freshness & Subscriptions:** The distribution system that seamlessly updates your project's local DevCodex with the latest global engineering intelligence.

*You can build your own proprietary graphs using our open engine, entirely for free.*

## 🧭 Orientation & Preparation

We are preparing the engine for massive scale. If you are an open-source contributor, an AI agent builder, or an engineering leader looking to standardize your company's knowledge, here is how you can orient yourself:

1. **Understand the Graph:** Knowledge is stored as nodes connected by typed edges. Agents enter the graph where the task points (a tag, a layer, or a tool) and pull only the handful of nodes they need.
2. **Respect Authority:** Nodes declare their authority (`rule`, `recommendation`, `principle`) to augment judgment, not railroad it.
3. **Embrace Curation:** A project should only curate what it needs. Knowledge flows from the main graph to the project locally.

## 🤝 Join the Revolution
We are standardizing how AI builds software. Prepare your agents. Define your graphs. Let's build the future, perfectly aligned.

*More engine components, schema definitions, and tooling will be released into this public repository shortly. Star the repo to stay tuned!*
