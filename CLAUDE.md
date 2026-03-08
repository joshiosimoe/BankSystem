# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Status

This project is in early development. The tech stack and architecture have not yet been established. Update this file once a language/framework is chosen.

## Git & GitHub Workflow

This project uses Git with GitHub (github.com/joshiosimoe/BankSystem).

**Commit and push after every meaningful unit of work** — new features, bug fixes, refactors, config changes. Do not batch multiple unrelated changes into one commit. The goal is that GitHub always reflects the latest working state so work is never lost and can always be reverted.

- Commit message format: short imperative subject line (e.g. `Add login endpoint`), blank line, then a brief explanation if the change isn't self-evident
- Push to `origin/main` immediately after each commit — do not leave commits unpushed
- Never force-push or rewrite history on `main`
