# Route2Charge – Website

Statische Website für die iOS-App **Route2Charge** (Englisch + Deutsch), gehostet über GitHub Pages.

Bewusst schlicht und sicher: nur HTML und CSS. Kein JavaScript, keine Cookies, kein Tracking,
keine externen Schriften oder Dienste. Eine Content-Security-Policy verbietet Skripte komplett.

## Aufbau
- `index.html`, `privacy.html` – Englisch
- `de/index.html`, `de/datenschutz.html` – Deutsch
- `404.html` – Fehlerseite
- `assets/` – Stylesheet, Icon, Vorschaubilder, App-Screenshots
- `tools/build.py` – erzeugt alle Seiten aus einer Vorlage (Texte EN/DE an einer Stelle)

## Ändern
Texte oder E-Mail-Adresse in `tools/build.py` anpassen, dann:

```
python3 tools/build.py
```

Danach committen und pushen – GitHub Pages veröffentlicht automatisch.
