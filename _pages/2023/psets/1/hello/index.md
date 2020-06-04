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

Rufe im Browser deiner Wahl (am besten Firefox, Safari oder Chrome) (ide.cs50.io)[https://ide.cs50.io] auf und melde dich via GitHub an. Standartmäßig ist die IDE so eingestellt, dass du links deine Dateien siehst, rechts oben deinen Texteditor zum Bearbeiten deiner Dateien hast, und unten rechts ein Konsolenfenster, womit du Befehle ausführen kannst.

### Ordner

Mit einem Klick in die Konsole kannst du nun damit beginnen deinen Arbeitsplatz einzurichten. Zuerst sieht die Konsole so aus:

``` ~/ $```

Hier kannst du nun deinen ersten Befehl eingeben:

``` mkdir ~/_ifgk ```

Mit einem Enter schickst du den Befehl ab, und sollte alles funktionieren, kannst du sehen, dass links ein neuer Ordner mit dem Namen "\_ifgk" in deinem Dateibrowser erschienen ist. ```mkdir``` ist der Konsolenbefehl zum Erstellen eines neuen Ordners ("make directory"), und mit ```~/_ifgk``` gibst du an, wo der Ordner erstellt werden soll (in diesem Fall im Order ```~```) und wie der Ordner heißen soll (in diesem Fall ```_ifgk```). Der Unterstrich bedeutet nur, dass das Verzeichnis im Dateibrowser ganz oben erscheint und hat sonst keine Bedeutung, es ist aber ein ganz normaler Bestandteil des Namens, wie jeder andere Buchstabe auch.

Einen Befehl mit der Konsole (auch Terminal oder Kommandozeile genannt) auszuführen heißt, ihn einzutippen und Enter zu drücken. Alle Befehle sind "case-sensitive", sie unterscheiden also zwischen Groß- und Kleinschreibung!

Als nächstes kannst du

```cd ~/_ifgk```

ausführen, um mit der Konsole in deinen neuen Ordner zu wechseln ("change directory"). Wo du dich befindets, kannst du immer vor dem $-Zeichen in der Konsole sehen, welche jetzt so aussehen sollte:

```~/_ifgk/ $```

Falls nicht, lies dir alles nochmal durch und probiere es noch einmal!

Erstelle jetzt einen Order für deine ersten Hausaufgaben mit dem Befehl

```mkdir ~/_ifgk/pset1```,

wechsle in den Ordner (```cd ~/_ifgk/pset1```), und erstelle direkt noch einen Ordner für deine erste Unteraufgabe mit dem Befehl

```mkdir ~/_ifgk/pset1/hello```

Eine durchdachte Ordnerstruktur ist wichtig, um später, wenn du einmal viele Dateien hast, den Überblick zu behalten. Wechsle jetzt noch in den Ordner (na, weißt du noch, wie das geht? Wenn nicht, dann lies oben noch mal nach!), welchen du gerade erstellt hast, und dann kann es auch schon losgehen!

### Programme schreiben

Bist du bereit, dein erstes Programm innerhalb der IDE zu schreiben? Dann klicke oben auf _File_, dann auf _New File_, und speichere die Datei direkt (mit der Option _Speichern_ im Menü _File_) als hello.py innerhalb des Ordners ```~/pset1/hello```. Jetzt kannst du im Editor folgendes eintippen:

```print("hello, world!")```

Die IDE versucht dir zu helfen, indem sie den Text automatisch einfärbt - so wird es für dich einfacher, zwischen Verschiedenen Schlüsselwörtern und anderen Bausteinen eines Programms zu differenzieren. Diese Farben nenntn man "syntax highlighting". Die IDE färbt den Code basierend auf die Dateiendung (in diesem Fall .py für eine Python Datei), es ist also wichtig, dass du deine Dateien immer direkt mit der richtigen Endung speicherst!

### Programme ausführen

Wenn du dich an die Einführung zu Programmiersprachen erinnerst, dann weißt du bestimmt, das es höhere und tiefere Programmiersprachen gibt. Die tieferen werden meistens kompiliert (z.B. C), die höheren interpretiert (z.B. Python). Um dein interpretiertes Programm auszuführen reicht es aus, im Terminal den Interpreter und das auszuführende Programm zu benennen, wie folgt:

```python hello.py```

Hello, world!

## Aufgabenstellung
Unser Programm kann einen Nutzer jetzt schon problemlos begrüßen, aber es wäre doch schön, wenn es etwas persönlicher wäre. Lass uns das Programm so verändern, dass es den Nutzer erst nach seinem Namen fragt, und dann ```hello, so-und-so``` ausgibt, wobei ```so-und-so``` natürlich der vorher abgefragte Name seien sollte.

Für dieses Beispiel solltest du davon ausgehen, dass der Nutzer kooperiert, und stets einen validen Namen an das Programm weitergibt. Das wird aber nicht immer so sein, und ein guter Programmierer bereitet sein Programm auf alle Möglichkeiten vor!

Bevor du dein Programm abgibst solltest du es vorher mit ein paar Beispielnamen auf funktionstüchtigkeit prüfen!

### Walktrough

(Wird noch hinzugefügt)

### Tipps

#### Kannst du dich nicht mehr erinnern, wie man den Anwender eines Programmes um eine Eingabe bittet?
Du kannst die Python Funktion ```input``` wie folgt verwenden, und dabei die Eingabe des Nutzers (den Returnwert der Funktion) als eine Variable abspeichern.

```python name = input("Wie lautet dein Name? ")```

#### Kannst du dich nicht erinnern, wie man eine Variable ausgibt?
Du kannst die Python Funktion ```print``` benutzen, um Texte wie folgt zu *printen*:

```print("Ich bin das Schwert, ich bin die Flamme")```

In den Klammern befindet sich das sogenannte Argument der Funktion, nämlich ein *String*, in welchem unser Text steht. Du kannst auch mehrere Argumente, z.B. Variablen und/oder Strings, verbinden, indem du beide in der Klammer aufführst und mit einem Plus verbindest:

```print("Ich bin das Schwert, " + "ich bin die Flamme")```

Beachte aber, dass das Plus nicht automatisch ein Leerzeichen erzeugt, das musst du schon selbst hinzufügen!

### Code testen

Nachdem du dein Programm selber getestet hast, kannst du auch unsere Tests automatisch ausführen lassen:

```check50 ifgk/problems/2023/hello```

Um zu überprüfen ob dein Programm rein optisch gut ist, führe folgenden Befehl aus:
```style50 hello.py```

## Abgabe

Führe, unter Verwendung deiner GitHub Anmeldedaten, sollten diese gefordert werden, den nachfolgenden Befehl aus. Aus sicherheitstechnischen Gründen wirst du anstelle deines Passworts nur Sterne (```*```) sehen.
```submit50 ifgk/problems/2023/hello```
