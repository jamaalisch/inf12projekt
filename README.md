## Schönen guten Tag Herr Stier,
Unsere erste Idee von einem CAS auf einem Raspberry Pi Zero wurde bedauerlicherweise verworfen, da dieser einfach nicht die nötige Leistung für eine geeignetes GUI bieten konnte. Als CLI-Anwendung hat dieses wundervoll funktioniert.
Aufgrund dieser Probleme, können Sie dieses Projekt von uns auffinden, welches wir zur Bewertung einreichen. Zudem hängen wir noch das Websitenprojekt aus dem letzen Jahr an, da wir der Auffassung waren, dies ist uns außerordentlich gut gelungen. 

https://github.com/jamaalisch/websitegruppenarbeit.git 

Da wir zu viel Langeweile hatten, haben wir 2 Versionen des Spiels erstellt, da wir keine Lust hatte, beide Versionen zusammenzufassen. Sie benötigen nach unserem Wissenstands keine weiteren Dinge, um die normale Version (ezmode) zu spielen. Um den Hardmode zu spielen, benötigen Sie allerdings das Paket "zufallsworte", welches Sie mit "pip install zufallsworte" installieren können. Falls Sie darauf bestehen, dass wir beide Programme zusammenführen soll, werden wir dies selbstverständlich tun, doch bitte sehen Sie davon ab, da wir stark abgeneigt sind, dies zu tun.

Jetzt zu den Spielen.

ezmode:
Spieler: >= 2
Ein Spieler gibt nach Programmstart ein Wort ein, welches verdeckt wird, damit die anderen Spieler dieses nicht sehen. Dann bekommt der andere Spieler gesagt, wie viele Buchstaben das Wort hat. Dieser Spieler muss nun das Wort korrekt erraten, indem er immer einen Buchstaben eingibt. Falls dieser Buchstabe nicht im Wort vorhanden ist, wird ein Versuch abgezogen. Es wird ebenfalls ein Versuch abgezogen, wenn der Spieler einen Buchstaben errät, der davor schon geraten wurde. Wenn der Spieler keine Versuche mehr übrig hat, wird das Programm beendet und das Wort ausgegeben.

hardmode:
Spieler: >= 1
Der Spieler spielt gegen das Programm. Es wird zufällig ein Wort mit der Länge 6-28 Buchstaben ausgewählt. Der Spieler weiß nur, wie lang das Wort ist. Er bekommt alle abgezogen, wenn er ein Buchstaben doppelt rät. Sonst ist alles identisch.

Bei Fragen können Sie mich (Cedric) auf itsLearning erreichen.
VG Cedric
