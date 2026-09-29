# SiteMed website

Official public website, privacy policy, and support documentation for the SiteMed
Chrome extension.

## Pages

- `index.html` — product homepage
- `privacy.html` — public extension and website privacy policy
- `support.html` — troubleshooting and support information
- `404.html` — not-found page

The site is static and does not use a package manager, analytics, cookies, accounts, or
a separate build service.

## Publish with GitHub Pages

1. In the GitHub repository, open **Settings**, then **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/(root)`, then save. GitHub Pages publishes future pushes to
   `main` automatically.
4. Confirm the homepage, `privacy.html`, and `support.html` are visible without signing
   in.

Use the deployed `privacy.html` URL for the Chrome Web Store privacy-policy field.
Enable the Store's built-in Support hub for questions and bug reports. The current
`support.html` page directs visitors to that hub, so do not use it as the listing's
Support URL until the page offers a separate contact method.
