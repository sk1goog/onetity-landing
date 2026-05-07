# Onetity – öffentliche Infoseite

Kleine statische Seite für **Marketing-URL** und **Support-URL** in App Store Connect. Enthält **keinen** App-Quellcode.

- **Öffentliche URL:** https://sk1goog.github.io/onetity-landing/
- **Datenschutz:** https://sk1goog.github.io/onetity-landing/datenschutz.html · alternativ https://sk1goog.github.io/onetity-landing/datenschutz/

## Änderungen veröffentlichen

Geänderte HTML-Dateien committen und pushen → GitHub Actions baut die Seite neu:

```bash
git add index.html datenschutz.html datenschutz/index.html README.md
git commit -m "…"
git push
```

Quellabgleich erfolgt aus dem Ordner `Onetity-App/` im **Onetity_iOS**-Entwicklerrepo (per Copy).

## Lizenz

Inhalte nach Bedarf; das Repo ist bewusst minimal.
