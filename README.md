# gitagent registry

The public agent registry at [registry.gitagent.sh](https://registry.gitagent.sh).

Community-submitted agents, validated by CI, browsable on the web. GitHub is the source of truth — no database, no backend.

## How it works

```
PR → CI validates → merge → index.json regenerated → website reads index.json
```

- **Submit**: Open a PR adding your agent folder under `agents/<author>__<agent-name>/`
- **Validate**: CI checks your metadata, clones your repo, and verifies it's a real gitagent
- **Browse**: The website fetches `index.json` and renders a searchable marketplace

## Submit your agent

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full submission guide.

Quick start:

1. Fork this repo
2. Create `agents/<your-github-username>__<agent-name>/`
3. Add `metadata.json`, `README.md`, and optionally `icon.png`
4. Open a PR

## Development

```bash
npm install
npm run build:index    # Generate index.json from agents/
npm run dev            # Start the site dev server
npm run build          # Build everything
```

## License

MIT
