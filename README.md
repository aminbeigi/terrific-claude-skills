# Terrific Cursor Rules

A central place for my *opinionated* Cursor rules shared across all my python projects. I titled this repo "terrific" because I have no idea if these rules are terrible or not. But im using it and its working alright so far...

## Usage

On my local linux machine, new projects have the rules from this repo symlinked into the `.cursor/rules/` directory at the root of each repo, so every project automatically picks up the latest standards.

**Step 1 - Clone the repo once**

```bash
git clone https://github.com/aminbeigi/terrific-cursor-rules.git ~/code/terrific-cursor-rules
```

**Step 2 - Symlink a rule into a project**

```bash
ln -s ~/code/terrific-cursor-rules/my-rule.mdc ~/code/my-project/.cursor/rules/my-rule.mdc
```

