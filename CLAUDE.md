# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

`awesome-ai` is a curated "awesome list" for Enterprise AI, LLMs, GenAI, AI Agents, MCP, governance, security, MLOps, and production-ready AI tooling. It is content, not software.

Files: `README.md` (the entire list), `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `LICENSE` (MIT), `CLAUDE.md`.

There is no build system, test suite, package manifest, or CI. Do not add tooling unless asked — the deliverable is the curated content in `README.md`.

## Structure of README.md

Fixed order, and the anchors in the Table of Contents depend on it:

1. Centered header block — title, tagline, badges (repo badges use dynamic shields.io endpoints against `seyhunak/awesome-ai`, so counts stay live; never hardcode a star or follower number)
2. `## 📖 About` — positioning and the badge legend
3. `## 📑 Table of Contents` — a two-column table ("Build" / "Measure, Secure & Operate") linking to all 23 content sections
4. The 23 emoji-prefixed content sections, ordered build → tools → measure → secure → operate → learn
5. `## 🤝 Contributing`, `## ⭐ Star History`, `## 👤 Author`, `## 📄 License`

Every content section ends with `**[⬆ back to top](#-table-of-contents)**` followed by `---`. Add it to any new section.

## Entry conventions

All entries live in Markdown **tables**, not bullet lists. Column layout varies per section — match the surrounding table exactly rather than imposing one shape.

```markdown
| [Project Name](https://github.com/org/repo) ⭐ 🔓 | What it does, in one line, no hype |
```

Badge legend, defined in the About section and applied inline:

| Badge | Meaning |
|---|---|
| ⭐ | Widely adopted default for its category |
| 🔓 | Open source |
| 💰 | Commercial / paid tier |
| ☁️ | Managed service |
| 🆓 | Free |

Use ⭐ sparingly — roughly one to three per section. It means "if you have no opinion, pick this."

Ordering within a table is **by adoption and relevance, not alphabetical**. Place a new entry where a reader would expect it.

Descriptions state capability, not adjectives. Prefer "PagedAttention, continuous batching, OpenAI-compatible API" over "blazing fast and powerful." Avoid copying a project's marketing tagline.

Links must be canonical — the project's GitHub repo or official docs. No aggregators, redirects, or referral links.

## Anchor links

Section headings are emoji-prefixed, and GitHub strips the emoji while keeping the resulting leading hyphen:

- `## 🧠 RAG` → `#-rag`
- `## 🛡️ AI Security & Guardrails` → `#️-ai-security--guardrails` (the variation selector U+FE0F survives; `&` becomes `--`)

Headings whose emoji carries a variation selector (🛡️ ☁️ 🛠️) produce a different anchor from plain ones. If you rename a heading, update its Table of Contents entry and verify the anchor.

## Avoiding duplication

Several sections legitimately overlap (LiteLLM is both an SDK and a gateway; Ragas is both a RAG tool and an eval framework). Cross-section repeats are acceptable when each listing serves a different reader intent.

**Not acceptable:** the same URL twice within one section, or a tool listed in three or more places. When a topic gets its own section, strip the now-redundant entries from the older section and leave a pointer instead — as `Open Source Projects` does for `AI & ML Frameworks`, and `AI Agents → Agent Benchmarks` does for `Benchmarks`.

Boundaries currently in force:

- **Agent Frameworks** orchestrate models; **AI & ML Frameworks** are what models are built and trained in
- **Benchmarks** are public/comparative; **Metrics** are what you compute on your own traffic; **Evaluation & Observability** is the tooling that runs both
- **Developer Tooling** is the workbench (tokenizers, labeling, quantization, CLIs); **Open Source Projects** is applications built on the stack

## Verification

No automated checks exist. Before proposing changes:

- Confirm links resolve and point at the canonical home
- Check the entry isn't already listed in another section
- Confirm the project is actively maintained (not archived, recent activity)
- Verify Table of Contents anchors still resolve if headings changed

Two throwaway scripts are worth recreating when editing structure: one that slugs every heading with `github-slugger` and diffs it against every `](#...)` link, and one that flags any URL starting a table row in more than one section. Both caught real errors during the initial build.

`CONTRIBUTING.md` holds the full inclusion criteria — keep it and this file consistent when either changes.
