# lissom — keramikk & håndverk

Design system for **lissom**, a ceramics workshop and studio. Lissom runs courses in
**dreiing** (wheel throwing), **plateteknikk** (slab building) and **paint on pots**, plus
**datenights**, **medlemskap** (memberships) and **drop-in** sessions.

- Location on the printed material: Nordre Løkkevei 15, 3120 Nøtterøy (Teie, Nøtterøy)
- Web: lissom.no · Tel: +47 94 13 46 01 · monica@lissom.no
- Voice of the brand in one line, taken verbatim from the product card: *"100% HÅNDLAGET MED KJÆRLIGHET"*
- Positioning line from lissom.no: *"et kreativt fristed for skaperglede, håndverk og fellesskap"*
- Instagram: [@lissom_keramikk](https://www.instagram.com/lissom_keramikk/)

The brief for this system, in the owner's words: *"vi jobber med stemning, leire som er mye
naturtoner, mens selve logoen er gul og brun — skap et innbydende miljø."* The identity is
therefore two-layered: a loud yellow-and-brown mark sitting inside a quiet room of clay tones.

## Sources this system was built from

The printed identity, the vector logo and the studio photography came from the owner; the
language, the offer and the structure of the digital presence were read from **lissom.no** and the
three **understory.io** booking sites in August 2026. No codebase, Figma file
or website source was provided.

| File | What it gave us |
|---|---|
| `lissom-logo_full.pdf` | The full lockup — cup mark, wordmark, letterspaced descriptor |
| `lissom-mailLogo.png` | The lockup as used in e-mail signatures (transparent) |
| `SKILT.JPG` | Signage artwork — the yellow field, exact brand yellow, high-res wordmark and cup |
| `BREVARK.JPG` | Letterhead — address typography, letterspacing, small-caps/old-style figure treatment |
| `Lissom-Gavekort-KURS_200x100_rev2.pdf` | Gift card, both sides — the wavy die-cut edge, oversized cup crop |
| `Lissom-kort.pdf` | Product care card — the ornament rule, the "håndlaget med kjærlighet" line, `WWW.LISSOM.NO` |
| `logo.png` | A hand-drawn heart used alongside the kjærlighet line |
| `logo-lissom-full.svg`, `logo-lissom-wordmark.svg` | **The vector master.** Full lockup and wordmark, supplied later in the process — these are now the logo of record |
| Four studio photographs | Courses in progress, the workshop interior, Monica at the wheel, and a portrait |
| `LISSOMKOPP.AI`, `lissom-logo.eps` | Referenced in the brief but never arrived — superseded by the SVG master above |

Copies live in `assets/reference/`. `assets/reference/print-sheets.png` is a contact sheet of all
four printed pieces rendered together — the fastest way to see the brand as it actually exists.

## Content fundamentals

**Language is Norwegian (bokmål).** English appears only where the craft itself uses it — *paint on
pots*, *drop-in*, *datenight* are left untranslated because that is what the studio calls them.

**Address the reader as *du*, speak as *vi*.** "Hos oss får **du** hendene i leira." "**Vi** holder
kurs i dreiing." Never *De*, never a passive institutional voice, never first-person singular.

**Plain, warm, matter-of-fact.** The printed cards say what a thing is and what it costs, then
stop. *"Dette produktet er matsikret og kan vaskes i oppvaskmaskin."* No adjectives are spent on
atmosphere; the atmosphere comes from the colour and the material, not the copy.

**Invitation, not persuasion.** The strongest line on any printed piece is a question followed by
an instruction: *"Vil du prøve keramikk? Spør oss om kurs!"* Copy invites; it does not sell, urge,
or count down. Scarcity is stated as fact ("2 plasser igjen"), never as pressure.

**Casing.** Three registers, and they are not interchangeable:
1. **lowercase** — the wordmark, always. `lissom`, never `Lissom` in a logo position. **In running
   prose the name is capitalised: *Lissom*.** The lowercase form belongs to the mark, not the
   sentence — lissom.no writes "Velkommen til Lissom", "Hos Lissom handler keramikk om mer enn
   leire". Full legal name: *Lissom Keramikk & Håndverk AS*.
2. **LETTERSPACED CAPS** — labels, descriptors, addresses, buttons, eyebrows, section kickers.
   `KERAMIKK & HÅNDVERK`, `100% HÅNDLAGET MED KJÆRLIGHET`, `NORDRE LØKKEVEI 15`. Tracking is wide
   (0.14em), and wider still (0.2em) at the smallest sizes.
3. **Sentence case** — everything else. Headings included: *"Dreiing for nybegynnere"*, not
   *"Dreiing For Nybegynnere"*.

**Punctuation.** Exclamation marks are used, sparingly, and only on invitations (*Spør oss om
kurs!*). Ampersands are used in the descriptor (`KERAMIKK & HÅNDVERK`). Prices are written with a
space as thousands separator and a lowercase unit: `890 kr`, `1 190 kr`.

**Emoji: never in the letterspaced-caps voice, occasionally in the conversational one.** No
headline, label, button or piece of print uses one. In FAQ answers and Instagram captions Lissom
does use them, sparingly and warmly — the answer to *"Har dere kaffe?"* on lissom.no is
"Ja, alltid ☕🙂". Follow that: at most one or two, at the end of a sentence, never carrying
meaning on their own. The hand-drawn heart mark (`assets/mark-heart-brown.png`) remains the
brand's own pictographic warmth device, reserved for the *håndlaget med kjærlighet* line.

**Examples to imitate**

> Vil du prøve keramikk? Spør oss om kurs!
> 100% HÅNDLAGET MED KJÆRLIGHET
> Dette produktet er matsikret og kan vaskes i oppvaskmaskin.
> Gavekort · KAN KUN BENYTTES PÅ ET AV VÅRE KURS

**Examples to avoid**

> Opplev keramikkens magi — book din reise i dag! ✨
> Vi tilbyr et bredt spekter av skreddersydde keramikkopplevelser.
> KUN 2 PLASSER IGJEN!!! SIKRE DIN PLASS NÅ

## Digital surfaces

Lissom's presence is split across two systems, and the design system has to serve both:

| Surface | What it is | What you control |
|---|---|---|
| **lissom.no** | WordPress marketing site — front page, Om Lissom, Spørsmål og svar, personvern | Everything. This is where the design system applies fully. |
| **lissom-kurs.understory.io** | Booking of courses and workshops | Almost nothing. Understory owns the layout; you supply logo, cover image and copy. |
| **lissom-events.understory.io** | Date Night, Paint on Pots, Sip & Clay, private events | Same. |
| **lissom-medlemskap.understory.io** | Membership and *Prøv Lissom – 30 dager* | Same. |

**Every booking flow leaves the brand's own surface.** The website's job is to make the handover
feel deliberate: name the thing, state the price, then send the visitor to Understory. Do not
design fake booking UI on lissom.no that Understory will not honour — the checkout, the seat
counts and the confirmation e-mails are theirs. The booking screens in `ui_kits/` exist to
exercise the components, not to propose replacing Understory.

**Availability is written, not counted.** Understory shows *"Flere ledige tidspunkter"*, not
"2 plasser igjen". `CourseCard` takes a `status` string for this reason. Prices are quoted the
same way Understory quotes them: *Fra 1 490 kr*.

## The offer, as it stands

Written out because the words are fixed and the design system should not paraphrase them:

- **Kurs** — Nybegynner dreiekurs (fra 2 800 kr, 2 økter over 2 dager), Kurs boller (fra 1 490 kr),
  Store fat kurs (fra 1 490 kr), Keramikk Workshop (fra 1 490 kr)
- **Events** — Date Night, Paint on Pots, Sip & Clay, utdrikningslag, teambuilding, private events
- **Medlemskap** — Prøv Lissom – 30 dager (fra 390 kr) and full membership. Verkstedet is open
  24/7 while the membership is active; **a course or prior experience is required to join**
- **Drop-in** — only together with an active member, who must be present throughout. Includes
  clay, materials, firing and one finished piece up to 20 × 20 cm
- **Gavekort** — valid on courses, Paint on Pots, Date Night, Sip & Clay, membership and workshop time
- **Butikk** — a small shop by the workshop selling ceramics made by Monica and Joakim

Food safety has its own careful language on lissom.no and it should be reproduced, not simplified:
pieces intended for food are fired with approved glazes at the correct temperature; decorative
glazes and art objects are not necessarily food-safe, and that is stated when it applies.

## Visual foundations

### Colour

Two brand colours, sampled from the print artwork and used at full strength:

- **Lissom Gul `#FFCF38`** — the signage field. A saturated, slightly warm yellow. It is a
  *background*, not an accent: whole surfaces are yellow, and the brown sits on top of it.
- **Lissom Brun `#4D1D12`** — a deep red-leaning brown. Every mark, rule and letter in the printed
  identity is this one colour. It is the ink, the headline colour, and the outline colour.

Around those sits the **clay ramp** (`--clay-50` → `--clay-900`), a warm neutral ladder from
porcelain white through bisque, sand and dried clay down to stoneware. Backgrounds are almost
always `--clay-50` (`#FBF6EE`), never pure white — pure white is reserved for card surfaces so
cards read as paper lifted off the wall.

Three **glaze accents** carry semantic and editorial work: terracotta (`--terracotta-500`) for
eyebrows and links-on-hover, sage (`--sage-500`) for success and calm counterweight, slip
(`--slip-500`) for informational states. They are always desaturated relative to the brand yellow;
nothing in this system competes with the yellow for attention.

**Rule of thumb:** one yellow area per screen. Yellow marks the thing you want people to do.

Two theme scopes invert the whole palette: `[data-theme="ink"]` for full-bleed brown panels
(footers, hero bands, slides) and `[data-theme="sun"]` for yellow panels (posters, gift cards,
callouts). Set the attribute on a wrapper and every semantic token follows.

### Typography

The wordmark is a heavy Clarendon-style slab — bracketed serifs, ball terminals, very tight fit.
The letterhead sets its address lines in a warm humanist sans, letterspaced caps, with old-style
figures. Neither original font file was supplied, so the system substitutes (see Caveats):

- **Display — Bitter (700/800).** Slab serif, standing in for the wordmark's Clarendon. Used for
  every heading, price and hero line. Set tight: `--tracking-display: -0.02em`.
- **UI & body — Alegreya Sans (400/500/700).** Humanist, warm, slightly calligraphic. Used for
  running text, labels, buttons, navigation. `Alegreya Sans SC` covers small-caps needs.

Scale runs 12 → 92px on a roughly 1.25 ratio. Body copy is 17px at 1.65 line-height — generous, so
paragraphs feel unhurried. Prose is capped at `64ch`.

Never re-typeset the wordmark. Use `assets/wordmark-lissom-brown.png` or the `Logo` component.

### Layout and space

4px base step. Section rhythm is 96px vertical on desktop (`--section-y`), 64px tight. Content
column is 1120px, wide layouts 1360px. Cards pad at 24px, large cards 32px.

Layouts are calm and horizontal: a wide yellow or clay band, a centred content column, generous
air above and below. The header is sticky at 84px; nothing else is fixed. Grids are 2- or
3-up for course listings — never denser, because each card carries a photo.

### Backgrounds, imagery and texture

Backgrounds are **flat colour fields**, exactly as in print: a yellow plane, a brown plane, a clay
plane. No gradients as decoration — the only gradients in the system are the two protection scrims
(`--scrim-bottom`, `--scrim-warm`) used to keep white type legible over a photograph. No repeating
patterns, no noise overlays, no illustration style.

**Imagery is warm.** The studio photography in `assets/photos/` sets the standard: daylight through
the workshop windows, pale birch shelving, clay-grey and cream, warm mid-tones and no cool cast.
Hands in the clay and half-finished pots rather than styled product shots — people are shown
working, not posing. Four images ship with this system:

| File | Use |
|---|---|
| `kursrommet.jpg` | The course room seen wide — four people at the wheels, daylight from the window. The best single image of what Lissom is. |
| `dreiekurs.jpg` | Course in progress — hands at the wheel. The default course image. |
| `butikken.jpg` | The shop wall: glazed mugs on pegs, bowls and cups on shelves. The only image of finished work. |
| `verkstedet.jpg` | The workshop interior with shelves and finished work. Om oss, wide bands. |
| `monica-dreier.jpg` | Monica at the wheel. Course listings, portraits of the studio. |
| `monica-portrett.jpg` | Portrait. Avatars, contact, about. |

Where a photo is missing, `CourseCard` falls back to a flat `--clay-200` block labelled `FOTO`.
Do not substitute stock imagery — leave the block visible so the gap is obvious.

The one full-bleed image treatment the brand does use is the **oversized crop of the cup mark**,
as on the gift card: the mark scaled far past the edge of the sheet, in brown at low contrast over
yellow. That is the sanctioned "pattern".

### Shape and edges

Corner radii are soft but restrained: 5px on fields, 9px on small surfaces, 14px on cards, 22px on
modals. Buttons, tags and badges are fully pilled. `--radius-thrown` is an organic blob radius for
the rare decorative mask (a photo cut to a thrown-pot silhouette) — use it once per page at most.

Borders come in two weights: a 1px clay hairline (`--border-subtle`) for structure, and the **2px
brown rule** (`--border-width-ink`) that reproduces the printed line. Buttons use the 2px brown.

### Elevation and depth

Shadows are warm — tinted with `rgba(46,16,2,…)`, never neutral grey. Three steps only: `sm` at
rest, `md` on hover, `lg` for overlays. Yellow and brown surfaces carry **no** shadow; they are
fields, not objects. `--shadow-press` is an inset used on pressed toggles.

Transparency and blur are used in exactly one place: the modal scrim, `rgba(46,16,2,.42)` with a
3px backdrop blur. Nothing else in the system is translucent.

### Motion

Slow and settled — clay does not bounce. 120ms for hover and focus, 200ms for buttons, chips and
inputs, 320ms for panels and drawers. The house easing is
`--ease-clay: cubic-bezier(.2,.7,.3,1)` — a quick start and a long settle. No spring, no overshoot,
no bounce, no scale-up. Motion respects `prefers-reduced-motion`, which zeroes every duration.

### Interaction states

- **Hover** — primary buttons darken (`--yellow-500`); secondary buttons *fill* with brown and
  flip their label to cream; ghost buttons take a clay wash; cards lift 2px and step from `sm` to
  `md` shadow; links move from brown to terracotta.
- **Press** — a 1px downward nudge. Never a scale, never a colour flash.
- **Focus** — a 2px terracotta outline at 2px offset, plus a soft terracotta glow
  (`--shadow-focus`) on form fields. Focus is always visible; never removed.
- **Selected** — brown fill with cream text (tags, checkboxes, radios), or a 3px yellow underline
  (tabs, nav links).
- **Disabled** — 40% opacity, `not-allowed` cursor. No greyscale filter.

## Iconography

**Lissom's own iconography is a single glyph: the cup mark.** It appears on the signage, the
letterhead, the gift card and the care card, at every scale from 12mm to a full-bleed crop. It is
solid brown, filled, no outline. Use it as the app icon, the favicon, the bullet in a list of
studio facts, and the oversized background crop. It is available at
`assets/mark-cup-brown.png` / `-cream` / `-yellow`.

The second and last brand pictogram is the **hand-drawn heart** (`assets/mark-heart-brown.png`),
which appears only next to *håndlaget med kjærlighet*.

There is no icon font, no SVG sprite and no icon set in the supplied material — the print pieces
simply have no UI to need one. For interface work this system uses **Lucide**, loaded from CDN and
rendered inline by the `Icon` component so it inherits `currentColor`:

```jsx
<Icon name="calendar" size={18} />
```

**This is a substitution and it is flagged.** Lucide was chosen because its single-weight, rounded
open strokes sit quietly next to a very loud wordmark, and because it is CDN-available with no
build step. Lissom draws Lucide at **stroke-width 1.75** rather than the default 2, which softens
it toward the handmade register. Sizes: 16 inline with text, 18–20 in buttons, 22 in the mobile
tab bar, 24 standalone, 32+ only in empty states.

Unicode characters are used as typographic separators, not as icons: `·` between meta items,
`|` on the letterhead address line, `&` in the descriptor. No emoji, anywhere.

## Index

**Root**
- `styles.css` — the single entry point consumers link. `@import` lines only.
- `thumbnail.html` — homepage tile for this design system.
- `SKILL.md` — Agent Skills front-matter, for use in Claude Code.
- `readme.md` — this file.

**`tokens/`** — `fonts.css`, `colors.css`, `typography.css`, `spacing.css`, `elevation.css`,
`motion.css`, `base.css`.

**`assets/`** — vector logo: `logo-lockup.svg` (+ `-cream`, `-yellow`), `wordmark-lissom.svg`
(+ `-cream`), `mark-cup.svg` (+ `-cream`, `-yellow`); `mark-heart-brown.png`; `photos/` (four
studio photographs); `reference/` (the original print artwork plus a contact sheet). The raster
lockups from the first pass are kept alongside for e-mail signatures and other non-SVG contexts.

**`guidelines/`** — 23 specimen cards feeding the Design System tab, grouped Brand / Colors /
Type / Spacing.

**Components**

| Group | Components |
|---|---|
| `components/core/` | `Button`, `IconButton`, `Icon`, `Logo`, `Badge`, `Tag`, `Card`, `Divider` |
| `components/forms/` | `Input`, `Textarea`, `Select`, `Checkbox`, `Radio`, `Switch` |
| `components/navigation/` | `NavBar`, `Tabs`, `BottomNav` |
| `components/feedback/` | `Dialog`, `Toast`, `Tooltip` |
| `components/patterns/` | `CourseCard` |

Each directory carries a `.card.html` demo, and each component a `.d.ts` contract plus a
`.prompt.md` usage note.

**Intentional additions.** No component library was supplied, so the set above is the standard
primitive inventory sized to a course-booking product. Four entries go beyond that standard set
and are justified here: `Icon` (wrapper for the substituted Lucide glyphs), `Logo` (so the wordmark
is never re-typeset), `BottomNav` (the mobile app surface needs a tab bar), and `CourseCard` (the
listing unit that every Lissom surface repeats).

**UI kits**
- `ui_kits/website/` — lissom.no marketing site: forside, kursoversikt, kursdetalj, medlemskap.
- `ui_kits/app/` — the booking app: kursliste, kursdetalj/booking, mine plasser, profil.

**Slides**
- `slides/` — seven 1280×720 slide types: title, section, content, comparison, quote, closing, full-bleed photo.

**Templates**
- `templates/kursdeck/` — the same six slides as a ready-to-copy Design Component deck.

## Caveats

1. **Fonts are substituted.** Bitter and Alegreya Sans stand in for the real Clarendon-style slab
   and humanist sans. Send the original files and the swap is a one-line change in
   `tokens/fonts.css`.
2. **Icons are substituted.** Lucide, from CDN, at stroke-width 1.75. The sandbox could not fetch
   the SVGs to vendor them locally, so `Icon` loads them at runtime.
3. **`LISSOMKOPP.AI` and `lissom-logo.eps` never arrived** in the project. The logo artwork here
   was extracted from the supplied PNG, JPG and PDF at print resolution — clean, but raster. A
   vector SVG export would let the mark scale without limit.
4. **No photography exists in the supplied material.** Every image slot is a labelled clay
   placeholder. Nothing has been invented or substituted from stock.
5. **No website, app or codebase was supplied.** The UI kits are new work built from the printed
   identity, not recreations of an existing product. Treat them as proposals.
