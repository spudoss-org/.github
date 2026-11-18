# Contributing

Most changes in this org are written by AI agents and reviewed by a human. The same flow applies to people.

1. **Start from an issue.** Use an issue form. The issue is the spec: acceptance criteria and out-of-scope must be filled in.
2. **Plan before code.** For anything non-trivial, the agent posts a plan on the issue (label `agent:plan`) and a human approves it.
3. **Open a PR that says `Closes #N`.** Keep it to one concern. Use [Conventional Commits](https://www.conventionalcommits.org/) for the title.
4. **Pass `make check` locally**, then CI. Required checks come from `shared-workflows`.
5. **A human approves and merges.** Agents never merge their own PRs.

Full standards: `spudoss-org/platform-standards`.
