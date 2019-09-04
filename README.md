# Profil-Seite

![layout](drafts/page.png "Portfolio Seite")

- Seite nur für mobile
- meta Tag für die korrekte Skalierung auf Handys benutzen:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1">
  ```
- Link für Email, der E-Mail Anwendung öffnet (0/5)
```diff
- Soll ein Link mit href value im format 'mailto:name@provider.com' sein
```
- Link für Telefon, der Telefon-Anwendung öffnet (5/5)
- Link zum Lebenslauf(PDF), der einen Download auslöst (5/5)
- Links zu Social Media Profilen
  - Haben Icons der Dienste (10/10)
  - Sollen in einem neuen Tab öffnen (0/5)
```diff
- Die Links öffnen keinen neuen Tab weil das target-Attribut fehlt
```
  
- Foto, das im Kreis dargestellt wird, mit border-radius (3/5)
```diff
- border-radius wurde in CSS angewendet, aber das Bild kann nicht geladen werden weil du
- 1. einen absoluten Pfad benutzt hast
- 2. der Pfad zu einem Ordner außerhalb deines Projektordners zeigt. Deshalb wurde das Bild beim Push nicht mit übertragen.
```
- Navigation zu den Abschnitten mit Hash-Links (0/10)
```diff
- In der Navigation sind keine Links
```
- Bilder im Portfolio sollen verlinkt sein (0/10)
```diff
- Das Projektbild in Portfolio ist nicht verlinkt
- Das Bild wird nicht geladen weil der Pfad auf einen Ordner außerhalb des Projektordners verweist.
```

## Anforderungen für den Code
- Keine Block-Tags in Inline-Tags (10/10)
- Padding in den Links der Hauptnavigation (0/10)
- Abstand zwischen Text und Fensterrand und zwischen Text und Element-Rand (5/10)
```diff
- Ich sehe nicht dass padding verwendet wurde um Abstände sicherzustellen.
```
- Korrekte html-Grundstruktur (html, head, body) (9/10)
```diff
- Kein title-Tag im head
```
- Keine Viewport-Elemente im head (5/5)

### Punkte
(**52**/100)
