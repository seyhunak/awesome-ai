# Contributing to Awesome AI

Thanks for helping keep this list useful. Corrections and removals are as welcome as additions.

## What belongs here

This list is **production-first**. An entry should be something an engineering team would realistically deploy, operate and defend in a review.

**Accepted:**

- Actively maintained tools, frameworks, SDKs and platforms
- Standards, specifications and governance frameworks
- Substantive learning resources (courses, books, talks, engineering writeups)
- Real production case studies with public detail

**Not accepted:**

- Abandoned projects (no meaningful activity in ~12 months, or archived)
- Thin wrappers with no distinct value over what they wrap
- Marketing pages, waitlists and unreleased products
- Paid-only content behind a signup wall with no substance
- Duplicate entries already listed under another section

## Entry checklist

Before opening a pull request, confirm your entry:

1. **Is production-relevant** — not a weekend demo
2. **Is actively maintained** — recent commits, releases or doc updates
3. **Is not already listed** — search the README first
4. **Uses the canonical link** — the project repository or official docs, never an aggregator, redirect or referral link
5. **Follows the table format** of the section you're adding to
6. **Has a one-line, non-marketing description** — say what it does and who it's for
7. **Sits in the most specific applicable section** — don't add a new section for a single entry

## Format

Every section uses a Markdown table. Match the columns of the section you are editing exactly.

```markdown
| [Project Name](https://github.com/org/repo) ⭐ 🔓 | What it does, in one line, no hype |
```

**Badge legend** (apply only where genuinely true):

| Badge | Meaning |
|---|---|
| ⭐ | Widely adopted default for its category |
| 🔓 | Open source |
| 💰 | Commercial / paid tier required |
| ☁️ | Managed / hosted service |
| 🆓 | Free to use |

Use ⭐ sparingly — it means "if you don't have an opinion, pick this one." Roughly one to three per section.

### Description style

- One line, no trailing period needed for fragments
- Describe capability, not adjectives: "PagedAttention, continuous batching, OpenAI-compatible API" beats "blazing fast and powerful"
- Avoid copying the project's own tagline verbatim if it's pure marketing
- Prefer an em dash to separate name-clarification from purpose

## Ordering

Within a section, follow whatever ordering is already there. Most tables are ordered roughly by adoption and relevance rather than alphabetically — put your entry where a reader would expect to find it, not automatically at the end.

## Submitting

```bash
git clone https://github.com/<your-username>/awesome-ai.git
cd awesome-ai
git checkout -b add-awesome-tool
# edit README.md
git commit -am "Add <Tool> to <Section>"
git push origin add-awesome-tool
```

### Automated checks

Every pull request runs a [lychee](https://github.com/lycheeverse/lychee) link check over the Markdown. If it fails, your link is unreachable — fix the URL rather than working around the check.

To run it before pushing:

```bash
# macOS
brew install lychee
# or: cargo install lychee

lychee --config lychee.toml --no-progress .
```

A handful of hosts (LinkedIn, X, iso.org) block automated traffic and are listed in `.lycheeignore`. Add to that file only when a link genuinely works in a browser but cannot be verified by a bot — never to hide a dead link.

Then open a pull request. In the description, include:

- A link to the project
- One or two sentences on why it belongs here
- Any disclosure of affiliation (see below)

**One entry per pull request** where practical — it keeps review fast.

## Self-promotion and affiliation

You may submit your own project. **Disclose the affiliation in the pull request.** Self-submitted entries are held to the same bar as everything else, and "actively maintained" is checked more carefully for projects with few external users.

## Reporting problems

[Open an issue](https://github.com/seyhunak/awesome-ai/issues/new) for:

- Dead or redirected links
- Projects that have been archived or deprecated
- Descriptions that are no longer accurate
- A ⭐ that no longer reflects reality

These are high-value contributions. A curated list decays quietly, and corrections are what keep it trustworthy.

## Code of Conduct

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
