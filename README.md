# eco-skills
Testing own skills environment

## Structure

- `.claude-plugin/marketplace.json` — marketplace catalog (must stay at repo root for `/plugin marketplace add`).
- `claude-code-plugin/` — the Claude Code plugin itself (`.claude-plugin/plugin.json` + `skills/`), installed via:
  ```
  /plugin marketplace add alannovais/eco-skills
  /plugin install eco-system-tech-and-athlet@eco-system-tech-and-athlet
  ```
- `claude-desktop/` — self-contained skill packages meant to be zipped and uploaded manually through the Claude Desktop app (Settings → Capabilities → Skills).
