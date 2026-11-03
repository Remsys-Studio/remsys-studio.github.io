# Remsys Studio static site

Publish the **contents of this directory** at the root of `https://remsys-studio.github.io/`. There is no build step, JavaScript, external font or external stylesheet. `index.html` is the studio page; `/again/` is the app page. Privacy and terms default to English, with `es`, `pt` (Brazilian Portuguese), `de`, `fr` and `tr` paths and language links.

Replace every `remsysstudio@icloud.com` before publishing. Effective date: 3 November 2026. The app's legal URLs target `/again/privacy/` and `/again/terms/`.

Local preview in an environment that allows listening sockets: `python3 -m http.server --directory site 8000` from the workspace root. Open `http://localhost:8000/`. Paths are absolute from the domain root, matching the specified GitHub Pages URL.

Light and dark themes follow the system preference. Pages use semantic headings, keyboard-visible focus, native-language navigation labels and a wrapping language switcher.

The app facts were checked against its Dart storage, barcode, purchase, backup and native-sync services and its Swift App Intents/notification implementation. The privacy pages link RevenueCat's privacy, App Privacy, customer-profile and SDK-attribute documentation, Apple's privacy/Siri documentation and Open Food Facts. Purchase analytics are distinguished from behavioral analytics; network metadata, Apple's Siri processing and possible iOS system backups are disclosed explicitly.
