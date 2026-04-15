---
name: audit-max
description: Audits the whole project for potential issues.
disable-model-invocation: true
effort: max
---

Analyze the whole project for potential implementation issues. Be really thorough. Look out for:

- framework/libraries missues/misconfiguration
- technical debt
- security issues
- accessibility issues
- UX issues
- SEO issues
- performance issues
- potential optimization opportunities

Make a table of issues by each category, include references to files where possible, suggest solutions.

Create an md file `AUDIT.md` with the audit output in root of project.
