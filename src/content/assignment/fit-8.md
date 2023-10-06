---
number: 8
title: 'FiT Assignment 8 - Rasa Zusammenfassung'
course: 'fit'
pubDate: 'Nov 28 2022'
---
## Aufgabe
Sehen Sie sich diese Einführungsvideos an und fassen Sie zusammen:
https://learning.rasa.com/conversational-ai-with-rasa/introduction-to-rasa/
https://learning.rasa.com/conversational-ai-with-rasa/creating-a-new-assistant/
https://learning.rasa.com/conversational-ai-with-rasa/domain-file/

## Lösung
Mit Rasa ist es möglich, ein CUI zu erstellen. Dazu werden in der NLU-Datei werden dazu die möglichen Eingaben des Benutzer angegeben und in verschiedene "Intents" kategorisiert. Mithilfe von Rules und Stories kann der Entwickler angeben, wie die CUI auf die jeweiligen Aktionen des Benutzers antwortet. Diese werden in den jeweiligen rules- bzw. stories dateien angegeben. In der Domain-Datei werden die möglichen Antworten des CUI's definiert. Mit dem Befehl Rasa Train kann nun aus all diesen Dateien ein Modell trainiert werden. Dieses Modell kann man dann mit Rasa Shell interaktiv testen.