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

1. Create an empty GitHub repository for this folder.
2. Add that repository as the Git remote and push the `main` branch.
3. In the GitHub repository, open **Settings**, then **Pages**.
4. Choose **GitHub Actions** under **Build and deployment**.
5. Run **Deploy SiteMed website** from the Actions tab if it did not start after the
   push.
6. Confirm the homepage, `privacy.html`, and `support.html` are visible without signing
   in.

Use the deployed `privacy.html` URL for the Chrome Web Store privacy-policy field and
the deployed `support.html` URL for the support URL field.
