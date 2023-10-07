---
title: 'Einführung in die Medieninformatik Final Project'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Feb 4 2022'
heroImage: '/em-proj.png'
---

## Idee

In unserem Spiel "Sandmännchen Parkour" steuert der Spieler das Sandmännchen welches in 60 Sekunden 5 Häuser mit Sand bewerfen muss. Einer der zentralen Punkte dabei sind die Hindernisse welche für den Spieler eine Herausforderung darstellen sollen. Der Spieler muss um alle Häuser zu erreichen über eine eingestürzte Brücke und einen umgefallenen Baum Springen. Des Weiteren stellt das Zeit Limit eine weitere Herausforderung da. 

## Implementation

Die Entwicklung der Spielmechanik war meine Aufgabe. Die Entwicklung bestand aus folgenden zentralen Punkten und Problemen:

- Ein grundlegendes Bewegungssystem für den Spieler implementieren.Hierbei war hauptsächlich das konvertieren zwischen globalen und lokalen Orientierungen eine Herausforderungen.
- Das Implementieren von Kollision mit der Welt und den Modellen aus Blender.
- Das Werfen des Sandes mithilfe eines Unity Partikelsystems.
- Die globales Verwaltung von UI-Elementen welche anzeigt wieviel Zeit dem Spieler noch bleibt oder wie viele Häuser er noch abwerfen muss.
- Das Erstellen eines globalen GameObjects in welchem alle relevanten Konfigurations-Einstellungen sind, damit diese nicht über alle Skripte hinweg verteilt liegen.
- Die Implementierung der Gameplay-Loop in welcher mitgezählt werden muss, welche Häuser der Spieler bereits abgeworfen hat. Dafür war es unter anderem nötig mithilfe eines Raycasts zu bestimmen ob der Spieler ein Haus - getroffen, wie weit dieses entfernt ist, und ob er dieses zuvor bereits getroffen hat.
- Implementierung des Game-Overs wenn der Spieler kein Zeit mehr hat, oder in das Wasser fällt.
- Dem Fine-Tuning der Konfigurations-Variablen für die Geschwindigkeit und die Sprung-Eigenschaften des Spielers damit es nicht zu leicht, aber auch nicht zu schwer ist.
- Einbindung von verschiedenen Soundeffekten und der Hintergrundmusik welche während des Spiels läuft.
- Die Gestaltung und Erstellung der Welt beziehungsweise der 3D-Modelle aus denen diese besteht war die Aufgabe von Lukas. Lukas hat auch die Hintergrund Musik selbst komponiert.

## Verwendete Assets

Für die Erstellung des Spiels beziehungsweise der Assets im Spiel haben wir folgende Assets und Tutorials verwendet:

[Skybox](https://assetstore.unity.com/packages/2d/textures-materials/sky/fantasy-skybox-free-18353)

[Texturen](https://assetstore.unity.com/packages/3d/environments/landscapes/terrain-sample-asset-pack-145808)

[Sounds](https://www.zapsplat.com/)

[Shader](https://www.youtube.com/watch?v=Vg0L9aCRWPE)

## Download

[Spiel Download](https://mega.nz/file/MJUBDATI#ktdVu2vcSgtgUM4q2VK_83ic1LM5xl2QfAkf0rmkSLg)
