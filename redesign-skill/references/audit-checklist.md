# Audit Checklist

Use this file when auditing an existing UI before editing it.

## Typography

- Check whether the project uses default browser fonts or `Inter` everywhere.
- Check whether display text has clear hierarchy, tighter tracking, and controlled line height.
- Check whether body copy is too wide or too cramped.
- Check whether number-heavy views need monospace or tabular figures.
- Check whether labels, captions, and secondary text all use the same bland weight.
- Check whether long headlines need `text-wrap: balance` or a layout change.

## Color and surfaces

- Check for pure black backgrounds or harsh contrast that could be softened.
- Check for multiple competing accent colors.
- Check for warm and cool grays mixed in the same screen.
- Check for default purple-blue gradients that make the UI feel generic.
- Check whether shadows carry the hue of the surface or default to gray mud.
- Check whether flat sections need texture, image, or ambient depth.
- Check whether light and dark sections coexist without a clear system.

## Layout

- Check whether everything is centered and symmetrical by default.
- Check for three-equal-card rows that should become a stronger layout.
- Check for `100vh` or `h-screen` usage that will jump on mobile browsers.
- Check for fragile flexbox width math that grid could replace.
- Check for missing max-width container rules.
- Check for forced equal-height cards that create awkward whitespace.
- Check for inconsistent vertical rhythm, button alignment, and feature-list start lines.
- Check whether side-by-side elements are mathematically aligned but optically wrong.

## States and interaction

- Check for missing hover, active, and focus-visible states.
- Check for missing loading, empty, and error states.
- Check for dead links or buttons that point to `#`.
- Check whether the active page or selected tab is visually obvious.
- Check for jumpy anchor scrolling or motion based on layout properties.
- Check whether the interface feels dead because every transition is instant.

## Content

- Check for placeholder names, fake brand names, or lorem ipsum.
- Check for suspiciously round metrics, prices, dates, or phone numbers.
- Check for AI cliches in marketing copy.
- Check for repeated avatars or obviously duplicated testimonial content.
- Check whether tone is too loud for the product, especially in success and error copy.

## Components and code quality

- Check for generic card treatment everywhere.
- Check for default component-library styling that was never customized.
- Check for icon inconsistency or cliche icon choices.
- Check for div soup where semantic HTML would be clearer.
- Check for inline styles fighting the main styling system.
- Check for missing alt text, meta tags, favicon, or legal links.
- Check for missing back-navigation, validation, or a helpful `404` state.
