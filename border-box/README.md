# Das CSS Box-Modell - Eine Einführung für Anfänger

## Lernziele

- Verstehen der grundlegenden Komponenten des Box-Modells
- Kennenlernen der verschiedenen Abstände und Bereiche
- Praktische Anwendung des Box-Modells in CSS

## Das Box-Modell erklärt

### 1. Die Grundkomponenten (von innen nach außen)

```
+---------------------------- (Außenbereich)
|       margin (Außenabstand)
|   +------------------------ (Rahmen)
|   |    border (Rahmen)
|   |   +------------------- (Innenbereich)
|   |   |  padding (Innenabstand)
|   |   |  +--------------- (Inhalt)
|   |   |  |    content
|   |   |  |
|   |   |  +---------------
|   |   +-------------------
|   +------------------------
+----------------------------
```

### 2. Detaillierte Erklärung der Komponenten

#### Content (Inhalt)

- Der eigentliche Inhalt des Elements (Text, Bilder etc.)
- Wird durch `width` und `height` definiert
- Beispiel:

```css
div {
  width: 200px;
  height: 100px;
}
```

#### Padding (Innenabstand)

- Abstand zwischen Inhalt und Rahmen
- Kann für alle Seiten einzeln definiert werden
- Beispiel:

```css
div {
  padding-top: 10px;
  padding-right: 20px;
  padding-bottom: 10px;
  padding-left: 20px;
  /* oder kurz: */
  padding: 10px 20px 10px 20px;
  /* oder noch kürzer für gleiche Werte: */
  padding: 10px;
}
```

#### Border (Rahmen)

- Umrandung des Elements
- Besteht aus Breite, Stil und Farbe
- Beispiel:

```css
div {
  border-width: 2px;
  border-style: solid;
  border-color: black;
  /* oder kurz: */
  border: 2px solid black;
}
```

#### Margin (Außenabstand)

- Abstand zu anderen Elementen
- Kann für alle Seiten einzeln definiert werden
- Beispiel:

```css
div {
  margin-top: 10px;
  margin-right: 20px;
  margin-bottom: 10px;
  margin-left: 20px;
  /* oder kurz: */
  margin: 10px 20px 10px 20px;
  /* oder noch kürzer für gleiche Werte: */
  margin: 10px;
}
```

## Praktische Übung

### Aufgabe 1: Erstelle eine Box

1. Erstelle eine neue HTML-Datei mit folgendem Inhalt:

```html
<!DOCTYPE html>
<html lang="de">
  <head>
    <meta charset="UTF-8" />
    <title>Box-Modell Übung</title>
    <style>
      .box {
        width: 200px;
        height: 100px;
        background-color: lightblue;
        padding: 20px;
        border: 5px solid blue;
        margin: 30px;
      }
    </style>
  </head>
  <body>
    <div class="box">Dies ist eine Box mit Inhalt</div>
  </body>
</html>
```

### Aufgabe 2: Experimentiere

Verändere die Werte für:

1. `padding`
2. `margin`
3. `border`
4. `width` und `height`

## Wichtige Konzepte

### Box-Sizing

```css
* {
  box-sizing: border-box;
}
```

- `content-box` (Standard): Width und Height beziehen sich nur auf den Content
- `border-box`: Width und Height beinhalten Padding und Border

### Gesamtbreite berechnen

- Bei `content-box`:
  - Gesamtbreite = width + padding-left + padding-right + border-left + border-right + margin-left + margin-right
- Bei `border-box`:
  - Gesamtbreite = width + margin-left + margin-right

## Übungsaufgaben

1. **Basis-Übung**

   - Erstelle zwei Boxen nebeneinander
   - Gib ihnen unterschiedliche Padding- und Margin-Werte
   - Beobachte, wie sie sich zueinander verhalten

2. **Erweiterte Übung**
   - Erstelle eine Box in einer Box
   - Experimentiere mit verschiedenen Margin- und Padding-Werten
   - Beobachte das Verhalten der inneren Box

## Tipps

- Nutze die Browser-Entwicklertools (F12 bzw `Strg+Shift+I`)
- Die Entwicklertools zeigen das Box-Modell visuell an
- Experimentiere mit verschiedenen Werten
- Beachte den Unterschied zwischen `content-box` und `border-box`

## Zusatzaufgabe

Erstelle eine "Visitenkarte" mit:

- Einem Bild
- Text
- Rahmen
- Angemessenen Abständen
- Schatten (`box-shadow`)

Dies hilft dir, das Box-Modell in einem praktischen Kontext zu verstehen und anzuwenden.
