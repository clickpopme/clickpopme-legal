# Privacy Policy — My Mini App Launcher

**Last updated:** 28 July 2026

This Privacy Policy describes how the **My Mini App Launcher** Chrome browser extension ("the Extension", "we", "our") handles your information.

The Extension is published under the name **ClickPopMe**. ClickPopMe is a publishing handle and is not a registered company or trading name.

---

## 1. Summary

My Mini App Launcher is a local-only utility. It lets you upload `.html` files from your computer and launch them as mini apps inside your Chrome browser. **All data stays on your device.** We do not collect, transmit, sell, or share any personal information. We do not use analytics, advertising, tracking, or remote servers of any kind.

If you want a one-line summary: the Extension never sends your data anywhere.

---

## 2. What information the Extension handles

The Extension only handles content that you actively choose to upload or set. Specifically, when you save a mini app, the Extension stores the following on your own device:

- A name you type for the mini app.
- A randomly generated identifier (UUID) used internally to look the mini app up.
- The full text contents of the `.html` file you uploaded.
- A colour you pick for the mini app's tile.
- A timestamp recording when the mini app was created.

The Extension also stores your display preferences on your own device:

- Whether you chose the grid or list layout.
- The order you arranged your saved mini apps into.

The Extension does **not** access, collect, or process:

- Your name, email address, phone number, or any other personally identifying information.
- Your browsing history, open tabs, cookies, bookmarks, passwords, or form data.
- The contents of any web page you visit.
- Your IP address, device identifiers, or location.
- Health, financial, authentication, or personal communications data.

---

## 3. Where your data is stored

All data created or uploaded through the Extension is stored **locally on your own device**. Your saved mini apps are held in your browser's built-in **IndexedDB** storage, and your display preferences are held in the Extension's own local storage area (`chrome.storage.local`). This data:

- Never leaves your computer.
- Is not transmitted to the publisher, to Google, or to any third party.
- Is not synchronised across devices through Chrome Sync or any other service.
- Is accessible only to you and to other software running under your user account on that device.

If you uninstall the Extension, clear browsing data for the Extension, or use Chrome's "Remove site data" tools, the stored mini apps and preferences will be permanently deleted.

---

## 4. Permissions explained

The Extension uses the minimum permissions required to function. Its manifest declares exactly one permission:

- **`storage`** — used only to remember your own display preferences on your device: which layout you chose (grid or list) and the order you arranged your saved mini apps into. Nothing stored under this permission is transmitted anywhere. This permission grants the Extension its own private storage area; it does **not** grant access to any website's storage.

It also relies on two capabilities that do not require a manifest permission:

- **Toolbar action / popup** — to show the Extension's interface when you click its icon.
- **`chrome.tabs.create`** — used only to open the mini app viewer page (`viewer.html`), bundled inside the Extension itself, in a new tab when you click a saved tile. The Extension does not read or modify any other tab.

The Extension does **not** request access to:

- Your browsing activity or any website's content.
- Any website's cookies or stored data.
- Your tabs' contents, history, or downloads.
- Your microphone, camera, location, or clipboard.

---

## 5. Network and third-party services

The Extension makes **no network requests**. It does not contact any server, API, analytics provider, advertising network, content delivery network, or remote logging service. It contains no third-party tracking SDKs.

The HTML files you upload are rendered locally inside a sandboxed page (`display.html`) within the Extension. If a mini app you uploaded contains references to external resources (for example, a `<script src="https://...">` tag, an embedded image URL, or a link), opening that mini app may cause your browser to make requests to those external addresses. Those requests are caused by the content of your own HTML file, not by the Extension itself, and are governed by the privacy practices of the destinations you have referenced.

---

## 6. Cookies and tracking

The Extension does not set, read, or use cookies. It does not use web beacons, fingerprinting, session identifiers, or any other tracking mechanism.

---

## 7. Sharing of information

We do not sell, rent, share, transfer, or disclose your information to any third party for any purpose, because the Extension does not collect any of your information in the first place. We have no servers, no databases, and no user accounts.

---

## 8. Your control over your data

You have full control over your data at all times:

- **View** — open the Extension popup to see all saved mini apps.
- **Edit / replace** — open Settings (the gear icon in the popup) and use the edit button beside any mini app to rename it, change its colour, or replace its HTML.
- **Reorder** — drag any mini app into a new position in the Settings list.
- **Delete a single mini app** — open Settings and use the delete button beside that mini app.
- **Delete all data** — uninstall the Extension, or clear the Extension's site data via Chrome's settings (`chrome://settings/content/all`).

Because no data is ever sent to us, there is no separate request you need to make to delete information from any server.

---

## 9. Children's privacy

The Extension is not directed at children under 13. It does not knowingly collect any personal information from anyone, including children.

---

## 10. Security

Your mini apps are stored in your browser's IndexedDB under your operating system user profile. Their security depends on the security of your device and your Chrome profile. You should keep your computer and browser up to date and avoid uploading confidential information that other users of the same device account could view.

The Extension renders uploaded HTML inside a Chrome **sandboxed** page so that the HTML cannot access the Extension's storage or other browser data. Even so, you should only upload HTML files whose contents you trust, because HTML can include scripts that perform their own actions when rendered.

---

## 11. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. Material changes will be reflected in an updated version of the Extension, with a new "Last updated" date at the top of this document. Continued use of the Extension after an update constitutes acceptance of the revised policy.

---

## 12. Compliance

The Extension is designed to comply with the Chrome Web Store **Developer Program Policies**, including the User Data Policy and Limited Use requirements. Because the Extension does not collect or transmit user data, no data sale, advertising use, or model training use occurs.

---

## 13. Contact

If you have questions about this Privacy Policy or the Extension's handling of data, contact us at:

**clickpopme@gmail.com**
