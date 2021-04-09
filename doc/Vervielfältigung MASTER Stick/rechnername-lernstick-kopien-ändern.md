# Rechnername auf Lernstick-Kopien ändern

Der Rechnername ist von der Live-DVD mit 'debian' in /etc/hostname und /etc/hosts festgelegt.

Damit sich die Rechner im lokalen Lernstick-Netzwerk unterscheiden, sollte man als Rechnername den
USERNAME des Stickbesitzers verwenden.

In einem Terminal eingeben:
```bash
user@debian:~$ pkexec nano /etc/hostname
```

Dort die Zeichenkette 'debian' durch 'USERNAME' ersetzen → Speichern → nano verlassen

Und das gleiche Spiel noch einmal mit:
```bash
user@debian:~$ pkexec nano /etc/hosts
```
Dort die Zeichenkette 'debian' überall durch 'USERNAME' ersetzen → Speichern → nano verlassen.
