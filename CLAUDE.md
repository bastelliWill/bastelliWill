# CLAUDE.md

## Repository purpose

This is the **GitHub profile README repository** for user `bastelliWill`
(repo name matches the username, so GitHub renders `README.md` on the
profile page at github.com/bastelliWill).

There is no application code, build system, dependencies, or test suite —
the entire repository is a single Markdown file.

## Structure

- `README.md` — the profile page content (in Portuguese). Contains:
  - A header/intro section with tech badges (Oracle, PL/SQL, SQL, WMS) using
    `img.shields.io` badge URLs.
  - An "About me" section describing the author's background as an Oracle/
    PL/SQL developer focused on WMS (Warehouse Management System) backends.
  - An "Areas of expertise" bullet list.
  - A GitHub stats card via `github-readme-stats.vercel.app`.

## Working conventions

- Keep content in Portuguese (pt-BR) to match the existing tone, unless the
  user explicitly asks for another language.
- Preserve the centered HTML layout (`<p align="center">`, `<h1 align="center">`)
  and the shields.io / github-readme-stats badge style when adding new
  sections.
- Changes are purely content/formatting edits to `README.md` — there is
  nothing to build, lint, or test.
- When adding badges, follow the existing pattern:
  `https://img.shields.io/badge/<label>-<color>?style=for-the-badge&logo=<logo>&logoColor=white`.

## Git workflow

- Develop on the feature branch specified for the task, commit with clear
  messages, and push when done.
- Do not open a pull request unless explicitly requested.
