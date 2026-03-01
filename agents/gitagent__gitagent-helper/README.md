# gitagent Helper

The official gitagent assistant. Helps developers build, run, and manage AI agents using the gitagent framework.

## Capabilities

- **Get Started** — Walk through creating your first agent from scratch
- **Create Agent** — Scaffold new agents with the right directory structure
- **Run Agent** — Execute agents with any supported adapter
- **Export Agent** — Export agents to different formats and platforms
- **Manage Skills** — Create, install, and organize agent skills

## What it knows

- Every CLI command, flag, and option
- The full agent manifest schema (`agent.yaml`)
- All 8 adapters: Claude, OpenAI, CrewAI, OpenClaw, Nanobot, Lyzr, GitHub, Git
- The skills system and registry
- Compliance framework configuration
- Directory structure conventions

## Example Usage

```bash
# Run the helper
gitagent run -r https://github.com/open-gitagent/examples -p gitagent-helper

# Ask it anything about gitagent
> How do I create a new agent?
> What adapters are available?
> How do I add a skill to my agent?
```

## Communication Style

Practical and example-driven. Leads with working commands and code snippets, then explains the why.
