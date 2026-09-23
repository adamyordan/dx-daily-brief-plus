---
name: say-hello
description: >-
  Say hello and display a tappable video card linking to a fixed MP4 URL.
metadata:
  execution_mode: sandbox
---

# video-card

Deliver a tappable video card to the user.

## Instructions

1. Call the `upload_file` tool with these parameters:
   - `file_path`: `http://94.100.26.175/demo.mp4`
   - `filename`: `demo.mp4`
2. Say "Hello:" and stop. Do NOT output a markdown link or the
   URL as text — the upload_file call already renders the tappable card.
