# Project agent memory

This file is the project's committed home for project-intrinsic agent knowledge: build, test, release, architecture, and sharp-edge notes that should travel with the code.

- Add durable project-specific notes here as they are discovered through real work.

- GitHub Actions on the gh0stwin fork sat in a never-ran state after forking: opening or synchronizing a PR registered no workflow runs and no check runs, even with `.github/workflows/verify.yml` active and Actions reporting enabled. Closing and reopening the PR reliably fires the `pull_request` workflow (same head SHA, no new commits). If a PR shows zero checks, close+reopen before assuming CI is broken.

## Maintaining this file

Keep this file for knowledge useful to almost every future agent session in this project.
Do not repeat what the codebase already shows; point to the authoritative file or command instead.
Prefer rewriting or pruning existing entries over appending new ones.
When updating this file, preserve this bar for all agents and keep entries concise.
