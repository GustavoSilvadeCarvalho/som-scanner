---
name: Som Scanner
description: Download page for a free Windows tool that names mystery-cargo contents by sound, styled as a night-room tactical HUD.
colors:
  chao: "#0d0e0b"
  chao2: "#121410"
  painel: "#171a14"
  linha: "#2a2e25"
  linha2: "#3c4135"
  osso: "#e7e3d6"
  fraco: "#a3a294"
  ambar: "#f5a524"
  ambar2: "#ffbf47"
  ambar-deep: "#e0921a"
  tinta: "#16120a"
  alert-ground: "#1d1a10"
  alert-edge: "#5a4716"
  alert-text: "#f1d79a"
  alert-strong: "#fff1cc"
  rarity-common: "#b4b9c4"
  rarity-uncommon: "#58d36c"
  rarity-rare: "#4ea8ff"
  rarity-epic: "#b875ff"
  rarity-legendary: "#ffb534"
  rarity-mythic: "#ff5252"
typography:
  display:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(46px, 6.2vw, 92px)"
    fontWeight: 800
    lineHeight: 0.93
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "clamp(34px, 4.2vw, 54px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "0.02em"
  numeral:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "72px"
    fontWeight: 800
    lineHeight: 1
    fontFeature: "tnum"
  body:
    fontFamily: "Barlow, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  body-lead:
    fontFamily: "Barlow, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(17px, 1.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "14px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.12em"
  label-small:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.16em"
  button:
    fontFamily: "Saira Condensed, Arial Narrow, sans-serif"
    fontSize: "21px"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.06em"
rounded:
  none: "0px"
  chamfer: "14px"
spacing:
  gutter-mobile: "20px"
  gutter: "28px"
  container: "1200px"
  section: "104px"
  section-tablet: "80px"
  block: "48px"
components:
  button-primary:
    backgroundColor: "{colors.ambar}"
    textColor: "{colors.tinta}"
    typography: "{typography.button}"
    rounded: "{rounded.chamfer}"
    padding: "20px 34px 20px 30px"
  button-primary-hover:
    backgroundColor: "{colors.ambar2}"
  button-primary-active:
    backgroundColor: "{colors.ambar-deep}"
  scanner-panel:
    backgroundColor: "{colors.painel}"
    textColor: "{colors.osso}"
    rounded: "{rounded.none}"
    padding: "22px 24px 20px"
  rarity-tag:
    typography: "{typography.label}"
    rounded: "{rounded.none}"
  header:
    backgroundColor: "{colors.chao}"
    textColor: "{colors.osso}"
    height: "60px"
  alert-callout:
    backgroundColor: "{colors.alert-ground}"
    textColor: "{colors.alert-text}"
    rounded: "{rounded.none}"
    padding: "20px 24px"
---

# Design System: Som Scanner

## Overview

**Creative North Star: "The Night-Room Tactical HUD"**

The page reads like an operator's heads-up display seen in a dark room: a near-black, olive-tinted ground, bone-coloured text, and a single brand amber that marks everything you can act on or should look at. Structure comes from hairline steel rules, not boxes or cards. Evidence (the live scanner panel, the real app screenshot) is framed by amber corner brackets, as if a targeting reticle had locked onto it. Actions are chamfered plates. A faint fractal grain sits over everything so the dark never reads as flat digital black.

Density is moderate and calm: big condensed uppercase headlines, generous section padding (104px), and body copy in a humanist sans held to readable measures. The game's own vocabulary carries the colour story: the six rarity tiers appear only where the data is rarity data, so they keep the meaning they have in-game. The style bar is the official Arena Breakout Infinite site's tactical look, taken as style only, with no marks, logos, or game art.

The system rejects the generic dark-SaaS template: no glow halos, no emoji or icon tiles, no decorative chip rows, no gradient text.

**Key Characteristics:**
- Olive-black ground, bone text, amber as the sole interface accent.
- Rarity colours reserved for result data.
- Condensed uppercase display type over a humanist sans body; tracked condensed labels.
- Chamfered actions, corner-bracketed evidence, hairline rules, faint grain.
- Square geometry everywhere else; depth from tone, with one ambient shadow under the scanner panel.

## Colors

A nearly monochrome olive-black field with one hot amber voice and a reserved rarity spectrum.

### Primary
- **Brand Amber** (`ambar`): the only interface accent. Fills the primary button, colours the emphasised words of headlines, the step numerals, line icons, corner brackets, the status dot, the resolved waveform, selection highlight, caret and native control accents.
- **Hot Amber** (`ambar2`): the lighter interaction amber. Button hover, link colour, focus ring, FAQ summary hover, the "listen again" text button.
- **Pressed Amber** (`ambar-deep`): button active state only.
- **Amber Ink** (`tinta`): text on amber fills (button label, selection text). Never plain black.

