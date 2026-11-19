# FitLife

Eine minimalistische, lokal speichernde Fitness-Web-App für iPhone.

## Funktionen
- Ernährungstagebuch: Kalorien und Protein pro Mahlzeit dokumentieren, ohne Kalorienziel oder Defizitwertung
- Wasser- und Schlafprotokoll
- Eigener Home-Trainingsplan, Übungssammlung und Trainingshistorie
- Körperdaten mit getrennten Liniendiagrammen für Gewicht und Größe
- Private Fortschrittsfotos (IndexedDB auf dem Gerät)
- Persönliche Trainingsrekorde sowie Wochen-/Monatsübersicht

## Datenschutz und Speicherung
Einträge werden im Browser-LocalStorage und Fotos in IndexedDB gespeichert. Es gibt keine Anmeldung und keine Cloud-Synchronisierung. Beim Löschen der Browserdaten oder Gerätewechsel können Daten verloren gehen.

## Auf dem iPhone installieren
1. Repository über GitHub Pages veröffentlichen (Settings → Pages → Deploy from a branch → main → /root).
2. Die veröffentlichte Seite in Safari öffnen.
3. Teilen → Zum Home-Bildschirm.

Die App nutzt einen Service Worker für Offline-Caching, sobald sie über HTTPS aufgerufen wird.
