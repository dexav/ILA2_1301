# Projekt-Dokumentation

Gruppe: Xavier Nursiwat, Artur Bytyqi, Leonardo Grigioni

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 15.09.2023      | 0.0.1   | Erstellung von Projektdokumentation und Idee für Projekt gesammelt. |
|22.09.2023       | 0.0.2   | In Roblox Funktionen für die Tools gemacht.                                                             |
|29.09.2023       | 0.0.3   | In Roblox Questsystem gemacht                                                             |

## 1 Informieren

### 1.1 Ihr Projekt

Wir machen ein Spiel auf Roblox. Ein Spiel, wo man als Hausmeister eine Schule putzt. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |    
| 1    | muss            | Funktional | Als User möchte ich, dass ich die Schule putzen kann, damit es sauber wird.  |
| 2 |  muss               | Funktional     | Als User möchte ich, dass es verschiedene Räume gibt, wo man putzen kann, damit ich nicht an der selben Stelle putzen muss|
| 3  |  muss            |  Funktional       |  Als User möchte ich eine Quest bekommen. |
| 4  |  muss            |  Funktional       |  Als User möchte ich mit einem Besen den Schmutz putzen.  |
| 5 |  muss            | Funktional        | Als User möchte ich, dass nicht nur der Boden dreckig ist sondern auch die Tische und Fenster, damit ich nicht immer das Gleiche putzen muss              |
| 6 |  kann      | Qualität|Als User möchte ich, dass die Umgebung einigermassen gut aussieht, damit es nicht langweilig aussieht. |


9
### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
|1.1|Man möchte spielen.|(Spiel startet)|Das Spiel startet|
|1.2|Benutzer möchte die Schule nicht putzen|(Spiel startet)|Spiel läuft weiter; Benutzer macht keinen Fortschritt|
|2.1|Man will Räume haben, wo man putzen kann|(Spiel startet)|Das Spiel generiert die Schule und die Räume|
|2.2|Man ist neben dem Schmutz|Man läuft mit dem Besen über den Schmutz|Der Schmutz verschwindet |
|3.1|Man möchte mit einer Quest beschäftigt sein.|(Spiel startet)|Der Schulleiter gibt dir eine Quest.|
|4.1|Man will den Schmutz beseitigen |(Spiel startet)|Der Besen ist schon im Inventar.|
|4.2|Man will den Schmutz beseitigen |1| Man nimmt den Besen raus.|
|4.3|Man will den Besen weglegen |1| Der Besen wird im Inventar abgelegt.|
|4.4|Benutzer steht neben dem Schmutz|Benutzer nutzt Besen um den Schmutz zu putzen|Schmutz verschwindet und man macht Fortschritt.|
|5.1|Man will nicht nur den Boden dreckig haben|(Spiel startet)|Spiel generiert Schmutz auf den Boden in der Schule|
|5.2|Man will nicht nur den Boden dreckig haben|(Spiel startet)|Spiel generiert Schmutz auf die Fenster in der Schule|
|5.3|Man will nicht nur den Boden dreckig haben|(Spiel startet)|Spiel generiert Schmutz auf den Tischen in der Schule|
|6.1|Man will, dass die Welt einigermassen gut aussieht|(Spiel startet)|Das Spiel hat ein festes Aussehen|
|6.2|Man will, dass die Welt einigermassen gut aussieht|(Spiel startet)|Das Spiel hat eine feste Umgebung|
|6.3|Man will, dass es überall dreckig ist, nicht nur der Boden|(Spiel startet)|Das Spiel generiert Schmutz auf Fenster, Boden und Tischen|



