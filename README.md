# Matt's Portfolio - Setup Guide

## 📁 File Structure

```
portfolio/
├── index.html          (Main portfolio file)
├── images/             (Image folder)
│   ├── Banner-Photo.png
│   ├── Profile-Photo.png
│   ├── Project1.png
│   ├── Project2.png
│   ├── Project3.png
│   ├── Project4.png
│   ├── Project5.png
│   ├── Project6.png
│   ├── Project7.png
│   ├── Project8.png
│   ├── Project9.png
│   └── Project10.png
└── README.md          (This file)
```

## 🚀 Quick Start

1. **Add Your Images**
   - Replace the placeholder files in the `images/` folder with your actual images
   - Keep the same filenames or update them in the `PORTFOLIO_DATA` section

2. **Edit Your Content**
   - Open `index.html` in a text editor
   - Find the `PORTFOLIO_DATA` object at the top of the `<script>` section
   - Update the values as needed

## ✏️ Editing Your Portfolio

### Profile Information
```javascript
meta: {
  tabTitle: "Matt's Portfolio",      // Browser tab title
  name: "Matt",                       // Your display name
  title: "Designer | Developer",     // Your subtitle
  contactDiscordId: "1272978844248178730",  // Your Discord ID
  bannerUrl: "images/Banner-Photo.png",     // Banner image
  pfpUrl: "images/Profile-Photo.png"        // Profile picture
}
```

### Discord Server
```javascript
discord: {
  inviteCode: "bigsky",              // Your server invite code
  serverName: "Big Sky Roleplay",    // Server name
  iconUrl: "https://..."             // Server icon URL
}
```

### Music Playlist
```javascript
playlist: [
  {
    title: "Telekinesis",
    artist: "Travis Scott",
    cover: "https://...",  // Album cover URL
    url: "https://..."     // MP3 file URL
  }
  // Add more songs...
]
```

### Projects (Using Local Images)
```javascript
projects: [
  { url: "images/Project1.png", name: "Project 1" },
  { url: "images/Project2.png", name: "Project 2" },
  // Add or remove projects as needed...
]
```

### Client Reviews (3 Editable Reviews)
```javascript
reviews: [
  {
    id: 1,
    name: "sharky2091",
    avatar: "https://...",
    stars: 5,                          // 1-5 stars
    feedback: "Great designer...",     // Review text
    date: "2026-02-19"                 // Review date
  },
  // Edit these 3 reviews...
]
```

### Service Pricing
```javascript
services: [
  { label: "Per Livery", price: "130", unit: "rbx" },
  { label: "Per Photo", price: "100", unit: "rbx" },
  // Edit or add more services...
]
```

## ✨ Key Features

- ✅ **Music dots always animate** (no pausing on hover)
- ✅ **Local image support** (images folder included)
- ✅ **3 editable reviews** (directly in the code)
- ✅ **No admin panel** (simple file-based editing)
- ✅ **No plans section** (removed completely)
- ✅ **Persistent smooth scrolling pricing** (always animating)
- ✅ **Custom cursor**
- ✅ **Splash screen entrance**
- ✅ **Reveal animations**
- ✅ **Discord server integration**
- ✅ **Music player**
- ✅ **Project portfolio**
- ✅ **View counter**

## 🎨 Customization Tips

1. **Images**: Use high-quality PNG or JPG files
   - Banner: Recommended 1400x280px
   - Profile: Recommended 300x300px
   - Projects: Recommended 900x260px

2. **Colors**: All colors are defined in CSS variables at the top of the file
   ```css
   :root{
     --bl:#3b82f6;    /* Primary blue */
     --ac:#60a5fa;    /* Accent blue */
     --mu:#64748b;    /* Muted text */
     /* etc... */
   }
   ```

3. **Music**: Upload MP3 files to a hosting service and use the URLs

4. **Discord**: Get your Discord ID by enabling Developer Mode in Discord settings

## 📝 Notes

- **No external dependencies** - Everything works offline except Discord API
- **Mobile responsive** - Works on all screen sizes
- **Browser compatibility** - Works in all modern browsers
- **Performance optimized** - Smooth animations and fast loading

## 🐛 Troubleshooting

**Images not showing?**
- Check that image files are in the `images/` folder
- Verify filenames match exactly (case-sensitive)
- Make sure `index.html` and `images/` are in the same directory

**Music not playing?**
- Check that MP3 URLs are publicly accessible
- Some browsers block autoplay - user must click play first

**Discord info not loading?**
- Verify your invite code is correct
- Server must be public or have a valid invite link

## 📧 Support

For questions or issues, feel free to reach out via Discord!

---

**Made with ❤️ for Matt's Portfolio**
