# Autonomous Self-Improving Research System

An AI-powered agent-based system that autonomously:
- Generates scientific hypotheses
- Runs experiments
- Analyzes data and visualizations
- Writes research papers
- Evolves by rewriting its own code
- Learns and improves continuously

## 🔬 Key Concepts

This system combines three advanced approaches:
1. **AI Scientist v2** — hypothesis generation and experimentation
2. **Darwin Gödel Machine (DGM)** — self-improving code through empirical evolution
3. **Agent Architecture** — modular, scalable, inspectable design

## 🚀 System Overview

| Component              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `Idea Agent`           | Uses LLMs and literature to propose hypotheses                              |
| `Experiment Manager`   | Orchestrates research phases: prototyping, tuning, ablation                 |
| `Experiment Tree`      | Tracks branching paths and results of multiple agents                       |
| `VLM Agent`            | Interprets data visualizations and plots                                    |
| `Code Generator Agent` | Writes and tests Python code for experiments                                |
| `Darwin Gödel Agent`   | Evolves its own codebase using mutations, testing, and selection            |
| `Integrations`         | APIs: OpenAI, GitHub, SWE-bench, Hugging Face, Semantic Scholar             |
| `Evolution Storage`    | Logs all mutations, results, and rollback history                           |

## 📦 Setup

```bash
git clone https://github.com/your-org/autonomous-research-ai.git
cd autonomous-research-ai
docker-compose up --build
