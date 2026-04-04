# ✦ Pam Plus — Constellation Companion

> A warm, thoughtful AI conversation companion with a cosmic identity.

![Pam Plus](https://img.shields.io/badge/Pam%20Plus-Constellation%20Series-6ea4ff?style=flat-square&labelColor=050818)

---

## What is Pam Plus?

Pam Plus is a beautiful, single-page web app that gives you access to a warm AI conversation companion named Pam. She's built for real, flowing back-and-forth dialogue — not task completion. Think of her as a thoughtful friend who's always ready to listen, reflect, and explore ideas with you.

---

## Live Site

Once deployed to GitHub Pages, your site will be live at:

```
https://YOUR-USERNAME.github.io/pam-plus/
```

---

## How to Deploy (Step by Step)

### 1. Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up — it's free.

### 2. Create a New Repository
- Click the **+** icon → **New repository**
- Name it: `pam-plus`
- Set it to **Public**
- Click **Create repository**

### 3. Upload the File
- In your new repo, click **Add file → Upload files**
- Drag and drop `index.html` from this folder
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to your repo **Settings** tab
- Click **Pages** in the left sidebar
- Under **Source**, select `main` branch and `/ (root)` folder
- Click **Save**

### 5. Visit Your Site
After a minute, your site will be live at:
```
https://YOUR-USERNAME.github.io/pam-plus/
```

---

## How Users Use Pam Plus

1. Visit the website
2. On first visit, a prompt will ask for an **Anthropic API key**
3. Get a free key at [console.anthropic.com](https://console.anthropic.com)
4. Paste the key — it's saved in the browser (never sent anywhere except Anthropic)
5. Start talking to Pam!

---

## API Key & Privacy

- Each visitor uses **their own Anthropic API key**
- Keys are stored in the visitor's browser `localStorage` only
- No data is collected or stored by the site
- Conversations go directly from the visitor's browser to Anthropic's API

---

## Tech Stack

- Pure HTML, CSS, JavaScript — no build tools, no dependencies
- Anthropic Claude API (`claude-sonnet-4-20250514`)
- Canvas-based animated starfield
- Google Fonts (Orbitron + Inter)

---

## Customization

Open `index.html` and find the `SYSTEM` constant near the bottom to edit Pam's personality and prompt. Everything is in one self-contained file.

---

*Pam Plus · Constellation Series*