### 1.4 Diagramme
![HausmeisterJoe](https://github.com/dexav/ILA2_1301/assets/110892637/b8f031e3-111b-4f0d-8b2d-f8c5880bfcdc)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
|1.A|29.09.2023|Xavier Nursiwat|Man kann die Schule putzen|180 min|
|2.A|22.09.2023|Artur Bytyqi|Es gibt eine Schule, die man betreten kann|90 min|
|3.A|29.09.2023|Leonardo Grigioni|Ein NPC steht vor der Schule|15 min|
|3.B|29.09.2023|Leonardo Grigioni|Man kann mit dem NPC interagieren|30 min|
|3.C|29.09.2023|Leonardo Grigioni|Der NPC gibt einen Dialog aus (Quest) |60 min|
|4.A|22.09.2023|Artur Bytyqi|Besen-Modell gemacht|120 min|
|4.B|06.10.2023|Xavier Nursiwat|Man kann den Besen benutzen|90 min|
|4.C|29.09.2023|Xavier Nursiwat|Man startet das Spiel mit dem Besen bereits im Inventar|30 min|
|5.A|29.09.2023|Artur|Schmutz-Modell gefunden|30 min|
|5.B|06.10.2023|Xavier Nursiwat|Es gibt Schmutz in der Schule auf dem Boden|150 min|
|5.C|06.10.2023|Leonardo Grigioni|Es gibt Schmutz auf den Tischen und Fenster|180 min|
|6.A|13.10.2023|Artur Bytyqi|Es hat Bäume in der Umgebung|120 min|
|6.B|20.10.2023|Artur Bytyqi|Es hat einen Fluss in der Umgebung|45 min|
|6.C|20.10.2023|Artur Bytyqi|Es hat Steine in der Umgebung|30 min|
|6.D|20.10.2023|Artur Bytyqi|Es hat eine schöne Aussicht als Hintergrund|15 min|



Total: 1185 min = 19 h 45 min


## 3 Entscheiden

Als allererstes mussten wir uns um eine Schule entscheiden. Wir haben uns für eine zweistöckige Schule entschieden, da eine einstöckige zu klein war und man viel zu schnell fertig war. Dann haben wir uns um einen Besen entschieden. Wir hatten die Wahl einen eigenen zu machen oder länger zu suchen, da alle langweilig aussahen. Wir entschieden uns einen eigenen zu machen, damit wir nicht Zeit verschwenden beim Suchen. Dann haben wir uns für ein Schmutz-Modell entscheiden müssen. Wir nahmen Kot als Modell. Wenn wir Flecken auf den Boden oder Gegenstände machen wollten, würde das mehrere Tagen brauchen, da es erstaunlicherweise viel Aufwand und Zeit braucht die Skripts und Modelle zu machen. Für die Umgebung entschieden wir uns für die Natur, da es viel weniger Zeit braucht, als ein Dorf oder eine Stadt zu machen.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |29.09.2023       | Xavier Nursiwat          |180 min               | 150 min                  |
| 2.A  |22.09.2023       | Artur Bytiqi          |90               |   95 min                |
| 3.A  |29.09.2023      |Leonardo Grigioni          |  15 min             |  20 min                 |
| 3.B  |29.09.2023      |Leonardo Grigioni          |  30 min             |  45                 |
| 3.C  |29.09.2023      |Leonardo Grigioni           |  60             |    55               |
| 4.A  |22.09.2023     |Artur Bytiqi           |    120           |      130             |
| 4.B  |06.10.2023      |Xavier Nursiwat           |  90             |      100             |
| 4.C  |29.09.2023       |Xavier Nursiwat           |    30           |        40           |
| 5.A  | 29.09.2023      |Artur Bytiqi          |     30          |40
| 5.B  | 06.10.2023    |  Xavier Nursiwat     |     150          |   130                |
| 5.C  | 06.10.2023     |Leonardo Grigioni          |     100          |  100                 |
| 6.A  | 13.10.2023      |Artur Bytiqi      |  120             |    115               |
| 6.B  |  20.10.2023     |Artur Bytiqi      |  45             |    50               |
| 6.C  | 20.10.2023       |Artur Bytiqi      |    30           |     45              |
| 6.D  | 20.10.2023       |Artur Bytiqi      |      15         |       30            |








## 5 Kontrollieren


|TC-№|	Datum|	Resultat|	Tester|
|----| ------|----------|-------|
|1.1|	03.11.2023|	OK|	Leonardo Grigioni|
|1.2|	03.11.2023|	OK|	Artur Bytyqi|
|2.1|	03.11.2023|	OK|	Xavier Nursiwat|
|2.2|	03.11.2023|	OK|	Leonardo Grigioni|
|3.1|	03.11.2023|	OK|	Artur Bytyqi|
|4.1|	03.11.2023|	OK|	Xavier Nursiwat|
|4.2|	03.11.2023|	OK|	Leonardo Grigioni|
|4.3|	03.11.2023|	OK|	Artur Bytyqi|
|4.4|	03.11.2023|	OK|	Xavier Nursiwat|
|5.1|	03.11.2023|	OK|	Leonardo Grigioni|
|5.2|	03.11.2023|	OK|	Artur Bytyqi|
|5.3|	03.11.2023|	OK|	Xavier Nursiwat|
|6.1|	03.11.2023|	OK|	Leonardo Grigioni|
|6.2|	03.11.2023|	OK|	Artur Bytyqi|
|6.3|	03.11.2023|	OK|	Xavier Nursiwat|

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
