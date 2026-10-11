# akg-profiles

Team source for [akg](https://github.com/anthonykgross/akg): shared Claude Code conventions and plugins. No code.

## Use it in a project

Run `/akg:setup`, answer "Yes, I have one" when asked for a team source, and give this repo's URL
(`github:anthonykgross/akg-profiles`). The answers in `.claude/akg/config.yaml` become the project's defaults.

## Maintain it

- **Conventions**: `.claude/akg/config.yaml`.
- **Plugins**: add an entry to `.claude-plugin/marketplace.json`.
- **Developer instructions**: `.claude/akg/team.md` (shown by `/akg:team`).
- **Team questions**: `.claude/akg/questions.md` (same format as the akg catalog).
