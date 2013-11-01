AnaScript
=========
Script zur Analysisvorlesung von Prof. Margit Rösler (UPB, WS13/14)

Ich erhebe keinen Anspruch auf Vollständigkeit oder Fehlerfreiheit, obwohl ich versuche möglichst akurat zu arbeiten. Einige Beispiele lasse ich weg, aber den Rest versuche ich sogut es geht mitzunehmen.

Solltest du, geneigter Leser, Fehler in dem Script schicken, dann kannst du mich per Mail an <mail@ccjordan.de> kontaktieren und helfen, das Script besser zu machen. 

### Kompilierinformationen

Da ich meine Unicode-Tastaturbelegung zum Einsatz bringe, ist der Compiler XeLaTeX. Dieser Compiler sollte bei den meisten LaTeX Paketen mitgeliefert werden und muss nur noch ausgewählt werden.

Falls ihr keine Graphen im kompiliertem Script haben solltet, stellt sicher, dass ihr _gnuplot_ installiert habt und dass in eurem Ordner mit den TeX-Dateien das Verzeichnis _plots_ existiert und beschreibar ist. (Die .gnuplot und .table Dateien, die am Ende für die Graphenzeichnerei zuständig sind, committe ich bewusst nicht, da sie jeder mit dem TeX-Dokument erzeugen kann und die meisten TeX-Kompiler sowieso Fehler werfen, wenn sie nicht selbst gnuplot ansprechen dürfen.)