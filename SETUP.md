# Setup — 5 minutes

## 1. Install Obsidian
https://obsidian.md (free)

## 2. Open this folder as a vault
Obsidian → "Open folder as vault" → select this directory

## 3. Install plugins
Settings → Community plugins → Browse → install:
- **Dataview** (required for INDEX.md live tables)
- **Templater** (optional)

## 4. Browse
Open `README.md` for the Map of Content.
Open `INDEX.md` for a live searchable Dataview table.

## 5. Use a skill in Claude Code
Pick any skill folder, copy into ~/.claude/skills/:
```bash
cp -r 00-AI-Agents/agent-orchestrator.md ~/.claude/skills/agent-orchestrator/SKILL.md
```
Or symlink whole categories:
```bash
ln -s "$(pwd)/00-AI-Agents" ~/.claude/skills/_suprapack-ai-agents
```

## 6. Search
Cmd+Shift+F (full text) or use the Dataview INDEX.md.