### Neutral
- **Night Ground** (`chao`): page background, header (at 92% opacity with blur), theme colour.
- **Ground Raised** (`chao2`): reserved second ground step; defined, rarely used.
- **Panel Olive** (`painel`): the scanner panel and inline code chips. The one raised surface.
- **Steel Hairline** (`linha`): every 1px rule and border: header and section dividers, list rows, panel edge, screenshot edge, FAQ rows.
- **Steel Heavy** (`linha2`): the 2px top rule on steps, the idle waveform bars while listening, scrollbar thumb.
- **Bone** (`osso`): primary text and headings.
- **Faded Bone** (`fraco`): secondary text: subcopy, paragraph body under headings, labels, meta line, captions, footer.

### Rarity (data only)
- **Common** (`rarity-common`), **Uncommon** (`rarity-uncommon`), **Rare** (`rarity-rare`), **Epic** (`rarity-epic`), **Legendary** (`rarity-legendary`), **Mythic** (`rarity-mythic`): the game's six tiers. Used for rarity tags in item rows and for the match-confidence percentage (Uncommon green). Never for chrome, buttons, or decoration.

### Alert (warning callout only)
- **Alert Ground / Edge / Text / Strong** (`alert-ground`, `alert-edge`, `alert-text`, `alert-strong`): an amber-steeped dark plate for the SmartScreen warning. Used once; extend only for genuine warnings.

### Named Rules
**The One Voice Rule.** Amber is the only interface accent. If something is interactive, emphasised, or a framing device, it is amber; nothing else gets a hue.

**The Rarity Is Data Rule.** Rarity colours appear only on result data (rarity tags, match confidence). A rarity hue on a button, border, or heading is a bug.

**The Amber Ink Rule.** Text on an amber fill is `tinta`, never `#000` or white.

## Typography

**Display Font:** Saira Condensed 600/700/800 (with Arial Narrow, sans-serif), self-hosted.
**Body Font:** Barlow 400/500/600 (with Segoe UI, system-ui, sans-serif), self-hosted.
**Label/Mono Font:** labels use Saira Condensed tracked uppercase; code uses Cascadia Mono / Consolas at 500.

**Character:** A tall, hard-edged condensed military face for everything that shouts or labels, against a plain-spoken humanist sans for everything you read.

### Hierarchy
- **Display** (800, clamp(46px, 6.2vw, 92px), 0.93, uppercase, balanced wrap): the hero H1 only. Emphasised phrase in amber.
- **Headline** (800, clamp(34px, 4.2vw, 54px), 1, uppercase): section H2s. A Faded Bone paragraph at 18px follows directly, 12px below.
- **Title** (700, 22-24px, 1.1-1.2, uppercase, +0.02em): feature titles, step titles, FAQ summaries. Match name in the panel at clamp(20px, 2vw, 26px), not uppercase.
- **Numeral** (800, 72px, tabular; 56px on mobile): step counters in amber; match percentage at clamp(38px, 3.6vw, 52px).
- **Body** (400, 17px, 1.6): running copy; lead at clamp(17px, 1.6vw, 20px). Measures held to 44-72ch (lead 44ch, features 46ch, FAQ 66ch, footer 72ch).
- **Label** (600, 13-14px, +0.12 to +0.16em, uppercase): header tagline, meta line under the CTA, figure captions, panel top bar. Rarity tags at 700, 14px, +0.1em.
- **Button** (800, 21px, +0.06em, uppercase).

### Named Rules
**The Condensed Shouts, Barlow Speaks Rule.** Uppercase belongs to Saira Condensed only. Barlow is always sentence case.

**The Tabular Numbers Rule.** Numerals that count or measure (steps, percentages, item sizes) use tabular figures.

## Layout

Single column of full-bleed bands separated by 1px Steel Hairline rules, content in a 1200px container with 28px gutters (20px under 560px). Sections pad 104px vertically (80px under 960px); the hero 72px/96px (48px/72px under 960px). The hero is a two-column grid (1.08fr / 1fr, 64px gap, centred) with copy left and the scanner panel right; it stacks under 960px. Feature lists are a 2-column grid divided by hairlines (vertical rule between columns, row rules between items), not cards. Steps are a 3-column grid with a 28px gap, stacking under 960px. Content blocks sit 40-56px below their section heading. The closing CTA band is left-aligned, heading and button split with space-between. Under 560px the primary button goes full width and item rows drop the rarity tag to a second line.

The header is sticky, 60px, with a hairline bottom rule, 92% Night Ground and an 8px backdrop blur.

## Elevation & Depth

Flat and tonal. Depth comes from the Panel Olive surface stepping up from Night Ground and from hairline rules. Exactly one shadow exists, ambient and soft, under the scanner panel to lift the signature evidence off the page. A fixed grain overlay (fractal noise SVG, 5% opacity, above content, non-interactive) gives the whole page a material tooth.

### Shadow Vocabulary
- **Panel lift** (`box-shadow: 0 30px 60px -20px rgba(0,0,0,.7)`): the scanner panel only.

### Named Rules
**The Rules Not Boxes Rule.** Group with hairline rules and spacing. A filled, bordered container is reserved for the scanner panel, the warning callout, and code chips.

