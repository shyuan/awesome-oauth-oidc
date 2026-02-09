# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is an **awesome list** — a curated collection of OAuth 2.0 and OpenID Connect resources. The entire content lives in a single `README.md` file. There is no application code, build system, or tests.

## Structure

- `README.md` — The sole content file. A categorized link collection covering:
  - **Site** — Reference websites
  - **Specification** — RFCs (formal) and IETF drafts (active / expired)
  - **Article** — Tutorials and blog posts (includes Chinese-language resources)
  - **Book** — Published books
  - **Server Implementation** — Open-source OAuth/OIDC servers and IAM platforms
  - **Client Library** — Libraries organized by language (Go, JS/TS, Python, Java, Rust, .NET, PHP, Ruby)
  - **Tool** — Playground, JWT debuggers, and CLI tools
  - **Video** — Conference talks and educational videos
  - **Social Media** — Social media posts
  - **Community** — Working groups, foundations, and conferences
- `LICENSE` — MIT License
- `AGENTS.md` — Symlink to `CLAUDE.md`

## Editing Guidelines

- All contributions go into `README.md` following the existing Markdown link format: `* [Title](URL)`
- Server Implementation, Client Library, and Tool entries use the format: `* [Name](URL) - Short description`
- Maintain the existing section hierarchy and alphabetical/logical ordering within sections
- Formal RFCs are ordered by RFC number; draft specs are listed alphabetically
- Draft specifications should be placed under the correct sub-section (Active vs Expired & archived) and include the draft version number
- RFC links should use `https://datatracker.ietf.org/doc/html/` as the base URL
- All links should use HTTPS
- Client libraries are grouped by language with `### Language` sub-headers
- Keep link descriptions concise and consistent with existing entries
- The default branch is `main`
