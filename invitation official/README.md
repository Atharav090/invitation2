# 💍 Royal Indian Wedding Invitation

A premium, modern Indian wedding invitation built as a single `index.html` file. Zero dependencies to install — just deploy.

---

## 🚀 Deploy to Vercel (2 mins)

### Option A — Drag & Drop (Easiest)
1. Go to [vercel.com](https://vercel.com) and sign in
2. Click **"Add New Project"** → **"Deploy"**
3. Drag the folder containing `index.html` + `vercel.json` into the upload zone
4. Click **Deploy** — done ✅

### Option B — GitHub + Vercel
1. Push this folder to a GitHub repo
2. Import the repo in Vercel
3. Vercel auto-detects it as a static site
4. Deploy 🎉

---

## 🎨 Customise the Invitation

Open `index.html` in any text editor and find/replace:

| Placeholder | What to change |
|---|---|
| `Priya` | Bride's first name |
| `Arjun` | Groom's first name |
| `Priya Sharma` | Bride's full name |
| `Arjun Mehta` | Groom's full name |
| `November 28, 2025` | Wedding date |
| `The Grand Leela Palace` | Venue name |
| `Connaught Place, New Delhi` | Venue address |
| `Mr. Ramesh & Mrs. Sunita Sharma` | Bride's parents |
| `Mr. Vijay & Mrs. Kavita Mehta` | Groom's parents |
| `2025-11-28T18:00:00` | Countdown target (ISO date) |
| Google Maps embed URL | Your actual venue coords |

### Change Photos
Replace the `src="https://images.unsplash.com/..."` URLs with your own hosted image URLs (upload to Cloudinary, ImgBB, or any CDN).

### Change Music
Replace the audio `src` in the `<audio>` tag with your own `.mp3` URL.

---

## ✨ Features Included
- 🔐 Entry screen with door-open animation
- 💑 Couple introduction with framed portraits
- 📅 Wedding details + event timeline
- ⏳ Live countdown timer
- 🖼️ Horizontal photo gallery/slider
- 🗺️ Google Maps embed + directions
- 💌 Interactive RSVP form
- 🎵 Floating music button (auto-plays on open)
- 🙏 Closing section with family names
- 🌸 Floating petal animation
- 📱 Fully responsive
- ✦ Mandala watermarks, gold accents, Indian arch motif

---

## 🛠 Tech
- Pure HTML + CSS + Vanilla JS (no build step needed)
- AOS.js for scroll animations (loaded from CDN)
- Google Fonts: Cormorant Garamond + Playfair Display + Josefin Sans
- Deployable on Vercel, Netlify, or any static host
