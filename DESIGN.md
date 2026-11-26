---
version: 0.1
name: AnnaWorks Studio — warniaku.github.io
colors:
  primary: "#ED7518"   # orange Garis Spark (logo accent)
  accent: "#E07B39"    # orange caption/highlight family
  navy: "#0A2054"      # brand navy (logo background, headings)
  ink: "#14213D"
  paper: "#FFFFFF"
  muted: "#5A6B84"
typography:
  fontFamily: "\"Optimistic AI VF\", system-ui, -apple-system, 'Segoe UI', sans-serif"
  headlineWeight: 700
  bodySize: 16px
  lineHeight: 1.55
radius:
  card: 18px
  button: 999px
spacing:
  section: 64px
  cardGap: 20px
---

# AnnaWorks Studio — Design Rules

Rules for warniaku.github.io and any AnnaWorks Studio landing page. Follow these
before inventing new styles.

## Brand

- Logo: "Garis Spark" — one continuous orange line forming A→W with a
  four-point AI spark, on navy. Master file lives in the studio goal files.
- Voice: warm, concrete, proof-first. Show real work (embedded videos),
  no stock-photo filler, no purple gradients, no generic AI look.

## Color usage

- Navy `#0A2054` for headers, hero background and footer.
- Orange `#ED7518` only for calls-to-action, the spark, and one highlight
  per section. `#E07B39` is the softer sibling for captions/highlights.
- Body text ink `#14213D` on white; secondary text muted `#5A6B84`.
- Never introduce a new hue without updating this file first.

## Layout

- One column, max content width 960px, generous whitespace.
- Sections separated by 64px; cards have 18px radius and a soft shadow.
- Every service section ends with exactly one CTA (email or Telegram).
  The owner's personal WhatsApp number is never published on the site.

## Media

- Portfolio videos are embedded from YouTube (unlisted is fine for
  not-yet-aired samples); never commit raw MP4 files to the repo.
- Images: real screenshots/photos of our work first; generated images must
  match the brand colors above.

## Accessibility

- Text contrast at least 4.5:1 against its background.
- Buttons and links keep a visible focus state.
- Videos always carry captions in the video itself.
