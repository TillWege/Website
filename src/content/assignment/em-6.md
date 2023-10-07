---
number: 6
title: 'Assignments 33 - 37 - Computergrafik'
course: 'em'
pubDate: 'Nov 28 2021'
---

## Aufgabe 33

[Fallstudie 1:](https://unity.com/de/case-study/autoliv)

[Fallstudie 2:](https://unity.com/de/case-study/shipbreaker)

[Fallstudie 3:](https://unity.com/case-study/apex)

## Aufgabe 34

Aus dem Skript folgt für das Drehen eines Punktes (X,Y) um den Ursprung um den Winkel b:

P(x', y') = P(x∙cos b - y∙sin b, x∙sin b + y∙cos b)

Das Viereck mit den Punkten (100,200), (400,200), (400,400) und (100,400) hat dann folgende Punkte wenn es um 10° um den Ursprung gedreht wird:

P1:

P(x', y') = P(100∙cos(10°) - 200∙sin(10°), 100∙sin(10°) + 200∙cos(10°))P(x', y')= P(63,75 , 214,33)

P2:

P(x', y') = P(400∙cos(10°) - 200∙sin(10°), 400∙sin(10°) + 200∙cos(10°))P(x', y')= P(359,19 , 266,42)

P3:

P(x', y') = P(400∙cos(10°) - 400∙sin(10°), 400∙sin(10°) + 400∙cos(10°))P(x', y')= P(324,46 , 463,38)

P4:

P(x', y') = P(100∙cos(10°) - 200∙sin(10°), 100∙sin(10°) + 200∙cos(10°))P(x', y')= P(29,02 , 411,29)

Diese Werte stimmen mit den Werten (64,214), (359,266), (325,463), (29,411) größtenteils überein. In diesem Fall dürfen wir die Rotationsformel für den Zweidimensionalen Raum auch für 3-Dimensionale Punkte verwenden, da der Dritte Wert immer 0 ist.

## Aufgabe 35

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung35)

Resultat:

![Grafik A](/em-6a.png)

## Aufgabe 36

[Code](https://github.com/TillWege/Medieninformatik/tree/master/Uebung36)

Resultat:

![Grafik B](/em-6b.png)

## Aufgabe 37

![Grafik C](/em-6c.png)

Die Textur in diesem Bild wir in der oberen Rechten und der unteren Linken ecke verzogen. Hierbei wird die Textur wie folgt verzogen:

![Grafik D](/em-6d.png)

Die Textur ähnelt also einem Trapez, da in den jeweiligen Ecken nicht die 0 punkte der Textur, sondern der Mittelpunkt angegeben wird. Deshalb erscheint die Textur so verzogen.