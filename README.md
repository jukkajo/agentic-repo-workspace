# Generalizable Agentic Workspace

This workspace is aiming to be a reusable, multi-repository capable AI agentic development workspace and governance pipeline for agentic platforms such as **Google Antigravity (AGY)**, **Claude Code**, and **GitHub Copilot**. Core: baseline templates for agentic personas and skills, that can be dynamically adjusted to perform with different tech stacks across varying task scopes.

## Planned Skills & Personas

| Skill | Usecase |
| :--- | :--- |
| `workspace-init` | Probe repo manifests, interview for missing context, generate `clean-code-<lang>` skills, adapt governance/tracker rules, and wire cross-host `/` slash commands. |
| `context-builder` | Build and sync per-repo `.context/<repo>.md` profiles, `AI_SEMANTIC_MAP.md`, and task-scoped context dossiers. |
| `extract-repo-context` | Inspect a single repository's entrypoints, APIs, datastores, and tests to generate `.context/<repo>.md`. |
| `architect` | First-principles architectural sparring, blast-radius analysis, and phased implementation plans. |
| `product-owner` | Challenge business logic, user flows, and domain edge cases to produce a Product Requirements Document (PRD). |
| `privacy-officer` | Audit features and architectures for GDPR (DPIA), EU AI Act (FRIA), data minimization, and PII protection. |
| `analyst` | Convert architectural plans or stakeholder interviews into structured User Stories with Acceptance Criteria. |
| `tech-lead` | Design cross-service API/schema contracts and decompose Stories into single-repo Sub-tasks. |
| `builder` | End-to-end task implementation controller (`SK-01` -> `SK-02` -> TDD code -> 5-Gate Verification Ladder). |
| `understand-the-task` | Pre-coding ground-truth gate (`SK-01`) that reconciles ticket claims against live code and git history. |
| `produce-spec-before-coding` | Pre-coding specification gate (`SK-02`) locking inputs, outputs, 4D edge cases, and error states before coding. |
| `clean-code-template` | Adaptable template for language/tech specific craftsmanship rules and anti-pattern guards. |
| `code-diff` | Extract the exact git diff between the active feature branch and its parent base branch for audits. |
| `global-code-reviewer` | Run parallel read-only subagent audits for Functional ACs, regressions, Clean Code, and ISO 27001 security. |
| `iso27001` | Perform a dedicated Information Security Management System (ISMS) audit against ISO/IEC 27001:2022 controls. |
| `submit-for-review` | Verify all quality and security audit gates have passed and transition the task to peer-review/approval phase. |
| `pr-creator` | Draft a standardized Pull Request summary mapped to task ACs, edge cases, and verification output. |
| `bitbucket-pr` | Automate Pull Request creation on Bitbucket Cloud via REST API v2 (`scripts/create-pr.sh`). |
| `github-pr` | Automate Pull Request creation on GitHub via GitHub CLI (`scripts/create-pr.sh`). |
| `skill-architect` | Author, refactor, or audit `.agents/skills/<name>/SKILL.md` files against the AgentSkills specification. |
