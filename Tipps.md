# Posten 1: Versteckte Datei finden

- Tipp 1: Überprüft sorgfältig alle Ordner und Dateinamen. Manchmal sind die Dinge nicht sofort sichtbar.
- Tipp 2: Denkt daran, dass versteckte Dateien oft im System verborgen sind. Könnte die Einstellung „Versteckte Dateien anzeigen“ helfen?
- Tipp 3: Nutzt die Dateisuche, wenn ihr Schwierigkeiten habt. Achtet besonders auf ungewöhnliche Dateiendungen oder Namen.

# Posten 2: USB-Falle umgehen

- Tipp 1: Nicht alle USB-Sticks sind vertrauenswürdig. Denkt darüber nach, welche Anzeichen euch den richtigen Stick verraten könnten.
- Tipp 2: Ein schneller Fund ist oft verdächtig. Schaut genau hin und überlegt, welcher Stick versteckt oder schwerer zu finden ist.
- Tipp 3: Wenn ihr einen Fehler macht, kann euch das Hinweise darauf geben, was der Hacker wirklich geplant hat. Achtet auf die ausgelösten Nachrichten und nehmt sie als Lektion mit.

# Posten 3: Steganografie entschlüsseln

- Tipp 1: Achtet auf die Reihenfolge des Befehls. Die Blöcke sind durcheinander und müssen korrekt sortiert werden, um das Bild zu entschlüsseln.
- Tipp 2: Das Bild wurde als E-Mail vom IT-Team geschickt und ist auf dem „USB-Stick“ gespeichert. Vielleicht wurde dort auch etwas hinzugefügt.
- Tipp 3: Nicht jedes Passwort wird funktionieren. Probiert die Passwörter der Liste nacheinander aus, um die Nachricht im Bild zu entschlüsseln.

# Posten 4: Hashtyp bestimmen

- Tipp 1: Fangt mit hash-identifier im Terminal an, um den Hashtyp zu ermitteln. Kopiert dann den Hash aus dem zweiten Posten und fügt ihn ein.
- Tipp 2: Öffnet danach ein neues Terminalfenster und nutzt hashid (Hash aus 2. Posten) -m, um den „Hashcat“-Wert herauszufinden.
- Tipp 3: Merkt euch den „-m“-Wert gut. Er ist für die endgültige Entschlüsselung im nächsten Schritt entscheidend.

# Posten 5: Hash knacken und Passwort finden

- Tipp 1: Nutzt den „-m“-Wert aus dem vorherigen Schritt, um den Hashcat-Befehl korrekt auszuführen.
- Tipp 2: Gebt den Befehl vollständig ein und wiederholt ihn danach mit --show, um das Passwort anzuzeigen.
- Tipp 3: Schaut genau hin, ob der Befehl und der kopierte Hash korrekt sind. Kleine Fehler können zu falschen Ergebnissen führen.
