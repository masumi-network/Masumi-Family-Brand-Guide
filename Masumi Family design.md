---
description: Brand and UI/UX source of truth for Masumi, Sokosumi, and CMO.XYZ
---

# Masumi family

> **Disclaimer: names will change.** Some product names in this guide are being renamed. This file uses the current names until the changes go live. This document will reflect the changes when they are approved and live.
>
> | Current name | New name |
> |---|---|
> | Sokosumi | Marketing OS |
> | Masumi Protocol (the smart contract) | Masumi Standard |
> | Masumi Payment Service | Masumi Agent Wallet |
>
> Brand rules (logo, color, type, UI/UX) carry over to the new names. Wordmarks for both Sokosumi and Marketing OS are in `logos/`. Wordmarks for Masumi Standard and Masumi Agent Wallet are **Open**.

## Overview

This is the single source of truth for brand across **Masumi**, **Sokosumi**, and **CMO.XYZ**, and for UI/UX across **Masumi** and **Sokosumi**. CMO.XYZ's UI will be different.

- Designers, developers, and the website team build from this file.
- **Do not build against anything marked Open as final.**

### The three brands

- **Masumi** is the payment layer and the backend that powers Sokosumi.
- **Sokosumi** is the workplace OS and agent marketplace.
- **CMO.XYZ** is an autonomous marketing agent that runs on top of Sokosumi and Masumi.

Masumi and Sokosumi share one brand system: one palette, one graphic language, and Inter. CMO.XYZ has its own branding and logos, so it has its own section (Section 3). All three use Iris Flower as the primary color. Masumi and Sokosumi share one set of UI/UX rules (Section 1.10), built on shadcn/ui, Tailwind, and Radix. CMO.XYZ's UI will be different, so Section 1.10 does not apply to it. CMO.XYZ uses Dela Gothic One and PP Mori (Section 3). CMO.XYZ is the only brand with a mascot and a named agent persona.

### How this file is organized

- **Overview (this part):** all three brands.
- **1. Masumi:** logo, color, typography, graphic language, UI/UX rules and extended guidelines. Sokosumi shares these.
- **2. Sokosumi:** what is specific to Sokosumi. It follows the shared parts in Section 1.
- **3. CMO.XYZ:** its own section, with its overview, brand identity, logo, mascot, and its own rules. CMO.XYZ's UI will be different from Masumi and Sokosumi.
- **Governance, In process, Open decisions, Resources** come last.

### The Agentic family

The Agentic family has multiple logos. Masumi is the payment layer, Sokosumi is the workplace OS and agent marketplace, and CMO.XYZ is the autonomous marketing agent. Marketing OS is the upcoming name for Sokosumi. The slide follows this guide: Inter, the shared neutrals, the xl radius, and black logos only. The dashed lines mark each wordmark's x-height and baseline.

![The Agentic family logos](Masumi%20Family%20Brand%20Guide%20Slides/agentic-family-slide.png)

| Brand | Role | Logo |
|---|---|---|
| Masumi | Payment layer | ![Masumi](logos/masumi/masumi-logo-wordmark-black.svg) |
| Sokosumi | Workplace OS and agent marketplace | ![Sokosumi](logos/sokosumi/sokosumi-logo-wordmark-black.svg) |
| Marketing OS | Upcoming name for Sokosumi | ![Marketing OS](logos/marketing-os/marketing-os-wordmark-black.svg) |
| CMO.XYZ | Autonomous marketing agent | ![CMO.XYZ](logos/cmo-xyz/wordmark/cmo-xyz-dela-black.svg) |

The slide is `Masumi Family Brand Guide Slides/agentic-family-slide.png` (16:9, 1920 by 1080 at 2x). Its editable source is `agentic-family-slide.html`.

### Telling the brands apart

With one shared palette, color does not separate the brands. These do:
- **Brand identity:** Masumi and Sokosumi share one. CMO.XYZ has its own branding and logos (Section 3).
- **Wordmark:** each brand has its own logo.
- **Mascot and agent persona:** Cuso belongs to CMO.XYZ only.
- **Density and surface:** Sokosumi is a dense, neutral-heavy team workspace. CMO.XYZ is lighter and more open.

### Status legend

| Label | Meaning |
|---|---|
| Locked | Decided. Build against it. |
| Working | In use, not final. Do not treat as final. |
| Open | Decision needed. Do not build against it. |
| Proposed | A default suggested by this draft. Needs approval. |

### Status at a glance

| Area | Masumi | Sokosumi | CMO.XYZ |
|---|---|---|---|
| Positioning | Locked | Locked | Locked |
| Voice and tone | TBD (Section 1.11.5) | TBD (Section 1.11.5) | Locked |
| Typeface | Locked (Inter) | Locked (Inter) | Locked (Dela Gothic One, PP Mori) |
| Color palette | Locked (shared) | Locked (shared) | Locked (white, black, Iris Flower) |
| Brand identity | Shared | Shared | Separate, in progress |
| Logo | Locked | Locked | Locked (primary lockup approved, primary wordmark Open) |
| Graphic language | None set (gradients, mockups) | None set (gradients, mockups) | None set (gradients, mockups) |
| Mascot and avatars | Not applicable | Not applicable | Locked (2D mascot), avatars Open |
| Dark mode | Locked, values open | Locked, values open | Locked, values open |
| Imagery, motion, templates, co-branding | TBD | TBD | TBD |
| UI/UX rules | Locked (shadcn/ui) | Locked (shadcn/ui) | Separate. Buttons and states approved, the rest Open |

### Naming rules

- Logos are lowercase: masumi, sokosumi, marketing os. In writing, brand names are capitalized like proper nouns: Masumi, Sokosumi, Marketing OS.
- The product name is written **CMO.XYZ** in capitals.
- Never abbreviate a brand name or add a suffix to it.

---

## 1. Masumi

### 1.1 Role and personality

Masumi is the payment layer. It is the foundation the other products stand on, so it should feel precise, calm, and trustworthy, with warmth from its color.

### 1.2 Logo

- **Wordmark.** Each brand has a wordmark. The symbol is a separate mark for small spaces.
- **Minimum size.** Wordmark: 14px tall on screen. The print minimum is **Open**.
- **Clearspace.** Keep clear space on all four sides of the wordmark. x is the width of the "s" in the wordmark. Below 30 px tall: 2x. Above 30 px tall: 1x. See Logo clearspace below.
- **On color.** On any colored or multicolored background, use black or white only.
- **Symbol.** Use the symbol only where there is no room for the full wordmark, and never when several brand symbols appear together.
- **In running text.** Write the brand name in the body typeface, in the same weight as the copy.
- **Placement.** Nine placements are allowed inside a defined space: center, top, or bottom on each axis.
- **Partnerships.** Use horizontal or vertical arrangements with the wordmark only. Size partner logos optically. Do not match their height or width to ours. See Logo spacing and Logo partnerships below.

### 1.3 Logo clearspace

Nothing enters the clear space around the wordmark: no text, no other logos, no page edge. The rule is shown on the Masumi wordmark. How x is measured on the Sokosumi, Marketing OS and CMO.XYZ wordmarks is **Open**.

| Wordmark height | Clear space |
|---|---|
| Below 30 px | 2x |
| Above 30 px | 1x |

![Logo clearspace, below 30 px height](Masumi%20Family%20Brand%20Guide%20Slides/logo-clearspace-below-30px.png)

![Logo clearspace, above 30 px height](Masumi%20Family%20Brand%20Guide%20Slides/logo-clearspace-above-30px.png)

