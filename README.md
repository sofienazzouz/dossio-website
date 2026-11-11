# Dossio — website

Static site (plain HTML + one CSS file, no build step), hosted on GitHub Pages.
Colours = the app's "Graphite & Soleil" tokens (`MyApp/Config/Theme.swift`).

| Page | French | English |
|---|---|---|
| Home | `/` | `/en/` |
| Privacy policy (App Store "Privacy Policy URL") | `/privacy/` | `/en/privacy/` |
| Support + legal notice (App Store "Support URL") | `/support/` | `/en/support/` |

Live: https://sofienazzouz.github.io/dossio-website/

## Before the App Store submission

Search the project for `TODO` and replace the "Bientôt sur l'App Store" / "Coming soon" buttons with the App Store link
`https://apps.apple.com/app/id…` (the id is in App Store Connect › App Information › Apple ID).

## Keep it in sync with the app

If the app changes what it stores, a permission, Spotlight/Siri, backup, or the price (2,99 €, 15 free items),
update the privacy and support pages (FR + EN) and the date at the top of the privacy policy.

## Preview locally

Run `python3 -m http.server` in this folder and open http://localhost:8000.
