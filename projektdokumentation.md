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
|2.2|Man ist neben dem Schmutz|Man läuft mit dem Besen über den Schmutz|Der Schmutz verschwindet und man wird bezahlt|
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
| 1.A  | 3.11.23      | LG          | Programmierung des Spiels inklusive Grafiken, Spiellogik und Benutzeroberfläche.             |30               |
| 1.b  | 3.11.23      | XN          | Implementierung der Logik, die das Spiel fortführt, wenn der Benutzer nicht putzen möchte.
             |  30             |
| 2.a  | 3.11.23      | AB          |Logik zur Erzeugung von Schulumgebungen und Räumen im Spiel.
              |    30           |
| 2.b  | 3.11.23      | LG          |Implementierung einer Mechanik, bei der der Schmutz beim Bewegen des Besens über ihn verschwindet und der Spieler belohnt wird.
              |      30         |
| 3.a  | 3.11.23      | XN          | Verwaltung des Spielerinventars und Sicherstellung, dass der Besen von Anfang an vorhanden ist.
             |        30       |
| 3.b  | 3.11.23      | AB          |Implementierung der Aktion, bei der der Spieler den Besen aus dem Inventar nimmt.
              |          30     |
| 3.c  | 3.11.23      | LG          | Implementierung der Aktion, bei der der Spieler den Besen zurück in das Inventar legt.
             |            30   |
| 3.d  | 3.11.23      | XN          |Programmierung der Mechanik, bei der der Schmutz entfernt wird, wenn der Spieler den Besen benutzt, und Fortschritt im Spiel gemacht wird.
              |              30 |
| 4.a  | 3.11.23      | AB          |Implementierung der Logik zur Erzeugung von Schmutz auf dem Boden, den Fenstern und den Tischen im Spiel.
              |30               |
| 4.b  | 3.11.23      | LG          |Implementierung der Logik zur Erzeugung von Schmutz auf den Fenstern in der Schule, um sicherzustellen, dass die Fenster schmutzig sind und vom Spieler gereinigt werden können.
              |  30             |
| 4.c  | 3.11.23      | XN          |Programmierung der Mechanik, die Schmutz auf den Tischen in der Schule erzeugt, sodass der Spieler die Tische reinigen kann.             |    30           |
| 5.a  | 3.11.23      | AB          |Programmierung der festen Aussehen und Umgebung des Spiels gemäß den Spielerwünschen und Erzeugung von Schmutz an den entsprechenden Stellen in der Spielwelt.

              |      30         |
| 5.b  | 3.11.23      | LG          |Implementierung einer festen Spielumgebung, die das Erscheinungsbild und die Elemente der Spielwelt definiert, um sicherzustellen, dass sie konsistent und vorhersehbar ist.

              |        30       |
| 5.c  | 3.11.23      | XN          Programmierung der Mechanik, die Schmutz auf verschiedenen Oberflächen wie Fenstern, Boden und Tischen in der Spielwelt generiert, um sicherzustellen, dass die Umgebung schmutzig ist und vom Spieler gereinigt werden kann.|          30     |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
