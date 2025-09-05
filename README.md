# Pocket Pal - Your Offline-First Finance & Task Manager
this was written by AI. the code and the readme file, i just had an idea and hard to explain it to AI.

**A 100% private, browser-based personal assistant to manage your finances, tasks, and daily life without ever needing an internet connection.**

### [Live Demo Link (Deploy your own!)](#how-to-use)

## Overview

Pocket Pal is a comprehensive Progressive Web App (PWA) designed for complete privacy and offline functionality. It's a full-featured tool that combines expense tracking, account management, debt logging (IOUs), and a simple to-do list in one place. All of your data is stored securely on your own device in the browser's IndexedDB, meaning you are in total control. Nothing is ever sent to a server.

The entire application is contained within a **single HTML file**, making it incredibly portable and easy to host or use locally.

## ✨ Key Features

* **💰 Account Management:** Create and manage multiple accounts (e.g., Cash, Bank, Credit Card) and track their balances in real-time.
* **📈 Expense & Income Tracking:** Log expenses and income with details like category, notes, and the exact date and time.
* **👥 IOU Tracker:** Easily log money you've lent to or borrowed from friends. Settle debts with a single tap, which automatically updates your account balances.
* **✅ Task Manager:** A simple but effective to-do list to manage your daily tasks.
* **📊 Visual Reports:** A dedicated reports page with a breakdown of your monthly spending by category, showing you exactly where your money goes.
* **🎨 40+ Themes:** Extensively personalize the app's appearance with a huge collection of themes, including originals, movie-inspired, game-inspired, and stylistic designs.
* **📂 Data Management:** Export your entire database (accounts, transactions, tasks, etc.) to a single JSON file for backup, and import it back at any time to restore your data.
* **📱 PWA Ready:** Installable on any modern mobile or desktop device for a native app-like experience, complete with offline access.

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS
* **Logic:** Vanilla JavaScript (ES6)
* **Database:** IndexedDB (in-browser database for 100% local storage)
* **Icons:** Lucide Icons

## 🚀 How to Use

The beauty of Pocket Pal is its simplicity. You can run it locally on your desktop or deploy it for a full mobile PWA experience.

### Quick Deploy (Recommended for Mobile Use)

To get the full PWA experience with offline capabilities, you need to host the `daa11.html` file on a web server. The easiest way is with a free service like [tiiny.host](https://tiiny.host) or [Netlify Drop](https://app.netlify.com/drop).

1. **Go to a hosting service:** For example, [tiiny.host](https://tiiny.host).
2. **Drag & Drop:** Upload the `daa11.html` file.
3. **Launch:** Get your live `https://` URL.

**To install it on your phone:**

* **Android (Chrome):** Open the URL, tap the three-dot menu, and select **"Install app"** or **"Add to Home Screen"**.
* **iOS (Safari):** Open the URL, tap the "Share" icon, and select **"Add to Home Screen"**.

### Local Development

For testing on a laptop or desktop:

1. Save the `daa11.html` file to your computer.
2. Right-click the file and choose "Open with" your favorite browser (Chrome, Firefox, etc.).

## 📂 File Structure

The entire application is self-contained in `daa11.html`. This was a deliberate design choice to make the project maximally portable and easy to manage.
/
└── index.html
