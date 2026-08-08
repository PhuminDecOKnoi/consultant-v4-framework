# Repository Governance

## Operating standard

This repository follows `/SKILL GitHub v2.0 — Repository Governance Standard` principles.

## Branch governance

- `main` is the stable release branch.
- Normal development occurs on `version-X.Y[-scope]` branches.
- Direct `main` edits are reserved for exceptional repository administration only.

## Change lifecycle

```text
Issue / improvement need
→ version branch
→ scoped changes
→ QA checklist
→ draft PR
→ review / corrections
→ explicit approval
→ squash merge
→ post-merge verification
→ release tag / notes when applicable
```

## Version governance

- **Major** — architecture or primary scope changes.
- **Minor** — new modules, tools, adapters or substantive capabilities.
- **Patch** — corrections, wording, examples or non-breaking logic fixes.

Every material change should record version, date, summary, compatibility impact and validation result.

## Quality gates

Repository QA considers at minimum:

- README clarity and accuracy;
- LICENSE and third-party rights;
- SECURITY;
- CONTRIBUTING;
- CHANGELOG;
- BRAND consistency;
- CITATION metadata;
- CODEOWNERS and templates;
- Markdown structure and links;
- naming and folder conventions;
- version consistency;
- copyright and standards-use controls;
- skill frontmatter and installability;
- AI/search metadata;
- professional source classification.
