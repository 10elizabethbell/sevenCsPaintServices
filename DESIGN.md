---
name: Seven C's Paint Services LLC
description: Toms River homes, painted right. A calm navy-and-paper one-pager for a family painting company.
colors:
  brass: "#e8b04a"
  brass-light: "#f0c26a"
  brass-ink: "#7d5612"
  ink: "#06204e"
  deep-navy: "#06204e"
  navy: "#183a72"
  paper: "#f4f6fb"
  light-band: "#e9eef6"
  card: "#ffffff"
  field: "#e6ecf5"
  body: "#25334d"
  soft: "#4b5872"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c8d4e8"
  line: "rgba(6,32,78,.12)"
  focus: "#1f5fbf"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 6vw, 28px)"
    fontWeight: 400
    lineHeight: 1.15
  title-sm:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.03em"
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  tag: "6px"
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter-mobile: "20px"
  gutter-desktop: "40px"
  section-mobile: "64px"
  section-desktop: "96px"
  stack: "16px"
  form-gap: "20px"
  column-gap: "64px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.brass}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.brass-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-soft:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "56px"
  input-text:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  photo-tag:
    backgroundColor: "rgba(6,32,78,.72)"
    textColor: "{colors.card}"
    typography: "{typography.label}"
    rounded: "{rounded.tag}"
    padding: "7px 10px"
  arrow-disc:
    backgroundColor: "rgba(255,255,255,.1)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    size: "44px"
  step-disc:
    backgroundColor: "{colors.brass}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-circle:
    backgroundColor: "{colors.brass}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Seven C's Paint Services LLC

## Overview

**Creative North Star: "The Harbour Logbook"**

The system is the logo's nautical navy laid out in calm horizontal bands: off-white paper, a pale blue-grey band, a mid navy band and a deep navy band carrying a faint diagonal line texture. Each band holds one idea, set in Cal Sans headings over a plain system body. One warm brass accent does all the pointing: it fills the primary button, the slider knob and divider, the step numbers and the floating text circle, and it never sits on a large surface. Real photography carries the craft (the hero is the client's own freshly painted blue wall under a navy wash, and the work band shows their before/afters); the chrome around it stays quiet.

Density is low and phone-first. Content stacks in a single 20px-gutter column with generous 64px band padding and only splits into two or three columns from 1024px. Forms are soft: rounded 24px cards, pill buttons, pill chips, 10px fields filled rather than outlined. Motion is short and purposeful: the hero headline's letters bounce in once, below-the-fold blocks rise 12px as they arrive, and the floating text circle slides up after the hero. All of it switches off under reduced motion.

**Key Characteristics:**
- Full-bleed colour bands alternating light (paper, light band) and dark (navy, deep navy); no borders between them.
- One brass accent, used as a fill; brass as text only in its darkened ink form on light ground.
- Cal Sans at weight 400 for every heading, label, button and row; system sans for running text.
- Pills, circles and 24px cards; no sharp corners on interactive elements.
- Flat surfaces; the only shadows sit under the two floating brass discs.
- A distinct focus blue for keyboard and form-hover states, kept apart from the brass fill.

## Colors

A cool navy-and-paper palette with a single warm brass accent.

### Primary
- **Harbour Brass** (brass): the action colour. Fills the primary button, before/after knob and divider, numbered step discs, the floating text circle, arrow discs on hover, the selection highlight and the dot inside eyebrows. Text on it is always Logo Navy.
- **Polished Brass** (brass-light): hover fill of the primary button only.
- **Brass Ink** (brass-ink): brass darkened to about 6:1 on paper, for brass used as text or line icons on light ground (the accent phrase, the header phone icon, trust-list icons, header phone hover).

### Neutral
- **Logo Navy** (ink): the logo's navy. Every heading on light ground, text on brass, the selected chip fill and the Facebook link banner.
- **Deep Navy** (deep-navy): same hue as Logo Navy, used as a surface: the hero base, the "how it works" band and the footer, both of the latter with the diagonal line texture.
- **Mid Navy** (navy): the services and close bands; also the text caret in fields.
- **Paper** (paper): page ground, header, trust and form bands; also the browser theme colour.
- **Light Band** (light-band): the work band, one step cooler and darker than paper.
- **White Card** (card): the form card surface and text on photos and selected chips.
- **Field Blue** (field): input, chip and soft-button fill on the white card; also the placeholder behind loading photos.
- **Body Slate** (body): running text on light bands.
- **Soft Slate** (soft): ledes, hints, placeholders and helper text on light bands.
- **Sea Mist** (on-dark): headings and primary text on navy bands.
- **Soft Mist** (on-dark-soft): running text on navy bands.
- **Hairline** (line): 1px dividers between list rows on light ground; on navy the equivalent is white at 14%.
- **Focus Blue** (focus): focus outlines, field borders on focus and hover, and the hover outline on form buttons. On navy bands, the hero and the footer, focus outlines switch to brass.
- **Error Red** (error): the invalid field border and its message.

