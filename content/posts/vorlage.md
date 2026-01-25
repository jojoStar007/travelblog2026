+++
date = '2026-01-14T21:35:46+01:00'
draft = true								#muss false sein, damit im Internet sichtbar, sonst nur in meinem Draft Modus (local) sichtbar
title = 'Post-Titel'
place = "Ort"

featured_image = 'https://jojoStar007.github.io/travelblog2026/images/me.jpg'		#Bild, welches man neben Post in Liste klein sieht -> nicht in Galerie
drawer_images = ['https://jojoStar007.github.io/travelblog2026/images/platzhalter-quer.jpg']		#Bilder, die man in Schublade sieht, wenn man auf Post geht -> in Galerie
# drawer_image = 'https://jojoStar007.github.io/travelblog2026/images/platzhalter-quer.jpg'		#wenn man nur ein Bild in die Schublade packen möchte, welches nicht in der Galerie auftaucht						

Location = [-33.04674036048734, -71.61516919332927]			# Format: [Breitengrad, Längengrad] --> für den Pin auf der Karte, wenn anders als vorheriger wird Pin erstellt

summary = "Kurze Zusammenfassung des Blogeintrages. Hier werden u.a. Formatierungen zu finden"
+++


# Die erste Überschrift
## Noch eine Überschrift
### Abschließend eine weitere Überschrift

Fett    ** ** oder __ __    **Fetter Text**

Kursiv  * * oder _ _    *Kursiver Text*

> Ich bin ein Zitat!

In diesem Satz möchte ich `ein Zitat` darstellen.

Für weitere Informationen [hier](https://www.it-talents.de/it-ratgeber/tutorial-markdown-zur-formatierung-von-readme-dateien/) klicken.

![Bildtext](Linkzumbild.jpg "Bildtitel")

- ungeordneter Listenpunkt 1
- ungeordneter Listenpunkt 2
- ungeordneter Listenpunkt 3

1. geordneter Listenpunkt 1
2. geordneter Listenpunkt 2
3. geordneter Listenpunkt 3


1. Titel 1
- Punkt 1
- Punkt 2
2. Titel 2
- Punkt 1
- Punkt 2

## Tabellen

Tabellen sind wunderbar dazu geeignet, um bestimmte Informationen übersichtlich darzustellen. Sie werden mit Pipes (|) und Bindestrichen (-) formatiert:

| Linke Überschrift | Rechte Überschrift |
| ------------------ | ------------------ |
| Etwas Text hier | Ein bisschen hier |

Mit Doppelpunkten (:) kannst Du die Textausrichtung bestimmen:


| Überschrift 1 | Überschrift 2 | Überschrift 3 |
|:--------------|:-------------:|--------------:|
| Links | Zentriert | Rechts |


## Fußnoten

Mit Fußnoten hast Du die Möglichkeit, dem Leser Informationen zu geben, ohne den Lesefluss zu stören. Fußnoten sind kleine, hochgestellte Nummerierungen, die hinter einem Wort erscheinen und zum Ende des Dokuments verlinken.

Hier ist ein Text, der weitere Informationen[^fu1] voraussetzt.

Die erste Syntax kreiert die Verlinkung. Nun musst Du Ihr einen entsprechenden Text zuweisen, den Du unter der Textpassage oder am Ende des Dokuments definierst:

[^fu1]: Weitere Informationen hier

In Fußnoten kannst Du Links einbauen und Text formatieren.
