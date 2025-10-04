# Copilot Instructions for AI Agents

## Project Overview
This repository is a self-tracking and self-improvement framework for daily self-love, using a points-based system. The project is content-driven, with daily logs and a guide, and is designed for both personal use and open-source contribution.

## Key Files & Structure
- `README.md`: High-level overview, usage, and philosophy of the system.
- `self-love-points-guide.md`: In-depth guide, scoring system, and domain definitions.
- `2025-09-day-XX.md` / `2025-09-day-XX.json`: Daily logs in Markdown and JSON, containing scorecards, reflections, and notes.
- `.github/copilot-instructions.md`: (this file) AI agent guidance.

## Data & Content Patterns
- Each day has both a `.md` and `.json` file. The `.md` is human-readable, the `.json` is structured for programmatic access.
- Scorecards use 5 domains: Creation & Work, Body & Energy, Finance & Discipline, Growth & Mind, Boundaries & Integrity.
- Scores: 0 (neglected), 1 (partial), 2 (fully honored). Total and cumulative monthly scores are tracked.
- Reflections and "Tomorrow's Must-Win" are required for each day.

## Contribution & Workflow
- No build or test system; this is a content-first repo.
- To add a new day: create both `.md` and `.json` files, following the established schema.
- When updating scores, ensure both formats are kept in sync.
- Use clear, concise language in logs and reflections.
- License: MIT. Contributions are welcome via PR.

## Project Conventions
- All logs and guides use Markdown for readability.
- JSON files mirror the Markdown content for automation or analysis.
- No external dependencies or code execution required.
- Keep all new content consistent with the domain definitions and scoring system in `self-love-points-guide.md`.

## Example
- See `2025-09-day-29.md` and `2025-09-day-29.json` for a canonical daily entry.
- Refer to `self-love-points-guide.md` for scoring and domain explanations.

---

For any automation, always update both `.md` and `.json` files for each day. When in doubt, follow the patterns in the most recent daily files.
