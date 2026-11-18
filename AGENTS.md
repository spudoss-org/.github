# AGENTS.md — .github (org defaults)

Org-wide rules live in `spudoss-org/platform-standards/AGENTS.md`. Follow those first; this file only adds repo-specific notes.

## What this repo is

Default community health files, issue forms, PR template and workflow templates applied across the org. Changes here affect **every repo**, so keep diffs small and explain the blast radius in the PR.

## Rules

- Issue forms are prompts for agents. Every field must be answerable and testable. Do not remove `acceptance-criteria` or `out-of-scope`.
- Workflow templates must only `uses:` reusable workflows from `spudoss-org/shared-workflows` pinned to a major tag (`@v1`). No inline build logic.
- Each `workflow-templates/<name>.yml` needs a matching `<name>.properties.json`.
- Nothing in this repo may contain secrets or internal hostnames. It is public.

## Check before opening a PR

```bash
yamllint -s .
```
