# Systemstart

Beim Einschalten eines Computers stellt die Firmware fest, von welchem Datenträger das System gestartet werden soll. 
Wenn das System vom Lernstick oder von der Lernstick-DVD starten soll, so muss dies in den meisten Fällen erst in der Firmware des Rechners eingestellt werden.

# Was ist eine Firmware?

Die Firmware ist ein Programm, welches auf der Hauptplatine in einem Speicher abgelegt ist, welcher auch ohne Stromzufuhr bestehen bleibt und ermöglicht, dass das Programm unmittelbar nach dem Einschalten des Rechners zur Verfügung steht.
Die primäre Aufgabe der Firmware ist, den Computer "zum Leben zu erwecken" und ein geeignetes Betriebssystem für den Start zu suchen. 
Leider hat jeder Hersteller seine eigene Vorstellungen davon, wie so eine Firmware auszusehen hat und welche Funktionen in der Firmware zur Verfügung stehen.

Es gibt verschiedene Firmware-Varianten. Die klassische Variante ist das [BIOS](https://de.wikipedia.org/wiki/BIOS), der Nachfolger heißt [UEFI](https://de.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface).

Als Boot-Loader verwendet der Lernstick bei einem BIOS-Boot SYSLINUX (siehe [https://de.wikipedia.org/wiki/SYSLINUX](https://de.wikipedia.org/wiki/SYSLINUX)) und für UEFI-Boots  GRUB (siehe [https://de.wikipedia.org/wiki/Grand_Unified_Bootloader](https://de.wikipedia.org/wiki/Grand_Unified_Bootloader)).

