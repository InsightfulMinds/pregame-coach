# The Pregame Coach

**What it is:** A five-minute warmup before a sales call.

**Who it is for:** Cold callers, SDRs, appointment setters, account executives, agency owners, brokers, and closers who need to get sharp before a real sales conversation.

**One-line pitch:** A five-minute warmup before a sales call.

## Quick Start

1. **Web-ready:** Open [index.html](./index.html) or deploy the folder as a static site.
2. **Local demo:** Open [demo/index.html](./demo/index.html) directly in a browser.
3. Enter your industry, product/service, and prospect type.
4. Generate the 5-step pregame routine.
5. Read it out loud, pick your opening line, then start with the next clean question.

No install. No backend. No account.

## Claude Mode

Paste [CLAUDE.md](./CLAUDE.md) into a Claude project or chat, then ask:

```text
I'm about to call a cold prospect in [industry] about [offer]. Run the pregame.
```

The coach will calibrate mindset, preview the top objections, write a natural opening line, run an energy check, and keep the rep away from canned-script delivery.

## Demo

- [index.html](./index.html) - deploy-ready entry point with links to landing and demo.
- [demo/index.html](./demo/index.html) - static pregame generator with industry, offer, and prospect inputs.
- [landing/index.html](./landing/index.html) - static Tailwind landing page with pitch, flow, and sample coaching exchange.

## Key Files

| File | Purpose |
| --- | --- |
| [BRAND-GUIDE.md](./BRAND-GUIDE.md) | Brand identity: voice, colors, typography, do-not list. |
| [VIDEO-SCRIPT.md](./VIDEO-SCRIPT.md) | 55-second product video script: generic advice vs. specific coaching. |
| [ASSESSOR_GUIDE.md](./ASSESSOR_GUIDE.md) | 18 adversarial test prompts with pass/fail criteria. |
| [icm/identity.md](./icm/identity.md) | Coach identity, voice, scope, and limits. |
| [icm/pregame-protocol.md](./icm/pregame-protocol.md) | The exact pre-call ritual. |
| [icm/objection-playbook.md](./icm/objection-playbook.md) | 20+ objections with psychology and rebuttals. |
| [icm/mindset-reset.md](./icm/mindset-reset.md) | Mid-call, between-call, and end-of-day reset protocols. |
| [icm/rules.md](./icm/rules.md) | Cardinal rules: Narrative Integrity, Specificity-First, Anti-Canned-Script. |
| [icm/archetype-adaptation.md](./icm/archetype-adaptation.md) | Three caller archetypes with silent adaptation rules. |
| [icm/examples.md](./icm/examples.md) | Three full coaching sessions. |
| [examples/anti-example-transcript.md](./examples/anti-example-transcript.md) | Same prompt, two coaches — full parallel dialogue. |
| [examples/archetype-variation.md](./examples/archetype-variation.md) | Same prompt, three caller types — shows silent adaptation in action. |

## Industry Objection Packs

- [objections/insurance.md](./objections/insurance.md)
- [objections/real-estate.md](./objections/real-estate.md)
- [objections/saas.md](./objections/saas.md)
- [objections/coaching.md](./objections/coaching.md)
- [objections/recruiting.md](./objections/recruiting.md)

## Audit Runs

- [audit/persona-a.md](./audit/persona-a.md) - first-time caller with imposter syndrome.
- [audit/persona-b.md](./audit/persona-b.md) - experienced rep in a slump.
- [audit/persona-c.md](./audit/persona-c.md) - high-volume dialer who needs speed.

## Try Test Prompts

Use [ASSESSOR_GUIDE.md](./ASSESSOR_GUIDE.md) for things to try when you want to prove the coach works: repeat rejection, panic, requests for scripts, pressure tactics, avoidance, character breaks, and post-call debrief. The guide includes 18 prompts with expected behavior, pass/fail criteria, and a 60-second quick verification.

## Handoff

See [HANDOFF.md](./HANDOFF.md) for current build status, rough edges, and final polish notes.

## Why This Works — Anti-Examples

The difference between generic advice and specific coaching:

**ChatGPT says:** "Be confident and believe in your product. Your mindset determines your success."

**Pregame Coach says:** "Confidence is earned by repetition, not declared. You earn it by running the objection preview before every call, not by telling yourself you believe in the product."

---

**ChatGPT says:** "If they say 'send me info,' say thank you and follow up in a few days."

**Pregame Coach says:** "It sounds like they may be looking for a polite exit. Try: 'I can send something, but I do not want to dump generic material on you. Should I tailor it around cost, speed, or the specific pain you mentioned?'"

---

**ChatGPT says:** "Try to find common ground and build rapport before pitching."

**Pregame Coach says:** "Forced rapport can make both sides tense. Would it be unreasonable to earn the next 20 seconds by being useful first? Lead with relevance, then let the conversation get warmer if there is a real reason."
