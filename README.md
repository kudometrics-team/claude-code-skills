# KudoMetrics Claude Code Skills

Shared Claude Code skills for the team.

## Install

Copy a skill into your Claude Code skills directory:

```
mkdir -p ~/.claude/skills
cp -r information-gain-researcher ~/.claude/skills/
```

Or symlink from this repo if you prefer live updates:

```
ln -s "$(pwd)/information-gain-researcher" ~/.claude/skills/information-gain-researcher
```

## Skills

- **information-gain-researcher** — mine stats and primary sources to add information gain so AI engines cite your content (listicles, articles). Runs the `filetype:` / `site:` search patterns and compiles a sourced stats document.

## Rule

AI invents statistics. Verify every number against its source before publishing.
