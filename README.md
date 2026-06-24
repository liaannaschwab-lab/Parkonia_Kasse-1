# Parkonia Kasse 2026

Offline-Kassenapp für das Parkonia Festival 2026.

Die App ist als einzelne HTML-Datei aufgebaut und kann direkt im Browser geöffnet werden.  
Sie ist für ältere iPads, insbesondere iPad Mini 2 mit iOS 12.5.8, optimiert.

## Website öffnen

Nach dem Hochladen auf GitHub Pages ist die App direkt über die GitHub-Pages-URL erreichbar.

Alternativ lokal:

1. Repository herunterladen oder ZIP entpacken.
2. `index.html` öffnen.
3. Am besten im Querformat verwenden.

## Adminbereich

Admin-Passwort:

```text
Parkonia
```

Das Passwort wird in der App nicht angezeigt.

## Anpassungen in dieser Version

- Favoritenleiste oben entfernt.
- Zahlungsart „Depot“ entfernt.
- Depot-Tasten `+ Depot 2.–` und `− Depot 2.–` bleiben erhalten.
- Admin-Passwort-Hinweis entfernt.
- Admin-Passwort auf `Parkonia` geändert.

## Zahlungsarten

- Bar
- TWINT
- Karte

## Funktionen

- Produktkategorien
- Warenkorb mit Mengenanpassung
- Depot hinzufügen und abziehen
- Tagesstatistik
- Bestseller-Auswertung
- CSV-Export
- Tagesabschluss / Reset

## Datenspeicherung

Verkäufe und Bonnummern werden lokal im Browser gespeichert (`localStorage`).  
Beim Tagesabschluss / Reset werden diese Daten gelöscht.

## GitHub Pages aktivieren

1. Neues Repository auf GitHub erstellen, z. B. `parkonia-kasse`.
2. Diese Dateien hochladen:
   - `index.html`
   - `README.md`
3. In GitHub öffnen: **Settings → Pages**
4. Unter **Build and deployment** auswählen:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Speichern.
6. Danach erscheint die Website-URL unter **GitHub Pages**.

## Hinweis

Die App benötigt keine externen Dateien und keine Internetverbindung nach dem Laden.
