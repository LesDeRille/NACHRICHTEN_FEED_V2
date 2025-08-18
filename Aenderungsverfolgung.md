## Änderungshistorie

#
### tagesschau_2025_08_18_V03

#### Basis: tagesschau_2025_08_18_V02

#### Änderung:
* blacklist wird beim Programmstart von localStorage gelesen

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_18_V02

#### Basis: tagesschau_2025_08_18_V01

#### Änderung:
* Auch Blacklist wird unter 'datenNachrichtenFeed' in localStorage abgelegt
* alle bisherigen Aufrufe von localStorage.setItem rausgenommen

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_18_V01

#### Basis: tagesschau_2025_08_16_V01

#### Änderung:
* Alternative Speicherung in localStorage unter einem eindeutigen Oberbegriff pro Programm eingeführt. Bis jetzt nur für Ressortaufrufe

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_16_V01

#### Basis: tagesschau_2025_08_15_V01

#### Änderung:
* try/catch bei 'letzte Aufrufe' nach weiter oben verschoben. Da gehört es thematisch hin
* 'knopf' in 'ressortButton' umgetauft

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_15_V01

#### Basis: tagesschau_2025_08_14_V04

#### Änderung:
* nicht mehr nachvollziehbar, es wird auch kein Unterschied zu vorher angezeigt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_14_V04

#### Basis: tagesschau_2025_08_14_V03

#### Änderung:
* Tag kann aus Blacklist gelöscht werden

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY
* Handling prüfen. Manchmal wechselt er des Ressort, wenn man die Tags ändert


#
### tagesschau_2025_08_14_V03

#### Basis: tagesschau_2025_08_14_V02

#### Änderung:
* Blacklist wird als Buttons angezeigt
* Der Dialog mit den Blacklist Buttons iat angelegt, es wird aber noch nichts aus der Blacklist gelöscht

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen
* Nach den Blacklist Buttons fehlt in der <h3> eine schließende Klammer
* Füge ich gleich nach dem Start der App einen Tag zur Blacklist hinzu, steht in <h3> kein Ressortname mehr
* für meldung als Button ausgeben gibt es jetzt eine function machButtonAusTag. Es steht aber auch noch einmal extra im Quelltext, das muß ich zusammenfassen wegen DRY


#
### tagesschau_2025_08_14_V02

#### Basis: tagesschau_2025_08_14_V01

#### Änderung:
* Setzt man einen Tag auf die Blacklist, kommen die Schlagzeilen wieder
* Das Ressort wird auch beim Setzen eines Tags auf die Blacklist wieder korrekt angezeigt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_14_V01

#### Basis: tagesschau_2025_08_13_V02

#### Änderung:
* Name des gewählten Ressorts wird in <h3> nicht mehr doppelt angezeigt
* Aber Fehler: Setzt man einen Tag auf die Blacklist, kommen keine Schlagzeilen mehr

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_13_V02

#### Basis: tagesschau_2025_08_13_V01

#### Änderung:
* Blacklist wird neben Ressort angezeigt, hat aber noch Fehler

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_13_V01

#### Basis: tagesschau_2025_08_12_V03

#### Änderung:
* erst mal verstehen, was bis jetzt schon drin ist.
* Kommentare rein
* unbenutzte Variable abklemmen
* neue function um mehr Übersicht zu bekommen

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_12_V03

#### Basis: tagesschau_2025_08_12_V02

#### Änderung:
* erst mal verstehen, was bis jetzt schon drin ist.
* Kommentare rein und nochmal Variable aussagekräftiger

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_12_V02

#### Basis: tagesschau_2025_08_12_V01

#### Änderung:
* erst mal verstehen, was bis jetzt schon drin ist.
* use strict eingebaut

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_12_V01

#### Basis: tagesschau_2025_08_11_V01

#### Änderung:
* erst mal verstehen, was bis jetzt schon drin ist.
* Variablennamen aussagekräftiger

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen


#
### tagesschau_2025_08_11_V01

