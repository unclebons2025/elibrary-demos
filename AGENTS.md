# Agent instructions

## Scope

- Work only within this repository: `/home/uncbons/elibrary-demos`.
- Keep all inspection, edits, generated files, and commands focused on this directory and its contents.
- Do not read, modify, or create files outside this repository. Do not follow symlinks that lead outside it.
- Do not access parent directories, sibling projects, personal configuration, or unrelated repositories.

## Project notes

- This repository contains the `aksu/` and `mue/` static demo sites.
- Preserve the separate site directories and their existing assets and deployment configuration.
- There are no source manifests or build instructions in the repository at present. Inspect the relevant site files before making changes, and avoid inventing a build process.

## Changes

- Make only changes needed for the user's request.
- Keep generated artifacts and temporary files inside the repository (or `/tmp` when necessary), and clean up temporary files you create.
- Do not run destructive commands or alter Git history unless the user explicitly asks.
- Before finishing, summarize changed files and any checks performed.
