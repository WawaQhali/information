# Wawa Qhali · information

Static site (GitHub Pages) with the legal documents that the mobile app links to:

| Page | URL once Pages is on |
| --- | --- |
| Home | https://wawaqhali.github.io/information/ |
| Terms and conditions | https://wawaqhali.github.io/information/terminos.html |
| Privacy policy | https://wawaqhali.github.io/information/privacidad.html |

The app reads these URLs from `assets/db.json` (`app.terminosUrl` and `app.privacidadUrl`) in the Mobile-App repo.

## Publish

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save. The site is live in about a minute.

## Edit

Plain HTML and one stylesheet (`styles.css`, same palette and fonts as the app). No build step. The texts are in Spanish because they are for the families who use the app.

If a change affects photo donation, also bump `versionTextoDonacion` in the app so families accept the new text.
