# only-skills-you-need

One install command, every agentic coding tool. The skills stack I run daily, curated down from everything available to what actually earns a permanent slot — for full-stack dev, frontend/React, SEO, and structured execution.

Works across **opencode, Claude Code, Antigravity (CLI + IDE), and Kilocode.**

No config rewrites, no per-tool setup. Run the commands below, restart your tool, done.

---

## Quick start

```bash
# verify install anytime by asking your tool:
"list installed skills"
```

Restart your AI tool after installing for skills to load.

---

## Core workflow — Superpowers suite

Brainstorming, TDD, systematic debugging, verification-before-completion, parallel agent dispatching, plan writing/execution.

```bash
npx skills add superpowers
```

## Frontend / React / UI

```bash
npx skills add https://github.com/anthropics/skills --skill frontend-design
npx skills add https://github.com/anthropics/skills --skill react-doctor
npx skills add https://github.com/vercel/skills --skill vercel-react-best-practices
npx skills add https://github.com/anthropics/skills --skill modal-drawer-system
npx skills add https://github.com/obra/skills --skill implement_lenis_scroll
```

## Research / live docs

```bash
npx skills add agent-reach
```

## SEO suite

```bash
npx skills add https://github.com/anthropics/skills --skill programmatic-seo
npx skills add https://github.com/anthropics/skills --skill seo-audit
npx skills add https://github.com/anthropics/skills --skill ai-seo
```

## Structured execution — GSD workflow

The original [GSD skills](https://github.com/instax-dutta/gsd-skills) repo ships 16 skills. Most teams don't use all 16 day to day, so this is the stripped-down set — `plan-phase`, `execute-phase`, `ship`, `code-review`, `debug`, `pause/resume`, `undo` — re-hosted here for faster onboarding.

```bash
git clone https://github.com/instax-dutta/gsd-skills.git ~/.config/opencode/skills/
```

## Code review

Built on Google's published engineering practices docs, published on [skills.sh](https://skills.sh).

```bash
npx skills add instax-dutta/google-code-review
```

---

## Why this list

Every skill here is something I run in production, not something that looked interesting in a changelog. Anything that didn't earn its slot after real use got cut. If you think something's missing, open an issue — this list updates as the stack changes, not as a one-time snapshot.

## Troubleshooting

- **Skill not showing up?** Restart your AI tool completely after install.
- **`npx skills add` failing?** Confirm you have a recent Node.js version and that `npx` resolves — run `npx --version` to check.
- **Still stuck?** Open an issue with your tool name + OS and I'll take a look.

## Contributing

Found a skill that should be on this list, or one here that shouldn't be? Open a PR or an issue. The bar is: you use it regularly, not that it sounds good.

## License

[Add a license here — MIT is the standard choice if you want this freely reusable by others.]
