# Anti-patterns

Use this file when a draft still feels AI-generated or overly generic.

## Visual

- Do not use pure black backgrounds. Prefer tinted dark neutrals.
- Do not stack multiple accent colors unless the user explicitly asks for a loud palette.
- Do not default to purple or blue glow gradients.
- Do not rely on generic box shadows. Tint shadows to the surface hue.
- Do not leave sections as flat color blocks with no texture, imagery, or depth cue.

## Typography

- Do not default to `Inter` for every project.
- Do not use serif fonts for dashboards unless the product is intentionally editorial.
- Do not create giant hero text with no hierarchy underneath it.
- Do not leave paragraphs too wide; keep reading width around `65ch`.
- Do not use only `400` and `700` weights if the type scale needs nuance.

## Layout

- Do not center everything by reflex.
- Do not ship the default three-equal-card feature row unless the brief explicitly wants it.
- Do not use `h-screen` for mobile-height sections.
- Do not rely on brittle flexbox math when grid solves the problem cleanly.
- Do not stretch content edge to edge on wide screens without a container rule.
- Do not force equal card heights when the content wants asymmetry or a masonry rhythm.

## Components and motion

- Do not leave buttons with hover but no pressed state.
- Do not ship pages without loading, empty, and error states.
- Do not animate `top`, `left`, `width`, or `height`.
- Do not overuse cards when spacing and dividers would communicate hierarchy better.
- Do not drop in component-library defaults without restyling them to fit the project.

## Content

- Do not use placeholder names like `John Doe`, `Jane Smith`, or `Acme`.
- Do not use suspiciously round numbers like `99.99%` or `$100.00` unless the product requires them.
- Do not use lorem ipsum or startup cliches like `Seamless`, `Next-gen`, or `Elevate`.
- Do not leave links pointing to `#` unless they are visibly disabled.
- Do not use the same avatar, date, or testimonial shape everywhere.
