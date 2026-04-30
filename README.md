# MOMO — Co-write a Story 🖋

与 AI 共写故事 · A collaborative story writing tool powered by Groq AI

---

## What is this?

MOMO is a beautiful, free co-writing tool where you and an AI take turns writing a story together. You write a passage, MOMO continues it, then invites you to write the next part — back and forth until your story is complete.

**完全免费 · Completely free**  
**无需服务器 · No server needed**  
**单文件 · Single HTML file**

---

## How to use

### 1. Get a free Groq API key
Go to [console.groq.com](https://console.groq.com), sign up free, and create an API key. It takes about 2 minutes.

### 2. Open the tool
Just open `index.html` in any browser. No installation needed.

### 3. Enter your API key
Click **⚙ API Key** in the top right and paste your Groq key. It's saved locally in your browser — never shared anywhere.

### 4. Start writing!
Type your opening line and click **Send my part + continue ↗**. MOMO will continue your story and invite you to write the next part.

---

## Features

- ✍️ **Co-write** — take turns writing with MOMO
- 💾 **Save stories** — saved locally in your browser
- 📖 **Load past stories** — continue where you left off
- ⬇️ **Download** — export your story as a .txt file
- 🌏 **Chinese / English** — language toggle built in
- 🎨 **Beautiful design** — literary aesthetic with sage, plum and camel tones

---

## How it works

The tool calls the [Groq API](https://groq.com) directly from your browser using your own API key. Groq provides free access to powerful AI models (LLaMA 3.3 70B). Your stories are stored only in your browser's localStorage — nothing is sent to any server except Groq's AI endpoint.

---

## Project structure

```
momo-storyweave/
└── index.html    ← everything is in this one file
```

---

## Deploy online (optional)

Want to share a live link with friends? Upload to any static hosting:

- **GitHub Pages** — push to GitHub, enable Pages in settings → free public URL
- **Netlify** — drag and drop the file → instant URL
- **Vercel** — connect GitHub repo → auto-deploy

Note: each user needs their own free Groq API key.

---

## License

MIT — free to use, share, and modify.
