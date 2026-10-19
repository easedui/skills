# Eased skills

Agent skills for building UI that moves well, from the [Eased](https://eased.dev?ref=skill) component library.

## eased-motion

Teaches your coding agent when to animate and with what: three springs, four curves, five durations, exits faster than enters, press scales, text swaps, staggers and reduced motion. Every value is the one Eased components ship with. If Eased components are installed in your project, the agent uses them instead of writing its own.

Install for Claude Code and other agents that read skills:

```bash
npx skills add easedui/skills
```

Or copy `skills/eased-motion/` into `.claude/skills/`.

For Cursor, copy `rules/eased-motion.mdc` into `.cursor/rules/`.

## Related

- The full Eased design skill (layout, spacing, corners, colour, type and motion): `npx shadcn add https://eased.dev/r/eased-skill.json`
- The components: [eased.dev](https://eased.dev?ref=skill)

MIT licensed.
