# Terrific Claude Skills

A central place for my *opinionated* Claude skills shared across all my python projects. I titled this repo "terrific" because I have no idea if these skills are terrible or not. But im using it and its working alright so far...

## Usage

On my local linux machine, new projects have the skills from this repo symlinked into the `.claude/skills/` directory at the root of each repo, so every project automatically picks up the latest standards.

**Step 1 - Clone the repo once**

```bash
git clone https://github.com/aminbeigi/terrific-claude-skills.git ~/code/terrific-claude-skills
```

**Step 2 - Symlink a skill into a project**

```bash
ln -s ~/code/terrific-claude-skills/skills/my-skill.md ~/code/my-project/.claude/skills/my-skill.md
```
