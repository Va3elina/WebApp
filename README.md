# WebApp for Wohnungsbot

🌍 This repository contains the **web interface** for [Wohnungsbot](https://github.com/Va3elina/Wohnungsbot).  
It provides filter forms in multiple languages, which are opened directly inside the Telegram bot.

## ✨ Features
- 🏠 Filter form for housing search
- 🌐 Multi-language support:
  - English (`filtersEN.html`)
  - Deutsch (`filtersDE.html`)
  - Русский (`filtersRU.html`)
  - العربية (`filtersAR.html`)
  - Türkçe (`filtersTR.html`)
- ⚡️ Lightweight HTML/JS, no backend required
- 📱 Integrated into Telegram via WebApp

## 🔗 Usage
The bot sends a button **“Set Filters”** → which opens the corresponding HTML page from this repository (via GitHub Pages).

If you enable GitHub Pages in repo settings:
- URL will be:  
  `https://va3elina.github.io/WebApp/filtersEN.html` (English)  
  `https://va3elina.github.io/WebApp/filtersDE.html` (Deutsch)  
  …and so on.

These links should be inserted in the bot configuration (`WEBAPP_URLS`).

## 🚀 Deployment
1. Go to **Settings → Pages** in this repo.  
2. Enable GitHub Pages for the `main` branch.  
3. The pages will be available at:  
   `https://<your-username>.github.io/WebApp/`

## 📂 Project Structure
WebApp/
│── filtersEN.html # English filters
│── filtersDE.html # German filters
│── filtersRU.html # Russian filters
│── filtersAR.html # Arabic filters
│── filtersTR.html # Turkish filters
│── filters.html # (default / fallback)


## 📜 License
MIT – free to use, modify and distribute.
