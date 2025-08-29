---
title: Obsidian Tips for Book 1
---

# Obsidian Tips

- Use Templates core plugin; set Hotkeys for quick insert.
- Dataview examples:
  - List scenes by status: `table file.mtime as Modified from "01 Drafts/Scenes" where contains(tags, "status/draft")`
  - Link counts by character: `table length(list(from("01 Drafts/Scenes") where contains(file.content, link(this.file.name))))`
- Use Canvas for plot/arc mapping if desired.
