---
name: arch-diagram
description: Turn a product plan, feature list, or PRD into a clear product architecture diagram. Use when creating a product architecture, capability map, product roadmap, or system relationship overview.
license: MIT
---

# Product architecture diagram

Build the reasoning before drawing. A useful product architecture diagram explains how a product is organized, what its boundaries are, and why the structure makes sense; it is not a feature list laid out as boxes.

## Workflow

Before choosing a diagram format, produce the following architecture brief:

1. **Core objects** — What business objects have an identity or lifecycle, and what do features operate on?
2. **Organizing axis** — Choose one primary structure: lifecycle, value chain, roles, data-to-experience, or another axis that fits the audience.
3. **Dependencies** — State what enables what. Only draw arrows that express a real dependency or sequence.
4. **Boundaries** — Separate owned capabilities from external systems, current scope from later scope, and horizontal foundations from product capabilities.
5. **Narrative** — Write one sentence that explains the product's value path.

If any item cannot be explained, return to the source material instead of polishing the diagram.

## Choose a format

| Situation | Suggested output |
| --- | --- |
| Simple structure that belongs in documentation | Mermaid |
| Detailed presentation or review | SVG or an HTML page with inline SVG |
| Slide or document asset | SVG or PNG |

Use [`references/judgment.md`](references/judgment.md) for decision rules and [`references/mermaid.md`](references/mermaid.md) for a lightweight pattern.

## Diagram checklist

- Each layer uses one organizing axis and contains elements at the same level of abstraction.
- Dependencies are meaningful; removing an upstream element would affect the downstream element.
- Owned capabilities, external systems, and future scope are visually distinct.
- The diagram tells the same story as the architecture brief.
- Unconfirmed content is marked as pending instead of being drawn as committed scope.
