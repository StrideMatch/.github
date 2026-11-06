# StrideMatch — organization GitHub config

This special `.github` repository provides default files to **every repository in the organization**
that doesn't have its own.

## Issue templates (`.github/ISSUE_TEMPLATE/`)

| Template | Type | Label | Use for |
|---|---|---|---|
| 🐛 Bug | Bug | `bug` | Something doesn't work |
| ✨ Feature | Feature | `enhancement` | New feature / product improvement |
| 🔧 Tech task | Task | — | Cleanup, refactoring, infrastructure, tech debt |

Every issue created from a template is **automatically added to the "Backlog" project**
(`projects: ["StrideMatch/2"]`). If the project number changes, update the 3 files.

Blank issues are disabled (`config.yml`) so that everything goes through a template.

⚠️ This repository is **public** (GitHub requires it for default files). Only put templates and
generic configuration here, never internal information.

A repository with its own `.github/ISSUE_TEMPLATE/` folder no longer uses these templates.
