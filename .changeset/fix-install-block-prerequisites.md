---
"mattpocock-skills": patch
---

docs: fix the one-skill install command, and name what each delegating skill needs

- `.agents/install-block.md`: `--skill=<name>` was discarded by the skills CLI and installed all 37 skills; switched to `--skill <name>`.
- `.agents/install-block.md`: added a note explaining the equals form pitfall and that standalone skills with delegating siblings name their prerequisites in `## Prerequisites`.
- `skills/in-progress/README.md`: same `--skill <name>` fix.
- `docs/engineering/improve-codebase-architecture.md`: added `## Prerequisites` noting `codebase-design` and `domain-modeling` are required.
- `docs/engineering/wayfinder.md`: added a note that `grilling` and `domain-modeling` are required.
- `docs/productivity/grill-me.md`: added `## Prerequisites` noting `grilling` is required.

See [#1012](https://github.com/mattpocock/skills/issues/1012) for details.
