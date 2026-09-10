# MyChat Web App

This package turns the existing MyChat build into a web/PWA-ready app.

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload all files/folders from this package.
3. Open Settings -> Pages.
4. Select Deploy from branch, choose `main` and `/ (root)`.
5. Open the HTTPS URL GitHub gives you.
6. In Chrome, press `🔔 Notifications: Off` in MyChat and choose Allow.
7. Optionally use Chrome's "Add to Home screen" / "Install app".

Important: the browser notification permission requires a secure HTTPS origin (or localhost). A downloaded `content://downloads/...` HTML file cannot provide the same permission flow.
