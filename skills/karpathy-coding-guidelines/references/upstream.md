# Upstream provenance

This ChatGPT-compatible skill is adapted from:

- Repository: `multica-ai/andrej-karpathy-skills`
- Upstream skill: `skills/karpathy-guidelines/SKILL.md`
- Upstream default branch at adaptation time: `main`
- Upstream README declares the project license as MIT.
- The upstream guidelines credit Andrej Karpathy's observations about common LLM coding pitfalls as their inspiration.

The adaptation preserves the upstream's four core principles:
1. Think Before Coding
2. Simplicity First
3. Surgical Changes
4. Goal-Driven Execution

ChatGPT-specific changes:
- Removed the nonstandard `license` key from SKILL.md frontmatter because ChatGPT skill frontmatter accepts only `name` and `description`.
- Added `agents/openai.yaml` metadata.
- Expanded trigger coverage so the skill can activate across coding, review, debugging, refactoring, repository, and implementation-planning tasks.
- Adjusted ambiguity handling so work does not block on minor uncertainty: ask only when ambiguity is consequential; otherwise state the assumption and proceed.
- Added explicit repository and verification workflow guidance.

Original source should remain credited when redistributing this adaptation.
