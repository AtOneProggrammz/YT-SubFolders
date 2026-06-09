# Privacy Policy for YT SubFolders

**Last updated:** June 9, 2025

## Overview

YT SubFolders ("the Extension") is a Chrome extension that allows users to organize their YouTube subscriptions into folders within the YouTube sidebar. This privacy policy explains what data the Extension does and does not collect.

---

## Data Collection

**YT SubFolders collects no personal data.**

The Extension does not collect, transmit, store on external servers, or share any information about you or your browsing activity.

---

## Local Storage

The Extension stores the following data **locally on your device only**, using Chrome's built-in `chrome.storage.local` API:

- Folder names you create
- YouTube channel URLs assigned to your folders
- Folder open/closed state preferences

This data:
- Never leaves your device
- Is never sent to any server
- Is never accessible by the extension developer
- Is never shared with any third party

You can delete this data at any time by removing the extension or clearing its storage via `chrome://extensions`.

---

## Permissions Explained

| Permission | Why it's needed |
|---|---|
| `storage` | To save your folder structure locally on your device |
| `tabs` | To check if YouTube is already open when you click the popup |
| `https://www.youtube.com/*` | To inject the folder panel into the YouTube sidebar |

No permission is used for data collection or tracking purposes.

---

## Third Parties

YT SubFolders does not:
- Use any third-party analytics services
- Load any external scripts or remote code
- Communicate with any external servers or APIs
- Sell, transfer, or share any data with third parties

All code is bundled within the extension package itself.

---

## Children's Privacy

YT SubFolders does not knowingly collect any information from anyone, including children under the age of 13.

---

## Changes to This Policy

If this privacy policy changes in the future, the updated version will be posted here with a revised "Last updated" date. Continued use of the Extension after any changes constitutes acceptance of the updated policy.

---

## Contact

If you have any questions about this privacy policy, please open an issue on the [GitHub repository](https://github.com/your-username/yt-subfolder-ext).

---

*YT SubFolders is an independent project and is not affiliated with, endorsed by, or connected to YouTube or Google LLC.*
