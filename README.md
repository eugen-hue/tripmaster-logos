# Vereinslogos für die Tripmaster-App

Die Tripmaster-App (eugen360.de) lädt diese Liste unter
**Menü → Eigenes Logo → Vereinslogo laden** und zeigt die Logos zur Auswahl an.
Ein geladenes Logo wird auf dem Gerät gespeichert und funktioniert danach auch ohne Internet.

**Wichtig:** Hier kommen nur Logos von Vereinen hinein, die der Nutzung **ausdrücklich zugestimmt** haben.

## Neues Logo hinzufügen

1. Logo als **PNG** in den Ordner `logos/` hochladen
   (am besten durchsichtiger Hintergrund, quadratisch oder quer bis 3 : 1, mind. 300 px breit,
   Dateiname ohne Leerzeichen und Umlaute, z. B. `oc-stolberg.png`).
2. In `logos.json` einen Eintrag ergänzen:

```json
{
  "version": 1,
  "logos": [
    { "name": "Oldtimerclub Stolberg e.V. im ADAC", "file": "logos/oc-stolberg.png" }
  ]
}
```

Mehrere Einträge werden mit Komma getrennt. Nach dem Speichern ist das Logo sofort in der App verfügbar
(GitHub braucht manchmal ein paar Minuten).

Am einfachsten geht das direkt auf github.com: Datei öffnen → Stift-Symbol (bearbeiten) → „Commit changes“.
