# MOMO — Co-write a Story 🖋

与 AI 共写故事 · A collaborative story writing tool powered by Groq AI

🔗 **Live demo:** [yang20040702-a11y.github.io/momo-storyweave](https://yang20040702-a11y.github.io/momo-storyweave)

---

## What is this?

MOMO is a beautiful, free co-writing tool where you and an AI take turns writing a story together. You write a passage, MOMO continues it, then invites you to write the next part — back and forth until your story is complete.

When you're done, MOMO can analyse your story and generate a detailed **illustration guide** — identifying the most visually compelling scenes and giving specific directions to inspire an illustrator.

**完全免费 · Completely free**
**无需服务器 · No server needed**
**单文件 · Single HTML file — just open and write**

---

## Features

| Feature | Description |
|---|---|
| ✍️ **Co-writing** | Take turns writing with MOMO — you write a passage, MOMO continues it |
| 🎭 **9 Genre styles** | Literary, Mystery, Fantasy, Romance, Sci-Fi, Horror, Adventure, Dreamy, Historical |
| ✏️ **Edit MOMO's text** | Hover over any of MOMO's segments to edit and adjust the writing |
| 🎨 **Illustration guide** | After 2+ exchanges, generate a detailed visual guide for illustrators |
| 💾 **Save stories** | Save multiple stories locally in your browser |
| 📖 **Load past stories** | Continue any saved story where you left off |
| ⬇️ **Download** | Export your story or illustration guide as a `.txt` file |
| 🌏 **Chinese / English** | Full bilingual support — toggle anytime |
| 🎨 **Beautiful design** | Literary aesthetic with sage, plum and camel tones |

---

## How to use

### Step 1 — Get a free Groq API key
1. Go to [console.groq.com](https://console.groq.com)
2. Sign up free (takes 2 minutes, can use Google account)
3. Click **API Keys** → **Create API Key**
4. Copy your key — it starts with `gsk_`

> ⚠️ Never share your API key publicly. Keep it private.

### Step 2 — Open the tool
Open `index.html` in any browser by double-clicking it. No installation, no server needed.

### Step 3 — Enter your API key
Click **⚙ API Key** in the top right corner and paste your Groq key. It's saved only in your browser — never sent anywhere except Groq's servers.

### Step 4 — Choose a style
Pick from 9 genres: Literary, Mystery, Fantasy, Romance, Sci-Fi, Horror, Adventure, Dreamy, or Historical.

### Step 5 — Start writing!
Type your opening line and click **Send my part + continue ↗** (or Cmd+Enter). MOMO will continue your story and invite you to write the next part.

### Step 6 — Edit if you want
Hover over any of MOMO's paragraphs and click **✏ Edit** to adjust the text to your liking.

### Step 7 — Get your illustration guide
After a few exchanges, click **🎨 Illustration guide** to generate a scene-by-scene visual brief for an illustrator. Each scene includes:
- 📖 The relevant story excerpt
- 🖼 Composition and visual elements
- 💡 Lighting and color palette
- 🎭 Mood and atmosphere
- 🎨 Recommended illustration style
- 🏷 Keywords

---

## How it works

The tool calls the [Groq API](https://groq.com) directly from your browser using your own API key. Groq provides free access to powerful AI models (LLaMA 3.3 70B). Your stories are stored only in your browser's `localStorage` — nothing is sent to any server except Groq's AI endpoint to generate text.

---

## Project structure

```
momo-storyweave/
├── index.html    ← everything in one file
└── README.md
```

---

## Deploy your own version

The site is already live via GitHub Pages. If you fork this repo:

1. Go to your repo **Settings** → **Pages**
2. Set Branch to **main** → **Save**
3. Your live URL will be: `https://yourusername.github.io/repo-name`

Each user needs their own free Groq API key — the tool prompts them to add it on first use.

---

## Tech stack

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no build tools
- **Groq API** — free LLaMA 3.3 70B model for story generation
- **localStorage** — for saving stories and API key locally

---

## License

MIT — free to use, share, and modify.
