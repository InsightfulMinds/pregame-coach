# Handoff

## Files Built

- `README.md` - overview, quick start, demo links, objection packs, audit runs, and assessor reference.
- `CLAUDE.md` - activation instructions and context loading order.
- `icm/identity.md` - Coach Rally identity, voice, scope, and boundaries.
- `icm/pregame-protocol.md` - seven-step pre-call ritual with exact prompts.
- `icm/objection-playbook.md` - 22 core objections with psychology and rebuttals.
- `icm/mindset-reset.md` - mid-call reset, between-call recovery, and end-of-day debrief.
- `icm/rules.md` - always/never rules and hard standards.
- `icm/examples.md` - three full coaching sessions.
- `ASSESSOR_GUIDE.md` - adversarial test prompts with expected behavior.
- `demo/index.html` - vanilla HTML/JS generator that works via `file://`.
- `landing/index.html` - Tailwind CDN landing page with pitch, flow, CTA, and sample exchange.
- `objections/*.md` - five industry objection packs: insurance, real estate, SaaS, coaching, recruiting.
- `audit/persona-*.md` - three test runs for anxious, slumping, and high-volume sales personas.

## What Is Missing Or Rough

- The demo is deterministic and static; it does not read the Markdown files at runtime.
- The objection routing is keyword-based and could use more industries.
- The landing page is clear enough for public review but could use a tighter visual identity pass.
- Examples are concise; a final pass could deepen the coaching sessions with more prospect-specific nuance.

## Open Questions

- Should the project be submitted as "The Pregame" or "The Pregame Coach"?
- Should the final demo include Spanish/bilingual selling mode?
- Should objection packs include compliance-sensitive disclaimers for insurance and real estate?

## Next Agent Notes

Keep the tone tactical, direct, and human. The core standard is: no generic motivation, no robotic scripts, no manipulation. The coach should make the user more ready to start the next call within five minutes.

## Follow-Up Iteration Note — 2026-05-24

- Public copy was softened so it feels more calibrated and less blunt.
- Public test-prompt language was changed to "Try Test Prompts" on the landing page.
- The landing and demo now frame the coach as a five-minute warmup, not a scolding pre-call drill.
- Next public/git pass should use the clean repo name `pregame-coach` and a simple commit subject such as `Build static pre-call coach demo`.

---

## Recent Update — 2026-05-24

### What Was Added

- **README.md** — anti-examples section: 3 "ChatGPT says X → Pregame Coach says Y" contrasts covering mindset advice, the send-info exit, and rapport-building approach
- **icm/examples.md** — named rules added to all three sessions. Rules cited inline: "that is a rule I hold," "I am staying out of the accept-and-follow-up pattern," "staying in diagnosis mode," "keeping you out of script mode"
- **_sources/SOURCES.md** — 12 sources across sales psychology, objection handling, pre-performance psychology, and coaching methodology. Includes Cialdini, Voss, Belfort (with note), Gallwey, GROW model.
- **objections/recruiting.md** — 9 objections (within spec range): not hiring, internal recruiters, fee objection, bad agency experience, just send candidates, can post ourselves, unclear need, compare agencies, tight market

### What's Still Rough

- Demo output is static/deterministic — does not read Markdown files at runtime
- Objection routing is keyword-based, could use more industry depth
- SOURCES.md attributes Belfort as a contrast baseline; may want a disclaimer line

### Final Polish Notes

- The anti-examples section in README is the highest-value addition because it shows what this is not as clearly as what it is.
- Named rules in examples show that the framework has boundaries, not just a description.

---

## Update — 2026-05-24

### What Was Added

- **icm/archetype-adaptation.md** — three caller archetypes (Anxious First-Timer, Experienced-But-Stuck, High-Volume Dialer) with silent adaptation rules, behavioral signals, and avoidance rules per type. Wired into CLAUDE.md load sequence.
- **examples/anti-example-transcript.md** — full parallel dialogue: same "timing is bad" scenario handled by generic AI vs. Coach Rally. Includes comparison table across 6 dimensions.
- **BRAND-GUIDE.md** — complete brand identity: name, tagline, voice rules, color palette, typography, texture, card styles, layout specs, do-not list.
- **ASSESSOR_GUIDE.md** — added Quick Verification (3 tests for 60-second spot check) and Pass/Fail Checklist (10 verification items).
- **VIDEO-SCRIPT.md** — fixed color palette reference (was green, now dark/gold to match actual brand).
- **README.md** — added archetype-adaptation.md, anti-example-transcript.md, and BRAND-GUIDE.md to key files table.
- **Landing and demo pages** — visual polish pass: animations, nav bar, hover states, improved mobile responsiveness.

### Quality Notes

- Archetype adaptation gives the coach stronger depth.
- The full anti-example transcript makes the contrast clearer.
- Pass/fail checklists make the test suite easier to verify.
- Tone consistency was maintained.
- Landing and demo polish improved the live experience.
