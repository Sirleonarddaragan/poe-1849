# The 1849 Baltimore Dossier (Interactive Companion Web App)
**Official Interactive Companion to *The Shadow at Gunner's Hall: The Seven Deaths of Edgar Allan Poe***  
**Curated by Sir Leonard Daragan (The Archive of Lost Authors)**

---

## 🏛️ Overview
A high-converting, 90-second bilingual (English / Spanish) interactive forensic dossier where readers play as Le Chevalier C. Auguste Dupin examining the 3 suppressed physical relics of Edgar Allan Poe's October 1849 disappearance.

* **Target URL on GitHub Pages:** `https://sirleonarddaragan.github.io/poe-1849/` (or `gunners-hall`)
* **Amazon Target:** [The Shadow at Gunner's Hall (ASIN: B0HN98S77P)](https://www.amazon.com/dp/B0HN98S77P)

---

## 📁 Repository Structure
```
├── index.html                 # Complete standalone SPA (HTML5 + CSS + Web Audio + Bilingual JS)
├── assets/                    # Photorealistic 8K forensic still-lifes & 3D book mockup
│   ├── book_mockup.png        # 3D Hardcover Mockup of The Shadow at Gunner's Hall
│   ├── daragan_seal.jpg       # Royal Gold Seal Emblem of Sir Leonard Daragan
│   ├── dupin_portrait.jpg     # Le Chevalier C. Auguste Dupin in his 1849 Parisian Study
│   ├── hero_banner.jpg        # Baltimore Wharf at Night
│   ├── relic1_blade.jpg       # Toledo Steel Rapier & Dr. Carter's Malacca Cane
│   ├── relic2_watch.jpg       # Antique Brass Watch Stopped at 3:15 & Scalpel
│   └── relic3_seal.jpg        # Cleaved Grey Wax Monogram & Unmailed Richmond Letter
└── README.md                  # Deployment Guide
```

---

## 🚀 How to Deploy to GitHub Pages in 2 Minutes

### Method 1: Using GitHub Desktop / Git CLI
1. Initialize git in this directory:
   ```bash
   cd C:\Users\rick\.gemini\antigravity\scratch\poe_1849_dossier
   git init
   git add .
   git commit -m "Initial commit: 1849 Baltimore Dossier interactive web app"
   ```
2. Create a new repository on your GitHub account (`sirleonarddaragan`):
   * Repository Name: `poe-1849` (or `the-shadow-at-gunners-hall`)
   * Public: **Yes**
3. Link and push:
   ```bash
   git remote add origin https://github.com/sirleonarddaragan/poe-1849.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub.com, go to **Settings** ➔ **Pages**:
   * Source: **Deploy from a branch**
   * Branch: **main** / **(root)** ➔ Click **Save**.

Your live URL will be active immediately at:  
👉 **`https://sirleonarddaragan.github.io/poe-1849/`**

---

### Method 2: Drag & Drop via GitHub Web
1. Go to `https://github.com/new` while logged into `sirleonarddaragan`.
2. Name the repository `poe-1849`.
3. Drag and drop `index.html` and the `assets` folder directly into GitHub.
4. Enable GitHub Pages under **Settings ➔ Pages**.
