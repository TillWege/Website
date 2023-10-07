---
number: 8
title: 'Assignments 41 - 43 - Neuronale Netzwerke'
course: 'em'
pubDate: 'dec 16 2021'
---

## Aufgabe 41

Prädiktoren und linearen Klassifizierer sind beide Programme welche Anhand von Daten "lernen" können mit neuen, unbekannten Daten umzugehen. 

Ein Prädiktor nimmt dabei einen Wert als Eingabe an, und gibt für diesen dann aus was der Prädiktor als richtiges Ergebnis "gelernt" hat. Dabei kann die Eingabe in bisher noch nie gesehener Wert sein. 

Ein linearer Klassifizierer welcher auch einen Wert einnimmt, ordnet diese Werte hingegen in Gruppen ein. Das "linear" kommt in diesem Fall davon, dass die interne Trennlinie des Klassifizierers eine lineare Funktion ist (Siehe Abbildung). Dies schränkt den Klassifizierer in seiner Fähigkeit komplexe Situationen zu bewerten ein. Diese Trennlinie könnte beispielsweise mithilfe eines Prädiktors gebildet werden um sicherzustellen, dass das Klassifizieren mit mehr Datenpunkten immer genauer wird.

In meinem Beispiel werden Hunde und Pferde von einander unterschieden. Dies geschieht anhand des Verhältnisses zwischen der Geschwindigkeit (X-Achse) und des Gewichts des Tieres (Y-Achse).

![Grafik A](/em-8a.png)

## Aufgabe 42

Ein Convolutional Neural Network (CNN) ist eine Art von Neural Network welche meistens für Daten verwendet werden, die eine hohe Komplexität aufweist wie Bildklassifizierung und Sprachanalyse.  

![Grafik B](/em-8b.png)

Dieses CNN dient der Bilderkennung. In unserem Beispiel wird der Grau markierte Ausschnitt des Eingabebildes als Roboterhand klassifiziert. Der erste Schritt des oben abgebildeten CNN's ist mithilfe einer Convolution (Faltungsschicht) verschiedene relevante Eigenschaften des Bildes (features) zu erkennen. Dabei ist jede Feature-Map (Merkmalkarte) für ein eigenes Merkmal in einem gewissen Bildbereich verantwortlich. Jede Feature-Map kann so als eigenes kleines Neural Network gesehen werden, welches bewertet wie wahrscheinlich es ist, dass das Eingabebild in einem gewissen Bereich eine spezifische Eigenschaft beinhält. Die Ergebnisse dieser Ebene werden dann an eine weitere Ebene an Merkmalskarten weitergegeben. 

Bevor wir die Daten allerdings in die nächste Ebene an Merkmalskarten weitergeben, verringern wir die Komplexität der Daten durch das sog. Subsampling. Dies geschieht im Subsampling-Layer zwischen den Feature-Maps. Die Neuronen dieser Ebene fassen mehrere Eingaben aus der vorherigen Ebene zusammen für ihren Output. Jedes einzelne Neuron dieser ebene hat also ein eigenes Rezeptives Feld auf das sie reagieren. So können aus mehreren Teil-Features wieder ein "großes Feature" zusammengebaut werden welches die nächste Merkmalskarte wieder bewerten kann. 

Dieser Vorgang des Merkmale bestimmen und zusammenfassen kann nun mehrfach wiederholt werden. Am Ende des CNN's sitzt ein Fully connected (komplett verknüpftes) Layer in welchem jedes Output-Neuron zugriff auf alle Neuronen aus der vorherigen Schicht hat. Die Anzahlt der Output-Neuronen ist hierbei gleich zu der Menge an verschiedenen Ausgaben die das CNN tätigen können soll. Anhand der Internen Gewichte des Neurons und denen der Verbindungen zwischen den Neuronen werden dann die Output-Wahrscheinlichkeiten für die verschiedenen Ergebnisse bestimmt.

# Aufgabe 43

![Grafik C](/em-8c.png)

![Grafik D](/em-8d.png)

![Grafik E](/em-8e.png)

Veränderte Parameter für Grafik E:

STYLE_WEIGHT = 0.025 anstelle des normalen 0.01

ITERATIONS = 50 anstelle der normalen 10