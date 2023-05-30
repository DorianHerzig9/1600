# Projekt-Dokumentation

cucumber, Meyer, Raviraj, Herzig

| Datum      | Version | Zusammenfassung                                                                     |
| ---------- | ------- | ----------------------------------------------------------------------------------- |
| 09.05.2023 | 1.0.0   | Projektdokumentation erstellt und Planung ausgefüllt. Angefangen mit dem HTML-index |
| 16.05.2023 | 2.0.0   |                                                                                     |
|            |         |                                                                                     |

## 1 Informieren

### 1.1 Ihr Projekt

wir wollen eine Website, die alle beliebten Filmen und Serien mit Beschreibungen und Rezensionen auflistet und erstellen.

Das Ziel dieses Projekts ist es, eine umfassende Website zu erstellen, die alle populären Filme und Serien mit detaillierten Beschreibungen und Rezensionen auflistet. Das Projekt wird uns dabei helfen, unsere Webentwicklungsfähigkeiten zu verbessern, insbesondere in den Bereichen Front-End-Design und Back-End-Programmierung.Wir werden auch lernen, wie man eine skalierbare und benutzerfreundliche Website erstellt, die den Bedürfnissen der Nutzer gerecht wird.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ        | Beschreibung                                                                                               |
| ---- | --------------- | ---------- | ---------------------------------------------------------------------------------------------------------- |
| 1    | Kann            | Funktional | Als Nutzer möchte ich einen Dark mode haben, damit ich meine Augen in der Nacht schonen kann.              |
| 2    | Kann            | Funktional | Als Nutzer möchte ich auf die Thumbnails von Serie oder Filmes draufklicken können, um genauere Infos zu bekommen. |
| 3    | Kann            | Funktional | Als Nutzer möchte ich einen Suchfilter haben, damit ich Filme und Serien die mir gefallen könnten finden kann,      |

### 1.3 Testfälle

| TC-№ | Ausgangslage                                                | Eingabe                           | Erwartete Ausgabe                                                   |
| ---- | ----------------------------------------------------------- | --------------------------------- | ------------------------------------------------------------------- |
| 1.1  | Ich will auf die Webseite zugreifen                         | Öffnen der Webseite               | Ich kann auf die Homepage zugreifen                                 |
| 1.2  | Ich will auf eine/n Serie/Film zugreifen                    | Klicken auf das Thumbnails        | Infos von der/m Serie/Film freigegeben                              |
| 2.1  | 1.2 wurde betätigt und nun will ich auf die Infos zugreifen | Keine Eingabe nötig               | Ich kann auf alle Infos Zugreifen                                   |
| 3.1  | Ich will auf der Homepage auf einen Suchfilter zugreifen    | Das Draufklicken der Suchfilters  | Der Suchfilter gibt mir eine Auswahl von Suchmöglichkeiten(A-Z/0-9) |
| 3.2  | 3.1 wurde ausgeführt                                        | Man klickt auf den Buchstaben "R" | Mir werden alle Filme mit "R" aufgelistet                           |

### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/110893245/237046835-05647338-0802-4b9f-9445-179f2616096c.png)

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung                                              | geplante Zeit |
| ---- | ----- | --------- | --------------------------------------------------------- | ------------- |
| 1.A  | 9.5.  | Herzig    | Website erstellen und auf github Pages veröffentlichen    | 30min         |
| 2.A  | 9.5.  | Raviraj   | Website Layout erarbeiten                                 | 20min         |
| 2.B  | 16.5. | Meyer     | Grobe design Ideen erarbeiten                             | 30min         |
| 3.A  | 16.5  | Herzig    | Liste Mit Animes erstellen                                | 45min         |
| 3.B  | 16.5. | Meyer     | Thumbnails für Animes suchen                              | 10min         |
| 3.C  | 16.5  | Raviraj   | Rezensionen für Animes Suchen                             | 20min         |
| 4.A  | 23.5. | Raviraj   | Kurze Beschreibung für jeden anime erstellen und einfügen | 45min         |
| 4.B  | 23.5. | Herzig    | Bilder einfügen                                           | 15min         |
| 4.C  | 23.5  | Meyer     | Rezensionen bei klicken auf Bild anzeigen                 | 60min         |
| ...  |       |           |                                                           |               |
| ...  |       |           |                                                           |               |
| ...  |       |           |                                                           |               |
| ...  |       |           |                                                           |               |
| ...  |       |           |                                                           |               |
| ...  |       |           |                                                           |               |

Total:

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

1. Dark Mode: Wir haben uns dafür entschieden, einen Dark Mode in die Website zu integrieren, um den Nutzern die Möglichkeit zu geben, die Augen bei nächtlicher Nutzung zu schonen. Wir gehen davon aus, dass dies die Benutzerfreundlichkeit und das visuelle Erlebnis verbessern wird.

2. Thumbnails für Filme und Serien: Wir haben beschlossen, Thumbnails für Filme und Serien in der Website einzufügen, damit die Benutzer durch Klicken auf die Thumbnails detailliertere Informationen erhalten. Wir gehen davon aus, dass dies den Nutzern dabei helfen wird, ihre gewünschten Filme oder Serien leichter zu finden und darauf zuzugreifen.

3. Suchfilter: Wir werden einen Suchfilter implementieren, mit dem die Benutzer nach Filmen und Serien suchen können. Wir gehen davon aus, dass dieser Suchfilter den Nutzern helfen wird, die gewünschten Inhalte basierend auf verschiedenen Kriterien wie Alphabet, Genre oder anderen Filteroptionen zu finden.

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
