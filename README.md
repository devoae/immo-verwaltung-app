# Immobilien-Verwaltung — App

Web-App zur Verwaltung von Immobilien: Gebäudedaten, Mieteinnahmen, Kosten, Finanzierung/Vermögensaufbau und Marktwert/Beleihungswert.

**Login erforderlich.** Die Seite selbst ist öffentlich erreichbar, zeigt aber ohne gültige Anmeldung (Firebase Authentication) nur den Login-Screen, nie echte Daten. Zugänge werden über die Firebase Console verwaltet (für Devran und ggf. Mitarbeiter).

Alle Daten liegen zentral in der Cloud (Firestore) — derselbe Stand ist auf jedem Gerät sichtbar, auf dem man sich anmeldet.

## Nutzung

Mit E-Mail + Passwort anmelden. Export/Import über den Tab "⚙️ Daten" für ein zusätzliches lokales Backup als JSON-Datei.
