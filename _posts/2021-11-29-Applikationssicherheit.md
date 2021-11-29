---
layout: post
title: Applikationssicherheit
---

# Einführung und Ziele des Eintrags #

In diesem Portfolio-Eintrag geht es um die Grundbegriffe der Applikationssicherheit. Ich möchte dem Leser das Grundkonzept der Applikationssicherheit näher bringen und an 2 Beispielen veranschaulichen.

# Schutzziele #
Die Schutzziele sind etwas Grundlegendes in der Applikationssicherheit. Dabei gibt es 3 wichtige Begriffe:

#### Vertraulichkeit ####
Beschreibt den Schutz vor Offenlegung vertraulicher Daten.
#### Integrität ####
Beschreibt die Unversehrtheit von Daten und Informationen.
#### Verfügbarkeit ####
Beschreibt die Verfügbarkeit von Prozessen, Informationen und Daten.

### Beispiel ###
Dies sind Fälle, welche die Schutzziele angreifen:

*a) Durch eine DDOS -Attacke wird die Applikation mit Anfragen überflutet und lahmgelegt.*

*b) Durch Phishing wird das Passwort eines Mitarbeiters gestohlen.*

*c) Ein Angreifer platziert ein Gerät im Firmennetzwerk, dass den Netzwerkverkehr protokolliert.*

*d) Ein Angreifer erhält Zugriff auf die Artikel-Datenbank und passt Werte für die Applikation an.*

*e) Über eine XSS-Attacke wird eine Session eines Mitarbeiters gestohlen.*

In dieser Tabelle wird jeweils angegeben, welches Schutzziel betroffen ist:


|     Aufgabe    |     Vertraulichkeit    |     Integrität    |     Verfügbarkeit    |
|----------------|------------------------|-------------------|----------------------|
|     a)         |     0                  |     0             |     2                |
|     b)         |     2                  |     0             |     0                |
|     c)         |     2                  |     0             |     0                |
|     d)         |     0                  |     2             |     2                |
|     e)         |     2                  |     2             |     0                |


#Risiko#
Folgender Sachverhalt besteht:
*Sie besitzen ein günstiges und ein teures Fahrrad und haben jeweils in einem Stadtteil mit niedriger und einem mit hoher Kriminalitätsrate zu tun. Sie haben Angst, dass die Fahrräder gestohlen werden könnten.*

Dies ist ein gutes Beispiel, wie Risiken abgeschätzt werden. In der Informatik kann nicht immer jedes Problem behoben werden, zum Beispiel aus zeitlichen oder finanziellen Gründen. Deshalb wird geschaut, welches Problem am wichtigsten zum Beheben ist.

Man kann dies also auflisten, wie in diesem Bild:

![bild](https://user-images.githubusercontent.com/54060230/143895572-2dd6bc60-b9c7-41ce-8cc0-9d9fb90b93aa.png)

Oder als Matrix darstellen:

![matrix](https://user-images.githubusercontent.com/54060230/143895432-c68c60c5-d238-46cd-986b-6a0233d8b85d.png)


# Verifizierung und Reflektion #
Mein Ziel, dem Leser einen Überblick zu verschaffen habe ich erreicht, da ich die wichtigsten Begriffe erklärt habe und ein Fallbespiel zum Risiko gemacht habe.

Leider habe ich mein letztes Ziel noch nicht ganz erreicht, deshalb möchte ich versuchen, den Verbesserungsvorschlag von letzem Mal noch einmal mir vorzunehmen und besser zu schaffen. Ich habe immernoch Mühe, dass ich zu schnell aufgebe und nicht dran bleibe bei Fehler. Auch sollte ich wohl ein wenig mehr fragen, wenn ich etwas nicht verstehe. Zudem habe ich ein wenig Mühe, lange zuzuhören wenn Code erklärt wird und verliere dann den Anschluss. Ich denke, es wäre besser für mich, die Aufträge zuerst selbstständig lösen zu versuchen und dann konkrete Fragen zu stellen, anstatt einfach der Erklärung wie es gemacht wird zuzuhören. Dies möchte ich auch noch in mein Arbeitsverhalten einbauen.
