# WLAN Passwort nicht in der grafischen Oberfläche anzeigen

Diese Anleitung beschreibt, wie man WLAN Verbindungen einrichten kann, bei denen dem Benutzer nicht das Passwort angezeigt wird. 

WARNUNG: Alle bis jetzt erstellten Verbindungen können nach Einrichtung dieser Anleitung nicht mehr über die grafische Oberfläche bearbeitet werden.

1. Terminal öffnen
2. `sudo -i` eingeben
3. folgendes kopieren und einfügen.

```bash
cat << EOF > /etc/polkit-1/localauthority/50-local.d/51-wiki-lernstick.pkla
[WLAN]
Identity=unix-user:user
Action=org.freedesktop.NetworkManager.settings.modify.system
ResultAny=no
ResultInactive=no
ResultActive=no
EOF
```
4. systemctl restart polkit.service
5. Terminal schließen
6. Nun das WLAN normal einrichten
7. Neues Terminal öffnen
8. `sudo -i` eingeben
9. `gedit /etc/NetworkManager/system-connections/WLANNAME` eingeben (den Teil WLANNAME durch den Namen des WLANs ersetzen).
10. Alles was hinter permissions= steht löschen
11. Speichern
12. Lernstick neustarten

Nun sollte das Passwort für das eingerichtete WLAN nicht mehr erscheinen.
