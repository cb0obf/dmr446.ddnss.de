# dmr446.ddnss.de

ist ein freier Server für nicht lizensierten Digitalen funkbetrieb.
Dieser wird ausschließlich Privat Betrieben und Finanziert.
Tools für ein offenes Digital Mobile Radio (DMR)-Repeaternetzwerk.

Aktuellen Zustand
Aktueller Projektstatus: Im Aufbau, funktionsfähig.

Da sich diese Software noch in einem sehr frühen Stadium befindet, benötigen Sie ein gewisses Grundverständnis für die Funktionsweise der Softwareentwicklung, um sie verwenden zu können.

Abhängigkeiten
Ich versuche, zu ausgefallene Abhängigkeiten zu vermeiden, damit die Software einfach zu erstellen, zu verwenden und zu warten ist. Sie benötigen jedoch mindestens:

C++-Compiler (g++)
pthread-Bibliothek
OpenSSL-Bibliothek (libssl) zur Hash-Berechnung für das Homebrew-Protokoll (Installation mit „apt-get update; apt-get install libssl-dev“ auf Debian/Raspbian-Systemen)
machen
Subversion oder Git machen die Aktualisierung viel einfacher
Erstellen der Software
Gehen Sie zum „src“-Verzeichnis und geben Sie „make“ ein.

Makefiles sind derzeit noch sehr rudimentär und können beim inkrementellen Erstellen fehlschlagen. Erwägen Sie im Zweifelsfall vor dem Erstellen ein „make clean“.

Es gibt derzeit keine Zweige mit stabilen Versionen. Alles befindet sich in intensiver Entwicklung und kann sich schnell ändern. Wenn die Kompilierung fehlschlägt, versuchen Sie es mit einer älteren Version.


Abhängig von Ihrer Linux-Distribution und Ihren Einstellungen müssen Sie möglicherweise den Unix-Benutzer zur Gruppe „Dialout“ (oder einer ähnlichen Gruppe) hinzufügen oder die Geräteberechtigungen ändern, um die Software als anderer Benutzer als Root auszuführen.

ACHTUNG: Für einige Funktionen der Software ist möglicherweise eine in Ihrem Land gültige Amateurfunklizenz erforderlich!

Bitte haben Sie Verständnis, dass ich bei diesem Projekt keinen Support leisten kann, da es sich lediglich um ein Hobbyprojekt in meiner Freizeit handelt.

Lizenz
Open Source lizenziert unter GPL v3, siehe „LICENSE“-Datei.

Die Software ist für Bildungszwecke  gedacht. 
