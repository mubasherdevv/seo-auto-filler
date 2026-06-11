# 🚀 SEO Profile Autofill Extension

A premium, intelligent Chrome Extension designed to turbocharge your workflow. Built specifically for SEO professionals, freelancers, and power users, this extension intelligently autofills complex registration, login, and profile forms across the web using a combination of **Artificial Intelligence** and **Smart Heuristic Fallbacks**.

---

## ✨ Key Features

### 🧠 1. AI-Powered Smart Autofill
Never struggle with weirdly named form fields again. By connecting your OpenAI API key, the extension reads the labels on any web page and uses AI (e.g., `gpt-4o-mini`) to perfectly map your profile data into the correct input boxes.

### 🛡️ 2. Heuristic Fallback Engine
If the AI is disabled or fails to parse a page, the extension instantly falls back to an ultra-fast Regex-based heuristic engine. It automatically detects fields like First Name, Last Name, Username, Email, Bio, Phone, and Passwords.

### 👥 3. Multi-Profile Management
Managing multiple clients? You can create, name, and switch between unlimited profiles. Each profile securely holds its own unique:
* **Register Data:** First Name, Last Name, Username, Email, Password.
* **Login Data:** Login Email/Username, Password.
* **Profile Data:** Website URL, Bio/About Me, Phone Number.

### ⚡ 4. Floating "Magic" Button
A sleek, draggable floating button appears on web pages. Just click the lightning bolt `⚡` to autofill the active page instantly. Don't like it? Toggle it off in the settings.

### 🔄 5. Google Sheets Live Sync
Keep your data safe in the cloud. Connect a Google Apps Script Web App URL to:
* **Export:** Send all your profiles to a Google Sheet.
* **Import:** Pull profiles from a Google Sheet directly into the extension.
* **Live Logging:** Automatically save a record of every form filled directly into a Google Sheet.

### 📜 6. Activity Log (History)
A built-in history tracker logs every action you take. View the Date, Time, Website Domain, Activity Type (*Register, Login, or Profile*), and the Profile used. Export your history to a CSV file for client reporting.

### 📥 7. Offline JSON Backup
Prefer local backups? Export your entire profile database as a `.json` file and import it anytime, anywhere.

### 🎨 8. Premium Dark-Mode UI
Enjoy a beautiful, eye-friendly dark interface with smooth animations, vibrant gradients, custom scrollbars, and sleek slide-in toast notifications.

---

## 🛠️ Technology Stack

This extension is lightweight, lightning-fast, and built without heavy frontend frameworks.

* **Frontend:** Vanilla HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Architecture:** Chrome Extension API (Manifest V3).
* **AI Integration:** OpenAI REST API (Fetch).
* **Cloud Database:** Google Sheets API via Google Apps Script (GAS).
* **Data Storage:** `chrome.storage.local` for secure, offline-first storage.

---

## 📖 How to Use

### 1. Installation
1. Go to `chrome://extensions/` in your browser.
2. Enable **Developer mode** (top right corner).
3. Click **Load unpacked** and select the folder containing this extension.

### 2. Setting Up a Profile
1. Click the extension icon in your Chrome toolbar.
2. Fill in the data under the **Register Data**, **Login Data**, and **Profile Data** tabs.
3. Your data saves automatically as you type!
4. Click the `➕` button at the top right to create a new profile for a different client.

### 3. Enabling AI Autofill (Optional but Recommended)
1. Click the ⚙️ **Settings** icon.
2. Go to **AI Configuration**.
3. Toggle "Enable AI Autofill" ON and enter your OpenAI API Key.

### 4. Using the Autofill
* **Method 1:** Use the floating `⚡` button on the webpage.
* **Method 2:** Open the extension popup and click the big green **🚀 Autofill Form** button.
* **Method 3:** Right-click anywhere on the page, go to `SEO Profile Autofill`, and select the type of form you want to fill.

### 5. Setting up Google Sheets Sync
1. Create a Google Sheet and open **Extensions > Apps Script**.
2. Paste the provided deployment code (from the guide) and deploy as a **Web App** (Access: "Anyone").
3. Copy the Web App URL.
4. Open the extension, click ⚙️ **Settings**, go to **Data Backup**, and paste the URL.
5. Click **💾 Save Configuration**. You can now Sync your data!

---

*Built with ❤️ for speed, efficiency, and scale.*
