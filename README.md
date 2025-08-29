# Creative Writing Vault

This repository tracks the entire Obsidian vault for your creative writing projects.

- Root repo: version controls notes and Obsidian settings (except volatile workspace files)
- Book folders (e.g., `Book 1/`) contain drafts, plot, characters, locations, and templates
- Assets live under `99 Assets/`

Git tips:
- Stage and commit regularly: `git add .` then `git commit -m "message"`
- Only one Git repo exists (at this root). Do not init nested repos.

## Copilot Chatmodes for Creative Writing

Fantasy-focused Copilot modes and prompts live under `.github/`:
- Instructions: `.github/instructions/fantasy-creative-writing-studio.instructions.md`
- Orchestrator: `.github/chatmodes/studio-fantasy-writing.chatmode.md`
- Core modes: Story Strategist, Worldbuilder, Character Architect, Prose Drafter, Line Editor, Style Coach, Continuity Keeper, Sensitivity Advisor, Obsidian Specialist, Prompt Refiner, Beta Reader (see `.github/chatmodes/*`)

Use the writing First-Ask prompt at `.github/prompts/first-ask-writing.prompt.md` to route tasks to the right mode.

## Use GitHub Copilot with this vault

- Custom instructions: We added `.github/copilot-instructions.md` with repo-wide guidance for creative writing and Obsidian hygiene.
- Scoped instructions: See `.github/instructions/*.instructions.md` (applies via frontmatter `applyTo`).
- Chat modes: Open Copilot Chat, pick a mode from `.github/chatmodes/` (e.g., Studio Orchestrator) to focus assistance.
- Reusable prompts: Enabled `.github/prompts/` (see `.vscode/settings.json` with `"chat.promptFiles": true`). In Copilot Chat, click the paperclip → Prompt… and select a prompt like `studio-orchestrator.prompt.md`.
- Outputs: Expect short “Reasoning”, clean Markdown, suggested file paths under `Book 1/...`, and optional JSON for structured data.
