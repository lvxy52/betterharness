# BetterHarness — A Generic AI Full-Stack Project Skeleton

[中文](./README.md) | **English**

> An **empty skeleton** for AI-assisted full-stack development: directory structure and READMEs only — no sample code, no prescribed tech stack.
> Typical usage: copy this skeleton → bring in source code from a mature open-source framework (pig / yudao / etc.) or start from scratch → let AI collaborate per [AGENTS.md](./AGENTS.md).

---

## 1. What This Skeleton Solves

| Problem | Approach |
|---------|----------|
| Open-source frameworks ship code only — docs / tests / deployment have no home | Tech-stack-agnostic wildcard peripheral structure |
| Backend / frontend layouts differ across frameworks and cannot be standardized | backend/ and frontend/ are placeholders only; internal structure follows whatever source is brought in |
| AI development needs a stable collaboration contract | AGENTS.md as the single handbook, auto-read by mainstream AI tools |

---

## 2. Top-Level Directory Index

| Directory / File | Purpose | Details |
|------------------|---------|---------|
| [AGENTS.md](./AGENTS.md) | AI collaboration handbook: reading boundaries, dev workflow, structure evolution rules | this file |
| [backend/](./backend/README.md) | Backend source (adopted framework or self-developed) | see its README |
| [frontend/](./frontend/README.md) | Frontend source (adopted framework or self-developed) | see its README |
| [docs/](./docs/README.md) | Project docs: requirements, contracts, plans, rules | see its README |
| [sql/](./sql/README.md) | Development-stage incremental SQL scripts | see its README |
| [test/](./test/README.md) | E2E / acceptance automation | see its README |
| [deploy/](./deploy/README.md) | Deployment config and release SQL | see its README |
| `.gitignore` | Cross-stack git ignore rules (Node / Java / Python / IDE / env files) | — |

> Each sub-directory README is the detailed index for that category. **After adding or removing any directory, sync this table and the corresponding README.**

---

## 3. Getting Started (Adopting an Open-Source Framework)

1. **Copy** this skeleton as the new project root; rename the project and fill in the positioning section.
2. **Bring in source code**: backend source into backend/, frontend into frontend/; keep the framework's own multi-module layout as-is — do not force-reorganize.
3. **Fill in AGENTS.md**: tech stack, build commands, module boundaries, permission model placeholders.
4. **Docs first**: docs/prd (requirements) → docs/api (contracts) → docs/plan (plans & acceptance).
5. **Init the repo**: git init + initial commit.

---

## 4. Evolution Principles

1. **Structure grows on demand**: directories can be added or removed anytime during development; completeness of the skeleton is not a goal. Sync README indexes after changes.
2. **Directory as documentation**: every directory kept has a README describing its responsibility and maintenance rules.
3. **Single source of truth**: each fact is maintained in exactly one place; elsewhere only links.
4. **Docs first**: changes to fields / menus / permissions / flows update docs before code (or in the same commit).

---

## 5. License

[MIT](./LICENSE)

---

## 6. Changelog

| Date | Change |
|------|--------|
| 2026-08-31 | Initial release: generic full-stack skeleton (MIT licensed) |
