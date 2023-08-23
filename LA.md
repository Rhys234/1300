# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Ihr Gruppenname und Ihre Nachnamen

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

✍️ Beschreiben Sie Ihr Projekt in einem griffigen Satz.

✍️ Erklären Sie genauer in 50 bis 100 Wörtern, was genau Sie in diesem Projekt erreichen möchten, und was Sie dabei zu lernen hoffen.

### 1.2 User Stories

| US-№ | Beschreibung                       |
| ---- | ---------------------------------- |
| 1    | Der Computer speichert eine Zufallszahl zwischen und mit 1 bis 100 als Geheimzahl.|
| 2  | Der Benutzer kann Zahlen raten.|
| 3  | Für jede der geratenen Zahlen gibt der Computer einen Hinweis aus: |
| 4  | Die geratene Zahl ist niedriger als die Geheimzahl. |
| 5  | Die geratene Zahl ist grösser als die Geheimzahl.|
| 6  | Die Geheimzahl wurde erraten.|
| 7  | Wenn die Geheimzahl erraten wurde, soll die Anzahl der Rateversuche ausgegeben werden.|
| 8  | Das Programm soll mit Fehleingaben umgehen oder sie vermeiden können.|
| 9  | Erweiterungen, die über diese Anforderungen hinausgehen, sind möglich und willkommen.|
| 10 | Es soll gefragt werden, ob man wieder Spielen will. |




✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Das Programm started und Computer generiert eine Zufallszahl zwischen und mit 1 bis 100 als Geheimzahl | - | Computer begrüsst den Spieler |
| 2.1  | Programm fragt: Geben sie eine Zahl ein | eingabe Zahl | Programm sagt ob das Zahl zu hoch oder tief ist. |
| 6.1  | Spieler hat richtige Zahl erraten und gratuliert. | eingabe richtige Zahl | Gratulation. Sie haben den richgtige Zahl erraten. |
| 7.1  | Wenn die Geheimzahl richitg erraten wurde, zählt anzahl Versuche. | - |  Gratulation. Sie haben den richgtige Zahl erraten. Ihre Anzahl versuche: ... |
| 8.1  | Das spielt geht weiter.| gebt Buchstaben ein | Sagt, dass die Eingabe nicht gültig ist. |
| 10.1 | Nach dem richtig erraten des Spiels frag das Programm ob man weiter spielen will | y | Das Spiel beginnt von vorne. |
| 10.2 | Nach dem richtig erraten des Spiels frag das Programm ob man weiter spielen will | n | Das Program schliesst. |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte.

## 2 Planen

| AP-№ | Frist | Beschreibung | Zuständig | geplante Zeit | 
| ---- | ----- | --------- | ------------ | -------------- |
| 1.A  | 16.08.2023 |Lektion 1 des Codecademy Kurses abschliessen| M.S | 40 min |
| 2.A  | 16.08.2023 |Informieren des Projekts | alle | 40 min |
| 3.A | 16.08.2023 | Mock-up / aufbau | alle|  20 min |
| 4.A  | 16.08.2023 | user stories | alle |  20 min |
| 5.A  | 23.08.2023 | Zufallszahl generieren| Carina |  20 min |
| 6.A  | 23.08.2023 | If Else Clause erstellen| Sathana | 30 min |
| 6.B  | 23.08.2023 | speichern des eingabe Spielers| Sathana | 15 min |
| 7.A  | 23.08.2023 | Try Catch | Carina | 20 min |
| 8.A  | 23.08.2023 | Code für damit man wieder spielen kann| Sathana | 15 min |
| 9.A  | 23.08.2023 | Anzahl Versuche generieren| Carina | 20 min |
| 10.A  | 23.08.2023 | Farbe erstellen| Carina |   10 min |
| 11.A  | 06.09.2023 | Testen und Kontrollieren| alle |  15 min |
| 12.A  | 06.09.2023 | Portfolioeintrag | jede Einzeln |  120 min |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 16.08.2023 | Alle | 40 min | 50 min|
| 2.A  | 16.08.2023 | alle | 40 min | 35 min |
| 3.A  | 16.08.2023 | alle | 20 min | 20 min |
| 4.A  | 16.08.2023 | alle | 20 min | 20 min |
| 5.A  | 23.08.2023 | Carina | 25 min | 20 min |
| 6.A  | 23.08.2023 | Sathana | 30 min | 25 min |
| 6.b  | 23.08.2023 | Sathana | 15 min | 15 min |
| 7.A  | 23.08.2023 | Carina | 20 min | 20 min |
| 8.A  | 23.08.2023 | Sathana | 15 min | 15 min |
| 9.A  | 23.08.2023 | Carina | 20 min | 10 min |
| 10.A  | 23.08.2023 | Carina | 10 min | 10 min |
| 11.A  | | alle | 15 min |     |
| 12.A  | | alle | 120 min |    |


✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