**The No Glow Rule.** No glows, halos, or coloured shadows. Amber sits flat.

## Shapes

Square by default: no border radius on surfaces, buttons, images, or rules. Two signature silhouettes carry the world:

- **Chamfer** (14px): the primary button is a plate with the top-left and bottom-right corners cut at 45 degrees (clip-path polygon on a pseudo-element behind the label).
- **Corner brackets**: amber L-marks (22px arms, 2px stroke) set 7px outside the four corners of framed evidence: the scanner panel and the app screenshot.

Small geometric marks: rarity tags carry an 8px diamond (a square rotated 45 degrees) in the tag colour; the status indicator is the one round element, an 8px dot. Icons are inline SVG line drawings, 2px stroke, square caps, in amber.

## Components

### Buttons
Heavy and decisive: an amber plate with cut corners.
- **Shape:** chamfered plate (14px cuts, top-left and bottom-right), otherwise square.
- **Primary:** Brand Amber fill, Amber Ink label, Button type, 20px 34px 20px 30px padding, a 22px download line icon left of the label with a 12px gap.
- **Hover / Active:** fill shifts to Hot Amber, then Pressed Amber, 150ms ease-out colour transition; no movement.
- **Focus:** 2px Hot Amber outline, 4px offset (global).
- **Meta line:** a Faded Bone tracked label (14px, +0.12em, uppercase) sits beside or beneath the button stating price, platform and version.
- **Text button:** the in-panel "listen again" action is Hot Amber, underlined (4px offset), inheriting the label type; hover turns Bone.

### Cards / Containers
There are no cards. Features are hairline-divided grid cells (44px icon column, 36px amber line icon, Title, Faded Bone body). Steps are open columns topped with a 2px Steel Heavy rule, a 72px amber numeral, a Title and Faded Bone text.

### Warning Callout
- **Style:** Alert Ground fill, 1px Alert Edge border, Alert Text copy with Alert Strong for emphasised words, 20px 24px padding, square.
- **Icon:** 26px amber line warning triangle at the leading edge.

### Disclosure (FAQ)
- **Style:** stacked rows divided by hairlines, max 820px wide. Summary in Title type, 22px vertical padding, a 20px amber plus icon at the trailing edge.
- **State:** hover turns the summary Hot Amber; open rotates the plus 45 degrees into an x (250ms, cubic-bezier(.16,1,.3,1)). Answer in Faded Bone, 66ch.

### Navigation
A slim sticky header: 30px app icon, the wordmark in Saira Condensed 700 19px at +0.12em, and the game name as a right-aligned Faded Bone label. No menu.

### Scanner Panel (signature)
The product demonstration, built from real capture data.
- **Frame:** Panel Olive, 1px Steel Hairline border, 22px 24px 20px padding (18px 16px on mobile), panel-lift shadow, amber corner brackets.
- **Top bar:** small label row: product name left, status right (8px amber dot plus state word in Bone).
- **Waveform:** a 72px band between hairlines, 40 vertical bars with 3px gaps, heights set per bar.
- **Match:** match name in Title type with a Faded Bone item count, confidence percentage at numeral scale in Uncommon green, tabular.
- **Item rows:** grid of name / size (Faded Bone, tabular) / rarity tag (108px), 10px vertical padding, hairline-divided.
- **Listening state:** bars go Steel Heavy and oscillate (scaleY .25 to 1.05, 0.9s ease-in-out alternate, phase offset per bar); the dot blinks in two hard steps (1s); the match line dims to 18%; rows hide and drop 6px.
- **Resolved state:** bars settle amber (500ms, cubic-bezier(.16,1,.3,1)); the match fades in (350ms); rows reveal in rarity order, staggered 90ms each.
- **Fallback:** without JS or under reduced motion the panel shows the resolved state, fully visible and static.

## Do's and Don'ts

### Do:
- **Do** keep amber the only interface hue: actions, emphasis, icons, brackets, focus.
- **Do** frame real evidence (live demo, real screenshots) with amber corner brackets, 22px arms, 2px stroke, 7px outside.
- **Do** give primary actions the 14px chamfer and Amber Ink labels.
- **Do** divide content with 1px Steel Hairline rules instead of boxing it.
- **Do** set display, titles and labels in uppercase Saira Condensed; body in sentence-case Barlow.
- **Do** use the house ease (cubic-bezier(.16,1,.3,1)) for settling motion and short ease-out colour transitions (150-400ms).
- **Do** show the final, readable state with all animation and transitions off under prefers-reduced-motion.

### Don't:
- **Don't** use rarity colours for anything but rarity or result data.
- **Don't** round corners on surfaces, buttons or images; the status dot is the only round element.
- **Don't** add glows, halos, coloured shadows, or gradient text.
- **Don't** wrap features in cards or icon tiles; no emoji, no decorative chip rows.
- **Don't** put game marks, logos or game art on the page; the tactical style is borrowed, not the brand.
- **Don't** use corner brackets as generic decoration on text blocks; they mark evidence.
