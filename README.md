# Last Rodeo Rally · Field Guide (Offline-App)

## Auf GitHub Pages veröffentlichen
1. Auf github.com ein neues Repository anlegen, z. B. `rodeo-rally` (Public).
2. „uploading an existing file“ → den **Inhalt** dieses Ordners hineinziehen (index.html, sw.js, manifest.webmanifest, die Ordner fonts und icons) → Commit.
3. Settings → Pages → Source: „Deploy from a branch“ → Branch `main`, Ordner `/ (root)` → Save.
4. Nach 1–2 Minuten ist die App unter `https://<dein-username>.github.io/rodeo-rally/` erreichbar.

## Auf dem Handy installieren
- **iPhone:** Link in Safari öffnen → Teilen → „Zum Home-Bildschirm“.
- **Android:** Link in Chrome öffnen → ⋮ → „App installieren“.
- Danach einmal den Tab „Water & info“ öffnen: Steht dort „✓ Saved on this device for offline use“, funktioniert die App ohne Netz.

## Änderungen später
Datei ersetzen und in `sw.js` die Zeile `VERSION = "rodeo-v1"` hochzählen (v2, v3 …). Die Handys holen sich das Update beim nächsten Öffnen mit Netz.

Schriften: SIL Open Font License (siehe fonts/OFL-LICENSE.txt).
