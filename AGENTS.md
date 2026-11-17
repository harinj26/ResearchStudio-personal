# research-studio

Rules for every coding agent (Claude Code, Codex, Pi, DeepSeek harness). Read `README.md` and `PERSONALIZATION.md` first.

## What this is
A personal copy of ResearchStudio: a collection of agent skills covering the research lifecycle, from a research direction (`ResearchStudio-Idea/`) to a published reel (`ResearchStudio-Reel/`). Local changes live on the `personal-project-workflows` branch.

## Layout
- `ResearchStudio-Idea/`, `ResearchStudio-Reel/` — the skill packs
- `experiments/` — local experiments
- `bin/`, `install.sh` — installers
- `.venv/` — local Python environment

## Project-specific rules
- Keep personal changes on the personal branch; do not open pull requests against the upstream project without asking.
- `install.sh` changes agent configuration outside this folder; ask before running it.

## Rules
- This folder is the only home of this app. Do not create copies elsewhere.
- Never commit `.env`, credentials, cookies or saved login sessions. New variables go in `.env.example` with empty values.
- Do not commit dependencies (`.venv`, `node_modules`), build output or large media.
- Ask before deleting files, changing Git history, or pushing.
