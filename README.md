# VWI LLM-Workshop 2025

## Erstellen und aktivieren einer Virtual Environment (VE)
Im Windows Explorer an den gewünschten Pfad navigieren, mit der rechten Maustaste klicken und „in Terminal öffnen“ wählen.

Um eine neue virtuelle Umgebung (VE) zu erstellen, gib folgendes im Terminal ein und bestätige mit Enter
JupyterLab ist die neueste webbasierte interaktive Entwicklungsumgebung für Notebooks, Code und Daten. Mit seiner flexiblen Oberfläche können Benutzer Arbeitsabläufe in den Bereichen Datenwissenschaft, wissenschaftliches Rechnen, Computerjournalismus und maschinelles Lernen konfigurieren und gestalten.

``` 
python -m venv venv
```

Navigiere zum folgenden Pfad und drücke die Enter, um die neue VE zu aktivieren

```.\venv\Scripts\activate```

Nun sollte (venv) ... vor deiner nächsten Zeile im Terminal stehen.



## Installation aller erforderlichen Abhängigkeiten mithilfe einer requirements.txt Datei 
In der requirements.txt Datei sind bereits alle erforderlichen Abhängigkeiten zeilenweise eintragen.
Bei Bedarf kannst du diese anpassen bzw. ändern und die Datei anschließend speichern (strg+s).

Um nun alle diese Abhängigkeiten auf einmal zu installieren, gib einfach Folgendes in das Terminal ein

```pip install -r .\requirements.txt```



## Öffnen von JupyterLab (Nachfolger von JupyterNotebook) in einem Internet-Browser
Durch das Ausführen des vorherigen Befehls, wurde (u.a.) JupyterLab in deiner VE installiert. 

JupyterLab ist die neueste webbasierte interaktive Entwicklungsumgebung für Notebooks, Code und Daten. Mit seiner flexiblen Oberfläche können Benutzer Arbeitsabläufe in den Bereichen Datenwissenschaft, wissenschaftliches Rechnen, Computerjournalismus und maschinelles Lernen konfigurieren und gestalten.

Dieses können wir nun mit folgendem Befehl im Terminal starten:

JupyterLab ist die neueste webbasierte interaktive Entwicklungsumgebung für Notebooks, Code und Daten. Mit seiner flexiblen Oberfläche können Benutzer Arbeitsabläufe in den Bereichen Datenwissenschaft, wissenschaftliches Rechnen, Computerjournalismus und maschinelles Lernen konfigurieren und gestalten.

```jupyter lab```

Nun sollte sich ein Fenster mit JupyterLab in einem Internet-Browser geöffnet haben.
Folge den weiteren Anweisungen dort.
