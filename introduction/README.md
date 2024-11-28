# Übung: Erste Schritte mit HTML und CSS - Gestaltete Webseite

## Lernziele

- Verstehen der grundlegenden Struktur einer HTML-Datei
- Kennenlernen wichtiger HTML-Elemente
- Erste Schritte mit CSS-Styling
- Verknüpfung von HTML und CSS

## Voraussetzungen

- Ein Texteditor (z.B. Visual Studio Code, Notepad++ oder ein ähnlicher Editor)
- Ein Webbrowser (z.B. Chrome, Firefox)

## Arbeitsschritte

### Teil 1: HTML-Grundstruktur erstellen

1. Erstelle einen neuen Ordner für dein Projekt
2. Erstelle darin eine neue Datei mit dem Namen `index.html`
3. Füge folgenden Code in die `index.html` ein:

```html
<!DOCTYPE html>
<html lang="de">
  <head>
    <meta charset="utf-8" />
    <title>Hallo Welt!</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div>
      <h1>Hallo Welt!</h1>
      <p>Mein erstes HTML+CSS Projekt</p>
    </div>
  </body>
</html>
```

**Erkläre dir den Code:**

- `<!DOCTYPE html>`: Gibt an, dass es sich um ein HTML5-Dokument handelt
- `<html lang="de">`: Das Hauptelement der Seite, `lang="de"` gibt Deutsch als Sprache an
- `<head>`: Enthält Metainformationen und Verweise auf externe Dateien
- `<body>`: Enthält den sichtbaren Inhalt der Webseite
- `<div>`: Ein Container-Element zur Gruppierung von Inhalten
- `<h1>`: Eine Überschrift erster Ordnung
- `<p>`: Ein Textabsatz

### Teil 2: CSS-Styling hinzufügen

1. Erstelle eine neue Datei mit dem Namen `style.css` im gleichen Ordner
2. Füge folgenden Code in die `style.css` ein:

```css
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}

body {
  background-color: darkred;
}

h1 {
  color: white;
}

p {
  color: gold;
}

div {
  background-color: black;
  margin: 20px;
  padding: 20px;
  border: 5px solid green;
}
```

**Erkläre dir das CSS:**

- `*`: Gilt für alle Elemente (Universal-Selektor)
- `margin`: Außenabstand
- `padding`: Innenabstand
- `box-sizing`: Legt fest, wie die Gesamtbreite eines Elements berechnet wird
- `background-color`: Hintergrundfarbe
- `color`: Textfarbe
- `border`: Rahmen (Dicke, Stil, Farbe)

### Teil 3: Testen und Experimentieren

1. Öffne die `index.html` in deinem Browser
2. Beobachte, wie die Seite aussieht
3. Experimentiere mit verschiedenen Änderungen:
   - Ändere die Farben im CSS (z.B. `background-color: blue;`)
   - Ändere den Text im HTML
   - Verändere die Abstände (`margin` und `padding`)

## Aufgaben zum Vertiefen

1. Ändere die Hintergrundfarbe des `body` in deine Lieblingsfarbe
2. Füge einen zweiten Absatz (`<p>`) mit eigenem Text hinzu
3. Ändere die Rahmenfarbe des `div` in eine andere Farbe
4. Vergrößere die Abstände (`margin` und `padding`) und beobachte die Änderungen

## Hilfestellung

- Farben können als Namen (z.B. `red`, `blue`) oder als Hexadezimalwerte (z.B. `#FF0000`) angegeben werden
- Abstände können in Pixeln (`px`) angegeben werden
- Nach jeder Änderung muss die Seite im Browser neu geladen werden

## Zusatzaufgaben

1. Füge eine zweite Überschrift (`<h2>`) hinzu und style sie in CSS
2. Experimentiere mit der Schriftgröße (`font-size`) für die verschiedenen Elemente
3. Füge einen weiteren `<div>`-Container mit anderem Inhalt hinzu

## Tipps

- Speichere deine Dateien regelmäßig
- Überprüfe die Dateinamen und Pfade genau
- Nutze die Browser-Entwicklertools (F12), um Probleme zu finden
- Experimentiere mit verschiedenen Werten, um die Auswirkungen zu verstehen
