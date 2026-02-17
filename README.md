# 🥂 Matt's Portfolio

A fully self-contained portfolio website with admin panel — no server needed. Runs 100% on GitHub Pages using `localStorage`.

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
