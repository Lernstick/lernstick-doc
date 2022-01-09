# Image auf Stick flashen

Die einfachste Art das Lernstick-ISO auf einen USB-Stick zu bespielen, ist einen sogenannten ISO-Stick über die Anwendung [Etcher](https://www.balena.io/etcher/) zu erstellen.

Laden Sie die Software herunter und installieren Sie diese. Wenn Sie die Anwendung öffnen, präsentiert sich Ihnen folgendes Fenster:

![](../../assets/balena-etcher-main.png "Balena Etcher Main")

## Schritt 1: Auswählen des Image

Klicken Sie auf _Flash form file_ und wählen Sie im Explorer das heruntergeladene Lernstick ISO-File aus.

![](../../assets/balena-etcher-step-one.png "Balena Etcher Step 1")

## Schritt 2: Auswählen des Speichermediums

Klicken Sie auf _Select target_ und wählen Sie im Explorer den gewünschten USB-Stick aus und bestätigen Sie ihre Auswahl.

![](../../assets/balena-etcher-step-two.png "Balena Etcher Step 2")

## Schritt 3: Flashen des Sticks

Klicken Sie nun auf _Flash_ um den Prozess zu starten. Falls Windows Sie um Berechtigung fragt, müssen Sie diese freigeben.

![](../../assets/balena-etcher-pre-flash.png "pre flash")

![](../../assets/balena-etcher-flash.png "flash")

Sobald der Prozess abgeschlossen ist, wird Windows Sie auffordern den USB-Stick zu formatieren, da dieser nun nicht mehr als verwendbar anerkannt wird. Klicken Sie auf _Abbrechen_.

![](../../assets/datentraeger-formatieren-flash.png "formatieren")

Beachten Sie bitte, dass ein so erstellter Stick nur so etwas wie eine _virtuelle DVD_ ist, also nicht die üblichen Partitionen enthält und nicht weiter beschrieben werden kann. Sie können diesen ISO-Stick jedoch booten und die dann automatisch startende Speichermedienverwaltung verwenden, um "richtige" Lernsticks mit beschreibbarer Datenpartition zu erstellen.
