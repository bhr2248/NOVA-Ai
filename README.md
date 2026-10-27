# NOVA AI Workspace

A single-page, mobile-friendly AI workspace built with plain HTML, CSS, and JavaScript.

## Run locally

Open `index.html` in a modern browser. Built-in/offline features work without hosting. Online AI providers require internet access and provider credentials.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html` and this `README.md` to the repository's root (top level).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then click **Save**.
6. Wait for the Pages deployment to finish. Your site URL will appear in Settings → Pages.

## Important security note

Do not put API keys in `index.html`, commit them to the repository, or share screenshots that expose them. A browser-only static site cannot keep API keys secret from its users. If you use a public GitHub Pages site, visitors can use their own provider credentials in their own browser, but don't build a public service around a shared secret key. For shared/public AI access, use a backend server or serverless function that keeps the key in server-side environment variables and applies authentication and rate limits.

## Limits

GitHub Pages hosts static files; it does not run a private backend or a local language model. Online provider access depends on each provider's API, CORS/browser support, model availability, pricing, and usage limits. The offline helper is not a full language model.
