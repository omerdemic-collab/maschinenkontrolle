# Mobile Maschinenkontrolle – GitHub Pages

Dieses Repository enthält ausschließlich die leere App. Es enthält keine Kataster-, Query-, OneLink- oder Kontrolldaten. Daten werden erst nach dem Start lokal importiert und in IndexedDB des jeweiligen Geräts gespeichert.

## Veröffentlichen
1. Neues GitHub-Repository anlegen.
2. Den **Inhalt dieses Ordners** in die oberste Ebene des Repositorys hochladen. `index.html` darf nicht in einem zusätzlichen Unterordner liegen.
3. In GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Branch **main** und Ordner **/(root)** auswählen, dann **Save**.
5. Nach der Bereitstellung den Pages-Link auf dem iPhone in **Safari** öffnen.
6. Safari: **Teilen → Zum Home-Bildschirm → Hinzufügen**.
7. App über das neue Symbol starten. Kontrollpaket importieren und Offline-Test durchführen.

## Wichtige Sicherheitsregeln
- Niemals Kontrollpakete, JSON-Sicherungen, Excel-Dateien, Kataster oder Kontrollergebnisse ins Repository hochladen.
- GitHub Pages ist öffentlich erreichbar. Nur diese App-Dateien veröffentlichen.
- Kontrolldaten liegen lokal im Browser des jeweiligen Geräts. Regelmäßig Handy-JSON sichern.
- Vor dem Baustelleneinsatz einmal online öffnen, zum Home-Bildschirm hinzufügen, Paket importieren, App schließen, Flugmodus aktivieren und die App erneut über das Symbol testen.
- Excel/JSON-Austauschdateien separat und nur über freigegebene Wege weitergeben.

## Aktualisierung
Bei einem späteren App-Update `CACHE` in `service-worker.js` erhöhen, zum Beispiel auf `sl3-mobile-v0-3`. Danach GitHub-Dateien ersetzen und die App einmal online öffnen. Vor Updates immer Handy-JSON sichern.
