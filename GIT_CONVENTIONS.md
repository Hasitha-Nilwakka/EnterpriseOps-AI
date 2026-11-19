##This document governs the standard git hub branch naming conventions, commit message convention and governance
## Repository Name: 
- enterpriseops-ai

# Branch Naming Convention:
-feat/<short-description> — new features (e.g., feat/rag-pipeline)
-fix/<short-description> — bug fixes (e.g., fix/token-timeout)
-docs/<short-description> — documentation updates (e.g., docs/git-workflow)
-security/<short-description> — security patches or dependency updates (e.g., security/sanitize-prompts)

# Commit Message Convention (Conventional Commits):
- Format: <type>: <imperative summary>
- Examples: docs: establish git workflow and branch rules, feat: add initial api healthcheck

# Branch Governance Rules:
- Direct feature commits to main are prohibited after initial bootstrap.
- Force-pushing (git push --force) to main is strictly prohibited.