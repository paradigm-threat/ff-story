# Agent instructions

Single entry point for assistants working on **Forgotten Future** manuscript and lore.

---

## Git and go-live

Catalog repo **`ff-story`** · branch **`main`** · publish origin **`iad1`**.

| Step | Action |
|------|--------|
| 1 | Checkout **`main`**. |
| 2 | **`git push iad1 HEAD:main`** first — server waits for mesh; **push failure = publish failed**. |
| 3 | **`git push gitlab HEAD:main`** after iad1 succeeds. |

**`atlanta3` is legacy** — use **`iad1`** / **`gitlab`** only unless ops restores atlanta3.

---

## What to read for each task

| Task | Document |
|------|----------|
| Consistency playbook (timelines, chapters, lore) | [`docs/AGENT_CONSISTENCY_CHECKLIST.md`](docs/AGENT_CONSISTENCY_CHECKLIST.md) |
| AI ethics | [`docs/AI_ETHICS.md`](docs/AI_ETHICS.md) |
| YA edition plan | [`docs/PLAN_YOUNG_ADULT.md`](docs/PLAN_YOUNG_ADULT.md) |
| 13+ edition plan | [`docs/PLAN_13_PLUS.md`](docs/PLAN_13_PLUS.md) |
| Chapter index | [`chapters/INDEX.md`](chapters/INDEX.md) |
| Master timeline (source of truth) | [`world-building/timeline/timeline.md`](world-building/timeline/timeline.md) |
| Style | [`manuscript/STYLE_GUIDE.md`](manuscript/STYLE_GUIDE.md) |

**Hard rules:** Never rewrite chapter **beats** except grammar/spelling/title when explicitly asked. Never invent calendar systems without updating **`world-building/facts.md`**.

*Last updated: 2026-08-23*
