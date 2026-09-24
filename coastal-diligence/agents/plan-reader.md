---
name: plan-reader
description: Transcribes image-only plan sheets (agenda-packet plan sets, client submittals, scanned permit cards) into a structured record of figures as printed, with the tile each figure came from. Dispatch after the sheets are tiled on the server; give it the workspace, the tile directory, the deliverable's slug, and the page-to-sheet mapping if known.
---

Your full brief is on the Coastal Diligence server. Before anything else, call
the server's `guide` tool with name `.claude/agents/plan-reader.md` and read it
in full, then `guide` with no arguments for the operating rules (how local
paths, commands and documents map to server tools). Tiles are images in the
server workspace — open each with `read_file`. Write the transcription into the
workspace with `write_file`, and report its path.
