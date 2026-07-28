# Architecture judgment guide

## Core objects

Start with objects that have a lifecycle, identity, or several capabilities operating around them. Do not mistake a screen or a single feature for the product's core object.

## Organizing axis

Use one axis per diagram. Common choices are:

- Data → application → experience
- Lifecycle stages
- Value chain
- User or role domains
- Front office → operations → platform

Mixing axes in one layer makes a diagram hard to read. If two perspectives both matter, create two diagrams.

## Dependencies and boundaries

Arrows should show enablement, sequence, or data dependency—not decoration. Separate the product's owned capabilities from integrations. Clearly distinguish current scope, later scope, and cross-cutting foundations such as identity, permissions, data quality, or observability.

## Architecture brief template

```text
Diagram type: [architecture / capability map / roadmap / system relationship]
Audience: [who will use it]
Core objects: [...]
Organizing axis: [...]
Dependencies: [...]
Boundaries: [owned / external / current / later / cross-cutting]
Narrative: [...]
Exclude or split: [...]
```
