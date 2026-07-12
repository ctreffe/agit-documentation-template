# CODEX.md

This file defines local operating rules for Codex or another AI coding assistant working in this repository.

## Repository role

This repository is a reusable template for AI-assisted technical documentation projects. Keep changes generic unless the maintainer explicitly asks to specialize a derived project.

## Operating rules

- Read repository guidance before substantive edits: `README.md`, `ChatGPT.md`, `DOCUMENTATION.md`, `PROJECT_SETUP.md`, and `DOCS_SETUP.md`.
- Preserve maintainer control over documentation intent, structure, technical correctness, and publication decisions.
- Do not inspect or ingest raw screenshots, logs, exports, configuration files, tickets, or operational data when they may contain sensitive information unless the maintainer confirms that this is appropriate.
- Prefer sanitized derivatives when raw material is not needed.
- Keep technical documentation task-oriented, precise, and reviewable.
- Treat links, screenshots, diagrams, and generated outputs as documentation artifacts that need provenance and QA.
- Record substantial documentation decisions as DDRs.
- Do not create commits, rewrite history, drop stashes, reset branches, push or perform other Git history actions unless the maintainer instruction for that specific action contains a recognized control word: `explicit` or `explicitly` in English, or the German word family `explizit`, including `explizite`, `expliziten`, `expliziter` and `explizites`.

## Commit policy

Regular commits should use Conventional Commits. Milestone commits should omit the prefix, be descriptive, and include the version number.
