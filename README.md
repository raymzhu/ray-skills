# ray-skills

Raymond's personal Claude Code skills marketplace.

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| [poster-design](./plugins/poster-design) | 一句话生成大师级 Mondo 风格海报、书籍封面、专辑封面 | [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) |

## Usage

### Claude Code

```bash
# Add marketplace
/plugin marketplace add raymzhu/ray-skills

# Install a plugin
/plugin install poster-design@ray-skills
```

### Claude.ai / Cowork

Browse and install from Customize → Skills.

## Adding new skills

1. Create a new folder under `plugins/`
2. Add `.claude-plugin/plugin.json` and `skills/<name>/SKILL.md`
3. Update `marketplace.json` with the new plugin entry
4. Push to GitHub
