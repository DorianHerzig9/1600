# Projekt-Dokumentation

cucumber, Meyer, Raviraj, Herzig

| Datum      | Version | Zusammenfassung                                                                     |
| ---------- | ------- | ----------------------------------------------------------------------------------- |
| 09.05.2023 | 1.0.0   | Projektdokumentation erstellt und Planung ausgefüllt. Angefangen mit dem HTML-Index.|
| 16.05.2023 | 2.0.0   | Use Case Diagramm verbessert und Planung ausgebaut.                                |
| 23.05.2023 | 3.0.0   | Selbständiges Arbeiten.                                                             |
| 30.05.2023 | 4.0.0   | Skizze zur Webseite erstellt.                                                        |
| 06.06.2023 | 5.0.0   | Weiterarbeit an der Webseite.                                                       |
| 13.06.2023 | 6.0.0   | Selbständiges Arbeiten.                                                             |
| 20.06.2023 | 7.0.0   | Präsentation erstellt und vorgetragen.                                              |
| 27.06.2023 | 8.0.0   | Projekt und Projekt-Dokumentation fertigstellen.                                  |



## 1 Informieren

### 1.1 Ihr Projekt

wir wollen eine Website, die alle beliebten Filmen und Serien mit Beschreibungen und Rezensionen auflistet und erstellen.

Das Ziel dieses Projekts ist es, eine umfassende Website zu erstellen, die alle populären Filme und Serien mit detaillierten Beschreibungen und Rezensionen auflistet. Das Projekt wird uns dabei helfen, unsere Webentwicklungsfähigkeiten zu verbessern, insbesondere in den Bereichen Front-End-Design und Back-End-Programmierung. Wir werden auch lernen, wie man eine skalierbare und benutzerfreundliche Website erstellt, die den Bedürfnissen der Nutzer gerecht wird.

### 1.2 User Storys

| US-№ | Verbindlichkeit | Typ        | Beschreibung                                                                                               |
| ---- | --------------- | ---------- | ---------------------------------------------------------------------------------------------------------- |
| 1    | Kann            | Funktional | Als Nutzer möchte ich einen Darkmode haben, damit ich meine Augen in der Nacht schonen kann.              |
| 2    | Kann            | Funktional | Als Nutzer möchte ich auf die Thumbnails von Serie oder Filmes draufklicken können, um genauere Informationen zu bekommen. |
| 3    | Kann            | Funktional | Als Nutzer möchte ich einen Suchfilter haben, damit ich Filme und Serien, die mir gefallen könnten, finden kann.|
| 4.1  | Kann            | Qualitativ | Als Nutzer möchte ich eine übersichtliche und gut designte Seite, um mich besser zurechtzufinden.      |

### 1.3 Testfälle

| TC-№ | Ausgangslage                                                | Eingabe                           | Erwartete Ausgabe                                                   |
| ---- | ----------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------- |
| 1.1  | Ich will auf die Webseite zugreifen                         | Öffnen der Webseite               | Ich kann auf die Homepage zugreifen                                 |
| 1.2  | Ich will auf eine/n Serie/Film zugreifen                    | Klicken auf das Thumbnails        | Informationen von der/m Serie/Film freigegeben                              |
| 2.1  | 1.2 wurde betätigt und nun will ich auf die Informationen zugreifen | Keine Eingabe nötig               | Ich kann auf alle Informationen zugreifen                                   |
| 3.1  | Ich will auf der Homepage auf einen Suchfilter zugreifen    | Das Draufklicken der Suchfilters  | Der Suchfilter gibt mir eine Auswahl von Suchmöglichkeiten(A-Z/0-9) |
| 3.2  | 3.1 wurde ausgeführt                                        | Man klickt auf den Buchstaben "R" | Mir werden alle Filme mit "R" aufgelistet                           |


### 1.4 Diagramme

