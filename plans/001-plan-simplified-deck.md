# 001 - Simplified deck for beginners

Goal: a second, simpler version of the Claude Code in VS Code deck. The old one is kept as `_advanced`.

## Decisions
- VS Code extension only. No CLI, terminal, git or Amplify section.
- Three parts: Start, Configure, Orchestrate (31 slides), same dark marine look as the advanced deck.
- Vibe: the human describes, Claude does everything (skills, CLAUDE.md, rules, agents, hooks, MCP).
- Skills get the most space: intro, global vs local, then 2 of my skills per slide (initialize-project + create-ppt-presentation, create-notebook + create-video, create-tests + run-tests).
- Agents, rules, hooks, settings: one short "optional" slide.
- Ralph loop: concept (slide 24), hands-on setup via CLAUDE.md + skill + plan (slide 25), files (26), gates (27), run modes (28).
- Built with a pptxgenjs script (kept out of the repo); PDF exported from PowerPoint.

## Outputs
- `resources/claude_code_vscode_tricks_simplified.pptx` and `.pdf`
- Old files renamed to `..._advanced.pptx` and `.pdf`; README updated.
