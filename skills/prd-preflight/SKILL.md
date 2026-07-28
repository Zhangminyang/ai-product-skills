---
name: prd-preflight
description: Review whether a PRD or product specification is ready for engineering review, estimation, design delivery, and test planning. Use before development starts to identify actionable gaps and delivery risks.
license: MIT
---

# PRD preflight

Review a PRD for delivery readiness. Find gaps that matter to engineering, design, and testing; do not silently invent product decisions or turn the review into bureaucracy.

## Review modes

- **Quick**: small or urgent work; check the core flow, scope, permissions, acceptance criteria, and immediate risks.
- **Standard**: normal engineering review.
- **Deep**: workflows with complex permissions, state changes, reporting, import/export, integrations, or release risk.

## Workflow

1. Read the PRD together with relevant flows, designs, API notes, data definitions, and prior decisions.
2. Choose a review mode based on complexity and risk.
3. Identify what is already clear and cite its source.
4. Convert missing decisions or ambiguity into actionable questions. Mark affected stage, risk, and whether development or test planning is blocked.
5. Return `ready`, `ready_with_risks`, or `blocked`, with next steps.

## Review areas

Check only what is relevant: goal and scope, users and permissions, primary and reverse flows, states, pages and fields, validation, data definitions, integrations, failure cases, non-functional needs, and acceptance criteria.

Read [`templates/prd-checklist.md`](templates/prd-checklist.md) and use [`templates/prd-preflight-report.md`](templates/prd-preflight-report.md) for the final report.

## Rules

- Do not infer an answer simply because it is absent from the PRD; check the provided supporting material first.
- Keep questions assignable and specific.
- Small requests do not need a full state machine or exhaustive non-functional requirements.
- A review flags decisions; product owners make the decisions.
