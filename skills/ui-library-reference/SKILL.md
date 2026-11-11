---
name: ui-library-reference
description: Use when building or restyling a web UI and you need to choose a component library or UI primitive. Lists foundations, focused components, showcase collections, and discovery sites, and how to pick among them.
---
# UI library reference

Choose the library before inventing a component. Read `package.json` and any existing `components/ui` first. If the project already uses one of these and it covers the job, keep it.

## How to pick

1. Prefer [shadcn/ui](https://ui.shadcn.com) on [Radix](https://www.radix-ui.com) or [Base UI](https://base-ui.com) as the base for product UI: buttons, inputs, dialogs, menus, forms, and the rest of the app shell. shadcn/ui copies the component source into the project. New shadcn projects default to Base UI; Radix stays supported with `shadcn init -b radix`. Match whichever base the repo already has.
2. Add a focused component when the screen needs that one job: [Sonner](https://sonner.emilkowal.ski) for toasts, [Vaul](https://vaul.emilkowal.ski) for drawers, [cmdk](https://cmdk.paco.me) for a command menu, [NumberFlow](https://number-flow.barvian.me) for animated numbers.
3. Use the showcase collections sparingly, for a hero or marketing section. One designed moment is enough. Keep the rest of the page on the base library.
4. For an agent talking to a person (thinking traces, streaming answers, approvals), add the matching piece from [Beautiful UI](https://beautifului.dev) on top of the base.
5. When the job sits outside this list (charts, drag and drop, general motion, state, styling helpers, and similar), use the [pick-ui-library](https://github.com/emilkowalski/skills) skill in emilkowalski/skills. That skill is a related reference. Follow it there.

## Foundations and headless primitives

- [shadcn/ui](https://ui.shadcn.com) — Composable, accessible components with thoughtful defaults. You copy the code into the project and make it your own. Reach for it as the styled base of an app.
- [Base UI](https://base-ui.com) — Unstyled UI components for building accessible web apps and design systems, from the creators of Radix, Floating UI, and Material UI. Reach for it for headless, accessible behavior (including Combobox and Autocomplete) that you style yourself, or as the primitive layer under shadcn/ui.
- [Radix](https://www.radix-ui.com) — Unstyled, accessible, open-source React primitives for web apps and design systems. The same site also ships components, icons, and colors. Reach for the primitives when you want accessibility and behavior without a visual opinion, including as the Radix base under shadcn/ui.

## Focused, single-purpose components

- [Sonner](https://sonner.emilkowal.ski) — An opinionated toast component for React. Reach for it for toasts.
- [Vaul](https://vaul.emilkowal.ski) — A drawer component for React. Reach for it when the UI needs a drawer.
- [cmdk](https://cmdk.paco.me) — A fast, unstyled command menu for React, also usable as an accessible combobox. Reach for it for a command menu.
- [NumberFlow](https://number-flow.barvian.me) — A React component that animates numbers. Dependency-free, accessible, and customizable. Reach for it when a count, price, or stat should transition as the value changes.

## AI-native interface components

- [Beautiful UI](https://beautifului.dev) — Copy-paste components for AI-native interfaces: chat agents, thinking states, and human-in-the-loop approvals. Reach for it when an agent has to talk to a person.

## Animated and showcase collections

- [RareUI](https://rareui.in) — Free, open-source animated React components, built with Tailwind CSS and Framer Motion, copied into the project. Reach for one animated effect on a marketing page.
- [Magic UI](https://magicui.design) — 150+ free animated components and effects, built with React, TypeScript, Tailwind CSS, and Motion, as a companion to shadcn/ui for landing pages. Reach for one effect or section, and keep shadcn/ui for the product UI.
- [Aceternity UI](https://ui.aceternity.com) — 200+ copy-paste React components, blocks, and landing-page templates, built with Tailwind CSS and Motion. Reach for a hero, background, or marketing section.

## Discovery and marketplaces

- [21st.dev](https://21st.dev) — 12,000+ hand-crafted React and Tailwind components, templates, and shadcn themes from many design engineers. Preview live, then install one into the repo. Reach for it to compare real takes on a single piece.

## Related reference

The [pick-ui-library](https://github.com/emilkowalski/skills) skill in emilkowalski/skills is a related reference for choosing a library by task. Use that skill for the wider list. Leave its text there.
