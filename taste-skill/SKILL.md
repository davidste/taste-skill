---
name: taste-skill
description: Build distinctive frontend interfaces from scratch with strong typography, restrained color, purposeful motion, and realistic content. Use when creating new landing pages, marketing sites, dashboards, SaaS screens, or React/Next/Tailwind frontends that should avoid generic AI design patterns.
---

# Taste Skill

## Work sequence

1. Inspect reality first: identify the framework, styling system, Tailwind version, design system, and installed dependencies before proposing imports.
2. Choose the product mode: marketing, app, dashboard, or editorial.
3. Set the design dials from the user's request or the defaults below.
4. Build the interface completely: layout, copy, states, motion, and responsive behavior.
5. Run the preflight checklist before finalizing.

## Default dials

- `DESIGN_VARIANCE`: `8`
- `MOTION_INTENSITY`: `6`
- `VISUAL_DENSITY`: `4`

Use the user's explicit direction over these defaults. If the user does not specify a visual target:

- Lower variance for enterprise and admin tools.
- Lower motion for accessibility-sensitive or data-heavy UI.
- Lower density for marketing and editorial work.

## Non-negotiables

- Verify every external dependency in `package.json` before importing it. If a package is missing, say so and provide the install command instead of hallucinating the import.
- Respect the existing stack. Default to React or Next.js patterns only when the project does not specify something else.
- Isolate interactive or animated leaves into client components. Keep surrounding layout server-safe when working in Next.js.
- Check Tailwind version before using version-specific syntax or config guidance.
- Use `min-h-[100dvh]` instead of `h-screen` for full-height sections.
- Prefer CSS Grid over complex flexbox width math.
- Use semantic HTML and clean layering. Do not scatter arbitrary `z-index` values.
- Use one accent color and a consistent neutral family. Avoid default purple-blue AI gradients unless the user explicitly asks for them.
- Keep copy concrete and specific. Use believable names, brands, and numbers instead of placeholders or startup cliches.
- Include complete states: loading, empty, error, hover, active, and focus-visible.
- Keep forms conventional: label above input, helper or error text below, and visible validation feedback.

## Direction by product mode

### Marketing and editorial

- Favor asymmetry, stronger display typography, and spacious sections.
- Prefer one hero idea per screen instead of dense grids.
- Use imagery, pattern, or texture so sections do not feel flat.

### App and dashboard

- Prioritize clarity and navigation before spectacle.
- Use serif fonts only for explicitly editorial products.
- Reduce card overuse. Use spacing, dividers, and grouping before defaulting to bordered boxes.
- Use monospace or tabular figures for dense numeric content.

## Motion rules

- `MOTION_INTENSITY` `1-3`: use hover and active states plus small reveal transitions only.
- `MOTION_INTENSITY` `4-7`: use staggered entry, spring easing, and occasional background motion.
- `MOTION_INTENSITY` `8-10`: use advanced motion only when it improves the concept and the stack supports it.
- Animate with `transform` and `opacity`, not layout properties.
- Isolate perpetual animation in tiny leaf components so the main layout does not rerender.
- Avoid custom cursors and gratuitous effect stacks that hurt accessibility or performance.

## Reference files

Read these only when needed:

- `references/anti-patterns.md`: banned visual, content, and layout tells to remove from drafts
- `references/pattern-library.md`: hero, layout, interaction, and bento ideas when the UI needs a stronger concept

## Final preflight

- Confirm the visual direction matches the product type rather than a generic style-board.
- Confirm mobile collapse is clean and intentional.
- Confirm the palette, radius scale, shadow language, and icon style are consistent.
- Confirm there are no placeholder names, lorem ipsum, fake links, or incomplete states.
- Confirm the interface would still feel polished if animations were disabled.
