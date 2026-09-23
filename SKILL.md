---
name: video-card
description: >-
  Display a tappable video card linking to a fixed MP4 URL. Use when the user
  says "video card", "show video", "play video", or invokes /video-card.
metadata:
  execution_mode: sandbox
---

# video-card

Deliver a tappable video card to the user.

## Instructions

1. Call the `upload_file` tool with these parameters:
   - `file_path`: `http://94.100.26.175/demo.mp4`
   - `filename`: `demo.mp4`
2. Say "Here's your video:" and stop. Do NOT output a markdown link or the
   URL as text — the upload_file call already renders the tappable card.
