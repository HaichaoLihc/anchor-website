# Knowledge Index

## Observations

- 2026-06-05 corrected homepage pet-feature language: proctors are the entities that watch/check sessions, while pets are collectible rewards earned from sufficiently high session scores.
    - importance: yellow
    - review_state: informed
- 2026-06-05 updated the public homepage for the new pet feature: hero copy now frames Anchor around proctor check-ins and earned pets, the landing hero uses `assets/session-set-up-view.mov` with `assets/newdesign/setup.png` as poster, the flow uses the new setup/during-session/notification/result/history screenshots, and the bottom Companion section shows the pet collection. Renamed new asset files to URL-safe names: `during-session.png`, `pet-collection.png`, and `result-pet-gone.png`.
    - importance: green
    - review_state: informed
- 2026-06-05 GitHub Pages live check showed `/index.html`, `/styles.css`, and `/app-icon.png` all serving 200 with the correct MIME types. Added `?v=20260605` stylesheet cache-busting query to `index.html`, `privacy.html`, and `support.html` because browsers/CDN edges can temporarily show an unstyled page after seeing a stale or missing stylesheet during deploy.
    - importance: green
    - review_state: informed
- 2026-06-04 rebuilt the public homepage into a fuller static marketing page matching the macOS app's minimal native style: warm off-white canvas, system typography, green/deep-green AnchorTheme accents, pill CTAs, real app icon asset, and a CSS-rendered focus-session preview with proctor-eye motif.
    - importance: green
    - review_state: informed
- 2026-06-04 updated public contact email on the static website privacy and support pages to haichaoli616@gmail.com.
    - importance: green
    - review_state: informed

- This repository is the public static website for Anchor. It is separate from the private app source repository so GitHub Pages can serve public App Store metadata pages.
    - importance: red
    - review_state: informed
- GitHub Pages is configured to publish from the `main` branch root. Expected public URLs are `https://haichaolihc.github.io/anchor-website/`, `/privacy.html`, and `/support.html`.
    - importance: yellow
    - review_state: informed
- 2026-06-06 added `appcast.xml` here to host the Anchor macOS app's Sparkle auto-update feed at `https://haichaolihc.github.io/anchor-website/appcast.xml` (referenced by the app's `SUFeedURL`). It currently has zero `<item>` entries (valid "no update" state) plus a commented item template. New releases are appended (newest first) using `make_appcast_item.sh` in the app repo, which signs the GitHub-Release DMG with the EdDSA key.
    - importance: yellow
    - review_state: approved
- `privacy.html` is the App Store Connect privacy policy URL. It states that Anchor does not collect personal data on developer-operated servers, while disclosing local app data and optional third-party AI service use.
    - importance: yellow
    - review_state: informed

## Child Indexes