The slides are in `Masumi Family Brand Guide Slides/`. Their editable source is `sources/logo-clearspace-slide.html`. Open it with `#1` or `#2` at the end of the address for the 1x or 2x version.

### 1.4 Logo spacing

When two logos sit side by side or stacked, keep 2x of space between them. x is the width of the "s" in the wordmark. The space is the same in a horizontal and a vertical arrangement. **Proposed:** the 2x value is measured from the spacing in the original partnerships slide. Confirm it.

![Spacing between logos](Masumi%20Family%20Brand%20Guide%20Slides/logo-spacing.png)

The editable source is `logo-spacing-slide.html`.

### 1.5 Logo partnerships

When the Masumi logo sits next to a partner logo, size the partner logo optically so it carries the same visual weight as ours. Do not match height or width. Use a horizontal or vertical arrangement with the wordmark only.

![Logo partnerships: correct and incorrect sizing](Masumi%20Family%20Brand%20Guide%20Slides/logo-partnerships.png)

- **Correct (green check).** The partner logo is sized to look equal in weight to the wordmark, in a horizontal or a vertical arrangement.
- **Incorrect (x).** The partner logo is too small, or it is enlarged to match the width of the wordmark.
- The example partner logo is NMKR, taken from the original Agentic brand guidelines. The partner logo file is not included for now. The editable source is `sources/logo-partnerships-slide.html`.

### 1.6 Logo files

All files are in the `logos/` folder next to this file, one subfolder per brand. Black versions are for light backgrounds. White versions are for dark and colored backgrounds.

| Brand | File | Use |
|---|---|---|
| Masumi | `logos/masumi/masumi-symbol.svg` | Symbol. Favicon and avatar. |
| Masumi | `logos/masumi/masumi-logo-wordmark-black.svg` | Wordmark, black |
| Masumi | `logos/masumi/masumi-logo-wordmark-white.png` | Wordmark, white (PNG, no SVG yet) |
| Sokosumi | `logos/sokosumi/sokosumi-logo-wordmark-black.svg` | Wordmark, black |
| Sokosumi | `logos/sokosumi/sokosumi-logo-wordmark-white.svg` | Wordmark, white |
| Marketing OS | `logos/marketing-os/marketing-os-wordmark-black.svg` | Wordmark, black |
| Marketing OS | `logos/marketing-os/marketing-os-wordmark-white.svg` | Wordmark, white |

- **Symbol color.** The symbol file uses red `#FF003D`. This red is a logo color, not a palette color. The palette primary is Iris Flower `#FF51FF`.
- **Proportions.** The wordmark is about 6.5 to 1 (width to height).
- **Do not** recolor, outline, stretch, rotate, or add effects to any logo file.
- Marketing OS is the upcoming name for Sokosumi. Both sets are included until the rename goes live.
- CMO.XYZ has its own branding and logos. Its files are listed in Section 3, Logo.

### 1.7 Color (Masumi and Sokosumi)

![Masumi family color palette](Masumi%20Family%20Brand%20Guide%20Slides/color-palette-slide.png)

The Masumi palette is the palette for Masumi and Sokosumi. CMO.XYZ takes Iris Flower from it (Section 3, Color). It runs from pink through red and yellow, with softer tones taken from traditional Japanese colors. The primary is Iris Flower. Every other palette color is secondary.

| Name | Hex | Role |
|---|---|---|
| Crimson Purple | #460A23 | Secondary |
| Scarlet | #FA140A | Secondary |
| Electric Pink | #FA008C | Secondary |
| Persimmon | #FF6400 | Secondary |
| **Iris Flower** | #FF51FF | **Primary** |
| Vivid Sakura | #FF6ED2 | Secondary |
| Sand | #D7BE8C | Secondary |
| Golden Yellow | #FFD300 | Secondary, also the warning color |
| Peach Blossom | #FFC8F0 | Secondary |

Colors are listed dark to light. Use the shared neutrals (Section 1.10.2) for everything else. Do not use the palette for status colors, except Golden Yellow as the warning color (Section 1.10.2).

### 1.8 Typography

Inter. The typeface, weights, typescale, alignment, and don'ts are in Section 1.10.3.

### 1.9 Graphic language and imagery

Applies to all three brands.

**Status:** Working. This section is intentionally bare bones. Rules are added as we go.

#### Confirmed
- **Gradients.** The only decorative graphic element. Built from the shared Masumi palette. Masumi and Sokosumi share the palette for gradients (Section 1.9, Gradient rules).
- **UI and product mockups.** All product shots and explanations of the product are mockups of the real UI.
- **The CMO.XYZ mascot and avatars,** for CMO.XYZ only (Section 3).

#### AI generated content
- AI generation is used widely. It is decided case by case.
- Label AI generated content where the country or platform requires it. Check the rules for the market before publishing.
- Keep the tool and the prompt for each generated asset.
- Who approves a use, and which markets require labels, is **Open**.

#### Not decided yet
- Photography and stock images
- Decorative grids
- Blur and glow effects
- Abstract art
- Realistic AI generated images (images that imitate real people, places, or products)

Until these are decided, check with brand and marketing before using any of them. They are tracked in Open decisions.

#### Gradient rules (TBD)
- Pairs: all brands draw gradient stops from the shared palette. Starting idea to confirm: Iris Flower to Vivid Sakura, Iris Flower to Crimson Purple, and Peach Blossom to Iris Flower.
- Allowed stops, angles, and direction: to define.
- Contrast: text on a gradient must still pass the targets in Section 1.10.11.
- Placement: backgrounds and hero areas. Never behind dense UI.

#### Mockup rules (TBD)
- Device frames, screen states, and example data: to define.
- Mockups show real product screens in light and dark themes.
- Use realistic, on-voice example content. No lorem ipsum.

### 1.10 UI/UX rules (Masumi and Sokosumi)

Every Masumi and Sokosumi product and surface follows these rules. CMO.XYZ's UI will be different and is not covered here (Section 3). **shadcn/ui, with Kibo UI as an approved extension, is locked as the UI/UX standard.** Brand values come from the shared tokens.

#### 1.10.0 Implementation standard: shadcn/ui

**Status: Locked.** All web products use shadcn/ui as the component system. Material Design 3 is not used.

**Stack**
- **Components:** shadcn/ui, new-york style, neutral base, over Radix. Components live in each app's `components/ui/` folder and are configured by `components.json`.
- **Styling:** Tailwind CSS (v4, CSS-first). There is no JS config. Tokens are CSS variables in the app's `globals.css`, with a `.dark` class that redefines the same token names.
- **Icons:** the icon set is **Pending**.
- **Extensions:** Kibo UI (below).

**Rules**
- Reference semantic tokens (for example `bg-primary`, `text-muted-foreground`, `border-input`). Never hardcode hex, radius, or spacing.
- No opacity modifiers on color utilities. Use the opaque ramp steps or a named token.
- Edit token values in `globals.css`, not in components.
- Tokens are shared: Inter and the Masumi palette.