#### Basis: tagesschau_2025_07_19_V01

#### Änderung:
* erst mal verstehen, was bis jetzt schon drin ist.
* ToDo erweitert

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann
* nutze ich überhaupt alle vorhandenen ressorts? Bis jetzt sind die fest vorgegeben. Kann ich die Ressorts dynamisch festlegen? Es könnten ja auch mal welche dazukommen

#
### tagesschau_2025_07_19_V01

#### Basis: tagesschau_2025_06_14_V01

#### Änderung:
* Noch nicht begonnen: Blacklist programmatisch änderbar machen. Muß erst mal verstehen, was bis jetzt schon drin ist

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
    * Durch Rechtsklick kommt der Tag bereits auf die Blacklist, Blacklist wird aber noch nicht aktualisiert und gespeichert
    * Klicken auf einen Tag der Blacklist entfernt der Tag von der Blacklist
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* localStorage exportieren, damit ich es auf dem iPad oder einem anderen Browser einlesen kann


#
### tagesschau_2025_06_14_V01

#### Basis: tagesschau_2025_05_15_V02

#### Änderung:
* Blacklist um Israel, Basketball, Eishokey, Ukraine erweitert

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?


#
### tagesschau_2025_05_15_V02

#### Basis: tagesschau_2025_05_15_V01

#### Änderung:
* tagesschau.json wird nach dem Setzen eines tags auf die Blacklist neu gelesen und Schlagzeilen  unter Berücksichtigung der Blacklist neu aufgebaut

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_15_V01

#### Basis: tagesschau_2025_05_14_V03

#### Änderung:
* unerwünschter tag kann mit rechter Maustaste angeklickt und auf Blacklist gesetzt werden. Sonst passiert aber noch nichts mit der neuen Blacklist

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
    * Geht, der Neuaufbau der Seite unter Berücksichtigung der neuen Blacklist fehlt noch
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_14_V03

#### Basis: tagesschau_2025_05_14_V02

#### Änderung:
* ressorts ausgelagert, einige Varable umgenannt und Kommentare reduziert

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_14_V02

#### Basis: tagesschau_2025_05_14_V01

#### Änderung:
* Programm läuft auch wenn localStorage leer ist, oder von Safari nicht gelesen werden kann

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_14_V01

#### Basis: tagesschau_2025_05_13_V04

#### Änderung:
* Programm läuft auch im privaten Modus. Dann gibt es halt keine Markierung für bereits eingeblendete Schlagzeilen

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* Wenn localStorage nichts enthält, muß das Programm trotzdem laufen. Und natürlich localStorage befüllt werden (im normalen Modus)

#
### tagesschau_2025_05_13_V04

#### Basis: tagesschau_2025_05_13_V03

#### Änderung:
* localStorage war unerwartet leer, dann ging nichts mehr. Bastelhaft wieder aufgefüllt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?
* Es muß eine Abfrage rein, ob der private Modus benutzt wird. Dann geht ja localStorage nicht
    * Nach der Abfrage muß notfalls ein Programmabbruch rein. Absturz ist schlecht
* Wenn localStorage nichts enthält, muß das Programm trotzdem laufen

#
### tagesschau_2025_05_13_V03

#### Basis: tagesschau_2025_05_13_V02

#### Änderung:
* Fehler beim Ermitteln des Datums des letzten Ressoraufrufs behoben

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_13_V02 - Schein eher die V1 zu sein. Habe evt. im falschen Datum meine Änderungen eingetragen

#### Basis: tagesschau_2025_05_13_V01

#### Änderung:
* Die Tags kommen jetzt als Buttons

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags sollen  per rechtem Mausklick und Kontextmenü zur Blacklist hinzugefügt werden können. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_13_V01 - Scheint eher die V2 zu sein. Habe evt. im falschen Datum meine Änderungen eingetragen

#### Basis: tagesschau_2025_05_12_V02

