# Contributing

Thank you for helping improve Consultant v4.x.

## Repository workflow

This repository follows `/SKILL std GitHub` governance.

### 1. Do not edit `main` directly

Normal changes should use a version branch:

```text
version-X.Y-scope
```

Examples:

```text
version-4.1-quality-gates
version-4.2-commercial-tools
version-4.0.1-doc-fix
```

### 2. Use Conventional Commits

Examples:

```text
feat: add consultant capability assessment
fix: correct source classification example
docs: expand professional gates guidance
refactor: reorganize skill references
chore: update repository metadata
```

### 3. Preserve professional boundaries

Contributions must:

- distinguish `[STD]`, `[LAW]`, `[CLIENT]`, `[CONS]`, `[DATA]`, and `[EVID]`;
- avoid presenting consultant-created methods as ISO or statutory requirements;
- avoid reproducing copyrighted standards text without permission;
- preserve confidentiality and privacy;
- separate consultant recommendation from client decision;
- separate deliverable acceptance from benefit realization;
- state assumptions and limitations where material.

### 4. Version impact

Every substantive PR should state:

- proposed version impact: major / minor / patch;
- affected modules;
- compatibility impact;
- source / copyright impact;
- validation performed.

### 5. QA before PR

Use [`governance/REPOSITORY_QUALITY_STANDARD.md`](governance/REPOSITORY_QUALITY_STANDARD.md) and [`governance/RELEASE_CHECKLIST.md`](governance/RELEASE_CHECKLIST.md).

### 6. Pull request and merge

- Open one focused PR per coherent change set.
- Prefer a **draft PR** while work is incomplete.
- Resolve review findings before approval.
- Prefer **squash merge** after explicit approval.
- Update `CHANGELOG.md` for release-impacting changes.
- Create/update a release tag after approved merge when appropriate.
