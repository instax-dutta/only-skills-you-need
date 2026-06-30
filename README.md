# only-skills-you-need

A curated instruction set for agentic coding tools. Zero-config across opencode, Claude Code, Antigravity (CLI + IDE), and Kilocode.

```bash
# verify the runtime contract
"list installed skills"
```

---

## Installation

### Core workflow

```bash
npx skills add obra/superpowers
```

Provides: brainstorming, TDD, systematic debugging, verification-before-completion, parallel agent dispatch, plan authoring and execution.

### Frontend / React / UI

```bash
npx skills add https://github.com/anthropics/skills --skill frontend-design
npx react-doctor@latest install
npx skills add https://github.com/vercel/skills --skill vercel-react-best-practices
npx skills add https://github.com/patricio0312rev/skills --skill modal-drawer-system
npx skills add https://github.com/KailasMahavarkar/agentic-skills --skill lenis-react
```

### Research / live documentation

```bash
npx skills add https://github.com/Panniantong/Agent-Reach
```

### SEO

```bash
npx skills add https://github.com/coreyhaines31/marketingskills --skill programmatic-seo
npx skills add https://github.com/coreyhaines31/marketingskills --skill seo-audit
npx skills add https://github.com/coreyhaines31/marketingskills --skill ai-seo
```

### Structured execution

16 GSD primitives. The subset used day-to-day: `plan-phase`, `execute-phase`, `ship`, `code-review`, `debug`, `pause/resume`, `undo`.

```bash
git clone https://github.com/instax-dutta/gsd-skills.git ~/.config/opencode/skills/
```

### Code review

Based on Google's published engineering practices.

```bash
npx skills add instax-dutta/google-code-review
```

---

## Design principles

- **Signal over noise.** Every skill here earned its slot through sustained production use, not relevance at install time.
- **Cross-platform parity.** One install path, six runtimes. No per-tool configuration.
- **Composable by convention.** Skills are independently loadable and semantically versioned through their source repositories.

---

## Troubleshooting

| Symptom | Resolution |
|---|---|
| Skill not visible | Restart the host tool completely |
| `npx skills add` fails | Verify Node.js ≥ 18 and `npx --version` resolves |
| Runtime mismatch | Open an issue with tool name + OS |

---

## Contributing

The acceptance criterion: you use it weekly, not that it seems useful.

---

## License

MIT
