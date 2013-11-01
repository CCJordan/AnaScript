AnaScript
=========
Inoffizielles Script zur Analysisvorlesung von Prof. Margit Rösler (UPB, WS13/14)

### Allgemeiner Disclaimer

Ich erhebe keinen Anspruch auf Vollständigkeit oder Fehlerfreiheit, obwohl ich versuche möglichst akurat zu arbeiten. Einige Beispiele lasse ich weg, aber den Rest versuche ich sogut es geht mitzunehmen.

Solltet ihr Fehler in dem Script finden, könnt ihr mich per Mail an <mail@ccjordan.de> kontakten, ich versuche das dann schnellst möglich zu verbessern.

### Kompilierinformationen

Alle Dateien sind in UTF-8 codiert, besonders unter Windows kann das Encoding zu einem Problem werden, da viele Editoren unter Windows von einem ISO-8859-1 Encoding ausgehen, stellt daher bitte sicher, dass ihr UTF-8 verwendet.

Da ich meine Unicode-Tastaturbelegung zum Einsatz bringe, ist der Compiler __XeLaTeX__. Dieser Compiler sollte bei den meisten LaTeX Paketen mitgeliefert werden und muss nur noch ausgewählt werden.

Falls ihr keine Graphen im kompiliertem Script haben solltet, stellt sicher, dass ihr _gnuplot_ installiert habt und dass in eurem Ordner mit den TeX-Dateien das Verzeichnis _plots_ existiert und beschreibar ist. (Die .gnuplot und .table Dateien, die am Ende für die Graphenzeichnerei zuständig sind, committe ich bewusst nicht, da sie jeder mit dem TeX-Dokument erzeugen kann und die meisten TeX-Kompiler sowieso Fehler werfen, wenn sie nicht selbst gnuplot ansprechen dürfen.)

### Besonderen Dank an
**Stefan Heid**, die Ana-Script.tex-Datei stammt hauptsächlich aus seiner Feder