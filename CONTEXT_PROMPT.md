# Context Prompt — Safe Extension of This Repository

Hand this to a human or AI when extending **this documentation repo**.

---

## Mission

Keep **Holy Grail's Automated Trading** (Holy Grail Z-2311) documented in a way that feels **written by a person** — clear, honest, not a brochure. Single operator; crypto, stocks, forex. Automation and risk lead; machine learning stays shallow here (no training specs unless the user asks).

## Hard rules

1. **Public only** — No keys, seeds, `.env`, tokens, or infra credentials.
2. **No strategy leakage** — Generic categories, no proprietary thresholds or codenames.
3. **No live numbers** — Use "your configured limit" style placeholders.
4. **Docs only** — No trading executable or live-connection scripts in this repo.
5. **ML stays light** — Outcome learning and ranking in plain language; never executes or overrides risk.
6. **Mask secrets** in chat summaries.

## Allowed

Diagrams, module stories, process walkthroughs, stack lists, disclaimers.

## Workflow

Edit this repo only unless told otherwise. Touch [project.meta.json](./project.meta.json) when scope changes. No `git push` unless the user asks.

## Workspace

Use **`z-trader-engine-docs`**, not a Home chat.

## Tone (humanize)

- Write like you explain it to a trader friend who codes, or a dev who trades — not like enterprise marketing.
- Prefer short paragraphs and plain verbs over dense tables when one paragraph suffices.
- Keep **Holy Grail's Automated Trading**, author **Holy Grail Z-2311**, and **risk → automation → ML** order.
- It is okay to say "you" and "I" where it fits; avoid buzzword stacks and repeated bold.

## Checklist

- [ ] No secrets or strategy specifics  
- [ ] No deep ML architecture  
- [ ] Sounds human on read-aloud  
- [ ] README, ARCHITECTURE, PROCESS_FLOW still link sensibly  
