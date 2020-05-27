---
title:     if gk 2023 - Hello
permalink: /2023/psets/1/hello
layout:    page
---

# Hello

## Los geht's

Bei der CS50 IDE handelt es sich um eine sogenannte integrierte Entwicklungsumgebung, auf Englisch "integrated development environment" (kurz IDE).
Das bedeutet, einfach gesagt, dass du alle Werkzeuge und Programme, welche du zum Programmieren benötigst, auf einer einzelnen Website benutzen kannst.
Der Vorteil ist, dass du von jedem PC darauf zugreifen kannst, und das, ohne etwas installieren zu müssen.
Wenn du dich mit deinem GitHub Account angemeldet hast, kannst du hier in deinem Workspace (einem für dich reservierten, virtuellen Speicherplatz) deine Programme, Dateien und Ordner (auch Directories gennant) speichern.

### Anmelden

### Übersicht

### Ordner und Dateien erstellen

### Ordner und Dateien auflisten

### Programme schreiben und ausführen

## Aufgabenstellung
Unser Programm kann einen Nutzer jetzt schon problemlos begrüßen, aber es wäre doch schön, wenn es etwas persönlicher wäre. Lass uns das Programm so verändern, dass es den Nutzer erst nach seinem Namen fragt, und dann ```hello, so-und-so``` ausgibt, wobei ```so-und-so``` natürlich der vorher abgefragte Name seien sollte.

Für dieses Beispiel solltest du davon ausgehen, dass der Nutzer kooperiert, und stets einen validen Namen an das Programm weitergibt. Das wird aber nicht immer so sein, und ein guter Programmierer bereitet sein Programm auf alle Möglichkeiten vor!

Bevor du dein Programm abgibst solltest du es vorher mit ein paar Beispielnamen auf funktionstüchtigkeit prüfen!

### Walktrough

### Tipps

#### Kannst du dich nicht mehr erinnern, wie man den Anwender eines Programmes um eine Eingabe bittet?
Du kannst die Python Funktion ```input``` wie folgt verwenden, und dabei die Eingabe des Nutzers (den Returnwert der Funktion) als eine Variable abspeichern.

```python name = input("Wie lautet dein Name? ")```

#### Kannst du dich nicht erinnern, wie man eine Variable ausgibt?
Du kannst die Python Funktion ```print``` benutzen, um Texte wie folgt zu *printen*:

```print("Da steh ich nun, ich armer Tor! Und bin so klug als wie zuvor;")```

In den Klammern befindet sich das sogenannte Argument der Funktion, nämlich ein *String*, in welchem unser Text steht. Du kannst auch mehrere Argumente, z.B. Variablen und/oder Strings, verbinden, indem du beide in der Klammer aufführst und mit einem Plus verbindest:

```print("Ich bin das Schwert, " + "ich bin die Flamme")```

Beachte aber, dass das Plus nicht automatisch ein Leerzeichen erzeugt, das musst du schon selbst hinzufügen!

### Code testen

## Abgabe

Führe, unter Verwendung deiner GitHub Anmeldedaten, sollten diese gefordert werden, den nachfolgenden Befehl aus. Aus sicherheitstechnischen Gründen wirst du anstelle deines Passworts nur Sterne (```*```) sehen.
```submit50 ifgk/problems/2023/hello```
