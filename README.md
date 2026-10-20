# public-storage

Shared agent skills and reference packages.

## Contents

| Path | What |
|------|------|
| [`humanizer/`](./humanizer/) | [blader/humanizer](https://github.com/blader/humanizer) — rewrite AI-sounding prose to read like a person wrote it |
| [`dify/`](./dify/) | Dify reference tree (skills + project) |

## Install humanizer (all agents)

From any machine with Node:

```bash
npx skills add AshtonMedina22/public-storage/humanizer --global --agent '*'
```

Or install from upstream:

```bash
npx skills add blader/humanizer --global --agent '*'
```

Once installed, use `/humanizer` or ask the agent to humanize text/files.

### Cursor plugin

This repo's `humanizer/` folder includes `.cursor-plugin/plugin.json`. Copy it to:

```text
~/.cursor/plugins/local/humanizer
```

Or run the skills CLI install above (Cursor picks up `~/.agents/skills/humanizer`).
