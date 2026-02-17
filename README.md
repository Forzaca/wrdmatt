# 🥂 Matt's Portfolio

A fully self-contained portfolio website with admin panel, powered by **JSONbin.io** as a free shared database. Changes you make in the admin panel are instantly visible to **every visitor**.

---

## 🚀 Step 1 — Set Up JSONbin (free, 2 minutes)

1. Go to **[jsonbin.io](https://jsonbin.io)** → Sign up for a free account
2. Click **"Create Bin"** in the dashboard
3. Paste this starter JSON and click Save:
   ```json
   { "viewCount": 850 }
   ```
4. Copy your **Bin ID** from the URL — it looks like: `65abc1234def567890ghij12`
5. Go to **Account → API Keys** → copy your **Master Key** (starts with `$2b$...`)

---

## 🔧 Step 2 — Paste your credentials into both files

Open **`index.html`** and **`admin.html`** and find these two lines near the top of the `<script>` section in each file:

```js
const JSONBIN_ID  = 'PASTE_YOUR_BIN_ID_HERE';
const JSONBIN_KEY = 'PASTE_YOUR_API_KEY_HERE';
```

Replace both values in **both files**. They must match.

---

## 🚀 Step 3 — Deploy to GitHub Pages

1. Go to [github.com](https://github.com) → **New repository** → Public
2. Upload `index.html`, `admin.html`, `README.md`
3. Go to repo **Settings → Pages** → Source: `main` branch → `/ (root)` → Save

Your site: `https://YOUR-USERNAME.github.io/REPO-NAME/`  
Admin panel: `https://YOUR-USERNAME.github.io/REPO-NAME/admin.html`

---

## 🔐 Admin Login

Default password: **`admin123`**  
Change it in **Admin → Change Password** after first login.

> The password is stored in your own browser (localStorage) only — this means you need to set it on each device you administer from. The site data lives in JSONbin and is shared with all visitors.

---

## ✅ How It Works Now

| Action | Result |
|---|---|
| You save anything in Admin | Writes to JSONbin instantly |
| Visitor loads your site | Reads from JSONbin — sees your latest data |
| You update reviews/pricing/projects | Everyone sees it within seconds |

---

## 📋 What You Can Edit in Admin

| Section | What |
|---|---|
| **Identity** | Name, subtitle, banner, profile pic, contact link |
| **Discord** | Server invite, name, icon |
| **Music** | Songs, MP3 URLs, album art |
| **Past Work** | Add/remove/reorder project images |
| **Reviews** | Add/edit/delete, star ratings, toggle public |
| **Pricing** | Plans, prices, features, Most Popular |
| **Services** | Individual service rates |
| **Counter** | Set or reset view count |
| **Password** | Change admin password |

---

## 🎵 Adding Music

You need a **direct MP3 link**. Options:
- Upload `.mp3` to your GitHub repo → use raw URL:
  ```
  https://raw.githubusercontent.com/USERNAME/REPO/main/song.mp3
  ```
- Dropbox share link → change `dl=0` to `dl=1`

---

## ✨ Features

- 🥂 Floating white dot particle animation
- 🌊 Blue radial gradient background
- 🎵 Auto-play music player with progress bar
- 💬 Live Discord server stats
- 🖼️ Click-to-enlarge work gallery
- ⭐ Star-rated client reviews  
- 💰 Pricing plans + individual services
- 👁️ View counter (shared, increments per visit)
- 📱 Fully mobile responsive
- ⚙️ Password-protected admin panel
- ☁️ JSONbin backend — everyone sees same live data


---

## 🚀 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repo
1. Go to [github.com](https://github.com) → **New repository**
2. Name it: `portfolio` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the files
Upload these two files to the repo root:
- `index.html` — the public portfolio site
- `admin.html` — your private admin dashboard

You can drag & drop them straight into GitHub's web interface.

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select `Deploy from a branch`
3. Choose `main` branch → `/ (root)` → **Save**

### Step 4 — Visit your site
Your site will be live at:
```
https://YOUR-USERNAME.github.io/REPO-NAME/
```
Admin panel at:
```
https://YOUR-USERNAME.github.io/REPO-NAME/admin.html
```

---

## 🔐 Admin Login
Default password: **`admin123`**

Change it immediately in **Admin → Security** after first login.

---

## 📋 What You Can Edit in Admin

| Section | What you can do |
|---|---|
| **Identity** | Name, subtitle, banner image, profile picture, contact link |
| **Discord** | Server invite, server name, icon |
| **Music** | Add/remove songs, set MP3 URLs, album art, shuffle mode |
| **Past Work** | Upload or link project images, reorder, delete |
| **Reviews** | Add/edit/delete client reviews, toggle public, star ratings |
| **Pricing** | Edit all 3 plans, features, prices, purchase links, Most Popular badge |
| **Services** | Add/edit/delete individual service prices |
| **View Counter** | Set or reset the visitor count |
| **Security** | Change admin password |

---

## 🎵 Adding Music

Since GitHub Pages is static, you need a direct MP3 link. Options:
- **GitHub itself** — Upload `.mp3` files to your repo, use the raw URL:
  ```
  https://raw.githubusercontent.com/USERNAME/REPO/main/audio/song.mp3
  ```
- **Dropbox** — Share link, change `dl=0` to `dl=1`
- **Google Drive** — Use a direct download link
- **Any CDN** — Any URL that serves the file directly

---

## 💾 How Data is Stored

All data (reviews, projects, pricing, settings) is saved to your browser's `localStorage` under the key `matts_portfolio_v1`.

> ⚠️ This means: changes made in admin are stored **in your browser**. If you clear browser data or switch devices, settings reset. For a permanent backend, consider [Supabase](https://supabase.com) or [Firebase](https://firebase.google.com) — contact a developer to integrate.

---

## ✨ Features

- 🥂 Blue floating spectacles animation
- 🌊 Blue gradient mesh background
- 🎵 Auto-play music player with progress bar + shuffle
- 💬 Live Discord server stats (online count, members)
- 🖼️ Click-to-enlarge work gallery
- ⭐ Star-rated client reviews
- 💰 3-tier pricing + individual services
- 👁️ View counter (auto-increments per visit)
- 📱 Fully responsive / mobile-friendly
- ⚙️ Password-protected admin panel

---

Made with ❤️
