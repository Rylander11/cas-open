# cas-open

Launcher page for the CAS Bid Board. The board runs on claude.ai, which can't open desktop-app links (Revu, Word, Excel) directly. The board opens `open.html#<app link>` here, and this page launches the app.

- Accepts only `openspinrevu:`, `ms-word:ofe|u|`, `ms-excel:ofe|u|` and `ms-powerpoint:ofe|u|` links that point to a `*.sharepoint.com` file.
- The file link travels after the `#`, so it is never sent to GitHub's servers.
- Hosted with GitHub Pages: https://rylander11.github.io/cas-open/open.html
