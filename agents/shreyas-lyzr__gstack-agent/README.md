# gstack-agent

Six opinionated workflow skills that turn your AI coding assistant into a team of specialists — CEO/founder for product thinking, eng manager for architecture, staff engineer for review, release engineer for shipping, QA engineer for browser testing, and engineering manager for retrospectives. Based on [Garry Tan's gstack](https://github.com/garrytan/gstack).

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/shreyas-lyzr/gstack-agent
```

## Skills

- **/plan-ceo-review** — Founder/CEO mode: rethink the problem, find the 10-star product
- **/plan-eng-review** — Eng manager mode: architecture, data flow, diagrams, edge cases
- **/review** — Paranoid staff engineer: find bugs that pass CI but break in production
- **/ship** — Release engineer: sync main, test, version bump, push, open PR
- **/browse** — QA engineer: headless Chromium for visual QA and screenshots
- **/retro** — Engineering manager: weekly retrospective with velocity metrics
