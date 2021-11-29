---
layout: post
title: Applikationssicherheit
---

#Einführung und Ziele des Eintrags#

In diesem Portfolio-Eintrag geht es um die Grundbegriffe der Applikationssicherheit. Ich möchte dem Leser das Grundkonzept der Applikationssicherheit näher bringen und an 2 Beispielen veranschaulichen.

#Schutzziele#
Die Schutzziele sind etwas Grundlegendes in der Applikationssicherheit. Dabei gibt es 3 wichtige Begriffe:
>####Vertraulichkeit####
>Beschreibt den Schutz vor Offenlegung vertraulicher Daten.
>####Integrität####
>Beschreibt die Unversehrtheit von Daten und Informationen.
>####Verfügbarkeit####
>Beschreibt die Verfügbarkeit von Prozessen, Informationen und Daten.

###Beispiel###
Dies sind Fälle, welche die Schutzziele angreifen:

*a) Durch eine DDOS -Attacke wird die Applikation mit Anfragen überflutet und lahmgelegt.
b) Durch Phishing wird das Passwort eines Mitarbeiters gestohlen.
c) Ein Angreifer platziert ein Gerät im Firmennetzwerk, dass den Netzwerkverkehr protokolliert.
d) Ein Angreifer erhält Zugriff auf die Artikel-Datenbank und passt Werte für die Applikation an.
e) Über eine XSS-Attacke wird eine Session eines Mitarbeiters gestohlen.*

In dieser Tabelle wird jeweils angegeben, welches Schutzziel betroffen ist:


|     Aufgabe    |     Vertraulichkeit    |     Integrität    |     Verfügbarkeit    |
|----------------|------------------------|-------------------|----------------------|
|     a)         |     0                  |     0             |     2                |
|     b)         |     2                  |     0             |     0                |
|     c)         |     2                  |     0             |     0                |
|     d)         |     0                  |     2             |     2                |
|     e)         |     2                  |     2             |     0                |

#Aspekt 2#



#Verifizierung und Reflektion#