#### Änderung:
* Die Schlagzeilen werden ab dem Zeitpunkt des letzten Aufrufs eingefärbt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
    * Ressorts ausslesen und dann die entsprechenden Knöpfe erzeugen --> Ressort steht nicht im json, geht also nicht
* Tags anzeigen, evt Blacklist davon erstellen. Statt tags Symbole, z.B. Nationalflaggen?
* Refresh-Knopf (oder einfach neu laden?)
* Blacklist in localStorage
* Die tags als Buttons, damit man sie per rechtem Mausklick und Kontextmenü zur Blacklist hinzufügen kann. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_12_V02

#### Basis: tagesschau_2025_05_12_V01

#### Änderung:
* Die Schlagzeilen werden ab einer Grenze nach Datum eingefärbt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
    * Ressorts ausslesen und dann die entsprechenden Knöpfe erzeugen --> Ressort steht nicht im json, geht also nicht
* Tags anzeigen, evt Blacklist davon erstellen. Statt tags Symbole, z.B. Nationalflaggen?
* Refresh-Knopf (oder einfach neu laden?)
* Die Zeit jeder Ressortauswahl in localStorage speichern. Beim nächsten Aufruf die neueren mit anderem Hintergrund anzeigen
* Blacklist in localStorage
* Die tags als Buttons, damit man sie per rechtem Mausklick und Kontextmenü zur Blacklist hinzufügen kann. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen
* Grenze beim Datum fürs Einfärben der Schlagzeilen besser machen. Geht auch die ganze Meldung einzufärben? Jetzt, wo ich es verstanden habe?

#
### tagesschau_2025_05_12_V01

#### Basis: tagesschau_2025_05_11_V02

#### Änderung:
* Die tags werden verarbeitet
    * tags stehen hinter dem Datum der Schlagzeile
    * Meldungen mit tags der Blacklist werden nicht mehr angezeigt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
    * Ressorts ausslesen und dann die entsprechenden Knöpfe erzeugen --> Ressort steht nicht im json, geht also nicht
* Tags anzeigen, evt Blacklist davon erstellen. Statt tags Symbole, z.B. Nationalflaggen?
* Refresh-Knopf (oder einfach neu laden?)
* Die Zeit jeder Ressortauswahl in localStorage speichern. Beim nächsten Aufruf die neueren mit anderem Hintergrund anzeigen
* Blacklist in localStorage
* Die tags als Buttons, damit man sie per rechtem Mausklick und Kontextmenü zur Blacklist hinzufügen kann. 
* Blacklist - Inhalte irgendwo anzeigen, eigener Knopf z.B., damit man sie nicht ständig anschauen muß
* Blacklist programmatisch änderbar machen

#
### tagesschau_2025_05_11_V02

#### Basis: tagesschau_2025_05_11_V01

#### Änderung:
* Erster Buchstabe auf den Ressortknöpfen groß geschrieben
* Datum nicht mehr Teil des Links
* Schlagzeilen größer
* Statt Leerzeilen zwischen den Schlagzeilen kommt jetzt ein horizontaler Strich

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
    * Ressorts ausslesen und dann die entsprechenden Knöpfe erzeugen --> Ressort steht nicht im json, geht also nicht
* Tags anzeigen, evt Blacklist davon erstellen. Statt tags Symbole, z.B. Nationalflaggen?
* Refresh-Knopf (oder einfach neu laden?)
* 

#
### tagesschau_2025_05_11_V01

#### Basis: tagesschau_2025_05_10_V06

#### Änderung:
* Knöpfe werden jetzt generiert

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
    * Ressorts ausslesen und dann die entsprechenden Knöpfe erzeugen
* Tags anzeigen, evt Blacklist davon erstellen
* Refresh-Knopf (oder einfach neu laden?)

#
### tagesschau_2025_05_10_V06

#### Basis: tagesschau_2025_05_10_V05

#### Änderung:
* button statt input mit type button dazu, einfacher und funktioniert

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
* Rossortauswahl ist nicht schön programmiert
* Tags anzeigen, evt Blacklist davon erstellen
* Refresh-Knopf (oder einfach neu laden?)

