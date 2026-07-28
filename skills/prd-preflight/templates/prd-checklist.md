# PRD review checklist

## Core

- Is the goal, user, scope, and out-of-scope boundary clear?
- Does the primary flow have a clear start, actor, action, and completion condition?
- Are reverse, failure, and exception paths relevant to this request covered?
- Are states, transitions, and allowed actions clear where the workflow has states?

## Interaction and data

- Are entry points, pages, fields, validation, empty, loading, error, and access-denied states clear where relevant?
- Are role permissions and data scope distinguished?
- Are data definitions, calculation rules, time ranges, and statistical scope clear where relevant?
- Are integration, import/export, notifications, logging, historical data, migration, and rollback needs identified where relevant?

## Delivery

- Can engineering estimate the work from the available decisions?
- Can testing derive primary, permission, and boundary cases?
- Are acceptance criteria observable and testable?
- Are dependencies and release risks known?

Avoid asking for irrelevant detail. The purpose is a dependable delivery decision, not a perfectly uniform document.
