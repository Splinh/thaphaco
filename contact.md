# Liên Hệ

## Mission

Create implementation-ready, token-driven UI guidance for Liên Hệ that is optimized for consistency, accessibility, and fast delivery across e-commerce storefront.

## Brand

- Product/brand: Liên Hệ
- URL: https://thaphaco.com.vn/lien-he/
- Audience: online shoppers and consumers
- Product surface: e-commerce storefront

## Style Foundations

- Visual style: clean, functional, implementation-oriented
- Main font style: `font.family.primary=sans-serif`, `font.family.stack=sans-serif`, `font.size.base=16px`, `font.weight.base=400`, `font.lineHeight.base=25.6px`
- Typography scale: `font.size.xs=11.2px`, `font.size.sm=11.52px`, `font.size.md=12px`, `font.size.lg=12.24px`, `font.size.xl=12.42px`, `font.size.2xl=12.8px`, `font.size.3xl=13.19px`, `font.size.4xl=13.6px`
- Color palette: `color.surface.base=#000000`, `color.text.secondary=#60b301`, `color.text.tertiary=#ffffff`, `color.text.inverse=#222222`, `color.surface.strong=#111111`
- Spacing scale: `space.1=1.44px`, `space.2=1.49px`, `space.3=1.54px`, `space.4=1.66px`, `space.5=3px`, `space.6=3.6px`, `space.7=4px`, `space.8=5px`
- Radius/shadow/motion tokens: `radius.xs=3px`, `radius.sm=30px`, `radius.md=100px`, `radius.lg=999px` | `shadow.1=rgba(0, 0, 0, 0.1) 0px 1px 2px 0px inset` | `motion.duration.instant=200ms`, `motion.duration.fast=250ms`, `motion.duration.normal=300ms`

## Accessibility

- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone

Concise, confident, implementation-focused.

## Rules: Do

- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't

- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow

1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure

- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations

- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (342), lists (53), buttons (31), inputs (22), navigation (3), cards (1), tables (1).

## Quality Gates

- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
