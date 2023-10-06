---
number: 10
title: 'FiT Assignment 10 - Rasa part 1'
course: 'fit'
pubDate: 'Nov 28 2022'
---
## Lösung
Bei diesem Chatbot geht es darum, Informationen des Nutzer abzufragen, und diesen über einige Fakten zu informieren. Hierzu können in Rasa zuerst die Rules verwendet werden, um auf spezifische Fragen mit festgelegten Antworten antworten zu können. So lassen sich fragen wie "An wen kann ich mich bei weiteren Fragen wenden?" leicht bearbeiten. Mithilfe von Slots lassen sich Informationen im Chatbot "zwischenspeichern". So ist es möglich, dass sich der Bot Bsp. den Namen und die Email-Adresse der Person die ihn benutzt merkt. Diese Daten können dann entweder in Späteren Ausgaben, oder für andere Prozesse (wie bsp. die Registrierung einer Newsletter) verwendet werden.

Beispielkonversation:

![Beispielconversation](/fit-10.png)

[Code](https://github.com/TillWege/FiT/tree/main/Rasa%201)