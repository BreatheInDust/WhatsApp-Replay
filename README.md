WhatsApp Replay (GitHub Pages)

A fully client-side web app that lets you upload a WhatsApp chat export ZIP file and view it in a clean, interactive WhatsApp-style interface.

This tool runs entirely in the browser and is designed for GitHub Pages deployment — no backend, no database, no servers.


---

🚀 Features

📦 Upload WhatsApp .zip export files

💬 Parse .txt chat logs into structured messages

🖼️ Inline image previews inside chat bubbles

🎧 Voice note playback support

🎥 Video playback support

🔍 Message search functionality

📅 Jump to dates / scroll navigation

🌙 Light / dark mode support

📱 Responsive WhatsApp-style UI



---

⚙️ How It Works

1. User uploads a WhatsApp export ZIP file


2. Browser extracts it using JavaScript (no backend)


3. Chat .txt file is parsed into structured message objects


4. Messages are rendered in a WhatsApp-style interface


5. Media files are linked and displayed where available




---

🧱 Tech Stack

HTML5

CSS3

Vanilla JavaScript

JSZip (for ZIP extraction)



---

📁 Supported Format

Typical WhatsApp export format:

12/01/2025, 14:32 - John: Hello
12/01/2025, 14:33 - Jane: Hi!

Supports:

Multiline messages

System messages

Attachments (images, audio, video references)



---

🐞 Known Issues

This project is still in active development.

Group chat perspective bug

Messages in group chats may occasionally render on the wrong side (sender alignment issue).


Parsing edge cases

Some regional WhatsApp export formats may not parse correctly.

Multiline or malformed messages may break grouping in rare cases.


Media linking

Occasionally attachments may fail to link if filenames differ slightly.



---

🔒 Privacy

All processing happens locally in your browser

No data is uploaded anywhere

Your chats never leave your device



---

📌 Deployment

Deploy via GitHub Pages:

1. Push repo to GitHub


2. Enable GitHub Pages in settings


3. Select main branch / root


4. Done




---

⚠️ Legal / License Notice

This project is provided under a strict custom license.

Personal and educational use only

No commercial use

No redistribution or public forks

No monetisation or derivative publishing allowed


See LICENSE.md for full terms.

This project is not affiliated with WhatsApp or Meta Platforms Inc.


---

🧠 Final Note

WhatsApp Replay is a local-first chat visualisation tool designed to make exported chat logs readable, searchable, and usable in a modern interface.
