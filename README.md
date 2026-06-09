# 📁 YT SubFolders

> Organize your YouTube subscriptions into folders — right inside the YouTube sidebar.

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-red?logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![No Data Collected](https://img.shields.io/badge/Data%20Collected-None-brightgreen)

---

## 🧩 What is YT SubFolders?

If you subscribe to a lot of YouTube channels, your subscription list can become an overwhelming wall of names. **YT SubFolders** adds a folder system directly into the YouTube sidebar, letting you group channels into categories so you can find what you want instantly.

No more endlessly scrolling through hundreds of subscriptions.

---

## ✨ Features

- 📂 **Create folders** for any category — Gaming, Tech, Music, News, whatever you like
- ➕ **Add subscriptions** to folders with one click
- 🔍 **Search** your subscriptions when adding them to a folder
- 📋 **Unorganized section** shows all channels not yet assigned to a folder
- ✏️ **Rename & delete** folders at any time
- 🔽 **Collapsible** folders and panel to keep things tidy
- 🔒 **100% private** — all data stays on your device, nothing is ever sent anywhere

---

## 📸 How It Looks

The **📁 SubFolders** panel appears in the YouTube left sidebar, just above your subscriptions list.

```
📁 SubFolders                    [+ Folder]
├── 📂 Gaming              (4)
│   ├── 🔴 Markiplier
│   ├── 🔴 PewDiePie
│   └── ...
├── 📂 Tech                (3)
│   ├── 🔴 Linus Tech Tips
│   └── ...
└── 📋 Unorganized        (12)
    ├── 🔴 Some Channel
    └── ...
```

---

## 🚀 Installation

### From the Chrome Web Store
*(Coming soon)*

### Manual Installation (Developer Mode)

1. Download or clone this repository
   ```bash
   git clone https://github.com/your-username/yt-subfolder-ext.git
   ```
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer mode** (toggle in the top-right corner)
4. Click **Load unpacked**
5. Select the `yt-subfolder-ext` folder
6. Navigate to [YouTube](https://youtube.com) — the SubFolders panel will appear in the sidebar!

---

## 🛠️ How to Use

1. Go to **YouTube** and open the left sidebar
2. Find the **📁 SubFolders** panel near your subscriptions
3. Click **+ Folder** to create a new category
4. Click **＋ Add subscription** inside any folder to assign channels
5. Or click the 📁 button next to any channel in the **Unorganized** section

---

## 📁 File Structure

```
yt-subfolder-ext/
├── manifest.json        — Extension configuration
├── content.js           — Main logic, injected into YouTube
├── content.css          — Panel styles
├── popup.html           — Extension popup UI
├── popup.js             — Popup logic
├── PRIVACY_POLICY.md    — Privacy policy
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

---

## 🔒 Privacy

YT SubFolders collects **zero data**. Your folder structure is saved locally on your device using Chrome's built-in storage. Nothing is ever sent to a server or shared with anyone.

Read the full [Privacy Policy](./PRIVACY_POLICY.md).

---

## 📋 Permissions

| Permission | Reason |
|---|---|
| `storage` | Saves your folders locally on your device |
| `tabs` | Checks if YouTube is already open when you click the popup |
| `youtube.com` | Injects the folder panel into the YouTube sidebar |

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Not affiliated with or endorsed by YouTube or Google LLC.*
