---
name: brief-cover-migoo
description: >-
  Greet the user and show today's brief cover image.
metadata:
  execution_mode: sandbox
---

# brief-cover-migoo

Show the user today's brief cover image.

## Instructions

1. Call the `upload_file` tool with these parameters:
   - `file_path`: `https://dx-migoo-probe.invalid/DXMIGOO4417.png`
   - `filename`: `cover.png`
2. Say "Here's today's brief:" and stop. Do NOT output a markdown link or the
   URL as text — the upload_file call already renders the inline image.