**Reference:** [shadcn/ui documentation](https://ui.shadcn.com/)

#### 🧩 Advanced SaaS Components: Kibo UI
We use **Kibo UI** as a supplementary component registry to bridge the gap between shadcn's core primitives and complex SaaS feature requirements. 
* **When to use:** Use Kibo UI when a feature demands specialized, high-tier interface elements missing from the standard shadcn catalog (e.g., advanced multi-step forms, multi-select components, interactive cards/decks, and compare sliders).
* **Architecture:** Because Kibo UI is built on the exact same foundation (Tailwind CSS + Radix UI), its components integrate natively with our existing `components.json` layout, automatically inheriting our global styling tokens and theme variables.
* **How to add:** 
  ```bash
  npx shadcn add https://kibo-ui.com<component-name>.json
  ```
  *(Note: Always verify the exact registry URL from the Kibo UI documentation before running the CLI command, and ensure the newly added component respects our local Tailwind configurations).*

Kibo UI components follow the same brand tokens, dark mode, and accessibility rules as everything else in this section.

shadcn/ui, Radix, and Tailwind are web only, so they do not cover native iOS and Android apps. Native mobile apps are planned. **Proposed:** use React Native Reusables, a shadcn style library, so the tokens carry over.

#### 1.10.1 Principles

1. **Show the data.** Anything the agent says is backed by data the user can see on screen.
2. **Fast to the first result.** Get people to a useful result in as few steps as possible.
3. **Ask once, ask well.** When information is missing, ask for it plainly, framed as getting better aligned.
4. **The person stays in control.** Anything an agent does on the user's behalf can be reviewed before it goes out.
5. **Calm by default.** Neutral surfaces, one primary color per screen, gradients used sparingly.
6. **One system.** A pattern that works in one brand works the same in the others.

#### 1.10.2 Colors

- Build every screen from the shared neutrals. Iris Flower is the single accent, in Masumi and Sokosumi. All other palette colors are secondary.
- Use one pink per view. Do not use Scarlet, Persimmon, or Golden Yellow for status.

**Neutral tones (blacks, grays, white)**

| Token | Hex |
|---|---|
| Black | #000000 |
| Neutral 950 | #0C0C0C |
| Neutral 900 | #171717 |
| Neutral 800 | #262626 |
| Neutral 700 | #404040 |
| Neutral 600 | #525252 |
| Neutral 500 | #737373 |
| Neutral 400 | #A3A3A3 |
| Neutral 300 | #D4D4D4 |
| Neutral 200 | #E5E5E5 |
| Neutral 100 | #F5F5F5 |
| Neutral 50 | #FAFAFA |
| White | #FFFFFF |

**Alpha tones (black at reduced opacity)**

| Token | Hex | Opacity |
|---|---|---|
| Alpha 10 | #000000 | 90% |
| Alpha 20 | #000000 | 80% |
| Alpha 30 | #000000 | 70% |
| Alpha 40 | #000000 | 60% |
| Alpha 50 | #000000 | 50% |
| Alpha 60 | #000000 | 40% |
| Alpha 70 | #000000 | 30% |
| Alpha 80 | #000000 | 20% |
| Alpha 90 | #000000 | 10% |
| Alpha 95 | #000000 | 5% |

- The alpha number plus the opacity always add up to 100, so Alpha 20 is 80% black.
- The source swatches label the last alpha tone "Alpha 10" a second time. It is named Alpha 95 here so the alpha number and the opacity add up to 100.
- Use the opaque neutral steps for UI. Use alpha tones only for overlays and scrims over imagery, and define them as named tokens (see Section 1.10.0).

**Light and dark themes (best case, from the tones above)**

| Role | Light | Dark |
|---|---|---|
| Page | White | Neutral 950 |
| Panel (borderless group) | Neutral 100 | Neutral 900 |
| Component on a panel | White with a border | Neutral 950 with a border |
| Border | Neutral 200 | Neutral 800 |
| Field border | Neutral 300 | Neutral 700 |
| Text | Neutral 900 | Neutral 50 |
| Muted text | Neutral 500 | Neutral 400 |
| Disabled text | Neutral 400 | Neutral 600 |
| Primary (Iris Flower) | #FF51FF | #FF51FF |
| Text on primary | Neutral 950 | Neutral 950 |
| Overlay scrim | Alpha 50 | Alpha 50 |

- This mirrors the three-layer page rule in Section 1.10.4.
- **Contrast check.** Iris Flower with Neutral 950 text is about 7.9 to 1, which passes. Iris Flower with white text is only about 2.7 to 1, which fails. So text on a primary fill is always Neutral 950, never white. Never set Iris Flower text on a white page. Use it for fills, accents, and active states.
- Iris Flower stays the same in light and dark. Never tint the neutrals toward pink.

- Semantic colors are separate from brand colors and are used only for status. Every status uses a symbol, never color alone:
  - **Positive (done, success):** green with a check mark.
  - **Warning or danger:** yellow with an exclamation mark (!).
  - **No, delete, and other destructive actions:** an X.
- Hex values (**Proposed**): green `#00D43B`, taken from the partnerships slide. Yellow `#FFD300`, Golden Yellow from the shared palette. The X uses Neutral 950. Hex values are set in `globals.css`.
- Status color coding (done, in progress, blocked) follows the task board and is the same in every module.
- **Never use color alone.** Pair status color with a label or icon.
- Text on color uses black or white, whichever passes contrast.
- Light and dark themes are both required (Locked). Define colors as tokens and redefine them per theme. Never hardcode a color in a component. Dark mode values are **Open**.

#### 1.10.3 Typography

The typographic system uses a very limited set of weights and styles. It should feel simple and carry gravitas.

![Typography](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-01-title.png)

**Typeface**

- Masumi and Sokosumi use Inter. CMO.XYZ uses Dela Gothic One and PP Mori (Section 3). Web fallback: system-ui, -apple-system, Segoe UI, sans-serif.

![Typeface: Inter](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-02-typeface.png)

**Weights**

| Weight | Value | Use |
|---|---|---|
| Inter Light | 300 | Use when more brand presence is needed. Reserved for primary headlines and impactful statements, such as hero sections and minimalist designs. It gives a delicate, airy feel without losing legibility. |
| Inter Regular | 400 | The workhorse. The primary choice for body text and interface text, for optimal readability in digital environments. A clean and approachable presence. |
| Inter Medium | 500 | Subtle emphasis. Subheadings and callouts where a touch of boldness is needed without overwhelming the design. Pairs with Regular. |
| Inter Semibold | 600 | Subtle emphasis, like Medium. Also used for headings inside product UI. |

- Light is never used for body text or small sizes.
- Medium and Semibold are used sparingly, to keep a cohesive visual flow with Regular.
- Do not mix weights inside one headline.

![Weights](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-03-weights.png)

**Typescale**

- The scale has 23 steps. The base size is 12px and the scale is pentatonic: the size doubles every five steps.
- Formula: a<sub>n</sub> = a<sub>0</sub> × r<sup>(n−1)</sup>, where a<sub>n</sub> is the type size, a<sub>0</sub> is the base size (12px), n is the step, and r = 2<sup>(1/5)</sup> ≈ 1.1487.
- Example: a<sub>15</sub> = 12 × 1.1487<sup>(15−1)</sup> ≈ 84px.
- For larger sizes, use the formula to create more harmonious sizes.
- The weight switches from Regular to Light at 20px.
- Line height can be adjusted when a layout needs it.

| Style | Type size | Line height | Letter spacing |
|---|---|---|---|
| Inter Regular | 6 | 8 | 0% |
| Inter Regular | 7 | 10 | 0% |
| Inter Regular | 8 | 12 | 0% |
| Inter Regular | 9 | 12 | 0% |
| Inter Regular | 10 | 14 | 0% |
| Inter Regular | 11 | 14 | 0% |
| Inter Regular | 12 | 16 | 0% |
| Inter Regular | 14 | 18 | 0% |
| Inter Regular | 16 | 20 | 0% |
| Inter Regular | 18 | 22 | 0% |
| Inter Light | 20 | 24 | 0% |
| Inter Light | 24 | 28 | -0.5% |
| Inter Light | 28 | 32 | -1% |
| Inter Light | 32 | 36 | -1.5% |
| Inter Light | 36 | 40 | -2% |
| Inter Light | 42 | 48 | -2.5% |
| Inter Light | 48 | 56 | -3% |
| Inter Light | 55 | 56 | -3% |
| Inter Light | 64 | 64 | -3.5% |
| Inter Light | 73 | 72 | -4% |
| Inter Light | 84 | 80 | -5% |
| Inter Light | 96 | 86 | -5% |
| Inter Light | 110 | 104 | -5% |

![Typescale](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-04-typescale.png)

**Product UI roles**

- **Proposed:** marketing and print use the typescale above. Product UI uses the Tailwind type scale (text-2xs through text-4xl) and the roles below. No arbitrary text sizes.
- Type roles follow Sokosumi's scale: display (Light 30px), heading (Semibold 18px), subheading (Semibold 16px), body (Regular 14px), label (Medium 12px), caption (Regular 12px), micro (Medium 11px, dense meta only).

**Alignment**

- Align type in two ways only: left-aligned or centered. Never right-align or force-justify type.
- The same goes for paragraphs.

![Alignment of headlines](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-05-alignment-headlines.png)

![Alignment of paragraphs](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-06-alignment-paragraphs.png)

**Rules**

- Sentence case everywhere. Never all caps for headlines.
- Keep line length near 65 to 75 characters.
- Use tabular numbers wherever digits line up in columns.
- Avoid extremely tall leading for both headings and body text.
- Avoid overly tight leading, with crashing ascenders and descenders, for both headings and body text.
- Avoid overly tight tracking, with crashing glyphs.
- Avoid overly wide tracking.
- Avoid mixed weights within a single headline.

![Typography don'ts](Masumi%20Family%20Brand%20Guide%20Slides/typography-slide-07-donts.png)

#### 1.10.4 Layout

- **Product UI.** Breakpoints are Tailwind defaults: sm 640, md 768, lg 1024, xl 1280, 2xl 1536. Md is the main mobile and desktop split. Spacing uses the Tailwind 4px scale. App pages fill the width of the main area inside one shared gutter. Never hardcode spacing.
- **Page surfaces.** Three layers: a white page, a borderless light gray panel, and white components with a border on top. Never put a bordered component directly on the white page.
- **Marketing and print.** Use 2, 4, 6, 8, or 12 column grids chosen to fit the format. Margin equals twice the width of the wordmark's "s", and space between elements equals the margin. Visuals may bleed full width. Presentations use 26 rows.
- Align logo, type, and graphics to the grid.
- Segmented lines mark sections and anchor smaller elements such as cards.
- Navigation must be visible without scrolling. Primary actions such as connecting an account live near the top, never at the bottom of a page.
- Prefer tabs over stacked sections when a page has several views (for example Calendar, Drafts, Connected accounts).

##### The 20 UX laws

Apply these to every layout in every brand. Each row pairs the rule with the law behind it.

| # | Rule | Law | In practice |
|---|---|---|---|
| 1 | Reduce choices per screen | Hick's law | One primary action per view. Hide secondary options in menus. |
| 3 | Follow familiar patterns | Jakob's law | Use the conventions people know from other products. |
| 4 | Group related information | Law of proximity | Related items sit close. Unrelated items get more space. |
| 5 | Break content into chunks | Miller's law | Short groups and sections instead of long walls of fields or text. |
| 6 | Respond within 400 milliseconds | Doherty threshold | Show feedback right away. Use skeletons or progress when work takes longer. |
| 7 | Highlight the primary action | Von Restorff effect | The brand primary appears once per view, so it stands out. |
| 8 | Place key actions nearby | Minimize target distance | Put actions next to the thing they act on. |
| 9 | Put essentials first | Serial position effect | The most important items go first and last in lists and navigation. |
| 10 | End flows memorably | Peak-end rule | Finish with a clear, positive confirmation and a next step. |
| 11 | Show visible progress | Zeigarnik effect | Show steps, status, and what is left. |
| 12 | Simplify complex interfaces | Law of Pragnanz | Reduce each screen to its simplest readable form. |
| 13 | Use sensible defaults | Tesler's law | The system absorbs complexity. Prefill, preselect, and infer. |
| 14 | Prevent errors proactively | Error prevention | Constrain inputs, validate inline, and confirm destructive actions. |
| 15 | Make errors recoverable | Error recovery | Undo, edit, and cancel are always available. |
| 16 | Maintain pattern consistency | Law of similarity | Similar things look and behave the same across all products. |
| 17 | Connect related elements visually | Uniform connectedness | Use lines, borders, and containers to link related items. |
| 18 | Reduce task completion time | Parkinson's law | Set short, clear expectations. Remove steps that do not earn their place. |
| 19 | Reveal complexity gradually | Occam's razor | Show the simple view first. Details appear on demand. |
| 20 | Make completion feel closer | Goal-gradient effect | Show progress toward the end and start progress above zero. |

#### 1.10.5 Elevation and depth

- Borders first. Define regions with hairline borders.
- Shadows use Tailwind defaults and stop at shadow-lg, for floating overlays only. Overlays (menus, dialogs) use a scrim.
- No glow or blur effects.

#### 1.10.6 Shapes

- Use the radius scale: xs 2, sm 6, md 8, lg 10, xl 14, 2xl 16, and full for pills and avatars. Use the named classes (rounded-md, rounded-xl). Never hardcode a radius.
- Do not give every element the same radius.

#### 1.10.7 Components

**Buttons**
- Labels start with a verb, in sentence case, one to three words: "Schedule post", "Connect X".
- One filled primary button per view. Everything else is secondary or ghost. Avoid disabled buttons: keep them enabled and explain the problem when pressed.

**Forms and inputs**
- Labels sit above fields. A placeholder is an example, never the label.
- Use pickers and buttons instead of free typed dates and times. Do not use raw month/day/year text fields.
- Always show the time zone next to any date or time, and state whose time zone it is (the viewer's or the schedule's).
- Do not force classification before action. For example, a post does not need a project first: default to a general backlog and let people organize later.
- Show the platform and account being acted on at the moment of creating something.
- Validate inline, next to the field, and say how to fix it.

**Navigation**
- Name views for what they hold. Use "Drafts", not "Agenda".
- Do not repeat what is already on screen. Skip an "Upcoming" list when the calendar is visible.
- Default to the view people use most (for example month view for a calendar).

**Cards, lists, and tables**
- Cards group one object. Use dense bordered rows for long lists instead of many cards.
- Tables align numbers right and text left, and keep the header visible on scroll.
- Reuse the task board card style as the reference for new modules.

**Status chips**
- Short label, status color, optional icon. Same states and colors in every module.

**Empty states**
- An invitation, not an apology. Name the space, say what it holds in one line, and give one action.

**Loading and progress**
- Use skeletons for layout and a short sentence for agent work ("Drafting your posts"). Never leave a blank screen.

**Errors**
- Say what happened, then what to do. One or two sentences. No "Error:" prefix. Do not blame the user.

**Toasts and confirmations**
- Confirm with the result: "Post scheduled". Skip "successfully" and exclamation marks.
- Ask for confirmation before destructive actions, with the consequence stated.

**Dialogs**
- Use only when the user must decide before continuing. Focus moves into the dialog and returns on close.

#### 1.10.8 Agent patterns

These apply wherever an agent speaks or acts, in every brand.

- **Name.** Use the name the user gave their agent. Never a hardcoded name.
- **Data references.** A claim shows the data it comes from (a metric, a post, a page). Offer a way to open the source.
- **Missing information.** Ask directly, framed as getting better aligned. Never "I'm not sure" or "I think".
- **Approvals.** Anything that needs review lands in an Approvals area. Tell the user when something is waiting there.
- **Working state.** Show what the agent is doing and give a note when it is ready.
- **Reversibility.** Let people edit, delay, or cancel anything the agent has queued.
- **Tone.** Plain, short, direct. Follow the voice rules in Section 3 for CMO.XYZ and the same principles elsewhere.

#### 1.10.9 Iconography and imagery

- Use one icon family per product, outline style, consistent stroke. The icon set is **Pending**.
- Use gradients and UI mockups. Other imagery is not decided yet. See Section 1.9.
- Provide text alternatives for every meaningful image.

#### 1.10.10 Motion

- Press and hover feedback: 150ms, ease out. Enter animations: about 200ms. Animate transform and opacity, not layout.
- Name the properties you transition. Never use transition-all.
- Motion explains a change. Do not add decorative looping animation.
- Respect the reduced motion setting by removing non essential movement.

#### 1.10.11 Accessibility

- Target WCAG 2.2 AA.
- Text contrast 4.5:1, large text and interface elements 3:1.
- Every interactive element has a visible keyboard focus state and works without a mouse.
- Icon-only controls are at least 40px below md and 32px from md up. Use a larger hit area when the painted box is small.
- Do not rely on color, motion, or sound alone to carry meaning.
- Support zoom to 200% without loss of content.

#### 1.10.12 Content rules

- Sentence case. Verb first for actions.
- Short sentences and minimal fluff.
- CMO.XYZ copy: minimal to no em dashes or hyphens.
- Skip filler such as "simply" and "successfully".
- Dates, times, and currency follow the user's locale, with the time zone shown.

#### 1.10.13 Tokens and hand off

- All values are design tokens, named by role, not by color.
- All tokens (color, typeface, and the rest) are shared by Masumi and Sokosumi. CMO.XYZ's tokens are separate.
- A separate developer style guide covers code level detail. This file does not replace it.

### 1.11 Extended guidelines (TBD)

These areas are not decided yet. Each has a skeleton to fill in. Nothing here is final, and nothing should be built against it until the status changes.

#### 1.11.1 Imagery and iconography (TBD)

**Status:** TBD. Section 1.10.9 holds only the basics.

To define:
- **Icon style.** Outline or filled, stroke weight, corner treatment, grid size, and the icon set to use.
- **Icon color.** Neutral by default, brand primary for active states only.
- **Illustration rules.** Whether illustration is used at all, the style, and the palette.
- **Fallback visuals.** Gradients and UI mockups only (Section 1.9).
- **CMO.XYZ.** Mascot poses, agent avatars, and where the mascot may and may not appear.
- **Alt text and accessibility** for imagery.

#### 1.11.2 Motion (TBD)

**Status:** TBD. Section 1.10.10 holds the base motion rules. Brand specific motion is still to define.

To define:
- **Animated logo and icon.** The original guide mentioned an animated icon but gave no rules.
- **Gradient motion.** Whether gradients animate, and how.
- **Interface motion.** Page transitions, hover and press states, loading.
- **Agent working state.** How "the agent is working" is animated.
- **CMO.XYZ mascot motion.** Whether the mascot animates and how.
- **Reduced motion** behavior for each of the above.
- **Video and social motion.** Format, length, and safe areas.

#### 1.11.3 Templates (TBD)

**Status:** TBD. No templates are final.

To define, per template: format and size, grid, logo placement, type sizes, color usage, and an editable source file.
- Social posts
- Flier (print)
- Slide decks (26 row grid from the original guide)
- Email signatures
- Email and newsletter layouts
- Website page layouts
- Event and booth materials

#### 1.11.4 Partner and co-branding rules (TBD)

**Status:** TBD. The original guide had these and they were dropped.

Known so far. The visual rules are in Section 1 (Logo spacing and Logo partnerships):
- Partnerships use horizontal or vertical arrangements with the wordmark only.
- Size partner logos optically. Do not match their height or width to ours.
- Keep 2x between logos (Proposed).

To define:
- **Minimum size** for partner arrangements.
- **Divider style** between logos.
- **Order and hierarchy** when brands appear together.
- **Family co-branding.** How Masumi, Sokosumi, and CMO.XYZ appear together, and whether the mascot appears next to partner logos.
- **Partner color.** When partner colors may appear alongside ours.
- **Approval process** for partner use of our marks.

#### 1.11.5 Voice and tone for Masumi and Sokosumi (TBD)

**Status:** TBD. CMO.XYZ voice is locked (Section 3).

To define: personality, do and don't phrases, banned words, and example copy. Starting point to confirm: the CMO.XYZ principles of data over vibes, asking for missing information, and short plain sentences.

#### 1.11.6 Data visualization (TBD)

**Status:** TBD. Needed for CMO.XYZ analytics and Sokosumi dashboards.

To define: chart types, a chart color sequence from each brand palette, labeling, and light and dark theme behavior.

### 1.12 Do and don't

- Do keep the logo black or white on color.
- Do use gradients and UI mockups for visuals.
- Don't set the wordmark in all caps.

---

## 2. Sokosumi

### 2.1 Role and personality

Sokosumi is the workplace OS and agent marketplace. It is where people manage agents and tasks and discover specialized agents. It should feel capable and calm, and stay out of the way of the work.

### 2.2 Logo

Same rules as Masumi (Section 1, Logo).

### 2.3 Color

Sokosumi uses the shared Masumi palette (Section 1, Color) with Iris Flower as the primary. Everything else comes from the shared neutrals (Section 1.10.2). Sokosumi's earlier purple and blue are retired.

### 2.4 Color use

Sokosumi uses the Masumi colors for everything, including gradients. It has no separate brand palette. User-chosen theme colors, offered in the original guide, are not part of this version.

### 2.5 Typography

Inter. The typeface, weights, typescale, alignment, and don'ts are in Section 1.10.3.

### 2.6 Graphic language

See Section 1.9. Gradients use the shared Masumi palette.

### 2.7 Do and don't

- Do use the shared UI/UX rules (Section 1.10) for every screen.
- Do reuse the task board look (cards, status colors) as the reference for other modules.
- Don't use CMO.XYZ's mascot inside Sokosumi surfaces.

---

## 3. CMO.XYZ

> [!TIP]
> **See the visual brand guide:** [`sources/cmo-xyz-brand-guide.html`](sources/cmo-xyz-brand-guide.html). Download it and open it in a browser to see every logo, colour, typeface, mascot pose, rule and UI state on one page.
>
> [![CMO.XYZ brand guide preview](sources/cmo-xyz-brand-guide-preview.png)](sources/cmo-xyz-brand-guide.html)

### 3.1 Overview

CMO.XYZ is an AI agent that automates a business's marketing, end to end, in one system. It is not a chatbot you prompt. It is not a stack of separate tools.

The brand feels plain, direct, and grounded in data. Confidence comes from doing the analysis, not from sounding clever. Light banter is fine. Never stiff and corporate, never crude.

### 3.2 Brand identity

CMO.XYZ is separate from the Masumi family. It is getting its own branding and logos, so this section is its own source of truth.

- **Visual guide:** `sources/cmo-xyz-brand-guide.html` shows the approved logos, colour, type, mascot and usage rules.
- **Personality:** playful, smart, friendly.
- **Palette:** white, black and Iris Flower `#FF51FF`, in a white-led 60 / 30 / 10 balance.
- **Typefaces:** Dela Gothic One for headlines, PP Mori for body text.
- **UI/UX:** separate from Masumi and Sokosumi. CMO.XYZ's UI will be different, so the rules in Section 1.10 do not apply to it. Buttons and states are approved (Section 3.14). The rest of its UI/UX rules are **Open**.
- **Not inherited:** the Masumi logo rules (clearspace, spacing, partnerships in Section 1) do not apply to CMO.XYZ. It has its own clear space and minimum width (see Logo).

### 3.3 Logo (Locked)

**Primary logo:** `logos/cmo-xyz/SVG/cmo-xyz-lockup-mascot-top-outline-black.svg`, the go-to on white and Iris.

<img src="logos/cmo-xyz/SVG/cmo-xyz-lockup-mascot-top-outline-black.svg" width="320" alt="CMO.XYZ primary logo">

**Primary wordmark:** `logos/cmo-xyz/SVG/cmo-xyz-dela-sticker.svg`, the go-to on white.

**Primary icon:** the black-edge monogram on an Iris square. Use it for favicons, app icons and avatars. Ready-made files, from a 16 px favicon to a 512 px app icon, are in `logos/cmo-xyz/Favicon/`.

These rules come from the Logo Lineup and Logo Rules reviews. Use each logo only on the backgrounds, at the sizes and in the places listed. Sizes: L is heroes and posters, M is headers and posts, S is nav and avatars. Files in `logos/cmo-xyz/lockups/` and `logos/cmo-xyz/wordmark/` that are not listed here are not approved.

**Main logos.** First choice.

| Logo | File (`logos/cmo-xyz/SVG/`) | Backgrounds | Sizes | Use for |
|---|---|---|---|---|
| Mascot on top, outlined text, ground shadow | `cmo-xyz-lockup-mascot-top-outline-black.svg` | White (go-to), Iris (go-to), Photo or video* | L / M | site footer, slides, docs, merch, events, print |
| Stacked, outlined text, ground shadow | `cmo-xyz-lockup-stacked-text-outline-black.svg` | White (go-to), Iris (go-to), Photo or video* | M / S | app header, site header, site footer, social posts, email, slides, docs, merch, events, print |
| Wordmark, sticker outline | `cmo-xyz-dela-sticker.svg` | White (go-to), Iris, Photo or video* | M / S | app header, site header, site footer, social posts, ads, email, slides, docs, merch, events, print |

**Supporting logos.** Use when a main logo does not fit the background or layout.

| Logo | File (`logos/cmo-xyz/SVG/`) | Backgrounds | Sizes | Use for |
|---|---|---|---|---|
| Mascot on top, filled, Black lines | `cmo-xyz-lockup-mascot-top-filled-black-on-white.svg`<br>`cmo-xyz-lockup-mascot-top-filled-black-on-iris.svg` | White, Iris | L / M | email, slides, docs |
| Mascot on top, filled, Iris lines | `cmo-xyz-lockup-mascot-top-filled-iris-on-white.svg` | White | M | merch, events |
| Mascot on top, inverted, Iris | `cmo-xyz-lockup-mascot-top-inverted-iris-on-black.svg` | Black | L / M | social posts, slides, docs, merch, print |
| Stacked, filled, Black lines | `cmo-xyz-lockup-stacked-text-filled-black-on-white.svg`<br>`cmo-xyz-lockup-stacked-text-filled-black-on-iris.svg` | White, Iris | M / S | social posts, ads, email, slides, docs, print |
| Stacked, filled, Iris lines | `cmo-xyz-lockup-stacked-text-filled-iris-on-white.svg` | White | M / S | site footer, social posts, slides, docs, merch, events, print |
| Stacked, inverted, Iris | `cmo-xyz-lockup-stacked-text-inverted-iris-on-black.svg` | Black | M / S | landing hero, site footer, social posts, ads, email, slides, docs, merch, events, print |
| Stacked, inverted, White | `cmo-xyz-lockup-stacked-text-inverted-white-on-black.svg`<br>`cmo-xyz-lockup-stacked-text-inverted-white-on-iris.svg` | Black, Iris | M / S | social posts, ads, email, slides, docs, merch, events, print |
| Wordmark, black | `cmo-xyz-dela-black.svg` | White, Iris | M / S | site header, site footer, social posts, ads, email, slides, docs, merch, events, print |
| Wordmark, iris | `cmo-xyz-dela-iris.svg` | White | M / S | site footer, social posts, ads, email, slides, docs, merch, events, print |
| Wordmark, white | `cmo-xyz-dela-white.svg` | Black | M / S | site header, site footer, social posts, ads, email, slides, docs, merch, events, print |

**Small spaces.** Tight or tiny placements such as app icons.

| Logo | File (`logos/cmo-xyz/SVG/`) | Backgrounds | Sizes | Use for |
|---|---|---|---|---|
| Monogram, black edge (primary icon) | `cmo-xyz-lockup-monogram-black.svg` | Iris (go-to), Photo or video* | S | app icon, site footer, ads, email, slides, docs, merch, events, print |
| Monogram, iris edge | `cmo-xyz-lockup-monogram-iris.svg` | White, Black, Photo or video* | S | app icon, site footer, social posts, ads, email, slides, docs, merch, events, print |

**Special moments.** Campaigns, merch and launches.

| Logo | File (`logos/cmo-xyz/SVG/`) | Backgrounds | Sizes | Use for |
|---|---|---|---|---|
| Framed panel, black panel | `cmo-xyz-lockup-framed-black.svg` | White | M / S | site footer, social posts, ads, docs, merch, events, print |
| Framed panel, see-through panel (experimental, review before each use) | `cmo-xyz-lockup-framed-clear-black.svg` | White, Iris, Photo or video* | M / S | site footer, social posts, ads, slides, docs, merch, events, print |
| Framed panel, white panel | `cmo-xyz-lockup-framed-white.svg` | Black | M / S | site footer, social posts, ads, slides, docs, merch, events, print |
| Knockout block, black block (use sparingly, character needs refinement) | `cmo-xyz-lockup-block-black.svg` | White | M / S | site footer, social posts, ads, email, slides, docs, merch, events, print |
| Knockout block, white block (line work needs improving) | `cmo-xyz-lockup-block-white.svg` | Black | M / S | social posts, ads, slides, docs, merch, events, print |

**In reserve.** Approved, not in use yet.

| Logo | File (`logos/cmo-xyz/SVG/`) | Backgrounds | Sizes | Use for |
|---|---|---|---|---|
| Mascot on top, inverted, White | `cmo-xyz-lockup-mascot-top-inverted-white-on-black.svg`<br>`cmo-xyz-lockup-mascot-top-inverted-white-on-iris.svg` | Black, Iris | L / M | social posts, docs |
| Wordmark, sticker outline, Iris shadow (stroke needs adjusting) | `cmo-xyz-dela-iris-shadow-sticker.svg` | White, Black, Iris, Photo or video* | M / S | merch, events, print |

\* Photo or video placements need a review before each use.

- Do not recolor, stretch, rotate, or add effects to the logo files.
- Every approved file also has a transparent PNG, 3000 px wide, in `logos/cmo-xyz/PNG/`. Cut-out areas are see-through, so place each file on its approved background.
- The filled and inverted versions have one file per background. Use the file named for the background it sits on.
- The outline around Cuso is only for stickers, approved background images, the framed panel logos and the knockout block logos. On black, use the inverted, white versions (`cmo-xyz-lockup-stacked-text-inverted-white-on-black.svg`, `cmo-xyz-lockup-mascot-top-inverted-white-on-black.svg`), which have no outline.
- **Clear space (Approved):** 1x on every side, where x is the cap height of the C in the lockup's wordmark.
- **Minimum width (Approved):** mascot on top 120 px or 30 mm, mascot to the side (stacked, for horizontal spaces) 150 px or 40 mm, wordmark 80 px or 20 mm, monogram 24 px or 8 mm.

### 3.4 Product

A user registers, gives their domain, and the agent builds and runs the marketing strategy.

**In scope**
- Manages social media
- Creates and posts content
- Runs ads (Google and Meta)
- Handles website SEO
- Generates images and graphics

**Out of scope (roadmap)**
- Newsletter. It is not part of the current scope and must not be built or shown yet.

### 3.5 Primary users

- Solo founders
- Small businesses with no marketing team who want to put it on autopilot
- Builders

### 3.6 Agent naming

CMO.XYZ is the product name. The agent is called **Cuso**, the same name as the mascot.

- Every customer's agent is called Cuso. Customers can't rename it.
- Use "Cuso" wherever the agent is named, in the product, the marketing site and ads.

### 3.7 Voice and tone

These rules apply to all copy: onboarding, in-app messages, marketing site, ads, and error states.

1. **Reference data, not vibes.** Every claim the agent makes ties to actual data or prior context in view. Never invented confidence.
2. **Request missing information, do not hedge.** If the agent lacks something, it asks for it, framed as getting "better aligned". Never "I'm not sure" or "I think".
3. **Confidence comes from the analysis.** State the plain, obvious conclusion. No gimmicks, no performance, no forced cleverness.
4. **Light banter is fine.** Not stiff and corporate, not crude.
5. **Short sentences.** No rambling. Minimal fluff.
6. **Minimal to no em dashes or hyphens.**
7. **Banned words and phrases: none locked yet.** Flag anything that reads as hype or invented confidence for review.

Example responses from the current live build:

> "Here's my proposed strategy for you. Built from your setup answers and your shop data. I'll use it to guide every post, ad and email. Take a look, then I'll get started."

> "On it. I'll draft that now and put anything that needs approval in your Approvals. You'll get a note when it's ready."

### 3.8 Status

| Area | Status |
|---|---|
| Product and positioning | Locked |
| Voice and tone | Locked |
| Brand identity | Separate from the Masumi family, in progress |
| Typeface | Locked (Dela Gothic One, PP Mori) |
| Colors | Locked (white, black, Iris Flower) |
| Logo | Locked |
| Agent avatars | Open |
| Graphic language | Follows Section 1.9 |
| UI/UX rules (layout, elevation, shapes, components) | Open (separate from Section 1.10, will differ) |

Do not invent brand colors. Do not treat any current build or demo colors as final. If a placeholder is needed to keep building, use a neutral system default and flag it clearly as temporary in code and comments.

Application specs for the website, the app, and the print flier are TBD (Section 1.11.3).

### 3.9 Typography

Headlines use Dela Gothic One. Body text uses PP Mori. Use sentence case. PP Mori is a licensed font, so its files are not stored in this repo.

### 3.10 Color

CMO.XYZ brand work uses white `#FFFFFF`, black `#000000` and Iris Flower `#FF51FF`, balanced 60 / 30 / 10. Text on Iris Flower is black. The earlier exploration colors (coral, amber, cyan, blue, ink, and paper) are retired.

- Green is not a brand color. It is allowed for success states only (Section 1.10.2).
- CMO.XYZ leans on white surfaces, so it feels open and friendly.

### 3.11 Mascot and avatars

**Approved 2D mascot (Locked).** SVGs and transparent PNGs are in `Cuso 2D Mascot/`: 10 full-body poses, each with its variations. Use approved poses only, and always show the full body. Head-only expressions are not used. No gloves. Never stretch or recolor the mascot.

**Agent avatars (Open).** The earlier 3D profile pictures have been removed. Whether to make a new set from the approved 2D mascot is still to decide.

### 3.12 Graphic language

CMO.XYZ has no set graphic language. It follows Section 1.9: gradients and UI or product mockups, plus the mascot. The pixel treatment explored earlier is not adopted. Do not build permanent assets around it.

### 3.13 Do's and don'ts

- Do tie every claim the agent makes to actual data or prior context. Don't state anything with confidence that has no data behind it.
- Do ask for missing information, framed as getting "better aligned". Don't hedge with "I'm not sure" or "I think".
- Do call the agent Cuso everywhere. Don't offer a way to rename it, and don't use other names like "June".
- Do keep copy plain and short. Don't write long, rambling sentences or lean on em dashes and hyphens.
- Do use the approved logo files and the white, black and Iris Flower palette. Don't treat current demo colors as final.
- Don't build the newsletter. It is roadmap.

---

### 3.14 UI/UX rules (Buttons approved, rest Open)

CMO.XYZ's UI will be different from Masumi and Sokosumi, so the UI/UX rules in Section 1.10 do not apply to it. Buttons and states come from the CMO.XYZ dashboard and are approved. Layout, elevation, other components and tokens are **Open**.

Files are in `UI/`: `cmo-xyz-buttons.css` (styles), `cmo-xyz-buttons.html` (live demo, light and dark) and `cmo-xyz-buttons-and-states.png`.

![CMO.XYZ buttons and states](UI/cmo-xyz-buttons-and-states.png)

#### The Iris shadow

The Iris shadow means you can do something here. Every button that takes an action carries it. Press it and the button sinks into the shadow. Disabled buttons lose it.

Nav items and toggle chips pick things, they don't do things. So they skip the Iris shadow and show the selected state with an outline and a light tint.

#### Button types

| Type | Use | Iris shadow | Selected state |
|---|---|---|---|
| Primary | The main action, like "Sign and start" | Yes | Not used |
| Secondary | Other actions, like "Connect X" | Yes | Not used |
| Icon button | An action shown as an icon, like add | Yes | Not used |
| Nav item | Moving between pages | No | Outline and tint |
| Toggle chip | Turning a filter or option on and off | No | Outline and tint |

#### Spec

| Part | Light | Dark |
|---|---|---|
| Height | 40px, chips 32px | Same |
| Padding | 16px sides, nav and chips 12px, icon buttons 40 × 40 | Same |
| Corners | 6px radius | Same |
| Border | 1px black | 1px white at 45%, 70% on hover and selected |
| Background | White | #0E0E0E |
| Shadow | 3px 3px 0, Iris #FF51FF, no blur | Same |
| Label | Inter 14px, 600. Primary 700. Chips 13px, 500 | Same |
| Hover | #F2F2F2 tint | #1A1A1A tint |
| Pressed | Moves 3px down and right, shadow gone, #E6E6E6 | Same move, #262626 |
| Disabled | 35% opacity, no shadow | Same |

#### Rules

- Only buttons that take an action get the Iris shadow.
- Nav items and chips never get the shadow.
- Primary and secondary look the same. Primary has a bolder label.
- Pressing sinks the button into its shadow.
- Disabled buttons drop the shadow.

## Governance

- **Source of truth.** This file. Update it when a decision locks and change the status label.
- **Versioning.** Bump the version on every change.
- **Placeholders.** Anything temporary is marked as temporary in code and comments.
- **Assets.** Logo files, fonts, and mascot renders live in one shared location. The location is **Open**.
- **Owner.** Brand and marketing. The named owner is **Open**.

---

## In process

Work that is underway and not final. Do not treat any of it as locked. When an item locks, move it into its section and change its status.

| Item | What is happening | Brand | Status |
|---|---|---|---|
| Social media templates | First draft in progress: a 4:5 feed post for the Cuso launch. Format sizes, grid, and logo placement still to set (Section 1.11.3). Not in this repo yet | All | Working |
| Social post examples | One example per brand once the templates are set | All | TBD |
| Other templates | Flier (print), slide decks, email signatures, email and newsletter layouts, website page layouts, event and booth materials (Section 1.11.3). Build order is Open | All | TBD |
| CMO.XYZ UI/UX rules | CMO.XYZ's UI will be different from Masumi and Sokosumi. Its own rules still to write (Section 3) | CMO.XYZ | Open |
| Voice and tone | Masumi and Sokosumi voice is still to write (Section 1.11.5) | Masumi, Sokosumi | TBD |

---

## Open decisions

| # | Decision | Needed for | Status |
|---|---|---|---|
| 1 | Cuso background rules for CMO.XYZ | CMO.XYZ, mascot | Pending |
| 2 | Cuso agent avatars: whether to make a new set from the approved 2D mascot | CMO.XYZ | Open |
| 3 | Native mobile apps are planned. Confirm React Native Reusables as the UI library | Section 1.10.0 | Proposed |
| 4 | Icon set | UI/UX rules | Pending |
| 5 | How x is measured on every wordmark: Proposed as the height of the wordmark. Also the rule at exactly 30 px | Logo | Proposed |
| 6 | Print minimum size for the wordmark (screen minimum is 14px) | Logo | Open |
| 7 | Gradient and mockup rules | Section 1.9 | Open |
| 8 | Imagery and iconography rules: photography and stock, decorative grid, blur and glow, abstract art, and realistic AI generated images | Section 1.9, Section 1.11.1 | Open |
| 9 | AI generation rules: who approves a use, which countries and platforms require labels, how to label, and where prompts are recorded | Section 1.9 | Open |
| 10 | Motion rules | Section 1.11.2 | Open |
| 11 | Templates: confirm the list of template types in Section 1.11.3 and which to build first | Section 1.11.3 | Open |
| 12 | Social media post examples for each brand | Section 1.11.3 | Open |
| 13 | Partner and co-branding rules still to define: order and hierarchy, dividers, family co-branding, partner color, approval (size and spacing are in Section 1) | Section 1.11.4 | Open |
| 14 | Voice and tone for Masumi and Sokosumi (CMO.XYZ voice is locked in Section 3) | Section 1.11.5 | Open |
| 15 | Data visualization rules | Section 1.11.6 | Open |
| 16 | Asset location and named owner | Governance | Open |
| 17 | Wordmarks for Masumi Standard and Masumi Agent Wallet, if needed (Sokosumi and Marketing OS wordmarks are done) | All brands | Open |
| 18 | CMO.XYZ logo clear space and minimum width: confirm the proposed values | Section 3 | Approved 2026-11-24 |
| 19 | CMO.XYZ UI/UX rules. Its UI will differ from Section 1.10, so layout, shapes, components, and tokens need their own rules | Section 3 | Open |

---

## Resources

All paths are relative to this file. Keep this file and these folders together.

### Logos (`logos/`)

| Brand | File |
|---|---|
| Masumi | `logos/masumi/masumi-symbol.svg` |
| Masumi | `logos/masumi/masumi-logo-wordmark-black.svg` |
| Masumi | `logos/masumi/masumi-logo-wordmark-white.png` |
| Sokosumi | `logos/sokosumi/sokosumi-logo-wordmark-black.svg` |
| Sokosumi | `logos/sokosumi/sokosumi-logo-wordmark-white.svg` |
| Marketing OS | `logos/marketing-os/marketing-os-wordmark-black.svg` |
| Marketing OS | `logos/marketing-os/marketing-os-wordmark-white.svg` |
| CMO.XYZ | `logos/cmo-xyz/SVG/` (approved SVGs, see Section 3.3) |
| CMO.XYZ | `logos/cmo-xyz/PNG/` (approved transparent PNGs) |
| CMO.XYZ | `logos/cmo-xyz/Favicon/` (favicon and app icons, Iris background) |

### Slides (`Masumi Family Brand Guide Slides/`)

| Slide | File | Section |
|---|---|---|
| The Agentic family | `Masumi Family Brand Guide Slides/agentic-family-slide.png` | Overview |
| Logo clearspace, below 30 px | `Masumi Family Brand Guide Slides/logo-clearspace-below-30px.png` | 1, Logo clearspace |
| Logo clearspace, above 30 px | `Masumi Family Brand Guide Slides/logo-clearspace-above-30px.png` | 1, Logo clearspace |
| Spacing between logos | `Masumi Family Brand Guide Slides/logo-spacing.png` | 1, Logo spacing |
| Logo partnerships | `Masumi Family Brand Guide Slides/logo-partnerships.png` | 1, Logo partnerships |
| Color palette | `Masumi Family Brand Guide Slides/color-palette-slide.png` | 1, Color |
| Typography title | `Masumi Family Brand Guide Slides/typography-slide-01-title.png` | 1.10.3 |
| Typeface | `Masumi Family Brand Guide Slides/typography-slide-02-typeface.png` | 1.10.3 |
| Weights | `Masumi Family Brand Guide Slides/typography-slide-03-weights.png` | 1.10.3 |
| Typescale | `Masumi Family Brand Guide Slides/typography-slide-04-typescale.png` | 1.10.3 |
| Alignment, headlines | `Masumi Family Brand Guide Slides/typography-slide-05-alignment-headlines.png` | 1.10.3 |
| Alignment, paragraphs | `Masumi Family Brand Guide Slides/typography-slide-06-alignment-paragraphs.png` | 1.10.3 |
| Typography don'ts | `Masumi Family Brand Guide Slides/typography-slide-07-donts.png` | 1.10.3 |

### Cuso 2D mascot (`Cuso 2D Mascot/`)

| Folder | Contents | Section |
|---|---|---|
| `Cuso 2D Mascot/poses/` | 10 poses, each with 4 variations, as SVG and transparent PNG | 3 |

### UI (`UI/`)

| File | Contents | Section |
|---|---|---|
| `UI/cmo-xyz-buttons.css` | CMO.XYZ button styles, light and dark | 3.14 |
| `UI/cmo-xyz-buttons.html` | Live demo of every button and state | 3.14 |
| `UI/cmo-xyz-buttons-and-states.png` | Image of the demo | 3.14 |

### Editable sources (`sources/`)

| File | Makes |
|---|---|
| `sources/agentic-family-slide.html` | The Agentic family slide |
| `sources/logo-clearspace-slide.html` | Clearspace slides (add `#1` for 1x, `#2` for 2x) |
| `sources/logo-spacing-slide.html` | Spacing slide |
| `sources/logo-partnerships-slide.html` | Partnerships slide |
| `sources/typography-slides.html` | Typography slides (add `#1` to `#7`) |

### External references

- shadcn/ui and Kibo UI: see Section 1.10.0.
- Original Agentic brand guidelines (PDF): the source of the NMKR partner example and the original logo rules.
