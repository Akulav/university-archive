# CLAUDE.md

Notes for working on **University Archive**, 28 projects, labs and coursework from university and an internship, made
by Akulav. Each top-level folder is a separate, finished project (C#, C, Python, Elixir, JavaScript, Unity, …) with
its own README. The root `README.md` is the index and the highlights page.

## Rules

- **This is an archive, not an active codebase.** Don't refactor, modernize, upgrade dependencies or "fix" old
  projects unless asked. Changes are usually to READMEs, the root index, or adding a new project folder.
- Built binaries and Unity runtime data (`*_Data/`, `Runnable_Data/`, `.dll`) are committed on purpose so projects
  run without building. Don't delete them.
- Some projects are deliberately simple or insecure by modern standards (e.g. the old `OfflinePasswordManager`;
  its maintained successor is the `offline-password-manager` repo / SeePass). Describe them honestly, don't patch them.
- When adding a project: new top-level folder, its own README, and an entry in the root `README.md`.

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships. It is local only (`graphify-out/` is git-ignored).

Rules:
- When graphify-out/graph.json exists, run `graphify query "<question>"` before your first grep, search or source-file read for a question about a project. Read raw files only for lines the graph or an earlier read already located.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).
