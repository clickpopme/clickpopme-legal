# Privacy Policy — My Mini App Launcher

**Last updated:** 29 August 2026

This Privacy Policy describes how the **My Mini App Launcher** Chrome browser extension ("the Extension", "we", "our") handles your information.

The Extension is published under the name **ClickPopMe**. ClickPopMe is a publishing handle and is not a registered company or trading name.

---

## 1. Summary

My Mini App Launcher is a local-first utility. It lets you upload `.html` files from your computer and launch them as mini apps inside your Chrome browser. **All data stays on your device.** We do not collect, transmit, sell, or share any personal information. We do not use analytics, advertising, tracking, or remote servers of any kind.

The Extension itself makes no network requests. The only network activity that can occur is a mini app of your own fetching a resource it references — for example a library file such as Vue or Tailwind. That request comes from your page, not from the Extension, and carries none of your data. Section 5 explains this in full.

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
- The last version of the Extension whose release notes you have viewed, so that the same release notes are not shown to you twice.

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

- **`storage`** — used only to remember your own display preferences on your device: which layout you chose (grid or list), the order you arranged your saved mini apps into, and the last version whose release notes you viewed. Nothing stored under this permission is transmitted anywhere. This permission grants the Extension its own private storage area; it does **not** grant access to any website's storage.

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

The Extension has no server, no analytics, no tracking and no third-party services, and it never sends your files anywhere. **The Extension itself makes no network requests of any kind.** It does not contact any server, API, analytics provider, advertising network, or remote logging service, and it contains no third-party tracking SDKs. Nothing you save is transmitted, and nothing about your use of the Extension reaches the publisher.

The only network activity that can occur is caused by a mini app of your own. The HTML files you upload are rendered locally inside a sandboxed page (`display.html`) within the Extension. If a mini app you uploaded references an external resource — most commonly a library file such as Vue, React or Tailwind, but equally an image, font, stylesheet, or link — opening that mini app may cause your browser to fetch that resource. Those requests are made by your own page, not by the Extension. They carry none of your data: no file contents, no mini app names, no identifiers, and nothing reaches the publisher. They are governed by the privacy practices of the destinations you have referenced.

Scripts are the one case the Extension restricts. So that single-file apps which bundle their own code, or which load a common library, are able to run, the sandboxed page's Content Security Policy permits scripts from `blob:` URLs — code your own page builds in memory, which involves no network request at all — and from a fixed list of six well-known public library CDNs:

- `cdn.jsdelivr.net`
- `unpkg.com`
- `cdnjs.cloudflare.com`
- `cdn.tailwindcss.com`
- `esm.sh`
- `ajax.googleapis.com`

No other host may supply a script to a mini app. This allowlist is a Content Security Policy, not a host permission: it grants the Extension no access to those sites, and the Extension never chooses, injects, or requests a script itself — a library is fetched only if the file you uploaded already references it. The Extension's own pages are separately restricted to code bundled inside the Extension and cannot load remote code at all.

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

The Extension renders uploaded HTML inside a Chrome **sandboxed** page so that the HTML cannot access the Extension's storage or other browser data. The sandbox also limits where a mini app may load scripts from: code your own page builds in memory, and the six public library CDNs listed in section 5. Even so, you should only upload HTML files whose contents you trust, because HTML can include scripts that perform their own actions when rendered.

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
