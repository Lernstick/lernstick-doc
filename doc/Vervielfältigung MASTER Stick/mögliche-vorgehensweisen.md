# Mögliche Vorgehensweise beim Vervielfältigen eines MASTER-Sticks

A) Erstellen eines auf die Bedürfnisse und Notwendigkeiten angepassten MASTER-Sticks (siehe oben).

B) Mit der dlcopy-Funktion **"Das System in ein DVD-Abbild konvertieren"** auf einem Zwischenspeicher (mindestens 32 GB) eine Lernstick.iso erzeugen und diese dann z.B. auf einen weiteren Computer kopieren.
Diese Lernstick.iso ist dann eine angepasste Variante der Original-Lernstick-ISO, aber deutlich größer (zum Brennen ist evtl. eine 8 GB DVD erforderlich). Es sind dort alle Anpassungen aus der Datenpartition in die System-Partition integriert.

C) In einer VirtualBox (siehe  Pkt. **"Einrichten des Lernsticks in VirtualBox"**) die Lernstick.iso als VM starten und dann auf an USB3 der VirtualBox angeschlossene Ziel-Lernsticks zur allgemeinen Nutzung mit der dlcopy-Funktion **"Das System auf Speichermedien installieren"** kopieren und an die Nutzer verteilen.

D) Alternativ zu Pkt. C) kann die Erstellung der Lernsticks zur allgemeinen Nutzung auch nach der ‘Standard-Methode’ mit der Option: **ISO-Abbild** der dlcopy-Funktion **“Das System auf Speichermedien installieren”** von einem gestarteten Lernstick aus gemacht werden.
Dabei ist die Lernstick.iso vom oben genannten  Zwischenspeicher zu benutzen.

E) Vorteile der Methode

a) Alle Änderungen im MASTER-Stick gelangen in die System-Partition; der Speicherplatz auf dem Ziel-Stick wird optimal ausgenutzt.

b) Mit der dlcopy-Funktion **"Speichermedien reparieren"** kann ein Stick wieder in den Ausgangszustand wie der Ursprungs-MASTER-Stick zurück versetzt werden.


