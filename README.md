# Client-only Upload & Download (IndexedDB)

This adds a client-only example that stores uploaded files locally in the browser using IndexedDB. No server or installation is required.

Key points:
- Files are stored locally in the user's browser (IndexedDB). They are not uploaded to any server.
- Files are only accessible on the same device and browser profile where they were stored.
- This is suitable for private, local storage or demos where you don't want any server-side components.

How to use:
1. Open `index.html` in a modern browser. For best results host it via GitHub Pages or any static host (opening via `file://` works in many browsers but may be restricted in some environments).
2. Use the file input to select a file and click "Store file locally".
3. Stored files will appear in the list; use the "Download" link to retrieve the file or "Delete" to remove it.

Deploying:
- You can host this branch on GitHub Pages (Settings -> Pages) or copy `index.html` to any static host.

Limitations & security:
- No server-side virus scanning or type enforcement — files are stored exactly as the user supplies them.
- Storage limits are determined by the browser (varies by browser and device).
- This is not a replacement for central storage if you need files shared between users or devices.

If you'd like, I can now commit these files to the existing branch `add-upload-endpoints` and open a pull request titled "Add client-only upload/download (IndexedDB) — no server required" targeting the `main` branch. Please confirm the PR title/target or provide different text.
