# AI Learning Path: Agents for Beginners

A curated collection of free resources about **AI agents** and **agent harnesses**: the underlying structure—loops, tools, context, and permissions—that turns a language model into an agent that can get work done.

Use this learning path to understand the key concepts, explore common agent workflows, and see how to configure an agentic coding environment.

## Why build a harness?

The idea behind a setup (or harness) is to teach Claude how to do what you do:

- Automate your tasks and make your life easier.
- Standardize behavior, rules, and quality.
- Stop writing long, repetitive prompts every time.
- Reuse stored prompts and instructions (skills, rules, etc.).

Used one session at a time, an agent is already very powerful, but every session dies on its own. When you open a new one to ask a new question, it essentially starts from scratch and knows little about you.

With a customized setup and a few learning processes, it starts to learn what *you* like, what *you* want, and how to serve your needs better. You then create a learning loop in which it refines and improves its own setup after each session. If you make an important decision in a certain way, it writes that down, and the next session is born already knowing it.

## Contents

### 1. Videos

| # | Resource | What you'll learn |
|---|----------|-----------------|
| 1 | [Agent Harness explained](https://www.youtube.com/watch?v=Vzt4tB4ga1I) | An introduction to agent harnesses and why they matter. **Start here.** |
| 2 | [How to Build your own Agent Harness](https://www.youtube.com/watch?v=c85qiEJCGdM) | A hands-on guide to building your own harness. |
| 3 | [Video](https://www.youtube.com/watch?v=7zZy1QTvokM) | Another walkthrough on setting up your agent environment. |

### 2. Cheat sheet: 7 common agent workflow patterns

[![AI Agent Harness Workflows: 7 Common Patterns](resources/harness-patterns.png)](resources/harness-patterns.png)

1. **Ralph Loop**: an autonomous, persistent, goal-driven cycle with no human intervention.
2. **ReAct** (Reason + Act): reason, use a tool, and repeat based on feedback.
3. **Plan-and-Solve**: plan a sequence of steps, execute them, and reassess along the way—helpful for staying on track in long tasks.
4. **Orchestrator-Worker**: an orchestrator delegates work to specialized agents, each with isolated context.
5. **Evaluator-Optimizer**: one agent generates a result, another evaluates it, and the cycle repeats to refine and correct the output.
6. **Map-Reduce**: split large datasets across parallel workers, then combine their results.
7. **Human-in-the-Loop (HITL)**: include human approval points for governance and safety.

### 3. PDF: Claude Code in VS Code

[Claude Code in VS Code: the tricks I use every day](resources/claude_code_vscode_tricks.pdf) (35 slides)

A practical tour organized into four sections:

1. **Start**: Claude tools, extension vs. CLI, and opening a project.
2. **Configure**: the `.claude/` folder, `CLAUDE.md`, skills (including `initialize-project`), the LLM wiki, agents, and hooks.
3. **Orchestrate**: the Ralph Loop—inputs in `data/`, the LLM wiki, plans, `progress.md`, verification, and self-correction.
4. **Amplify**: context, flags, MCP (Drive, Gmail), code review, and remote workflows.

The examples focus on coding, but the techniques also apply to reports, research, spreadsheets, Word documents, and email.
