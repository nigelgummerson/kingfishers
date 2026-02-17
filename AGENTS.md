# AGENTS.md — kingfishers

## Project Overview
[Brief description of what this project is and its purpose.]

## Structure
```
personal/ornithology/kingfishers/
├── code/           # Source code
├── data/           # [Dropbox symlink] Large files
├── docs/           # [Dropbox symlink] PDFs, references
├── AGENTS.md       # This file (static project instructions for any AI)
├── CLAUDE.md       # Session history and collaboration tracking
└── .git/           # Version control
```

## Build & Run
```bash
# [Commands to build, compile, or run this project]
```

## Dependencies
- [List key dependencies, libraries, tools needed]

## Code Style
- LaTeX documents: use `main.tex` as entry point
- File naming: `kebab-case` for folders, `CAPS.md` for AI docs
- Commit messages: imperative mood, brief first line

## Testing
- [How to verify the project works correctly]

## Security
- Files in `research/medico-legal/` contain patient-identifiable data — NEVER commit to git
- Do not commit `.env`, credentials, or sensitive configuration files

## AI Collaboration
This project uses a dual-documentation system:
- **AGENTS.md** (this file) — Static project instructions for any AI agent (open standard)
- **CLAUDE.md** — Session history, work logs, next steps, and cross-AI collaboration tracking

Read CLAUDE.md for current status, last session context, and next steps.
