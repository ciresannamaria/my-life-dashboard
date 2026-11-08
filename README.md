# My Life Dashboard

A personal life management dashboard to track daily activities, wellbeing, nutrition, finances, habits and goals, and discover patterns over time.

## First design prototype

The initial version is a responsive, static HTML prototype with a warm coffee-inspired palette (espresso, mocha, latte, cappuccino and cream). It currently contains placeholder text and illustrative sample visuals only.

No personal records, credentials, API keys or Supabase secrets are included in this repository.

## Preview locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Open the repository **Settings**.
2. Select **Pages** in the left sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then save.
5. Wait for GitHub Pages to finish publishing. The site URL will appear on the Pages settings screen.

The repository is currently public, so the prototype website and its source code are public too. Do not add private personal information or secrets to this repository.

## Mobile app-style experience

The dashboard includes a mobile bottom navigation, an installable web app manifest, an app icon, and a lightweight service worker for caching the app shell. After GitHub Pages has published the latest commit, open the site on your phone and use your browser menu to choose **Add to Home screen** or **Install app** (the wording depends on the browser). The prototype remains public and has no login protection yet.

## Planned next steps

- Review the visual structure and module ideas.
- Replace placeholder content with the information and workflows you actually want.
- Connect the app to the dedicated Supabase project with authentication and row-level security before storing any private information.
