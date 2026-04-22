# Pau Layout Samples — Item 1 (Layout) Decision

**Current candidates (v3+):** `sample-3.html`, `sample-4.html`, `sample-5.html`
**Superseded (kept for reference):** `sample-1.html`, `sample-2.html`, `hybrid.html`

All samples use the **locked palette** from `Case study/sample-pair-page-know-your-reseller.html`: navy `#1A1F3A` + gold `#C9A84C` + cream `#FAF6EE` + Playfair Display + Inter.

---

## What changed in v3 (sample-3, sample-4)

Second round of feedback locked three additional constraints on top of v2's:

1. **No "one-person shop" language.** Undermines confidence. Replaced with value-focused framing.
2. **No founder-focus.** Removed founder quote sections. Replaced with principle-based value narrative.
3. **Flagship section headline sharpened.** "Six Questions. Six Answers. Six Systems." was tautological. Now: **"Six Case Studies. Six Systems."** (sample-3) or the retained pauanalytics pattern "Real Business Problems, Solved With Data" (sample-4).

Both samples now:
- Use the locked palette ✓
- Frame two-wings as **engagement modes**, not two companies or one person ✓
- Replace testimonials + founder quote with concrete flagship value-statements + principles ✓
- Keep search, drop categories ✓
- Feel like a **website** (browsing) not a **landing page** (funnel) ✓

---

## sample-3.html — Editorial (v2's sample-2, refined)

Structure:
1. Navbar
2. Hero — split layout (headline + value-focused intro + 2 soft CTAs on left · featured flagship preview on right)
3. **How Pau Works** — "Two Wings. One Engagement." framing (no one-person, no founder)
4. Flagships — "Six Case Studies. Six Systems." · search bar · 6 value-first rows
5. **Three Principles** (new — replaces founder quote) — Plain language / Rules earn their place / You own what Pau builds
6. Footer

**Intent:** Editorial consulting homepage. Narrative-led. Explains the approach, shows the work, then commits to three principles that differentiate Pau from templates or stock chatbots.

**Reading order:** Who (via How Pau Works) → Work → How Pau Delivers → Contact

## sample-5.html — Slim Classic (sample-4 minus the filler)

Sample-4 with four surgical edits applied:
- Search bar removed from sticky header
- Featured Work magazine layout swapped for sample-3's **"Six Case Studies. Six Systems."** row grid (no search, no subhead)
- **Process** section (3-step "Simple From Question to Insight") removed
- **Why Pau Analytics** (stats row) removed

Structure (7 sections):
1. Sticky header (no search)
2. Hero (2-col: text + device mockup + dual CTAs)
3. Problem Statement (3 cards)
4. What We Do (3 service cards)
5. **Featured Flagships — "Six Case Studies. Six Systems."** (6 value-first rows, 2-col grid)
6. Gold CTA strip
7. Footer (3-col)

**Intent:** The pauanalytics.com structure stripped of ceremony. Problem → What We Do → Six flagships with concrete value → CTA → Footer. The flagship row grid does the social-proof work that the stats row was trying to do — but with actual numbers from the work, not brand-level counts.

**Reading order:** Problem → What We Do → Work → CTA → Footer

## sample-4.html — Pau Analytics Classic (navy retrofit)

Structure (identical skeleton to current pauanalytics.com/index.html):
1. Sticky header with search
2. Hero (2-col: headline + device mockup) + dual CTAs
3. Problem Statement (3 cards, cream-alt bg)
4. What We Do (3 service cards, cream bg)
5. Featured Work — **6 flagships** in magazine layout (1 full-width + three 2-up grids, ending with "See All" tile)
6. How It Works (3 steps, navy bg)
7. Stats (4 cards, navy bg)
8. Gold CTA strip
9. Footer (3-col)

**Intent:** Proven pauanalytics.com layout, palette-retrofitted to match the case-study template. Zero structural risk — the site already worked for visitors; the changes are visual (navy palette) and content (6 flagships).

**Reading order:** Problem → What We Do → Featured Work → How It Works → Stats → CTA → Footer

---

## Structural diff — sample-3 vs sample-4

| Dimension | sample-3 (Editorial) | sample-4 (Classic retrofit) |
|---|---|---|
| Sections | 6 (Hero · How Pau Works · Flagships · Principles · Footer) | 8 (Hero · Problem · What We Do · Featured Work · Process · Stats · CTA · Footer) |
| Total scroll | Medium | Longer |
| Hero | Split (narrative + featured preview) | 2-col (text + device mockup) |
| CTAs in hero | "See the Work →" + "How Pau Works" link | "See Our Work" + "Get a Free Consultation" |
| Flagship display | Row-based, 2-col, full value copy | Magazine-style, 1 full-width + three 2-up grids |
| Extra narrative | 3 Principles section | Problem + What We Do + Process + Stats |
| Tone | Narrative, considered | Funnel-structured, comprehensive |
| Risk | Novel layout — needs user testing | Proven layout — already converts (or not) on pauanalytics.com |
| Who it suits | Visitors who prefer story + work | Visitors who need orientation → proof → CTA |

---

## Honest tradeoff

- **sample-3** is more distinctive, more editorial, shorter. Closer to the ai-project portfolio aesthetic but adapted for consulting. Tells Pau's story.
- **sample-4** is the current pauanalytics.com homepage with a palette swap and updated content. Lower design risk. Already-proven section rhythm. But carries over the pauanalytics.com "feel" — which got zero leads in 4 weeks.

If the pauanalytics.com layout is genuinely underperforming on distribution, sample-4 retains that risk. If the pauanalytics.com layout works and only the content/palette need refresh, sample-4 is the safer bet.

---

## What to ask yourself while comparing

1. **Does the homepage read as a website (browsing) or a landing page (funnel)?** Both should feel like browsing.
2. **Is the two-wings concept clear without being preachy about it?** Sample-3 foregrounds it; sample-4 distributes it across "What We Do" + flagship cards.
3. **Which one do you want to be reading in 12 months?** The one you'd still stand behind.
4. **Which one makes the 6 flagships feel most valuable?**
5. **If sample-4 carries over the pauanalytics.com distribution problem, is a retrofit enough — or does the work need a structural break?**

---

## Historical — DO NOT USE AS CURRENT CANDIDATE

- `sample-1.html` — "Library Front" minimalist. Good shape but contained one-person shop language.
- `sample-2.html` — Editorial narrative-led. Contained founder quote + one-person shop language.
- `hybrid.html` — v1. Landing-page funnel with fake testimonials. Superseded entirely.

Once a direction is locked, delete the historical files before Session 1 of Task 9.

---

**Decision due:** item 1 in `12-decisions.md`. Once locked, the secretary ticks it and we move to item 2 (homepage hero line, prompt #3 PAS).
