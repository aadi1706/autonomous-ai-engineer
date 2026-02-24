# Autonomous AI Software Engineer

A self-improving autonomous AI agent capable of generating, reviewing, and evolving code using local Large Language Models via Ollama.

---

## Features

- Task-based code generation
- Self-review and scoring system
- Tool memory persistence
- Modular multi-agent architecture
- Local LLM execution (Llama3 via Ollama)
- Performance tracking and learning logs

---

## Architecture

The system consists of multiple internal agents:

- Planner
- Coder
- Reviewer
- Improver
- Intelligence Engine
- Benchmark Engine

Each task follows this pipeline:

Task → Planning → Code Generation → Debug → Review → Score → Store Tool

---

## Tech Stack

- Python 3
- Ollama
- Llama3
- Modular AI architecture
- Local execution environment

---

##️ How To Run

1. Install Ollama  
2. Pull model:

```
ollama pull llama3
```

3. Run agent:

```
python3 agent.py
```

4. Enter engineering task in terminal

---

## Project Structure

```
core/        → AI engine modules  
tools/       → Generated tools  
memory/      → Logs and intelligence data  
agent.py     → Main execution loop  
dashboard.py → Optional UI  
```

---

## Future Improvements

- Multi-agent parallel execution
- Cloud deployment
- Web-based interface
- API integration
- Reinforcement learning loop


