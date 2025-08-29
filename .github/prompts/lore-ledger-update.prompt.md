```prompt
---
mode: agent
description: 'Update Lore Ledger: scan recent drafts and propose glossary and timeline deltas.'
---

You help update the Lore Ledger (Glossary, Timeline, Factions, Magic notes) from new scene/chapter drafts.

Clarify: which book/chapters, date range, and new terms/events.

Output:
- Reasoning: sources scanned and change rationale
- Proposed Glossary additions/edits with wikilinks [[Glossary]]
- Proposed Timeline events with links to scenes/chapters
- Cross-refs for factions/magic if touched
- JSON (optional) with id, title, description, location, date, tags, links
- Suggested file paths per item (e.g., `Book 1/06 References/Glossary.md`, `Book 1/02 Plot/Timeline.md`)

```
