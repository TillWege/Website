---
title: 'Fortgeschrittene Interaktionstechnologien Final Project'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Oct 6 2023'
updatedDate: 'Oct 7 2023'
heroImage: '/fit-proj.png'
---
## Theorie:

Bei meinem Projekt handelt es sich um einen Fahrsimulator der es ermöglichen soll, die grundlegenden Funktion des Autofahrens zu erlernen. Das Projekt ist in VR umgesetzt, und bietet eine Anbindung an die Logitech SDK um ein G920 Lenkrad zu unterstützen. Mithilfe des Lenkrads und Shifters wird dem Nutzer so ein Gefühl gegeben, welches sehr ähnlich zum tatsächlichen Autofahren ist.  

Um den Nutzer im Projekt eine klare Richtung zu geben was zu tun ist, hat er eine Liste an Aufgaben welche er abarbeiten soll. Diese Liste beinhaltet häufig auftretende Situationen und Vorgänge aus dem Straßenverkehr. Dinge wie anfahren, Schalten und das korrekte abbiegen mit gesetztem Blinker werden so an den Nutzer herangeführt.

## Die Implementation bestand aus folgenden Abschnitten:

- Beschaffung eines guten Automodells
- Implementierung der Fahrphysik
- Anbindung der Logitech-SDK
- Erstellung des Terrain
- Gestaltung der Karte
- Ausformulierung der Tasks
- Implementierung der unterschiedlichen Aufgaben
- Unterschiedliche Tag/Nacht Einstellung
- Regen mit unterschiedlicher Fahrphysik
- Einbindung von SteamVR

Der Komplexeste Abschnitt war dabei definitiv die implementierung der Fahrphysik. Hierbei war es wichtig, ein Gefühl zu vermitteln welches so realisitisch wie möglich ist. Wichtig war es, dass auch das Schalten zwischen verschiedenen Gängen die Fahrphysik beeinflusst. Hierbei habe ich verschiedene Ansätze probiert ein komplettes Fahrsystem zu simulieren. Es zeigte sich allerdings schnell, dass dies kein gutes Gefühl beim fahren gab.

Die finale Fahrphysik ist eine Mischung aus den Unity Wheel-Collidern und einer rudimentären Motor-Simulation. Dabei wird anhand des aktuellen Tempos des Autos eine Drehzahl berechnet. Mit dieser wird dann der Ton des Motors und das erzeugte Drehmoment berechnet. Mithilfe dieser Daten, und dem aktuell gewählten Gang wird dann dieses Drehmoment an die Wheel-Collider weitergeben. Wichtig war auch, dass die verschiedenen Gänge unterschiedliche maximale geschwindigkeiten hatten. Des Weiteren mussten die Gänge auch, wie in echt, einen Einfluss auf das Drehmoment nehmen.

Als Alternative zu der VR / Lenkrad Steuerung ist auch ein Fallback per Tastatur implementiert. Hierbei sind die Tasten wie folgt beleg:

Lenken: A /D
Gas: W
Bremse: S
Blinken (Links/Rechts): Q/E
Warnblinker: B
Scheinwerfer: H
In einen Gang schalten: 1-5, N und R
Kupplung: C
Tageszeit wechseln: L
Wetter wechseln: K
Motor Starten: Leertaste

Als Aufgaben für den Nutzer wurden die folgenden Aufgaben definiert:

Den Motor starten
Anfahren
In einen Gang schalten
Links abbiegen (mit blinker)
Rechts abbiegen (mit blinker)
Eine Kreuzung gradeaus überqueren
Am Stopschild halten und dannach die Kreuzung in irgendeine Richtung überqueren
5 Mal schalten ohne den Motor abzuwürgen
Die Scheinwerfer in der Nacht einschalten
Den Warnblinker aktivieren
Das Haus auf dem Hügel erreichen
Die Aufgaben basieren auf den wichtigstens und häufigst auftretenden Situationen des Autofahrens. Sie sollen also zumindest die absoluten Grundlagen des Autofahrens soweit vermitteln, dass die ersten Fahrstunden einfacher ausfallen.

Für diese Projekt verwendete Assets:

[Auto-Modell](https://sketchfab.com/3d-models/classic-mazda-miata-cabriolet-low-poly-8bda7836f6514196b7b2fcf32c26d519)

[Sky-Box](https://assetstore.unity.com/packages/2d/textures-materials/sky/fantasy-skybox-free-18353)

[RoadArchitect](https://github.com/MicroGSD/RoadArchitect)

[Code](https://github.com/TillWege/DriverVR)

[Download](https://drive.google.com/drive/folders/1Pk9AgSl5h0gmN1h9mRyb2viZFmL6o_-B)