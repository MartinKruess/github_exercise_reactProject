# Github Übung für das React-Projekt (~2h)

Diese Aufgabe ist eine Github auffrischung zur Vorbereitung auf die Gruppen-Projektarbeit. Eingeteilt seit ihr in der Gruppe, in der ihr auch nächste Woche am React-Projekt arbeiten werdet. Teilt die folgende Aufgabe unter euch auf und erstellt einen Plan, wie ihr vorgehen wollt. Ziel der Übung ist nicht zwangsweise eine funktionierende Seite, sondern ehr die Auffrischung eurer git und github Skills ;)

## Teilaufgabe

- Jeder von euch sollte eine Page aufbauen, in der es um euch geht. Schreibt einen kleinen Text über euch, der von einem Hobby, einer Erfahrung oder einfach ein kleiner Steckbrief eurerseits ist.
- Im src Ordner gibt es bereits eine Datei (data.jsx). Die schnelleren unter euch können gerne damit ein wenig rumspielen und ein paar Cards in weiteren Components, sowie weiteren feature Branches aufbauen.
- Jeder feature Branch sollte mindestens 2 commits haben, falls gröbere Fehler auftauchen.
Tipp: Mit der Timeline, seht ihr die commits der aktuell aktiven Datei auf eurem aktuellen branch. Dadurch kann man zu älteren Ständen der Datei zurückspringen.

Am Ende der Übung sollte jeder die selbe Version auf dem Rechner haben. Jedes funktionierende Feature sollte einzend gepushed, getestet und gepulled werden um Fehler zu vermeiden und den Arbeitsaufwand zu verringern. Welche Styling-Variante ihr verwendet ist euch überlassen.

### Hinweise

einen neuen Branch erzeugt man entweder mit:<br />
```cheackout -b``` oder mit ```switch -c```

Bevor jemand die neuen Änderungen puschen kann, sollte er den aktuellen<br />
Stand des Main-Branches pullen und auf den Feature-Branch mergen.

Nach einem erfolgreichen push, muss auf Github ein Pull-Request erstellt werden<br />
auf: main<br />
von: feature-branch

Commit-Nachrichten sollten EINDEUTIG zu erkennengeben was genau gemacht wurde<br />
Beispiele:<br />
```git commit -m "add NavLinks to Navi with correct Routes"```<br />
```git commit -m "change bg-color of Navi, create hover for NavLinks"```