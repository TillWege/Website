---
number: 3
title: 'Assignments 15 - 20 - Farben'
course: 'em'
pubDate: 'Nov 3 2021'
---

## Übung 15

Der Farbauswahldialog aus Gimp stellt einen 2-Dimensionalen Ausschnitt aus dem Würfel an der ausgewählten Stelle der aktiven Achse da. 

![Farben A](/em-3a.png)

Hierbei wird beispielsweise der Ausschnitt aus dem Farbwürfel angezeigt an denB=100 ist. Es wird also immer eine "Scheibe" des Würfels dargestellt. Das verschieben des Schiebereglers gibt dabei an welcher Stelle die "Scheibe" entnommen wird. Wenn wir für B=0 einstellen, so werden die Kombinationen aus Rot und Grün angezeigt in welchen kein Blau enthalten ist. Wir schauen also auf die Seite des Würfels, auf welcher der Vektor der B-Achse mit 90° steht.

![Farben B](/em-3b.png)

Wenn wir hingegeben B=255 einstellen, so sehen wir nur die Farben welche 100% an Blau beinhalten.

![Farben C](/em-3c.png)

Die Farbe RGB(150,200,100) liegt innerhalb des Würfels, da keine Achse 0 ist. Der Punkt liegt relativ mittig, da die Werte vergleichsweise nah beieinander liegen. 

![Farben D](/em-3d.png)

## Übung 16

Der RGB-Farbwürfel hat seinen Ursprung bei Schwarz, da kein RGB meisten mit additiven Farb-Prozessen genutzt wird. Dies äußert sich dadurch, das Weiß durch RGB(255,255,255) abgebildet wird. 

![Farben E](/em-3e.png)

Der CYM(K)-Farbwürfel hingegen hat seinen Ursprung bei Weiß, und CYM(255,255,255) stellt Schwarz da. Dieser Farbraum wird meistens bei Subtraktiven Prozessen wie beim Drucken verwendet.

![Farben F](/em-3f.png)

Aus den Bildern zeigt sich erneut, dass es sich bei den Farben um komplementäre handelt, denn die Ecken der Würfel sind zwar gleich, aber die Koordinatensysteme wurden so ausgelegt, dass ein Wert der in RGB mit einem Wert dargestellt werden kann (Beispiel Rot = RGB(255,0,0) in CYM zwei Achsen benötigt (Rot = CYM(0,255,255). Es handelt sich also um die gleichen Farben, nur anders beschrieben.

## Übung 17

[Code](https://github.com/TillWege/Medieninformatik/tree/master/%C3%9Cbung%2017)

## Übung 18

YCbCr:

```fy=0+(0,299*170)+(0,587*185)+(0,114*10)=160,565

fcb=128-(0,168736*170)-(0,331264*185)+(0,5*10)=43,03104

fcr=128+(0,5*170)-(0,418688*185)-(0,081312*10)=134,7296

=>(160,57|430,03|134,73)
```


CMY:
```
C= 1 - (R/255) => 1-(170/255)=0,33333

M= 1 - (G/255) => 1-(185/255)=0,2745

Y= 1-(Y/255)=> 1-(10/255)=0,9607

=>(0,33333|0,2745|0,9607)
```

## Übung 19

Die Farbachsen des gegenfarben-Modells ergeben sich aus der Art wie das Auge Licht war nimmt. So werden aus den Signalen der Zäpfchen 3 Achsen gebildet. Der Rot-Grün-Kanal ergibt sich aus beispielsweise aus der Differenz zwischen der Wahrnehmung des Roten und den Grünen sehens. Unser Gehirn scheint dies automatisch zu tun, da es in allen Kulturen ähnliche Farbeinteilungen in diese Achsen gibt.

## Übung 20

Der Farbraum welcher sich aus 3 Additiven Farben ergibt immer ein Dreieck. Das Chromatizitätsdiagramm ist aber eher Hufeisenförmig. Wenn alle Farben dieses im Dreieck der anzeigbaren Farben liegen sollen, müssen aber auch nicht sichtbare Farben im dreieck liegen. Deshalb ist es nicht möglich mit 3 Additatieven Farben alle sichtbaren Farben darzustellen. 