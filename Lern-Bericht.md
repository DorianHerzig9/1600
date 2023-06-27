# Lern-Bericht
Cucumber, Meyer, Herzig, Raviraj

## Einleitung

Eine Webseite mit verschiedenen Film- und Serienzusammenfassungen und Rezenzionen.

## Was habe ich gelernt?

Wir haben gelernt wie man CSS Image Reflection verwendet und implementiert.

## Beschreibung



Für unsere Seite haben wir das verwendet um das Bild unter einer Leicht Transparenten Textbox gespiegelt anzuzeigen. Dies hat mehrer vorteile.

1.Weichere Übergänge: Es entsteht ein weicher Übergang zwischen dem Bild und der Textbox. Anstatt dass das Bild abrupt an der Textbox endet, wird es durch die Reflexion subtil erweitert. Dies führt zu einer fließenden visuellen Verbindung zwischen den beiden Elementen.
2.Schaffung von Tiefe: Die Reflexion erzeugt eine zusätzliche Dimension und verleiht dem Bild mehr Tiefe. Dies kann dazu beitragen, dass das Bild interessanter und ansprechender wirkt.

3. Hervorhebung der Textbox: Durch die Platzierung des gespiegelten Bildes unter der Textbox konnten wir die Aufmerksamkeit auf die Textinhalte lenken. Da das Auge oft von natürlichen Reflexionen angezogen wird, wird der Betrachter dazu verleitet, den Text zu lesen und sich mit den Informationen in der Textbox zu beschäftigen.

Dies sieht dann Folgendermassen aus:
![Screenshot 2023-06-27 095559](https://github.com/DorianHerzig9/1600/assets/77541325/8d3823f4-9bf1-4eb4-91b0-a475ee0bb025)


Folgende Syntax wird dafür verwendet:
```css
box-reflect: <direction> <offset> <mask-box-image> <mask-border-outset>;
```

Das "direction" Attribut gibt die Richtung der Reflexion an und kann entweder "above" (oben), "below" (unten), "left" (links) oder "right" (rechts) sein.
Das "offset" Attribut definiert den Abstand zwischen dem Element und der Reflexion. Er kann in absoluten Einheiten (z. B. Pixel) oder in relativen Einheiten (z. B. %) angegeben werden.
Das "mask-box-image" Attribut ist eine optionale Eigenschaft, mit der ein Bild als Maske für die Reflexion festgelegt werden kann. Dadurch kann die Reflexion zum Beispiel einen Verlauf oder eine Textur aufweisen.
Das "mask-border-outset" Attribut ist ebenfalls optional und definiert den Abstand zwischen dem Maskenbild und dem Rand der Reflexion.


## Verifikation

Das Bild zeigt das Resultat in unserer webseite, der Code und die Textveschreibung zeigen die gelernte syntax auf. Wobei Die 3 genannten vorteile uns einiges im Bereich des dynamischen Designs weitergebiltet haben. 

# Reflexion zum Arbeitsprozess

Dierekte implementierung des Designs und der Funktionen

Die Kommunikation und Zusammenarbeit verlief anfangs sehr schlecht.

Um dies zu verbessern sollten wir in Zukunft genauer Planen wer was macht und möglichst voneinander unabhängige Arbeitspakete erstellen.

