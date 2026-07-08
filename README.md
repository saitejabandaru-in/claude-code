# Claude Code

**Anthropic's agentic CLI that codes in your terminal — reads your codebase, writes files, runs commands, ships working code.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What Is Claude Code?

Claude Code is a terminal-based AI agent that can:
- Read your entire codebase
- Write and edit files
- Run shell commands
- Execute tests and fix failures
- Commit and push to git

It's like having a senior engineer who works in your terminal.

## Installation

`npm install -g @anthropic-ai/claude-code`

Set `ANTHROPIC_API_KEY` environment variable, then run `claude` in your project.

## CLAUDE.md — Project Instructions

Create `CLAUDE.md` in your project root to set:
- Project architecture and tech stack
- Code standards and conventions
- Key file locations
- Common commands (test, build, run)

Claude Code reads this file automatically on every session.

## Real Workflows

### Feature Development
Describe the feature in plain English. Claude Code will:
1. Read relevant existing code
2. Implement the feature
3. Write tests
4. Fix any test failures

### Bug Investigation
Describe the bug. Claude Code will:
1. Find the root cause
2. Fix it
3. Add a regression test

### Codebase Migration
Describe the migration (e.g., pandas to polars).
Claude Code will migrate files one by one, running tests after each.

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
