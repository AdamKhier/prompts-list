# Prompt Templates — Project Summary

> Reconstructed 22 Nov 2026 from the repository itself, not from chat history.

## What it is
Six reusable prompt templates for shipping software with AI assistance, each self-contained Markdown with bracketed inputs at the top:

| File | Use it to |
| --- | --- |
| `01-build-cli-tool.md` | Scaffold a CLI tool from spec to tested binary |
| `02-build-stats-comparison.md` | Compare stats or benchmarks across runs |
| `03-deep-research.md` | Run a structured deep-research pass |
| `04-task-maker-and-manager.md` | Break work into tracked tasks and drive them |
| `05-csv-report-generator.md` | Turn raw data into a clean CSV report |
| `06-project-outline-manager.md` | Outline a project and keep scope controlled |

## How to use
Pick the template matching the job, copy it into an agent session, fill in the bracketed inputs, run.

## Status
**Action required — implement.** The templates are written and reviewed, but nothing has been built or applied from them yet. The natural next step is turning at least one (task manager or project outline) into working tooling.

## Notes
- `portfolio/` is a separate git repository (`AdamKhier/portfolio`) nested inside this one.
- No build step, no dependencies.

## Git
`AdamKhier/prompts-list` — public.
