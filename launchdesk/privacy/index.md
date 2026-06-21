# Privacy Policy — Launchdesk

**Last updated:** 21 June 2026

This Privacy Policy describes how the **Launchdesk** Chrome browser extension ("the Extension", "we", "our") handles your information.

The Extension is published under the name **ClickPopMe**. ClickPopMe is a publishing handle and is not a registered company or trading name.

---

## 1. Summary

Launchdesk replaces Chrome's new-tab page with a visual dashboard built from the bookmarks you already have. It is a read-only layer over your bookmarks, and all of your dashboard settings are stored locally on your own device.

Launchdesk has **no servers, no accounts, and no sign-in**. We do not collect, store, sell, or share any of your data, and the Extension contains no analytics, telemetry, advertising, or tracking of any kind. The only time information leaves your device is when *you* run a web search from the dashboard's search box, which sends your query to your own default search engine — exactly as the browser's address bar does. This is explained in full in section 5.

---

## 2. What information the Extension handles

**Your bookmarks (read-only).** Launchdesk reads your Chrome bookmark tree so it can display your bookmarks as a searchable, categorized dashboard. This access is strictly read-only: the Extension never creates, edits, moves, or deletes any bookmark. Your bookmark data is held in memory only while the new-tab page is open, solely to render the dashboard. It is never copied to a server, never stored by us, and never shared.

**Your dashboard preferences (stored locally).** Settings you choose — selected folders, theme, layout density, grouping, spaces, and which bookmarks you pin or hide — are saved using `chrome.storage.local`. This data lives only in your browser, on your device. It is never transmitted anywhere. Uninstalling the Extension removes it.

The Extension does **not** access, collect, or process:

- Your name, email address, phone number, or any other personally identifying information.
- Your browsing history, open tabs, cookies, passwords, or form data.
- The contents of any web page you visit.
- Your IP address, device identifiers, or location.
- Health, financial, authentication, or personal communications data.

---

## 3. Where your data is stored

The only data the Extension stores is your dashboard preferences, held **locally on your own device** using your browser's built-in `chrome.storage.local`. This data:

- Never leaves your computer.
- Is not transmitted to the publisher, to Google, or to any third party.
- Is accessible only to you and to software running under your user account on that device.

Your bookmarks themselves are not stored or cached by the Extension; they are read live from Chrome each time the new-tab page opens and held only in memory. If you uninstall the Extension, your local preferences are deleted and your bookmarks remain exactly as they were.

---

## 4. Permissions explained

The Extension requests only the permissions it needs to function:

- **bookmarks** — read your existing bookmarks so they can be displayed as a dashboard. Read-only; the Extension never changes your bookmarks.
- **storage** — save your own dashboard preferences locally via `chrome.storage.local`.
- **favicon** — display each bookmark's site icon by reading it from Chrome's local favicon cache (the `_favicon` API). This makes no network request; when no cached icon exists, the Extension draws a simple colored monogram tile locally. No bookmark URL or domain is sent anywhere.
- **search** — let you run a web search from the dashboard's search box using *your own* default search engine (see section 5).

The Extension does **not** request access to your browsing activity, the contents of websites you visit, your downloads, your history, your clipboard, your microphone, camera, or location.

---

## 5. Network, search, and third-party services

The Extension itself contacts **no server operated by us**. It has no backend, no analytics provider, no advertising network, no remote logging, and no third-party tracking SDKs. It loads no remotely hosted code — everything runs from the code bundled in the Extension.

There are two situations in which your browser may make a network request as a result of using Launchdesk, both initiated by you:

- **Running a web search.** The dashboard includes a search box. When you type a query and press Enter to search the web, the Extension passes that query to your browser's **own default search engine** (using Chrome's `search` API), and the results open in your tab — exactly as if you had typed the query into the address bar. The query goes to whichever search provider you have set as your default (for example, Google), and its handling is governed by **that provider's** privacy policy, not ours. If the search API is unavailable, the Extension falls back to opening a standard Google search URL. **Launchdesk does not see, store, log, or transmit your search queries to us.**
- **Opening a bookmark.** When you click a bookmark, your browser navigates to that site, just as clicking any link does. The Extension does not send your bookmark URLs to us or to any third party.

Aside from these actions that you trigger, nothing about your bookmarks, preferences, or activity leaves your device.

---

## 6. Cookies and tracking

The Extension does not set, read, or use cookies. It does not use web beacons, fingerprinting, session identifiers, or any other tracking mechanism.

---

## 7. Sharing of information

We do not sell, rent, share, transfer, or disclose your information to any third party, because the Extension does not collect any of your information in the first place. We have no servers, no databases, and no user accounts.

---

## 8. Your control over your data

You have full control over your data at all times:

- **Bookmarks** — manage them in Chrome as usual; Launchdesk only reflects them and never alters them.
- **Preferences** — change your dashboard settings at any time within the Extension.
- **Delete all data** — uninstall the Extension, or clear its site data via Chrome's settings, to remove your locally stored preferences.

Because no data is ever sent to us, there is no separate request you need to make to delete information from any server.

---

## 9. Children's privacy

Launchdesk is a general-purpose productivity tool. It is not directed at children under 13 and does not knowingly collect any personal information from anyone, including children.

---

## 10. Security

Your preferences are stored in your browser's local storage under your operating system user profile. Their security depends on the security of your device and your Chrome profile. You should keep your computer and browser up to date.

---

## 11. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. Material changes will be reflected in an updated version of the Extension, with a new "Last updated" date at the top of this document. Continued use of the Extension after an update constitutes acceptance of the revised policy.

---

## 12. Compliance

The Extension is designed to comply with the Chrome Web Store **Developer Program Policies**, including the User Data Policy and Limited Use requirements. Because the Extension does not collect or transmit user data to us, no sale of data, advertising use, or model-training use occurs.

---

## 13. Contact

If you have questions about this Privacy Policy or the Extension's handling of data, contact us at:

**clickpopme@gmail.com**
