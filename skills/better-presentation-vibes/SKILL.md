---
name: better-presentation-vibes
description: |
  Design principles for good presentation slides, distilled from hands-on deck
  building with AI. Use when creating, reviewing, auditing, or fixing slides or
  presentation decks (HTML decks, slide frameworks, AI-generated slide layouts),
  when generating slide content or images for decks, or when the user mentions
  slide design, presentation antipatterns, or clip art.
metadata:
  tags:
    - presentations
    - slide-design
    - decks
    - ai-generated-content
    - antipatterns
    - design-review
  category: design
---

# Good Presentation Design: Care & Craft

Think of every generated slide as a draft that must
pass a **visual test harness**. You just have to care — and caring means
checking the output before anyone else sees it.

## Why it matters

1. **Demonstrating that you care is good.** Virtue signaling is good, actually.
   A cared-for deck signals respect for the audience.
2. **Don't undermine the impression you already made.** People walk in assuming
   competence; sloppy slides spend that capital.
3. **Most importantly: nothing on a slide should distract from the message.**
   Every stray element competes with the one thing you came to say.

## The canon is already in the weights

These principles are established, and the models have read all of them:

- **CRAP** — Contrast, Repetition, Alignment, Proximity
  (designlab.wisc.edu/resources/design-tips-and-tricks/crap-principles/)
- **Presentation Zen** (Garr Reynolds) — restraint, simplicity, one idea per slide
- **slide:ology** (Nancy Duarte) — audience, message, visual story

Your job isn't to teach the model design — it's to **check the work**.

## The visual test harness

After generating any slide, check it against this list. Every item is fixable
by you, and most fixes are cheap.

### 1. AI images: don't add images for the sake of images

- Generated images that are just a bit "off" (wrong hands, gibberish text) read
  as psychological horror. If the image feels fake, everything near it starts
  to feel fake too.
- An image that distracts — or that the audience starts analyzing instead of
  reading — undermines the point it was meant to support.
- Default: no image unless it carries the message.

### 2. Redundant decoration

- Bullets + numbers + icons + borders + a different accent color for every item
  in a list = five signals where one would do. Each extra layer of decoration
  is another thing the eye triages before it reaches the words.
- Also: excessive borders — borders on the card, the page, the column, the
  image. One container signal is enough.

### 3. "Navigation" that isn't

- Real navigation has a purpose: **table of contents + you are here**, ideally
  consistent across the entire deck.
- Watch out for "nav" that is really just subtitles in a nav-like location — a
  breadcrumb reading *Introduction > Background > Methods* is a heading wearing
  a costume.
- If it doesn't orient, it's decoration. Move it, shrink it, or cut it.

### 4. Small-print asides

- Small explanatory sentences under a headline, subtitles in a smaller font,
  footnoted qualifiers. **Small text still gets read** — the whisper pulls
  attention away from the headline.
- It signals you didn't finish the thought: if the qualifier matters, it
  belongs in the statement itself.
- It drains hierarchy: when every statement ships with a caption, nothing reads
  as the headline anymore.
- Fix: say it once, say it big. Fold the qualifier into the full-size statement
  or cut it.

### 5. Old mistakes creeping back

- **Text too small.** If someone in row 30 can't read it, it doesn't matter how
  clever it is. Design for the back of the room.
- **Too much content on a slide.** Dense paragraphs, 11-point body text, and a
  figure crammed into a corner were bad in 2003 and are bad now. Nothing in the
  prompt said "legible from 20 meters" — say it yourself.

### 6. Smaller common mistakes

- **Text overlap** — creeps in when a design is generated on a fixed grid and
  the text is edited later. Swap one line for two and the layout never gets
  told. Re-check spacing after any text edit.
- **Icon misalignment** — there is no single alignment rule; it's contextual:
  - One-line label: center the icon optically on the **cap-height** of the
    text, not the line box (box-centering reads low).
  - Multi-line label: **top-align** the icon with the first line — never
    block-center, which floats the icon between lines.
- Both are easy to spot and easy to fix — if you look.

## Craft conventions that hold a deck together

Learned the hard way while building and iterating on a real deck:

- **One idea per slide.** When a slide lists three parallel points, give each
  point its own slide at full size. A list slide is acceptable for an agenda or
  recap, not for the argument itself.
- **Statements, not captions.** Body text is either a full-size statement or it
  doesn't exist. No whisper lines, no asterisks, no explanatory asides.
- **Consistent headings.** Section labels (e.g. "Antipatterns") sit in the same
  spot on every slide in the section, in the same style — big enough to be a
  heading, not a caption. Headings are noun phrases; drop the periods.
- **Demos should be minimal and bold.** A visual example of an antipattern
  (a wireframe of lines and boxes, a misaligned icon pair, an intentionally
  tiny paragraph) beats a paragraph describing it. Keep demos abstract enough
  to be unmistakable, and label the wrong/right explicitly when the difference
  is subtle.

## Fix order

When auditing a generated deck, sweep in this order — cheapest, most visible
fixes first:

1. Small-print asides → fold or cut
2. Redundant decoration → remove signals until one remains
3. Text overlap / icon alignment → re-verify after any text edit
4. Font sizes / content volume → design for the back of the room
5. Images that are merely present → remove unless they carry the message
6. Pseudonav → demote to headings or promote to real navigation
