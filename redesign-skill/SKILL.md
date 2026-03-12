---
name: redesign-skill
description: Audit and upgrade an existing website or app without rewriting it. Use when improving an existing frontend's typography, layout, color, states, content realism, or motion while preserving the current stack and functionality.
---

# Redesign Skill

## Work sequence

1. Inspect the codebase and identify the framework, styling system, component library, routing model, and installed dependencies.
2. Capture the current design language before changing it. Preserve product intent; remove only the generic or broken parts.
3. Run a full audit using `references/audit-checklist.md`.
4. Prioritize the highest-leverage fixes first: typography, color, spacing, states, and component patterns.
5. Apply small, reviewable changes that work with the existing stack.
6. Verify functionality after each batch.

## Rules

- Do not rewrite from scratch unless the user explicitly asks for it.
- Keep the existing frameworks, styling tools, and component systems unless the user approves a migration.
- Check dependency files before adding new libraries.
- Check Tailwind version before touching config or syntax.
- Prefer targeted visual upgrades over big structural churn.
- Preserve semantics, accessibility, and responsive behavior while restyling.
- Replace dead demo content with believable draft content when the task requires real-looking screens.

## Fix priority

1. Typography and spacing
2. Color palette and surface language
3. Hover, focus, pressed, loading, empty, and error states
4. Layout alignment and container rules
5. Generic component patterns that make the UI feel AI-generated
6. Motion and polish
7. Missing product basics such as 404s, legal links, validation, and back-navigation

## Reference files

Read these only when needed:

- `references/audit-checklist.md`: full audit prompts for typography, color, layout, states, content, components, and code quality
- `references/upgrade-patterns.md`: replacement ideas when a section needs a stronger layout or motion concept

## Final preflight

- Confirm the redesign still looks like the same product, only sharper and more intentional.
- Confirm the changes are stack-native and maintainable by the existing team.
- Confirm every visible interactive state exists.
- Confirm repeated alignment, spacing, and radius rules are consistent across sibling components.
- Confirm the UI works without placeholder assets or fake copy.