### Named Rules
**The Brass Is a Fill Rule.** Brass appears as a fill on small elements (buttons, discs, the slider divider), never as a band or card background, and never as text on light ground; for text on light ground use Brass Ink.

**The Two Signals Rule.** Brass means "act here"; Focus Blue means "you are here". Keyboard focus and form hover use Focus Blue on light ground so a focused brass button stays readable.

**The Dark-Band Accent Rule.** A heading's last phrase may take the accent ("What we *paint.*", "How it *works.*") only on dark grounds: the hero, navy and deep navy bands. Headings on light bands stay all Logo Navy.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** Cal Sans gives the headings a round, friendly geometric weight; the system body keeps running text fast and familiar on the Facebook in-app browser. Cal Sans is only ever set at 400 and also carries the "spoken" UI: buttons, field labels, service rows, the phone number.

### Hierarchy
- **Display** (400, clamp 42 to 80px, 1.02): the hero H1 only, in white, max 11ch on phone and 14ch on desktop.
- **Headline** (400, clamp 30 to 48px, 1.08): section H2s, balanced wrapping.
- **Title** (400, clamp 20 to 28px, 1.15): service rows and trust claims; the Facebook banner and step titles sit at its low end (19 to 22px). The close band's phone number is the one oversize exception (clamp 30 to 52px).
- **Title small** (400, 18px, 1.2): buttons, field labels and legends, the header phone (17px, 20px on desktop).
- **Lede** (system, clamp 17 to 19px): section introductions, max 40ch, in Soft Slate (Soft Mist on navy). The hero promise is the same role at 17 to 20px, line height 1.5, max 32ch.
- **Body** (system, 16px, 1.7): running text and field input text (16px keeps iOS from zooming).
- **Small** (system, 14px): hints, helper text, the "opens your messages" note, error text.
- **Label** (system, 600, 13px, +0.03em): Before / After photo tags.

### Named Rules
**The One Weight Rule.** Cal Sans is set at 400 everywhere; emphasis comes from size and colour, not boldness. The only bold in the system is a 600 system-sans phrase inside the hero promise.

## Layout

A single centred container (max 1160px) with a 20px gutter on phone and 40px from 760px. Every section is a full-bleed band with 64px vertical padding, 96px from 760px. Section heads are a left-aligned stack (16px gap, max 640px). Content is left-aligned throughout; nothing is centred.

Breakpoints: below 380px chips tighten their padding; from 760px the hero buttons sit in a row (min 240px each), services become two columns (48px gap) and the gutter widens; from 1024px trust and form bands split into two columns (64px gap), the form band's heading becomes sticky, the work band becomes a 1.35fr / 1fr grid (slider and Facebook banner left, the den pair right), the three steps sit in a row and the close band puts the big phone number at the bottom right.

The header is a plain paper bar (76px tall, 88px on desktop) with the logo left and the tap-to-call number right; it is not sticky. The footer leaves 96px at the bottom so the floating circle never covers its links.

**The Phone-First Rule.** Design every band as a single column first; add columns only at 760px and 1024px.

## Elevation & Depth

Flat by default. Depth comes from the band sequence (light, dark, light) and from photography with a navy gradient wash, not from shadows. Cards sit on bands as flat colour. Exactly two elements cast shadows, both brass discs that float over content.

### Shadow Vocabulary
- **Knob lift** (`box-shadow: 0 6px 18px rgba(6,32,78,.3)`): the before/after slider knob, so it reads above the photo.
- **Float lift** (`box-shadow: 0 10px 28px rgba(6,24,56,.3)`): the fixed floating text circle.

### Named Rules
**The Only Floaters Cast Shadows Rule.** A shadow means the element floats over other content. Cards, buttons, chips and bands stay flat.

## Shapes

Soft and round. Large containers use 24px corners (the form card, the before/after slider); the den photo tiles use 18px and the Facebook banner 20px, slightly tighter because they are smaller. Fields use 10px; photo tags 6px. Every button, chip and eyebrow is a full pill, and every icon holder (arrow discs, step numbers, the knob, the floating circle) is a perfect circle. Borders are rare: 1px hairlines separate list rows, and 2px transparent borders on buttons, chips and fields exist so hover and focus can colour them without shifting layout. The deep bands carry a faint 135-degree line texture (1px white at 3.5% every 23px), the one surface pattern in the system.

## Components

### Buttons
Confident, round, thumb-sized.
- **Shape:** full pill, min height 56px, Cal Sans 18px, optional 20px leading icon.
- **Primary:** Harbour Brass fill, Logo Navy text. Hover (real pointers only) lifts to Polished Brass; inside the form the hover is a Focus Blue outline instead. Press scales to 0.98.
- **Ghost:** transparent with a 70% Sea Mist 2px border, for the secondary action on dark grounds; hover goes to a white border and a 10% white wash.
- **Soft:** Field Blue fill, Logo Navy text, 17px, used for the paired fallback actions after the form is sent; hover shows the Focus Blue outline.
- **Focus:** 3px outline, 3px offset; Focus Blue on light, brass on dark.

