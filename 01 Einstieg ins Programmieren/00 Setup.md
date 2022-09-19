# Setup

## 01 Command Line Intro

### Start

Bevor wir loslegen, müssen wir die Commandline kennenlernen. Sie ist so etwas wie unsere Hauptsteuerungszentrum und unsere neue Maus. Von hier aus starten wir Programme, auch unsere eigenen, wir halten unsere Software uptodate und installieren neue Software.

In dieser Erklärung braucht ihr [] nicht anzuschrieben. Also ```cd [dirname]```
bedeutet, dass ihr einfach ```cd dirname```schreibt.

### Wir sind faul

* ↑ und ↓ scrollen uns zu alten Eingaben. Sehr nützlich.
* Mit ```Tab``` können Sachen autocompleted werden. Probiert es aus.
* Auf einem Mac könnte ihr auch mit Drag und Drop arbeiten, um Files und Folders hin und her zu bewegen.

### Navigation

* ```pwd```: prints working directory — zeigt uns an, wo wir uns gerade befinden.
* ```cd [dirname]```: changes directory, bewegt uns ins jeweilige Directory.
* ``cd ..``: Bewegt uns eine Stuff rauf.
* ``ls``: zeigt alle subdirectories an. ``ls -lah`` zeigt uns alles an.
* ```locate [filename]```: versucht Files zu finden. Wenn es etwas nicht findet, bedeutet es nicht, das es auf dem Gerät nicht ist.
* ```find```: Dauert länger als locate, findet aber alles.

* ```mv [source] [destination]``` bewegt eine Datei von A nach B
* ```cp [source] [destination]``` kopiert eine Datei an einen anderen Ort, nun habt ihr also zwei identische Kopien derselben Datei.
* ```rm [file] deletes``` zerstört eine Datei, ihr findet sie auch nicht mehr im Papierkorb
* ```mkdir [directoryname]``` Baut ein neues Verzeichnis
* ```rmdir [directoryname]``` löscht ein Verzeichnis mit dem kompletten Inhalt
* ```tar cvf [filename] [filename] [filename]...``` komprimiert eine Datei .tar.gz
* ```tar xvf [filename]``` extrahiert eine Datei .tar.gz file

### Individuelle Files

* ```cat [filename]```: displays the contents of a file
* ```wc [filename]```: displays the word count of a file
* ```wc -l [filename]```: displays the line count of a file
* ```head -n 10 [filename]```: displays the first 10 lines of a file
* ```tail -n 20 [filename]```: displays the last 20 lines of a file
* ```more [filename]```: displays the contents of a file one screen at a time (spacebar to continue)
* ```grep [text] [filename]```: show all of the lines in filename that contain text.
* ```sort```: sorts the lines of a file
* ```uniq```: removes duplicate adjacent lines of a file

* Und **wichtig**: Mit diesem wunderbaren Zeichen kann man Befehle kombinieren: ```|```

### Lustiges

* ```banner```
* ```cowsay```
* ```say```

### Abspeichern und Kombinieren

* ```grep xyz 'file' > output.txt```
* ```grep -E 'MyVariable = False|MyVariable = True' FormA.frm```

### Escaping commands

Has something gone wrong? Taking too long? Hold down Control and hit C, a.k.a. Ctrl+C.

### Mehr zu den einzelnen Befehlen lernen

* ```man``` pages are manuals that you can use from the command line.

* ```man grep``` would give you the entry for grep, and then you’d use the d and u to navigate up and down. You should probably just googlegrep man page or grep examples, though.

## 02 Installs

Hier installieren wir Zusatzprogramme und bereiten den Computer darauf vor, dass er in Zukunft einfacher Zusatzpakete installieren kann. Den Terminal öffnen und mit folgenden Befehlen die Software installieren. Manchmal dauern die Installs etwas lange. Geduld. Es funktioniert alles richtig. Und all das müssen wir nur einmal machen. Nicht mehr, aber auch nicht weniger.

- **Pip3** ist das gängigste Install-Modul, aber wird werden das etwas populärere conda benutzen weil es am besten bei windows und mac funktioniert. 

### Install-Programme und Python3

1. Geht auf https://www.anaconda.com/products/distribution und ladet euch das programm runter
2. Führt es aus und ihr solltet schon in der Lage sein Code auf eurem Rechner auszuführen. 

### Github

- Geht auf https://github.com/ und macht euch dort einen kostenlosen Account. 
- Geht auf https://desktop.github.com/ und ladet euch das Programm runter. 