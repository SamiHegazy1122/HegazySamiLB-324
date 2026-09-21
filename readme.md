# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.


## Pre-commit einrichten

1. `pip install pre-commit`
2. `python -m pre_commit install` 
3. `python -m pre_commit install --hook-type pre-push` 
Zuerst habe ich noch pip install pre-commit gemacht



## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

1. Azure Portal, dann Web App, dann Einstellungen und daraufhin Umgebungsvariablen
2. Neue Variable: Name = PASSWORD, Wert = <DeinPasswort>
3. Speichern (Dann App neu starten und Passwort eingeben im Login)
