# ⌨️ EasyPut

> One-click number input for repetitive form filling — built for Udvash and beyond.

Tired of typing the same marks over and over for every student? EasyPut adds a small numpad panel to any webpage so you can fill inputs and submit forms with a single tap — no keyboard needed.
*Made with frustration and too many repeated keystrokes — EasyPut *
---
## Full guide on installation and use
    Youtube link: 

## 🚀 Installation

# Desktop
1. Download and unzip this repository
2. Open Chrome → go to `chrome://extensions`
3. Turn on **Developer mode** (top-right toggle)
4. Click **Load unpacked**
5. Select the `EasyPut_extension_1.1.0` folder
6. The EasyPut icon will appear in your toolbar — click it to get started

# Android
1. Download .Zip file (No need to unzip it)
2. Install Kiwi browser. This is not available in google play store.
    Link: https://kiwi-browser-fast-quiet.en.softonic.com/android
3. Open the app and click on the three dot
4. Click **Extension**
5. Click **+(from .zip/.crx/.user.js)**
6. Select the `EasyPut_extension_1.1.0.zip`. This will add the extension to your browser.
7. Now the extension is started automatically. 
    If not you can find the extension in the three dot--> at the bottom (scroll if needed)
    Select Easyput and check if it is `ON`. If not then click it to turn on. 
    Then open udvash script evaluation site. It will be there (you might need to refresh)



## 🛠️ First-Time Setup

1. Go to the page where you want to use EasyPut (e.g. your marks entry page)
2. Click the ⚙️ icon in the EasyPut sidebar to open Settings
3. Selectors tab → Under Input Field, click + Add New, give it a name, and paste this in the input box.
    `this`
4. Do the same for the Submit Button, give it a name, and paste this in the input box.
    `this`
5. Buttons tab → Set the values you want on each numpad key (e.g. 10, 20, 30...)
6. Layout tab → Adjust columns/rows to fit your screen
7. Click any numpad button — it fills the input and submits automatically!

---

## ✨ Features at a Glance

| Feature | Details |
|---|---|
| Numpad buttons | Up to 12 buttons with any values you set |
| One-click fill & submit | Fills input and auto-submits in one tap |
| Dock anywhere | Pin to left, right, top, or bottom edge |
| Floating panel | Detach as a draggable, resizable popup |
| Enable/disable toggle | Turn off without reloading the page |
| Saves your settings | Presets and layout persist across sessions |
| Works on SPAs | Re-attaches after navigation in single-page apps |

---

## 🔒 Permissions

| Permission | Why |
|---|---|
| `storage` | Saves your presets and settings |
| `activeTab` | Reads the current tab to inject the sidebar |
| `scripting` | Injects the numpad UI into the page |
| `host_permissions: <all_urls>` | Lets EasyPut work on any website |

**No data ever leaves your browser.** Everything is stored locally.

---

## ⚠️ Known Limitations

- Some websites with strict security policies (CSP) may block the sidebar from loading
- If a website changes its layout, you may need to update your saved CSS selector
- The floating panel position resets on page reload (docked position is always saved)
- You cannot open chatgpt while using the extension, you need to completely turn it off to use chatgpt.

---

## ☕ Support the Project

If EasyPut saves you time, consider a small appreciation!

    **Buy me a coffee** you can find the method inside the extension

---


