# Prompt-a-Matic

A curated library of system prompts designed to guide LLM code assistants through software development workflows—from ideation to implementation.

## Overview

This repository provides structured prompts that transform LLM assistants into specialized agents for different phases of software development. Each prompt employs deliberate cognitive frameworks, Socratic questioning, or procedural rigor to enhance code assistant capabilities.

## Structure

### 🧠 Brain-Storming
Creative problem-solving and logical reasoning frameworks:

- **creative_problem_solver.md** – Multi-stage creative thinking using JOOTS, conceptual slippage, and analogy-driven exploration
- **logic_engine.md** – Ruthless logical deduction agent; strips personality for pure analytical reasoning
- **lot.md** – Language of Thought strategy; structured premise enumeration and derivation

### 🚀 Project Initialization
Prompts for launching new projects with clarity and structure:

- **new_project.md** – Bootstrap workflow: dependency analysis → acceptance criteria → actionable plan
- **project_scoping.md** – Socratic interview technique to extract comprehensive project requirements
- **model_scoping.md** – Socratic questioning for defining software architecture
- **logical_model.md** – Translates informal requirements into formal logical models (types, relations, invariants, temporal properties)
- **fishbone.md** – SDLC risk analysis across six categories (People, Process, Tools, Materials, Environment, Measurement)
- **ai_adoption.mmd** – Visual diagram of tiered spec-to-code workflow (Feature → Sub-specs → Tasks → Code)

### 📋 Project Plans
Continuation and execution strategies:

- **continue_project.md** – Instructions for resuming existing projects, with or without a pre-existing plan

### 📂 Placeholder Directories
Reserved for future prompt categories:
- `development-plans/`
- `security-plans/`
- `testing-plans/`
- `validation/`

## Usage

1. **Select a prompt** based on your current development phase
2. **Inject the prompt** into your LLM code assistant's system context
3. **Follow the framework** – each prompt contains its own workflow instructions
4. **Combine prompts** as needed (e.g., use `creative_problem_solver.md` for ideation, then `new_project.md` for bootstrapping)

## Design Philosophy

- **Minimal friction** – Prompts are self-contained; no external dependencies
- **Cognitive frameworks** – Leverage structured thinking (JOOTS, Socratic method, formal logic) rather than generic instructions
- **Procedural clarity** – Step-by-step workflows with explicit rules and output formats
- **Composability** – Prompts can be chained or combined for complex workflows

## License

GPL-2.0 – See [LICENSE](LICENSE) for details

---

*Built for developers who believe great software starts with great thinking.*

