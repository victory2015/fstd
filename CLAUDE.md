# CLAUDE.md — AI Assistant Guide for fstd

## Project Overview

**fstd** is an autonomous blog project intended to link the website [http://fstd.com.tw/](http://fstd.com.tw/) (including subsections `/victory` and `/carol`) with GitHub for automated blog posts and announcements.

The repository is currently in an early/placeholder state — there is no source code yet, only this documentation and the README.

---

## Repository State

| Item | Status |
|------|--------|
| Source code | None |
| Build system | None |
| Tests | None |
| CI/CD | None |
| Dependencies | None |
| Language/framework | Not yet determined |

The repository was created in February 2018 and contains 4 commits, all documentation-only.

---

## Git Workflow

### Active Branch

Development happens on feature branches. The current designated branch is:

```
claude/add-claude-documentation-7k0nz
```

- **Never push directly to `master`** without explicit permission.
- Always create or use a feature branch for new work.
- Push with: `git push -u origin <branch-name>`

### Commit Style

Commits in this repository use short, descriptive imperative messages:

```
backup blog
autonomous blog project
add links to fstd.com.tw with github blog integration
add subsection links /victory and /carol
```

Follow this pattern: brief lowercase imperative describing the change.

---

## Project Intent

Based on the README, the goal is to build an **autonomous blog system** that:

1. Connects the fstd.com.tw website with a GitHub-hosted blog
2. Automates blog posts and announcements
3. Serves content under at least two user sections: `/victory` and `/carol`

When implementing features, keep this purpose in mind. Likely future components include:
- A static site generator or blog engine
- GitHub Actions or webhook integration for automation
- A publishing pipeline from GitHub to fstd.com.tw

---

## Conventions to Follow

Since no code exists yet, these are guiding principles for any future implementation:

- **Keep it simple**: this appears to be a personal project — avoid over-engineering.
- **Automation-first**: the core value is autonomy; manual steps should be minimized.
- **Document as you go**: add README sections and inline comments when adding new code.
- **One concern per file**: keep blog logic, publishing logic, and config separate.

---

## Working with This Repo as an AI Assistant

- The repository has no build step, test suite, or linter to run.
- When adding code, propose a language/framework in a comment or discussion first unless the user specifies one.
- Do not add placeholder or stub files unless explicitly requested.
- If implementing the blog system, favor well-established tools (e.g., Jekyll, Hugo, or a simple Node.js/Python script) over custom solutions.
- Check for a `.gitignore` before committing generated files or secrets.
