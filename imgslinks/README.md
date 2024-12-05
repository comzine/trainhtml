# Übung: Hobby-Galerie mit HTML und CSS

## Ziel

Erweitere eine bestehende HTML+CSS-Webseite um eine Galerie-Seite, die deine Hobbys präsentiert. Dabei lernst du den Umgang mit Links, Bildern und Flexbox-Layout.

## Ausgangssituation

Du erhältst zwei Dateien ([introduction](../introduction)) mit folgendem Inhalt:

- Eine `index.html` mit einer einfachen "Hallo Welt!"-Seite
- Eine `style.css` mit grundlegender Formatierung

## Anforderungen

### 1. Erweiterung der index.html

1. Füge in der bestehenden `index.html` einen Link zur neuen Hobby-Seite hinzu
2. Ergänze einen Bildbereich mit einem verlinkten Fußballbild

### 2. Erstellung der hobby.html

1. Erstelle eine neue Datei `hobby.html` mit:
   - Korrekter HTML5-Grundstruktur
   - Einbindung der style.css
   - Überschrift "Meine Hobbies"
   - Einer Galerie mit 4 Bildern (abwechselnd Fußball und Basketball)

### 3. Erweiterung der style.css

1. Behalte die bestehenden Stilregeln bei
2. Ergänze neue CSS-Klassen:
   - `.hobby` für einzelne Bildcontainer
   - `.hobbies` für das Flex-Layout der Galerie

## CSS-Spezifikationen

1. **Hobby-Container** (`.hobby`):

   - Breite: 600px
   - Darstellung: inline-block

2. **Galerie-Layout** (`.hobbies`):
   - Display: flex
   - Ausrichtung: space-around
   - Hintergrundfarbe: darkred
   - Kein Rahmen, margin oder padding
   - Flex-wrap aktiviert

## Hinweise

- Alle Bilder sollen auf 100% ihrer Container-Breite skaliert werden
- Bilder müssen mit korrekten alt-Attributen versehen werden
- Links zu den Sportseiten:
  - Fußball: https://dfb.de
  - Basketball: https://www.nba.com

## Benötigte Dateien

- Zwei Bilder: `fussball.jpg` und `basketball.jpg`
- Die bestehenden Dateien `index.html` und `style.css`
- Die neu zu erstellende `hobby.html`

## Erfolgskriterien

- Die Navigation zwischen den Seiten funktioniert
- Die Bilder werden korrekt angezeigt und verlinkt
- Das Flex-Layout sorgt für eine responsive Darstellung der Galerie
- Alle HTML-Dateien sind valides HTML5
- Der CSS-Code ist korrekt formatiert und funktional

Quellen:

fussball.jpg von Marco Verch: https://ccnull.de/foto/fussball-auf-gruenem-spielfeld-mit-weiteren-baellen-im-hintergrund/1106229

basketball.jpg von pexels: https://pixabay.com/photos/man-ball-basketball-person-sport-1837119/
