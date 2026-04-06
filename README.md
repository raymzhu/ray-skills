# ray-skills

Raymond's personal Claude Code skills marketplace.

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| [poster-design](./skills/poster-design) | 一句话生成大师级 Mondo 风格海报、书籍封面、专辑封面 | [qiaomu-mondo-poster-design](https://github.com/joeseesun/qiaomu-mondo-poster-design) |

## Usage

### Claude Code

```bash
/plugin marketplace add raymzhu/ray-skills
/plugin install poster-design@ray-skills
```

### Claude.ai / Cowork

Browse and install from Customize → Plugins.

## API Key

Scripts require a `GEMINI_API_KEY` environment variable:

```bash
export GEMINI_API_KEY=your_key_here
```

Get your key at: https://aistudio.google.com/apikey
