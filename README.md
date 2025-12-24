<p align="center">
  <img src="docs/images/icon.png" alt="Agora" width="120" />
</p>

<h1 align="center">Agora</h1>

<p align="center">A curated collection of Claude Code plugins</p>

## About

Agora is a plugin marketplace for [Claude Code](https://claude.com/claude-code). It serves as a registry of community-contributed plugins that extend Claude Code's functionality.

## Available Plugins

| Plugin | Category | Description |
|--------|----------|-------------|
| [herald](https://github.com/get-cubed/herald) | Productivity | Text-to-speech notifications for Claude Code |

## Adding Your Plugin

To add your plugin to Agora, submit a pull request that adds your plugin to `.claude-plugin/marketplace.json`:

```json
{
  "name": "your-plugin-name",
  "source": {
    "source": "github",
    "repo": "your-username/your-repo"
  },
  "category": "productivity"
}
```

## License

MIT
