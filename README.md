# தமிழ் எழுத்துக்கள் — 247
### Interactive Tamil Alphabet Learning Chart
 
A distraction-free, single-page Tamil alphabet reference built for focused learning on laptop and desktop screens. No accounts, no ads, no installs — just open and learn.
 
---
 
## What It Is
 
A complete interactive chart of all **247 Tamil characters** — 12 vowels (உயிர்), 18 consonants (மெய்), and 216 combined (உயிர்மெய்) characters — organised the same way Tamil is traditionally taught.
 
Designed for:
- Parents teaching children at home
- Tamil school teachers
- Students learning Tamil script from scratch
- Heritage learners reconnecting with the language
Best experienced on a **laptop or desktop** (1280px+ wide). The full alphabet table needs horizontal space to be readable; a large screen is the point.
 
---
 
## Features
 
### Alphabet Table
- All 247 characters in a structured grid — vowels across the top, consonants down the left, combined forms filling the body
- Click any character to open a detail panel with pronunciation, IPA, romanisation, stroke order, memory tips, example words, and fun facts
- Filter by category: **All · Vowels / உயிர் · Hard / வல்லினம் · Soft / மெல்லினம் · Middle / இடையினம்**
- Search by character or romanisation
- Mark characters as **Learned** — a checkmark appears on the cell, and the header chip tracks your count
### Category Colours
| Category | Background | Text |
|---|---|---|
| Vowels / உயிர் | `#FFF4CC` | `#8A6D00` |
| Pure Consonants / மெய் | `#F0E6FF` | `#5A3E99` |
| Hard / வல்லினம் (க ச ட த ப ற) | `#FFE5E5` | `#B00020` |
| Soft / மெல்லினம் (ங ஞ ண ந ம ன) | `#E6F7EC` | `#1B7F3B` |
| Middle / இடையினம் (ய ர ல வ ழ ள) | `#E6F0FF` | `#1A4FBF` |
| ஃ Āyuta Eḻuttu | Tomato `#FF6347` | white |
 
### Memory Match 🃏
A card-flipping game using the formation formula — **க் + அ = ?** (pure consonant + vowel = combined character). Mix mode picks 8 random pairs. Tracks time and moves.
 
### Challenge Quiz 🎯
Formula-based multiple choice: given `க் + அ = ?`, pick the correct combined character from four options. Includes a 12-second timer per question, 3 lives, streak tracking, and a live score chip in the header banner.
 
### Light / Dark Mode
Toggle with the ☀️ button. Dark mode is the default; light mode uses the pastel category palette for a softer look.
 
### Feedback
A 💬 Feedback button (bottom-right) collects name, role, age range, source, star rating, and comments — submitted directly to Netlify Forms, no third-party service required.
 
---
 
## How to Use Locally
 
No build step. No dependencies. Just open the file.
 
```bash
# Clone or download the repo, then:
open index.html
# or drag index.html into any browser
```
 
---
 
## Deploying to Netlify
 
The feedback form uses **Netlify Forms** — it only works when served from Netlify (not from a local file). Everything else works locally.
 
```bash
# Option 1 — Drag and drop
# Go to netlify.com → drag the index.html file onto the deploy area
 
# Option 2 — Connect GitHub
# Push index.html to a GitHub repo
# In Netlify: New site → Import from Git → select repo → deploy
# Build command: (leave empty)
# Publish directory: . (or the folder containing index.html)
```
 
Once deployed, Netlify auto-detects the feedback form. View submissions at:
**Netlify Dashboard → Your Site → Forms → feedback**
 
To receive email notifications: **Forms → Notifications → Add email**.
 
---
 
## Tech Stack
 
| | |
|---|---|
| Structure | Pure HTML5 — single file, no framework |
| Styling | Inline CSS — no external stylesheet |
| Logic | Vanilla JavaScript — no libraries |
| Fonts | [Noto Sans Tamil](https://fonts.google.com/noto/specimen/Noto+Sans+Tamil) via Google Fonts |
| Forms | Netlify Forms (static, serverless) |
| Hosting | Netlify (recommended) or any static host |
 
**No build process. No npm. No bundler.** The entire app is one `.html` file (~260 KB including the header image encoded inline).
 
---
 
## Design Principles
 
- **Distraction-free** — no sidebar, no notifications, no clutter. The table is the UI.
- **Big-screen first** — the full 247-character grid needs width. Mobile is not the target.
- **Tamil-first** — characters are large and central. Romanisation is secondary.
- **Progressive learning** — explore freely, mark learned, quiz yourself when ready.
- **Zero friction** — no login, no app install, no cookies banner. Open and start.
---
 
## File Structure
 
```
index.html        ← entire app (HTML + CSS + JS + inline image)
README.md         ← this file
tamilscript.jpg   ← source image for the header banner (embedded at build time)
```
 
---
 
## Roadmap / Ideas
 
- [ ] Audio pronunciation for every character (Web Speech API or recorded clips)
- [ ] Stroke order animations
- [ ] Progress persistence via localStorage
- [ ] Print-friendly A4 worksheet export
- [ ] Mobile-responsive layout (tablet minimum)
- [ ] Spaced repetition for the learned set
---
 
## Contributing
 
Found a mistake in a romanisation, stroke description, or example word? Open an issue or submit a pull request. Tamil script corrections especially welcome from native speakers.
 
---
 
## Licence
 
MIT — free to use, adapt, and share.
