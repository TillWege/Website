---
number: 2
title: 'Assignments 8 - 14 - SVG'
course: 'em'
pubDate: 'Oct 27 2021'
---

## Übung 8
```svg
<svg xmlns="http://www.w3.org/2000/svg" width="300" height="300" version="1.1">
    <circle cx="150" cy="150" r="89.5" stroke="black" stroke-width="3" fill="green" />
</svg>
```

Grüner kreis mit d=197px und schwarzer Umrisslinie

## Übung 9

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="300" height="300" version="1.1">    <circle cx="200" cy="150" r="20" stroke="black" stroke-width="3" fill="gray" />    <polyline points="190,165 200,132 210,165 182,145 218,145 190,165" stroke="white" fill="none"/>    <circle cx="50" cy="150" r="20" stroke="black" stroke-width="3" fill="gray" />    <polyline points="40,165 50,132 60,165 32,145 68,145 40,165" stroke="white" fill="none"/>    <polygon fill="white" points="20,150 20,100 70,100 120,80 200,80 230,140 220,130 180,130 170,150 80,150 75,130 30,130" stroke="black" stroke-width="3"/>    <ellipse cx="140" cy="120" rx="10" ry="3" fill="white" stroke="black" stroke-width="1"/>    <polygon points="70,100 120,80 120,100" fill="gray" stroke="black" stroke-width="2"/>    <polygon points="150,85 150,100 170,100 170,85" fill="gray" stroke="black" stroke-width="2"/>    <polyline stroke-dasharray="5,5" points="150,88 170,88 170,90 150,90 150,92 170,92 170,94 150,94 150,96 170,96" fill="none" stroke="black" stroke-width="1"/></svg>
```

Auto

## Übung 10

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="300" height="500">
	<g transform="translate(100 100)" id="CLOCK">
        <circle r="80" stroke="black" stroke-width="3" fill="white" ID="outer"/>       
        <line stroke-width="5" x1="0" y1="0" x2="-44" y2="-44" stroke="green" opacity=".5" ID="Hours ">
		    <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="86400s" by="360" />
        </line>

         <line stroke-width="5" x1="0" y1="0" x2="-40" y2="-40" stroke="red" opacity=".5" ID="Minutes">
		    <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="3600s" by="360" />
        </line>

        <line stroke-width="5" x1="0" y1="0" x2="-44" y2="-44" stroke-linecap="round" stroke="blue" opacity=".5" ID="Seconds">
            <animateTransform attributeName="transform" type="rotate" repeatCount="indefinite" dur="60s" by="360" />
        </line>
        <circle r="7" />
        
	</g>
</svg>
```

Animierte Uhr


## Übung 11

Die erste Koordinate gibt den zur Anfangsposition gehörigen Kontrollpunkt an. Die zweite gibt den Kontrollpunkt an, welcher zum Endpunkt gehört.  Die letzte Koordinate gibt den Endpunkt der Curve an. Mithilfe der Position der Kontrollpunkte lässt sich die Form der Kurve steuern. Damit kann die Neigung welcher die Kurve folgt definiert werden. Optische Beispiele:


Im Beispiel sind die Kontrollpunkte jeweils genau 50 Einheiten über dem Start- bzw. Endpunkt der Kurve. Deshalb ist die Kurve relativ Flach.


Wenn wir die Kontrollpunkte um weitere 100 Einheiten nach oben verschieben, hat die Kurve eine extreme Biegung.

Wenn wir die Kontrollpunkte nun um 25 Einheiten weiter nach innen verschieben, läuft die Kurve spitzer zu.

Wenn wir nun den linken Kontrollpunkt unterhalb dem Startpunkt positionieren, folgt die Kurve einer S-ähnlichen Form

Wenn wir nun das große C durch ein kleines ersetzen, geben wir nicht mehr die Kontrollpunkte direkt an, sondern um wieviel die Kontrollpunkte von unserer aktuellen Position auf den jeweiligen achsen verschoben sind. Wenn wir dies bei der Ursprünglichen Kurve machen, ändert sich die Form sehr stark.

Dies geschieht, da die Kontrollpunkte und der Endpunkt immer weiter in die positive X und Y richtung, also nach unten Links gehen.

## Übung 12