#
### tagesschau_2025_05_10_V05

#### Basis: tagesschau_2025_05_10_V04

#### Änderung:
* Ressort wird unter dem Titel angezeigt

#### ToDo:
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?
* Ressortanzeige ist nicht schön programmiert
* Rossortauswahl ist nicht schön programmiert

#
### tagesschau_2025_05_10_V04

#### Basis: tagesschau_2025_05_10_V03

#### Änderung:
* Datum hinter der Schlagzeile eingefügt
* Style der anchors spezifiziert

#### ToDo:
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?

#
### tagesschau_2025_05_10_V03

#### Basis: tagesschau_2025_05_10_V02

#### Änderung:
* Beim Start wird das Ressort "Sport" angezeigt
* Schlagzeilen werden nach Datum absteigend sortiert

#### ToDo:
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?

#
### tagesschau_2025_05_10_V02

#### Basis: tagesschau_2025_05_10_V01

#### Änderung:
* Alle Ressorts vorhanden

#### ToDo:
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?

#
### tagesschau_2025_05_10_V01

#### Basis: tagesschau_2025_05_09_V03

#### Änderung:
* Jetzt werden die Schlagzeilen erst mal gelöscht, wenn man auf einen Ressort-Button klickt

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?

#
### tagesschau_2025_05_09_V03

#### Basis: tagesschau_2025_05_09_V02

#### Änderung:
* Ressortauswahl klappt, halbwegs, das gewählte Ressort wird aber hinten an die bestehenden Schlagzeilen angehängt. Ich schaffe es nicht, die bestehenden Schlagzeilen erst zu löschen. Nach Neuladen geht es

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren
* wäre es nicht besser, erst alles runterzuladen und dann nach dem Ressort zu filtern?

#
### tagesschau_2025_05_09_V02

#### Basis: tagesschau_2025_05_09_V01

#### Änderung:
* Angefangen mit der Resoortauswahl. Klappt aber noch nicht für alle Knöpfe

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren

#
### tagesschau_2025_05_09_V01

#### Basis: tagesschau_2025_05_08_V03

#### Änderung:
* Meldungen werden angezeigt, bisher aber nur Ausland
* Meldung kann angeklickt werden

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* nach Datum sortieren
* gelesene markieren

#
### tagesschau_2025_05_08_V03

#### Basis: tagesschau_2025_05_08_V02

#### Änderung:
* Denkfehler repariert, eine async function weniger

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* Meldung anklickbar machen
* firstSentence nur bei mouseOver?
* nach Datum sortieren
* gelesene markieren

#
### tagesschau_2025_05_08_V02

#### Basis: tagesschau_2025_05_08_V01

#### Änderung:
* tags werden angezeigt

#### ToDo:
* Ressort wählbar machen
    * inland, ausland, wirtschaft, sport, video, investigativ, wissen
* Region wählbar machen, oder ganz weglassen (https://www.tagesschau.de/api2u/news/?ressort=ausland')
    * Bundesland - 1=Baden-Württemberg, 2=Bayern, 3=Berlin, 4=Brandenburg, 5=Bremen, 6=Hamburg, 7=Hessen, 8=Mecklenburg-Vorpommern, 9=Niedersachsen, 10=Nordrhein-Westfalen, 11=Rheinland-Pfalz, 12=Saarland, 13=Sachsen, 14=Sachsen-Anhalt, 15=Schleswig-Holstein, 16=Thüringen. Mehrere Komma-getrennte Angaben möglich (z.B. regions=1,2).
* Optisch aufbereiten
* Meldung anklickbar machen
* firstSentence nur bei mouseOver?
* nach Datum sortieren
* gelesene markieren

#
### tagesschau_2025_05_08_V01

#### Basis: -

#### Änderung:
* Die Daten werden von der api eingelesen
* title und firstSentence werden angezeigt

#### ToDo:
* Ressort wählbar machen
* Optisch aufbereiten
* Meldung anklickbar machen