<img width="323" alt="image" src="https://github.com/DorianHerzig9/1600/assets/110893245/3b54601e-0526-4b8a-85f3-41693a4be6da">

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung                                              | geplante Zeit |
| ---- | ----- | --------- | --------------------------------------------------------- | ------------- |
| 0.A  | 9.5.  | Herzig    | Website erstellen und auf Github Pages veröffentlichen.    | 30min         |
| 1.A  | 16.5. | Meyer     | Button für Darkmode implementieren.                        | 30min         |
| 2.A  | 16.5  | Herzig    | Liste mit Filmen und Serien erstellen.                     | 45min         |
| 2.B  | 16.5. | Meyer     | Thumbnails in geeigneten Grössen und Formaten suchen.      | 10min         |
| 2.C  | 23.5. | Herzig    | Bilder einfügen.                                           | 15min         |
| 2.D  | 16.5  | Raviraj   | Rezensionen für Filmen und Serien suchen.                             | 20min         |
| 2.E  | 23.5. | Raviraj   | Kurze Beschreibung und Genre für jeden Film und jede Serie erstellen.  | 45min   |
| 2.F  | 23.5  | Meyer     | Rezensionen beim Klicken auf einen Bild anzeigen.                 | 60min         |
| 3.A  | 30.5. | -          | Als Vorbereitung für Filter jedem Film eine ID oder ein Genre zuweisen. | 15min   |
| 3.B  | 30.4  | -          | Filterfunktion erstellen, sodass nur gefilterte Filme und Serien angezeigt/ausgeblendet werden.    |    60min      |
| 4.A  | 9.5.  | Raviraj   | Einige Farben, Schriftarten und evtl. Icons festlegen.      | 20min         |
| 4.B  | 9.5.  | Meyer     | Grobe Design Ideen erarbeiten.                              | 30min         |
| 4.C  | 9.5.  | Raviraj   | Verschieden Farbpaletten testen.                            | 20min         |


Total:

## 3 Entscheiden

1. Dark Mode: Wir haben uns dafür entschieden, einen Dark Mode in die Website zu integrieren, um den Nutzern die Möglichkeit zu geben, die Augen bei nächtlicher Nutzung zu schonen. Wir gehen davon aus, dass dies die Benutzerfreundlichkeit und das visuelle Erlebnis verbessern wird.

2. Thumbnails für Filme und Serien: Wir haben beschlossen, Thumbnails für Filme und Serien in der Website einzufügen, damit die Benutzer durch Klicken auf die Thumbnails detailliertere Informationen erhalten. Wir gehen davon aus, dass dies den Nutzern dabei helfen wird, ihre gewünschten Filme oder Serien leichter zu finden und darauf zuzugreifen.

3. Suchfilter: Wir werden einen Suchfilter implementieren, mit dem die Benutzer nach Filmen und Serien suchen können. Wir gehen davon aus, dass dieser Suchfilter den Nutzern helfen wird, die gewünschten Inhalte basierend auf verschiedenen Kriterien wie Alphabet, Genre oder anderen Filteroptionen zu finden.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 0.A  | 6.5.  |  Herzig   |30min|29min|
| 1.A  | 16.5. |  Meyer    |30min|28min|
| 2.A  | 16.5. |  Herzig   |45min|53min|
| 2.B  | 16.5. |  Meyer    |10min|15min|
| 2.C  | 23.5. |  Herzig   |15min|20min|
| 2.D  | 16.5. |  Raviraj  |20min|22min|
| 2.E  | 23.5. |  Raviraj  |45min|40min|
| 2.F  | 23.5. |  Meyer    |60min|56min|
| 3.A  | 30.5. |  -----    |15min|--min|
| 3.B  | 30.4. |  -----    |60min|--min|
| 4.A  | 9.5.  |  Raviraj  |20min|20min|
| 4.B  | 9.5.  |  Meyer    |30min|25min|
| 4.C  | 9.5.  |  Raviraj  |20min|24min|


## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 0.1  | 27.06.2023 |  Ok        | Sanjay Raviraj |
| 1.1  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 2.1  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 2.2  | 27.06.2023      |  Ok       | Sanjay Raviraj |
| 2.3  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 2.4  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 2.5  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 2.6  | 27.06.2023      |  Ok        | Sanjay Raviraj |
| 3.1  | 27.06.2023      | Nok         | Sanjay Raviraj       |
| 3.2  | 27.06.2023      | Nok         | Sanjay Raviraj       |
| 4.1  | 27.06.2023      | Ok         | Sanjay Raviraj       |
| 4.2  | 27.06.2023      | Ok        | Sanjay Raviraj       |
| 4.3  | 27.06.2023      | Ok         | Sanjay Raviraj       |



## 6 Auswerten

https://github.com/DorianHerzig9/1600/blob/main/Lern-Bericht.md