Inkscape Export

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="400">
  <g id="bunny"
     inkscape:label="Layer 1"
     inkscape:groupmode="layer"
     id="layer1"
     transform="translate(-6.2294432,-138.31889)">
    <ellipse
       style="fill:#c87137;stroke-width:0.264583"
       id="path22"
       cx="109.77235"
       cy="221.0787"
       rx="72.219345"
       ry="44.63401" />
    <ellipse
       style="fill:#c87137;stroke-width:0.294944"
       id="path24"
       cx="-61.453342"
       cy="186.47321"
       rx="24.284969"
       ry="33.734375"
       transform="rotate(-33.326562)" />
    <ellipse
       style="fill:#000000;stroke-width:0.264583"
       id="path28"
       cx="34.377316"
       cy="178.70445"
       rx="3.3072915"
       ry="3.7797618" />
    <ellipse
       style="fill:#000000;stroke-width:0.264583"
       id="path30"
       cx="53.843094"
       cy="178.32648"
       rx="4.6302085"
       ry="4.3467264" />
    <path
       style="fill:#000000;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="M 31.259012,170.57796 C 10.848297,152.05713 5.3676442,147.71041 6.5015712,143.36368 c 1.133928,-4.34673 11.5282738,4.15774 11.5282738,4.15774 l 17.575893,20.03274 z"
       id="path32" />
    <path
       style="fill:#000000;stroke:#000000;stroke-width:0.36538px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 51.519424,166.22356 c 7.640952,-4.59606 22.740728,-23.54672 22.740728,-23.54672 0,0 9.41681,-7.05487 8.13469,-2.82494 -1.28214,4.22994 -21.31032,29.50574 -21.31032,29.50574 l -8.323797,-2.81993 z"
       id="path34" />
    <circle
       style="fill:#784421;stroke-width:0.264583"
       id="path52"
       sodipodi:type="arc"
       sodipodi:cx="181.97701"
       sodipodi:cy="219.71487"
       sodipodi:rx="21.450148"
       sodipodi:ry="22.867559"
       sodipodi:start="6.2688212"
       sodipodi:end="6.2164963"
       sodipodi:open="true"
       sodipodi:arc-type="arc"
       d="m 203.42494,219.38641 a 21.450148,22.867559 0 0 1 -20.8593,23.18741 21.450148,22.867559 0 0 1 -22.02117,-21.93246 21.450148,22.867559 0 0 1 20.28319,-23.76119 21.450148,22.867559 0 0 1 22.55181,21.31082" />
    <circle
       style="fill:#803300;stroke-width:0.264583"
       id="path56"
       sodipodi:type="arc"
       sodipodi:cx="44.015709"
       sodipodi:cy="189.94925"
       sodipodi:rx="1.4174107"
       sodipodi:ry="1.7953868"
       sodipodi:start="6.2688212"
       sodipodi:end="6.2164963"
       sodipodi:open="true"
       sodipodi:arc-type="arc"
       d="m 45.432973,189.92346 a 1.4174107,1.7953868 0 0 1 -1.378368,1.8205 1.4174107,1.7953868 0 0 1 -1.455143,-1.72197 1.4174107,1.7953868 0 0 1 1.340299,-1.86555 1.4174107,1.7953868 0 0 1 1.490208,1.67317" />
    <path
       style="fill:#784421;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 64.313551,252.82055 c 0,0 -14.911379,-8.92977 -18.117119,-1.53681 -3.205746,7.39295 30.584068,12.92855 30.584068,12.92855 0,0 9.060925,-0.60746 5.456536,-2.92404 -3.604394,-2.31661 -17.923485,-8.4677 -17.923485,-8.4677 z"
       id="path62" />
    <path
       style="fill:#a05a2c;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 126.27429,259.51466 c 0,0 -17.21725,-2.37838 -17.27238,5.67951 -0.0551,8.05788 33.20431,-0.0786 33.20431,-0.0786 0,0 8.09966,-4.1067 3.87601,-4.82705 -4.22367,-0.72038 -19.80794,-0.77383 -19.80794,-0.77383 z"
       id="path62-5" />
    <ellipse
       style="fill:#c87137;stroke-width:0.264583"
       id="ellipse84"
       cx="109.77235"
       cy="221.0787"
       rx="72.219345"
       ry="44.63401" />
    <ellipse
       style="fill:#c87137;stroke-width:0.294944"
       id="ellipse86"
       cx="-61.453342"
       cy="186.47321"
       rx="24.284969"
       ry="33.734375"
       transform="rotate(-33.326562)" />
    <ellipse
       style="fill:#000000;stroke-width:0.264583"
       id="ellipse88"
       cx="34.377316"
       cy="178.70445"
       rx="3.3072915"
       ry="3.7797618" />
    <ellipse
       style="fill:#000000;stroke-width:0.264583"
       id="ellipse90"
       cx="53.843094"
       cy="178.32648"
       rx="4.6302085"
       ry="4.3467264" />
    <path
       style="fill:#000000;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="M 31.259012,170.57796 C 10.848297,152.05713 5.3676442,147.71041 6.5015712,143.36368 c 1.133928,-4.34673 11.5282738,4.15774 11.5282738,4.15774 l 17.575893,20.03274 z"
       id="path92" />
    <path
       style="fill:#000000;stroke:#000000;stroke-width:0.36538px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 51.519424,166.22356 c 7.640952,-4.59606 22.740728,-23.54672 22.740728,-23.54672 0,0 9.41681,-7.05487 8.13469,-2.82494 -1.28214,4.22994 -21.31032,29.50574 -21.31032,29.50574 l -8.323797,-2.81993 z"
       id="path94" />
    <circle
       style="fill:#784421;stroke-width:0.264583"
       id="circle96"
       sodipodi:type="arc"
       sodipodi:cx="176.09708"
       sodipodi:cy="220.2494"
       sodipodi:rx="21.450148"
       sodipodi:ry="22.867559"
       sodipodi:start="6.2688212"
       sodipodi:end="6.2164963"
       sodipodi:open="true"
       sodipodi:arc-type="arc"
       d="m 197.54501,219.92094 a 21.450148,22.867559 0 0 1 -20.8593,23.18741 21.450148,22.867559 0 0 1 -22.02117,-21.93246 21.450148,22.867559 0 0 1 20.28319,-23.76119 21.450148,22.867559 0 0 1 22.55181,21.31082" />
    <circle
       style="fill:#803300;stroke-width:0.264583"
       id="circle98"
       sodipodi:type="arc"
       sodipodi:cx="44.015709"
       sodipodi:cy="189.94925"
       sodipodi:rx="1.4174107"
       sodipodi:ry="1.7953868"
       sodipodi:start="6.2688212"
       sodipodi:end="6.2164963"
       sodipodi:open="true"
       sodipodi:arc-type="arc"
       d="m 45.432973,189.92346 a 1.4174107,1.7953868 0 0 1 -1.378368,1.8205 1.4174107,1.7953868 0 0 1 -1.455143,-1.72197 1.4174107,1.7953868 0 0 1 1.340299,-1.86555 1.4174107,1.7953868 0 0 1 1.490208,1.67317" />
    <path
       style="fill:#784421;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 64.313551,252.82055 c 0,0 -14.911379,-8.92977 -18.117119,-1.53681 -3.205746,7.39295 30.584068,12.92855 30.584068,12.92855 0,0 9.060925,-0.60746 5.456536,-2.92404 -3.604394,-2.31661 -17.923485,-8.4677 -17.923485,-8.4677 z"
       id="path100" />
    <path
       style="fill:#a05a2c;stroke:#000000;stroke-width:0.264583px;stroke-linecap:butt;stroke-linejoin:miter;stroke-opacity:1"
       d="m 126.27429,259.51466 c 0,0 -17.21725,-2.37838 -17.27238,5.67951 -0.0551,8.05788 33.20431,-0.0786 33.20431,-0.0786 0,0 8.09966,-4.1067 3.87601,-4.82705 -4.22367,-0.72038 -19.80794,-0.77383 -19.80794,-0.77383 z"
       id="path102" />
  </g>
    <rect width="1000" height="1000" fill="white"/>
    <use href="#bunny" x="20" y="50" />
    <use href="#bunny" x="150" y="150" />
    <use href="#bunny" x="100" y="250" />
