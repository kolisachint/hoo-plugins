# hoo-plugins

The official hoocode plugin marketplace. It is a listing only: each entry points at a plugin's
own git repository, and nothing is copied here.

## Add and install

```
/plugin marketplace add https://github.com/kolisachint/hoo-plugins
/plugin install webtools@hoo-plugins
```

This marketplace is pre-trusted by hoocode, like the Anthropic directory. Installs from it need
no extra grant.

## Plugins

| Plugin | Version | What it does |
|---|---|---|
| `webtools` | 0.7.3 | Web fetch and search tools (WASM, gated network) |
| `hoo-browser` | 0.1.8 | Browser automation: one shared Chromium, a tab lease per agent (native helper) |

## License

MIT. See [LICENSE](LICENSE).
