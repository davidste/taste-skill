# Taste Skill

A collection of skills that improve how AI tools write frontend code. Instead of generating generic, boring interfaces, the AI builds modern, premium designs with proper animations, spacing, and visual quality.

## Feedback & Contributions

I'd love to hear your thoughts! If you have suggestions or find any bugs:

- Open a Pull Request or Issue right here on GitHub
- DM me on [x.com/lexnlin](https://x.com/lexnlin)
- Email me at [hello@learn2vibecode.dev](mailto:hello@learn2vibecode.dev)

## Skills

There are three skills in this project. Each one lives in its own folder and includes a `SKILL.md` file, optional `references/` material, and `agents/openai.yaml` metadata for agents that support it.

### 1. taste-skill
The main design skill. Teaches the AI how to write good-looking frontend code from scratch. Covers layout, typography, colors, spacing, motion, and overall visual quality.

### 2. redesign-skill
For upgrading existing projects. Instead of rebuilding from zero, this skill walks the AI through auditing what's already there and fixing the biggest design problems first.

### 3. output-skill
Stops the AI from being lazy. Prevents placeholder comments, skipped code blocks, and half-finished outputs. Forces the AI to actually write everything instead of cutting corners.

## How to Use

1. Copy the entire skill folder you need into your project, not just `SKILL.md`.
2. Keep the folder structure intact so the AI can read any referenced files.
3. Tell your AI to read and follow the skill. In editors that support direct references, point at the skill folder or `SKILL.md`.

That's it. The AI reads the file and follows the rules.

## Settings (taste-skill only)

The taste skill uses three design dials. Mention them in your prompt when you want to push the output in a specific direction:

**DESIGN_VARIANCE** — How experimental the layout is.
- 1-3: Clean, centered, standard grids.
- 4-7: Overlapping elements, varied sizes.
- 8-10: Asymmetric, lots of whitespace, very modern.

**MOTION_INTENSITY** — How much animation there is.
- 1-3: Almost none. Simple hover effects.
- 4-7: Fade-ins, smooth scrolling.
- 8-10: Magnetic effects, spring physics, scroll-triggered animations.

**VISUAL_DENSITY** — How much content fits on one screen.
- 1-3: Big and spacious. One element at a time. Luxury feel.
- 4-7: Normal spacing. Like a typical app or website.
- 8-10: Dense and compact. Dashboards, data-heavy interfaces.

Example: "Use `DESIGN_VARIANCE 7`, `MOTION_INTENSITY 3`, and `VISUAL_DENSITY 5` for a polished SaaS landing page."

## Examples

Created with taste-skill:

<p>
  <img src="examples/floria-top.webp" width="400" />
  <img src="examples/floria-bottom.webp" width="400" />
</p>

## Research

Background research that informed how these skills were built. See the [research](research/) folder.