</svg>
``````


## Übung 13

```SVG
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="400" version="1.1">
    <path d="M110,70 C90,90, 130,100, 90,200" fill="none" stroke="black"/>
    <path d="M90,200 C50,300 350,400, 360,130" fill="none" stroke="black">
</svg>
```

Die zweite Kurve soll am Endpunkt der ersten anlegen. Damit dies der Fall ist muss, wird für die Koordinate des M Befehls das gleiche eingesetzt, wie die letzte Koordinate der ersten Kurve (90|200). Damit die Kurven nun Glatt ineinander übergehen, muss die Steigung der beiden Kurve an diesem Punkt gleich sein. Um das sicherzustellen, muss der erste Kontrollpunkt der zweiten Kurve ein "Spiegelbild" des Zweitenn Kontrollpunkts der ersten Kurve sein. Um diesen Punkt zu berechnen kann der Vektor zwischen dem Endpunkt und dem zweiten Kontrollpunkt der ersten Kurve genutzt werden. Für diesen Folgt:Endpunkt - Kontrollpunkt = Vektor => (90|200) - (130|100) = (-40|100)Wenn wir diesen Vektor nun auf unseren Startpunkt addieren erhalten wir:(90|200) + (-40|100) = (50|300)50,300 ist also der zweite gesuchte Punkt.Der Pfad der zweiten Kurve lautet also:
``<path d="M90,200 C50,300 350,400, 360,130" fill="none" stroke="black">``

## Übung 14
```SVG
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="400" version="1.1">
    <path d="M110,70 C90,90, 130,100, 90,200 S350,400 360,130" fill="none" stroke="black"/>
</svg>


```
Um die Kurve in ein einzelnes Path Element umzuschreiben können wir den zweiten Endpunkt der zweiten Kurve (350|400) und den Endpunkt der zweiten Kurve (360|130)  mit einem S Befehl an die erste Kurve anhängen. Das Path Element sollte also wie folgt lauten:
``<path d="M110,70 C90,90, 130,100, 90,200 S350,400 360,130" fill="none" stroke="black"/>``