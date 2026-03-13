# Mojo Skills

Two Mojo skills:

- [`mojo-expert`](./mojo-expert/SKILL.md)
- [`mojo-reviewer`](./mojo-reviewer/SKILL.md)

From the repo root, go to this folder first:

```bash
cd mojo_skills
```

## Codex (quick install)

```bash
mkdir -p ~/.codex/skills
cp -R mojo-expert mojo-reviewer ~/.codex/skills/
```

For local development (symlink instead of copy):

```bash
ln -sfn "$(pwd)/mojo-expert" ~/.codex/skills/mojo-expert
ln -sfn "$(pwd)/mojo-reviewer" ~/.codex/skills/mojo-reviewer
```

Verify:

```bash
ls ~/.codex/skills | rg 'mojo-expert|mojo-reviewer'
```

## Claude Code (quick install)

```bash
mkdir -p ~/.claude/skills
cp -R mojo-expert mojo-reviewer ~/.claude/skills/
```

For local development (symlink instead of copy):

```bash
ln -sfn "$(pwd)/mojo-expert" ~/.claude/skills/mojo-expert
ln -sfn "$(pwd)/mojo-reviewer" ~/.claude/skills/mojo-reviewer
```

Verify:

```bash
ls ~/.claude/skills | rg 'mojo-expert|mojo-reviewer'
```
