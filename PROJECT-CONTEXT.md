# 📋 Word Counter Pro — Project Context

> **Is file ka maqsad:** Agar main (user) kisi nayi Claude chat me changes karwana chahun, to yeh file de dunga (ya iska path bata dunga). Isse Claude ko poora project foran samajh aa jayega aur kaam accurate + fast hoga.

---

## 🎯 Project kya hai
**Word Counter Pro** — ek browser-based word counter tool. Sirf HTML/CSS/JavaScript (ek hi `index.html` file). Koi backend/server nahi — browser me hi chalta hai.

## 📍 Locations (sab permanent, kisi chat par depend nahi)
- **Local (laptop):** `D:\projects\word-counter\`
- **GitHub:** https://github.com/mfaizan13-maker/word-counter
- **Live website (Vercel):** https://word-counter-beta-jet.vercel.app/
- Vercel **auto-deploy** hai: GitHub par push karte hi live site khud update ho jati hai.

## 📂 Files
- `index.html` — poora tool (HTML + CSS + JavaScript, sab ek file me)
- `README.md` — project ki tafseel
- `.gitignore` — git ke liye ignore list
- `PROJECT-CONTEXT.md` — yeh file (context)

## ✨ Current features
- Stats: words, characters, characters (no spaces), sentences, paragraphs, numbers, unique words, average word length, reading time
- 🔑 Keyword Density (top words + %) — SEO ke liye
- 🔁 Repetition Checker (dohraaye gaye 3-word phrases)
- 🔠 Case converter: UPPERCASE / lowercase / Title Case
- 📋 Copy results button
- ✨ "Try sample" button (example text load karta hai)
- 🎨 Animated premium theme: floating background orbs, driving-car motif (header me left→right chalti hai), gradient shimmer title, rising particles, rolling (count-up) numbers, hover effects

## 🎨 Design notes
- Dark theme, indigo (#6366f1) → cyan (#06b6d4) gradient accents
- Car ko subtle/elegant rakha jata hai (bhaddi detailed car pasand nahi aayi thi)
- User ko obvious/visible animations pasand hain (subtle bohot halki lagti hain)

## 🔧 Changes kaise karein aur live karein
1. `index.html` edit karein (VS Code me)
2. Terminal me (folder ke andar):
   ```
   git add .
   git commit -m "kya change kiya"
   git push
   ```
3. Vercel khud live site update kar dega (~30-60 sec)

## 👤 User ke baare me (taake jawab munasib ho)
- Naam: Faizan. SEO/backlink freelance kaam (Fiverr) karta hai.
- **Coding nahi aati** — changes AI (Claude) ko bata kar karwata hai, khud code nahi likhta.
- **Roman Urdu/Hindi** me baat karta hai; jawab bhi usi style me (simple, emoji, tables) chahiye.
- Beginner hai — cheezein aasan alfaz me samjhani chahiye, over-technical nahi.
- SaaS/tools banana seekh raha hai. Dev environment set: Python 3.13, Node.js 24, Git, VS Code, Postman, SQLite.

## 💡 Aage ke possible ideas
- Aur features (word/character limit, export, dark/light toggle)
- Asli plagiarism checker (paid API + backend chahiye — future)
- Naya tool (Step 3: database wala tool — data save karna)
