# Lohkforged Studios website

Official GitHub Pages site for Lohkforged Studios.

## Public URLs (after GitHub Pages is enabled)

- Homepage: https://lohkz.github.io/
- Knights Don't Fly privacy policy: https://lohkz.github.io/privacy/knights-dont-fly/
- Google AdMob seller declaration: https://lohkz.github.io/app-ads.txt

## Publishing

In this repository: **Settings → Pages → Build and deployment → Deploy from a branch**.
Select **main** and **/(root)**, then save. Give GitHub Pages a few minutes to publish.
Check the live URL in a browser. Publishing is not automatic until Pages is enabled.

The files are plain HTML/CSS, require no build tools and include no third-party
website analytics, scripts or external fonts.

## Required before commercial release

- Public studio support and privacy contact: `lohkforgedstudios@gmail.com`.
- Revisit the privacy policy and game age targeting once the live AdMob and
  Google Play Billing implementations are final. Match declarations to the
  actual SDKs and Play Console Data Safety responses.
- Add this website as the **developer website** on the Google Play Store listing
  for Knights Don't Fly, so AdMob can discover the root `app-ads.txt`.
- If AdMob supplies a different authorised sellers snippet, update `app-ads.txt`
  to match the account's exact publisher declaration.
