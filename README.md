# Toby Iverson

Automation engineer in Minneapolis. I build systems that do the legwork and check their own work — AI research agents, agentic workflows, LLM integration, guardrail design. Python · SQL · FastAPI.

**Verification beats trust, and memory beats a one-shot prompt.** Software should be able to prove it did what it claims — and remember what it already did.

Most of these projects share one architecture: a reusable engine plus a swappable folder of context — identity, rules, reference material — that turns a general agent into a specialist. Point it at sales prospects and it's Groundwork; at hearing testimony, For the Record. The domain changes; the discipline doesn't.

## Shipped

- **[Groundwork](https://github.com/BytesFromToby/Groundwork)** — an AI sales-intelligence engine: finds funded prospects, maps the buying committee, catches the buy-now trigger, and names the objection a rep will hit. A persistent ledger means run two reads run one — nothing worked twice, nothing dropped. Domain-agnostic; swap the pack and it researches anything.
- **[Walkdown](https://github.com/BytesFromToby/Walkdown)**: an early-alpha auditor for AI skills and agents. It reads what a model would load and cites every finding to a file and line, from hidden text to ways your data could leave. It shows you where to look and leaves the call to you.
- **[RepoRouter](https://github.com/BytesFromToby/RepoRouter)** — autonomous GitHub issue-triage operator, live in production on a local 8B model. Safety enforced by the harness; guardrails pinned by pytest.
- **[Polis](https://github.com/BytesFromToby/Polis)** — strategy game where 28 AI factions negotiate through live LLM audiences; a deterministic engine pinned by 638 tests enforces every deal.
- **[Plumbline](https://github.com/BytesFromToby/plumbline)** — spec-driven workflow: eight single-responsibility agent skills and two unattended orchestrators take a written brief to verified code. Cross-skill contract audited in CI.
- **[For the Record](https://github.com/BytesFromToby/for-the-record)** — critique-only AI editor for public testimony: every flag quotes the line, names the rule it breaks, and explains why — so the words stay the speaker's. Same engine-plus-domain-pack pattern as Groundwork.
- **[Log Analyzer](https://github.com/BytesFromToby/Log_breakdown)** — desktop log analysis in pure Python 3 + Tkinter, zero external dependencies.

## Elsewhere

🌐 [Portfolio](https://profile.bytesbytoby.workers.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/tobyiverson/)