### Chips
- **Style:** pill, 48px tall, Field Blue fill, system 16px Logo Navy text, wrapping row with 10px gaps. They are visually hidden checkboxes with styled labels.
- **State:** selected turns Logo Navy with white text; hover shows a Focus Blue border; keyboard focus a Focus Blue outline.

### Cards / Containers
- **Form card:** White Card on Paper, 24px corners, padding 20 to 32px, 20px gap between fields, max 600px.
- **Link banner:** Logo Navy block, 20px corners, min 80px tall, Cal Sans text with a brass icon left and an arrow disc right.
- **Shadow strategy:** none (see Elevation & Depth).

### Inputs / Fields
- **Style:** Field Blue fill, 2px transparent border, 10px corners, min 52px tall (textareas 120px), system 16px Logo Navy text, Soft Slate placeholder, Cal Sans 18px label above with an optional 14px "(optional)" note.
- **Focus / hover:** border turns Focus Blue; no glow.
- **Error:** border and a 14px message in Error Red, cleared as soon as the field has a value.

### Navigation
There is no nav menu. The header holds the logo and a tap-to-call number (Cal Sans, Brass Ink phone icon, hover to Brass Ink). Footer links are 44px-tall Sea Mist text that turns brass on hover.

### Link Rows
Services are a list of full-width links on a navy band: Cal Sans 22 to 28px, 76px tall, separated by 14% white hairlines, each ending in a 44px arrow disc. The row itself never changes; only the disc turns brass on hover or focus. Tapping a row pre-ticks the matching chip in the form.

### Before/After Slider
The signature component. A 24px-cornered photo with the "before" image clipped to a moving edge, a 3px brass divider and a 48px brass knob with a double-chevron icon and the knob lift shadow. Before / After tags sit in the top corners and fade out as the divider passes them. It drags sideways with a mouse or a horizontal touch (vertical scrolling still works), moves to a tapped point, and the knob is a keyboard slider (arrows 5%, Shift 20%, Home / End).

### Numbered Steps
An ordered list where each item has a 48px brass circle with its Cal Sans number, a Cal Sans 21px title in Sea Mist and a body line. One column on phone, three from 1024px.

### Floating Text Circle
A single 60px brass circle fixed 16px from the bottom-right safe area, holding a chat icon that opens a pre-written text. It slides up 120px into view (0.35s, cubic-bezier(.2,.8,.2,1)) once the hero has scrolled away, and steps aside while the form is on screen or while a row arrow, the banner arrow or the slider knob is in the bottom strip it covers.

### Motion
- **Letter bounce-in:** the hero H1 only. Each letter slides in from 50px right and fades in over 1s with a slight overshoot (cubic-bezier(.34,1.56,.64,1)), 20ms apart; afterwards the plain heading is restored so kerning and selection return. Runs only with JavaScript and without reduced motion.
- **Rise:** blocks that start below the first screen fade up 12px over 0.4s ease-out when they enter view. Anything visible at load never animates.
- **State transitions:** colours 0.15 to 0.2s; button press 0.12s.

**The Visible At Rest Rule.** Content is visible without JavaScript and under reduced motion; motion only ever adds an entrance, never gates content.

### Owner-exception element (not part of this system)
The build carries three small eyebrow pills (14px, with a brass dot) above the hero headline and two section headings. They are kept by Ellie's explicit house-style choice and recorded in HANDOFF.md as a conflict with the craft floor. This file does not adopt them as a component: new surfaces should not add more, and they must stay quiet (no arrow, no hover, no shadow, no brass fill).

## Do's and Don'ts

### Do:
- **Do** fill actions with Harbour Brass and set Logo Navy text on it.
- **Do** use Brass Ink, not brass, whenever the accent is text or a line icon on paper or the light band.
- **Do** alternate light and dark bands, and keep the diagonal line texture to deep navy bands.
- **Do** keep tap targets at least 44px (buttons 56px, chips 48px, rows 76px).
- **Do** gate hover styles behind a real pointer (`hover: hover`) so taps don't leave them stuck.
- **Do** switch focus outlines to brass on navy, hero and footer grounds.

### Don't:
- **Don't** use brass as a band, card or large background.
- **Don't** use Focus Blue as a decorative colour; it is reserved for focus and form hover.
- **Don't** add shadows to cards, buttons or bands; only floating discs cast them.
- **Don't** set Cal Sans bold or add a second display face.
- **Don't** add a sticky bottom bar; the floating circle is the one persistent action.
- **Don't** animate content that is visible on first load, beyond the hero letter bounce-in.
