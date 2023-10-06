---
number: 12
title: 'FiT Assignment 12 - Diverses'
course: 'fit'
pubDate: 'Nov 28 2022'
---
## Aufgabe
In der Vorlesungsfolien finden Sie unterschiedliche technische Realisierungen von AR und VR. Für welche Einsatzbereiche könnten folgende Varianten besonders geeignet sein?

## Lösung

- Augmented Audio, ohne visuelle Augmentierung
- Museumsführung
- Entertainment für Blinde
- AR mit einem See-Through-Display
- Interaktive Display-Anzeigen
- Projektionsbasiertes AR.
- Projektion von künstlerischen Projekten an Gebäudewende
- Unterstützungs bei Produktionsschritten
- VR in einer CAVE
- Kunstprojekte
- Vorschau von 2-Dimensionler gestalung
- VR mit einem Head-Mounted Display
- Immersive Erfahrungen, Gaming, virtuelle Kommunikation (Metaverse)

## Aufgabe

Erläutern Sie den Begriff des Horopter und des Panum-Bereichs. Erläutern Sie, warum der Horopter eine geschwungene Form hat, indem Sie geeignete Strahlengänge zeichnen. Als Grundlage können Sie folgende Graphik aus dem Lehrbuch verwenden.

![Horopter](/fit-12.png)

Horopter

Der Horopter beschreibt alle Punkte welcher bei einer Festen Augenstellung auf der Netzhaut abgebildet werden. Es ist also möglich alle diese Punkte fokussiert anzusehen, ohne die Fokusdistanz der Augen neu auszurichten. Bei einem einzelnen Auge ist dieser Bereich ein Kreis. Für beide Augen zusammen ergibt sich so ein Oval.

Panum

Das Panum Areal ist die Projektions des Horopters auf der Netzhaut.

## Aufgabe
Was ist eine negative Parallaxe? Wo liegt der betrachtete Punkt bei einer negativen Parallaxe? Verwenden Sie bei Ihrer Erläuterung den Begriff der Disparität.

## Lösung
Wenn ein Objekt sich auf der äußeren Seite eines der Displays befindet, wird der Fokus der Augen vor das Display geschoben, da sich die Sichtpunkte der Augen überschnieden. Hierbei handelt es sich also um eine negative Disperität, da das rechte Auge nach links, und das linke Auge nach rechts schaut.sich also um eine negative Disperität, da das rechte Auge nach links, und das linke Auge nach rechts schaut.

## Aufgabe
Durch dynamische Änderung der Virtual-Eye-Separation können Objekte näher an den Panumbereich gebracht werden. Wie funktioniert diese Technik? Was gewinnt man damit?

## Lösung
Durch eine erhöhte Seprierung der Augen ist es Möglich Objekt auf der Sichtsphäre zu skalieren. So werden diese zwar Größer, aber aufgrund des Erhöhten Sichtbereichs können diese auch auf größere Distanz platziert werden. So wird die mögliche "tiefe" auf der Objekt platziert werden, ohne das es zu Problemen mit der größendarstellung kommt erhöht.


## Aufgabe
Durch eine dynamische “zyklopische Skalierung” können Objekte ebenfalls näher an den Panumbereich gebracht werden. Wie funktioniert das Verfahren: Machen Sie plausibel, warum sich die Größen der Objekte für den Benutzer nicht ändern, obwohl wir es mit einer Skalierung zu tun haben.

## Lösung
Bei der zyklopischen Skalierung wird die Größe eines Objektes um den Selben Faktor wie seine Distanz zum Auge skaliert. So bleibt es für den Betrachter gleich groß, da es den gleichen Anteil des sichtbaren Bereiches füllt.

## Aufgabe
Geben Sie möglichst viele Beispiele für Möglichkeiten, dass sich in einem VR-Umgebung mittels eines HMD Tiefenhinweise widersprechen können.

## Lösung
Der mögliche tiefen-versatz in einem HMD ist limitiert, so gibt es also eine "maximale Tiefe" die dargestellt werden kann.
Aufgrund der Seperation der Augen ist es am rand des Displays nicht möglich ein Objekt so darzustellen, dass beide Augen es sehen. Dardurch geht der 3-Dimensionale Effekt verloren.

## Aufgabe
Ein Dreiecksnetz besteht aus 15 Dreiecken. Durch wie viele Eckpunkte werden die Dreiecke beschrieben, wenn das Netz durch einen einzigen Triangle Strip dargestellt werden kann?

## Lösung
17 Punkte

## Aufgabe
Erklären Sie bitte den Unterschied zwischen einer herkömmlichen Farbtextur und einer Bump Map. Welche Vor- und Nachteile weist ein Bump Map auf?

## Lösung
Eine reguläre Farbtextur gibt an in welcher Farbe die einzelnen Pixel der Objekte dargestellt werden. Ein Bump-Map hingegen wird verwendet um die Oberfläche eines Objektes zu verändern, ohne das hierfür weitere Polygone verwendet werden. Es handelt sich somit um "Fake-Geometrie" welche u.a. keine eigenen Schatten werfen kann. Dafür ist allerdings der Rendering-Aufwand bedeutend geringer.

## Aufgabe
Was bedeutet LOD? Erklären Sie!

## Lösung
Das Level-of-Detail beschreibt den Detailgrad eines Objektes. In 3D-Rendering ist es nicht nötig Objekte welche weit entfernt sind in voller Qualität zu rendern. Dafür werden verschiedene LOD-Stufen eines Modells verwendet, welche in der Qualität variieren können.