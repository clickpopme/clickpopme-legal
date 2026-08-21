# Privacy Policy — Knackle

**Last updated:** 21 August 2026

This Privacy Policy describes how the **Knackle** Chrome browser extension ("the Extension", "we", "our") handles your information. Knackle was previously published as **Simple FAQ** — it is the same extension under a new name, and this policy applies equally under either name.

The Extension is published under the name **ClickPopMe**. ClickPopMe is a publishing handle and is not a registered company or trading name.

---

## 1. Summary

Knackle is a free, local-only utility. It gives small teams a private answer bank inside Chrome — save your own customer replies, company FAQs, internal processes, and policies, then search and copy them with one click. Entries can be added directly in the Extension or imported from a CSV file you supply. **All data stays on your device.** We do not collect, transmit, sell, or share any personal information. We do not use analytics, advertising, tracking, or remote servers of any kind.

If you want a one-line summary: the Extension never sends your data anywhere.

---

## 2. What information the Extension handles

The Extension only handles content that you actively create or import. Specifically, when you save an answer, the Extension stores the following on your own device:

- The **title** (the question or label).
- The **answer / description** text.
- The **category** name you assign (optional).
- Any **tags** you assign (optional).
- An optional **answer type** (for example Customer Reply, Internal FAQ, Process/SOP) and **status** label (for example Customer-Safe, Draft, Needs Review, Internal Only).
- An optional **expiry date**, and an archived flag once an entry is archived.
- The **internal notes** field (optional, staff-only context — never copied with the answer).
- A **favourite** flag if you mark the entry.
- A randomly generated identifier (UUID) used internally to look the entry up.
- Timestamps recording when the entry was created, last updated, and most recently used or copied.

The Extension also stores a small set of preferences (theme — light, dark, or system; layout density — comfortable or compact), simple interface state (such as which sections are open or closed and whether you have dismissed in-app prompts), and a local count of copy events used for the "Recently used" and favourites features. All of this stays in your browser's localStorage and is never transmitted.

The Extension does **not** access, collect, or process:

- Your name, email address, phone number, or any other personally identifying information.
- Your browsing history, open tabs, cookies, bookmarks, passwords, or form data.
- The contents of any web page you visit.
- Your IP address, device identifiers, or location.
- Health, financial, authentication, or personal communications data.

---

## 3. Where your data is stored

All data created or imported through the Extension is stored **locally on your own device** using your browser's built-in **localStorage** mechanism, scoped to the Extension. This data:

- Never leaves your computer.
- Is not transmitted to the publisher, to Google, or to any third party.
- Is not synchronised across devices through Chrome Sync or any other service.
- Is accessible only to you and to other software running under your user account on that device.

If you uninstall the Extension, clear browsing data for the Extension, or use Chrome's "Remove site data" tools, the stored entries will be permanently deleted. The Extension provides an **Export CSV** feature so you can back up your own data at any time.

---

## 4. Permissions explained

The Extension declares **no permissions** in its `manifest.json` file. It uses only the default capabilities granted to extension pages:

- **Toolbar action** — to open the Extension's interface in a new tab when you click its icon.
- **chrome.tabs.create** for the Extension's own URL — used by the service worker only to open the Extension's bundled `index.html` page when the toolbar icon is clicked. No other tab is read or modified.

The Extension does **not** request access to:

- Your browsing activity or any website's content.
- Your tabs' contents, history, downloads, cookies, or storage.
- Your microphone, camera, location, or clipboard.

---

## 5. Network and third-party services

The Extension makes **no network requests**. It does not contact any server, API, analytics provider, advertising network, content delivery network, or remote logging service. It contains no third-party tracking SDKs.

All scripts, styles, and assets used by the Extension are bundled into the Extension package at the time of submission to the Chrome Web Store. There are no remote scripts, remote stylesheets, remote fonts, or runtime code loading.

CSV files you choose to import are read entirely on your local device using the browser's standard `FileReader` API. The contents are parsed locally and stored in your browser's `localStorage`. No part of an imported CSV file is transmitted off your device.

---

## 6. Cookies and tracking

The Extension does not set, read, or use cookies. It does not use web beacons, fingerprinting, session identifiers, or any other tracking mechanism.

---

## 7. Sharing of information

We do not sell, rent, share, transfer, or disclose your information to any third party for any purpose, because the Extension does not collect any of your information in the first place. We have no servers, no databases, and no user accounts.

---

## 8. Your control over your data

You have full control over your data at all times:

- **View** — open the Extension to see all your entries.
- **Search and filter** — filter by category, tag, or free-text search.
- **Edit** — open any entry and update its title, answer, category, or tags.
- **Delete a single entry** — use the delete action on any entry tile.
- **Export everything** — Settings → Export CSV downloads a complete backup as a UTF-8 CSV file.
- **Import from CSV** — Settings → Import CSV replaces all current entries with the contents of a CSV file you supply.
- **Delete all data** — uninstall the Extension, or clear the Extension's site data via Chrome's settings (`chrome://settings/content/all`).

Because no data is ever sent to us, there is no separate request you need to make to delete information from any server.

---

## 9. Children's privacy

The Extension is not directed at children under 13. It does not knowingly collect any personal information from anyone, including children.

---

## 10. Security

Your entries are stored in your browser's `localStorage` under your operating system user profile. Their security depends on the security of your device and your Chrome profile. You should keep your computer and browser up to date and avoid storing confidential information that other users of the same device account could view.

The Extension only treats your CSV imports and entered text as data. It does not render, execute, or evaluate any of that content as code.

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
