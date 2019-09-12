# fae-global-documentation

In diesem Repository sollen alle globalen und offenen Entscheidungen, das Glossar sowie die Richtlinien (Guides) dokumentiert werden.

## Benutzung
Um einen neuen eintrag zu erstellen legt zu aller erst eine Markdown-Datei nach dem folgendnen Template an.

Dateiname: DD-MM-YYYY-TITEL.md
Beispiel: 12-09-2019-Beispiel.md

Achtung: Jeder Titel muss einzigartig sein, sodass die Datei immer gefunden wird. 

Nachdem ihr die Datei angelegt habt, braucht der Server noch ein paar Metadaten um den Eintrag richtig zuzuordnen. 
Die Metadaten müssen an oberester Stelle innerhalb der Datei stehen. Darauf folgend kommt der Eintrag selbst.

Metadaten
```
---
layout: post
title: Titel (Dieser muss nicht der gleiche wie der Dateiname sein!)
author: DER JEWEILIGE NAME (optional)
categories: global (Weiter Optionen sind weiter unten genannt!)
---
```

Folgend auf diese Metadaten kommt nun der eigentliche Inhalt.
Sobald ihr einen Eintrag committed und pushed, wird der Server aktualisiert und stellt den neuen Eintrag zu verfügung.

### Nutzbare Kategorien
 - global <-- Globale Entscheidung
 - open <-- Offene Entscheidung
 - guide <-- Richtlinie
 - glossar <-- Glossar

 Bitte wählt je nach Eintrag die richtig Kategorie aus.
