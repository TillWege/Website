---
number: 5
title: 'Assignments 28 - 32 - Bildbearbeitung'
course: 'em'
pubDate: 'Nov 16 2021'
---

## Aufgabe 28

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung28)

Bild vor der Binärisierung:


![Bild A](/em-5a.jpg)

Bild nach der Binärisierung:

![Bild B](/em-5b.png)


## Aufgabe 29

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung29)

Bild vor der Binärisierung:


![Bild C](/em-5c.jpg)

Bild nach der Binärisierung:

![Bild D](/em-5d.png)

## Aufgabe 30

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung30)

Erklärung:

Der Code iteriert zweimal über das gesamte Bild. Bei der ersten Iteration wird der hellste und der dunkelste Farbwert des Bildes bestimmt. Mithilfe dieser Werte werden bei der zweiten Iteration alle Pixel des Bildes laut der Formel:

![Bild e](/em-5e.png)

angepasst. Anschließend wird das Bild mit "updatePixels()" aktualisiert und per "image(img,0,0,img.width,img.height);" ausgegeben.

## Aufgabe 31

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung31)

Erklärung:

Beim glätten des Bildes müssen wir die neu berechneten Pixel in ein zweites Bild schreiben, da wir sonst das Original-Bild anpassen würden welche gleichzeitig die Daten beinhält auf dessen Basis wir das Bild glätten wollen. Wir würden sonst also die Daten aus denen wir noch lesen verändern und damit zu einem falschen Ergbenis kommen

## Aufgabe 32

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung32)

Erklärung:

Der hier implementierte Laplace-Filter führt dazu, dass beinah alle Bereiche des Bildes Schwarz gefärbt werden. Die einzigen Stellen an welchen das Bild nicht schwarz ist, sind die Kanten des Original Bildes. Dies wird erzielt, indem der Pixel in der Mitte gleichstark gewichtet wird, wie die Pixel drumherum. Die Pixel drumherum werden allerdings abgezogen. So bleiben nur noch Stellen sichtbar welche verschieden gefärbte Flächen Trennen, also Kanten.
