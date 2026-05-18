# ⌨️ EasyPut

A one-click numpad sidebar for fast score entry — built for Udvash script evaluator tired of typing evaluation marks on phone or laptop.


---
## Guideline video: [How to use](https://www.youtube.com/watch?v=8r1FZxSl7cQ)

## Download EasyPut (free): [Download](https://github.com/roboz1005/EasyPut)

## Form Link (For supporters): [Form](https://forms.gle/bkJdmLUruM2HKdjk7)
## 📸 Screenshots

><img width="1570" height="626" alt="Screenshot 2026-05-18 164818" src="https://github.com/user-attachments/assets/d8c76c6a-fa48-4f1b-bef6-714d5549ddc9" />

><img width="941" height="528" alt="Screenshot 2026-05-18 165303" src="https://github.com/user-attachments/assets/c3a10de8-4472-496f-8649-276a14663979" />



---

## ✨ What It Does

EasyPut injects a sleek numpad sidebar into any webpage, letting you click numbers to fill in score fields instead of typing them manually. It works on **any website**, remembers your settings, and stays out of your way when you don't need it.

**Perfect for:**
- Entering Udvash script evaluation marks quickly
- Any repetitive number-entry workflow on the web

---

## 🚀 Features

| Feature | Description |
|---|---|
| **One-click numpad** | Click buttons (0–10) to instantly fill any input field |
| **Visual element picker** | Click any input or submit button on the page to target it — no CSS knowledge needed |
| **Sidebar & floating modes** | Dock the panel to any edge (left, right, top, bottom) or detach it as a draggable floating window |
| **Customizable buttons** | Edit button values and grid layout (rows × columns) to fit your use case |
| **Selector presets** | Save and reuse input/submit targets across sessions — switch with a dropdown |
| **SPA-aware** | Automatically re-injects on single-page app navigation (React, Vue, etc.) |
| **Persistent state** | All settings survive page reloads via `chrome.storage.local` |
| **Enable/Disable toggle** | Turn the extension on or off from the popup without uninstalling |

---

## 🛠️ Installation

> **EasyPut is not yet on the Chrome Web Store.** Install it manually in developer mode.

### Step 1 — Download the extension

Download the latest `.zip` from the [Download](https://github.com/roboz1005/EasyPut) page and unzip it to a folder on your computer.

> <img width="984" height="482" alt="Screenshot 2026-05-18 160907" src="https://github.com/user-attachments/assets/c0af4faf-f8d0-4d52-ad96-37adbacc9256" />


---

### Step 2 — Open Chrome Extensions

In your Chrome browser, navigate to:

```
chrome://extensions
```

Or go to **Menu (⋮) → Extensions → Manage Extensions**.

> <img width="1228" height="689" alt="Screenshot 2026-05-18 161435" src="https://github.com/user-attachments/assets/11ff348b-3267-4988-8b8e-e8301a455789" />


---

### Step 3 — Enable Developer Mode

Toggle **Developer mode** on using the switch in the top-right corner of the Extensions page.

> <img width="1554" height="415" alt="Screenshot 2026-05-18 161807" src="https://github.com/user-attachments/assets/3da9c8a1-8bd1-44ea-bbb3-27d714b7e3f7" />


---

### Step 4 — Load the extension

Click **Load unpacked** and select the unzipped `EasyPut_extension_1.1.0` folder.

> <img width="929" height="505" alt="Screenshot 2026-05-18 162133" src="https://github.com/user-attachments/assets/da0882e8-6c2d-4d3a-908a-cfee9b20797f" />


---

### Step 5 — Pin the extension (optional)

Click the puzzle piece 🧩 icon in Chrome's toolbar, find **EasyPut**, and click the pin icon to keep it visible.

> <img width="510" height="459" alt="Screenshot 2026-05-18 162329" src="https://github.com/user-attachments/assets/ae09e83d-3e8f-4e11-a6e6-d6d908dd0a53" />

---

## 📖 How to Use

### Targeting an input field

1. Open the page where you want to enter scores.
> <img width="1199" height="664" alt="Screenshot 2026-05-18 162858" src="https://github.com/user-attachments/assets/9dc1307d-914d-4514-b49e-7ad917473fc8" />

2. The EasyPut sidebar will appear on the right side of the screen.
3. Go to the **Selector** tab inside the panel.
4. Click **Pick Input** and then click the score input field on the page — EasyPut will capture its selector automatically.
5. Optionally click **Pick Submit** to also capture the submit/save button.

---

### Entering scores

Once your input field is targeted, click any numpad button (0, 1, 2 … 10) to instantly fill the field with that value. If a submit selector is set, click the **Submit** button in the panel to trigger form submission.

---

### Saving presets

If you use the same input field repeatedly (e.g., across multiple exam scripts), save it as a **preset**:

1. After picking your selectors, click **Save Preset** and give it a label.
2. Next time, select the preset from the dropdown — no re-picking needed.

---

### Switching modes

- **Sidebar mode** — docked to an edge of the page. Drag the resizer handle to adjust width.
- **Floating mode** — detach the panel so it floats freely. Drag it anywhere on screen.

Use the **Layout** tab in the settings to switch between modes and choose your dock edge (left / right / top / bottom).
---

### Customizing buttons

Go to the **Buttons** tab in the settings panel to:
- Change the value of any button slot
- Set a slot to `NONE` to hide it
- Adjust the grid (rows and columns)

---

### Enabling / Disabling

Click the EasyPut icon in the Chrome toolbar to open the popup. Use the **ON / OFF** toggle to enable or disable the sidebar without uninstalling the extension.

---

## 🔒 Permissions

| Permission | Why it's needed |
|---|---|
| `storage` | Saves your selector targets, presets, and layout settings locally |
| `activeTab` | Communicates with the current tab when toggling via popup |
| `scripting` | Injects the numpad sidebar into pages |
| `host_permissions: <all_urls>` | Allows the sidebar to work on any website |

> No data is ever sent to any server. Everything stays in your browser.

---


## ☕ Support

If EasyPut saves you time, consider buying the developer a coffee:

## 📄 License
 
This project is licensed under the [Apache 2.0](LICENSE).
