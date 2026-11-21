# MSB Nanotech UI Anti-Slop Gate

This is the project's persistent quality gate. Use it during every visual or copy change; it is a filter, not a mandatory style template. Preserve the intentional gold/indigo/midnight direction, but demand a specific reason for every pattern.

## Direction and specificity
- Identify the actual visitor, primary task, content and next action before adding UI.
- Reject interchangeable generic headlines, hype, filler, and unsupported claims.
- Avoid formulaic section rhythms, card grids and identical layouts. Use hierarchy, editorial composition, lists, whitespace and varied content density.
- Every visual motif must connect to MSB or its audience, not merely look fashionable.

## Surface / component rules
- Prefer spacing, alignment, type hierarchy and quiet separators over container nesting.
- No thick borders on rounded surfaces. Avoid card-on-card structures, unnecessary glassmorphism, decorative blur, glow and shadows.
- Cards are reserved for genuinely separate content or interaction. Don't create repeated cards solely to fill a layout.
- Iconography must be consistent, meaningful and not emoji placeholders. Use SVG/icon assets only where they help recognition.
- Avoid decorative gradients and gradient headline text as reflex; gold and indigo remain brand colors, not compulsory gradient effects.

## Copy / trust
- Replace generic marketing language with concrete, audience-specific descriptions.
- No fake awards, testimonials, statistics, video thumbnails, partners, events or outcomes.
- Use honest placeholders only where actual content is missing. Avoid simulated controls or links that imply unavailable functionality.
- No vague CTAs. Each CTA names a useful action.
- Check spelling, grammar, claims and real contact details before publication.

## Interaction / accessibility
- All interactive elements keyboard accessible, with visible focus states.
- Provide accessible names, aria-expanded/controls for toggles, semantic heading order and meaningful link labels.
- Ensure touch targets, mobile navigation, hover/focus/active states and no horizontal overflow.
- Honor prefers-reduced-motion; motion must support navigation, feedback or focus rather than decorate everything.
- Avoid scroll-triggered animation as a prerequisite for content visibility.

## Responsive / real-world QA
- Review at 1440px, 1024px, 768px and 390px widths.
- Check real content, long text, empty content, unavailable media, contact destination, menu behavior and anchor targets.
- Test keyboard-only, zoom, contrast and reduced motion.
- Performance: avoid unnecessary external scripts, oversized fonts, heavy animation, repeated observers and avoidable layout shifts.
- A design is not "verified" until it is rendered and tested in an actual browser.

## Purpose & convergence test
For each technique, answer: Why does this fit MSB and this section? If the same pattern is used across unrelated sections without a clear reason, remove or vary it. Judge user cost and evidence, not whether a design uses a fashionable technique.

## Current audit observations (first implementation)
- Orbital hero remains as the distinctive brand motif; simplify surrounding decorative effects if they compete with the copy.
- Original generic headline and abstract mission copy were replaced with clearer descriptions of actual event and hackathon services.
- Hackathon descriptions were made more concrete, especially pitch and documentation.
- Proof and video areas are explicitly content placeholders; never fabricate their content.
- Scroll-reveal opacity dependency was removed so content is not hidden when scripts fail.
- Mobile menu now exposes expanded state and visible focus styling was added.
- Reduced-motion preference was added.
- Contact destination still requires an authentic business email before launch.
- The site still requires browser-based visual QA and real content integration; don't claim those checks have been completed.

## Review format
For each issue: severity, exact evidence, user/business impact, minimal durable fix, and verification conditions. Remove or simplify before adding new decoration.
