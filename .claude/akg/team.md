# akg-profiles — Claude Code

## Getting started
<!-- What a new developer does first. -->

## Tools to install

- **rtk** — CLI proxy that filters command output before it reaches Claude (60-90% fewer tokens). `brew install rtk && rtk init -g`, then restart Claude Code.
- **caveman** — ultra-compressed answer mode, fewer output tokens. `/plugin marketplace add JuliusBrussee/caveman` then `/plugin install caveman@caveman`.
- **ponytail** — makes Claude write the smallest code that solves the task, reusing existing code first. `/plugin marketplace add DietrichGebert/ponytail` then `/plugin install ponytail@ponytail`.
- **gstack** — slash commands giving Claude team roles (CEO, eng manager, QA, release…) to plan, review, test and ship. `git clone --single-branch --depth 1 https://github.com/garrytan/gstack.git ~/.claude/skills/gstack && cd ~/.claude/skills/gstack && ./setup`
- **agent-skills** — production-grade engineering skills across the dev lifecycle. `/plugin marketplace add addyosmani/agent-skills` then `/plugin install agent-skills@addy-agent-skills`.
- **omniroute** — local AI gateway: one endpoint for many providers, automatic fallback on quota or failure. `npm install -g omniroute`, run `omniroute` (dashboard on http://localhost:20128), then launch Claude Code through it: `omniroute run claude --model <provider/model>`.
- **graphify** — turns the codebase (code, docs, schemas, configs) into a knowledge graph Claude queries instead of grepping. `uv tool install graphifyy` (or `pipx install graphifyy`), then `graphify install`.

<!-- Projects deploy to containers: docker / kubectl. No ticket tracker. -->

## Rules
<!-- Team rules that are not in the questions. -->
