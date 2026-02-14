# 🍕 Pizzeria Schichtplan

Einfache Web-App zur Schichtplanung für die Pizzeria.

## Features

### Admin-Modus (Jacob)
- Schichten erstellen mit Datum und Anzahl benötigter Mitarbeiter
- Quick-Buttons für "Nächstes Wochenende (Fr-So)"
- Notizen für besondere Tage (Feiertage, Events)
- Schichten löschen
- Übersicht wer sich eingetragen hat

### Mitarbeiter-Modus
- Name eingeben und speichern
- Verfügbare Schichten sehen
- Sich für freie Schichten eintragen
- Sich wieder austragen

## Nutzung

1. **Admin:** Erst Schichten erstellen (Datum + Anzahl Mitarbeiter)
2. **Mitarbeiter:** Link teilen, Mitarbeiter tragen sich selbst ein

## Technisch

- Reine HTML/CSS/JS (keine Dependencies)
- Daten werden im LocalStorage gespeichert
- Responsive Design (funktioniert auf Handy)

## Limitierung

⚠️ **LocalStorage:** Daten sind nur auf dem jeweiligen Gerät gespeichert. 
Für echte Multi-User Nutzung bräuchte es ein Backend (Firebase, Supabase, etc.)

## Deployment

Kann auf GitHub Pages, Netlify, oder jedem Webserver gehostet werden.
