# Laws of UX, as a skill for coding and design agents

The 54 Laws of UX cards by Jon Yablonski (lawsofux.com, 2022), turned into a skill any Claude Code, Cursor or similar agent can load. The agent reads `SKILL.md` to know when a law applies, then opens the deck file in `references/` for the law itself.

## Install

Claude Code: copy this folder to `.claude/skills/laws-of-ux/` in your project, or `~/.claude/skills/laws-of-ux/` for every project. Then ask for a design review, a test plan or a screen and the agent cites the laws by name.

Cursor or another agent: point a rule at `SKILL.md` and keep the `references/` folder beside it.

## What is inside

- `SKILL.md`: when to use it, which deck to open for which moment, the output shape.
- `references/ux-theory-1.md` and `ux-theory-2.md`: the 29 laws and effects.
- `references/psychology-concepts.md`: the 10 concepts.
- `references/interaction-principles.md`: Don Norman's 7.
- `references/ux-methods.md`: the 8 research methods.

## Credit

Jon Yablonski wrote the laws, the cards and the book. The takeaways here are paraphrased from the cards and credited to him; buy the cards and the book at lawsofux.com.

## Install in one line

```
npx skills add louismoody-huspy/laws-of-ux-skill
```

Or clone it into `~/.claude/skills/laws-of-ux` for Claude Code.

## Licence

The skill text (SKILL.md, README and the paraphrased takeaways in `references/`) is MIT. The laws, the cards and the book are Jon Yablonski's work and stay his; nothing here replaces them, and no card images are included.
