# Copilot Instructions

## Project Overview

This repository contains a personal resume/CV written in Markdown. The `README.md` is the sole content file — it uses a Markdown-to-PDF pipeline format with YAML front matter and LaTeX directives (e.g., `\newpage`).

## Key Conventions

- The resume uses Iconify `<span>` tags for inline icons (e.g., GitHub, LinkedIn, itch.io).
- Definition list syntax (` : `) is used for dates/employers alongside bold headers — preserve this formatting pattern when editing.
- `\newpage` is a LaTeX page break used to split the resume across pages — keep it in place.
- YAML front matter (`---`) at the top is required even if empty.

## Editing Guidelines

- When updating experience or projects, match the existing formatting exactly: bold title on one line, bold company/date on the next using ` : `, then bullet points.
- Keep bullet points concise and metrics-driven where possible, consistent with the existing style.
