# WAP2019
UV Wissenschaftliche Arbeitstechniken und Präsentation (WS 2019/20)

Homework + Presentation (Slides and Papers)

---

**HÜ1:** Erstellung einer latex Tabelle deren Einträge unterschiedlich skalierte und rotierte Bilder sind (um die Sklaierung zu erkennen sollten zumindest zwei verschieden grosse Varianten von einem Bild inkludiert sein).

**HÜ2:** Erstellung einer XFIG Graphik, die der Abbildung rechts unten auf S. 184 (Lineal und Auto darüber) möglichst ähnlich sieht, wobei das gesamte Auto noch kopiert und rotiert werden soll. Einzubinden in ein latex Dokument.

**HÜ3:** Erstellung von 4 Gnuplot Graphiken, die auf 4 verschiedene Arten die Anfängerzahlen der Informatikstudien (Bachelor, Master Lehramt) visualisieren. Bei diesen Graphiken muss die Fontsize der Achsenbeschriftungen und der Legende, sowie die Position der Legende unterschiedlich gewählt werden. Einzubinden in ein latex Dokument.

**HÜ4:** Lesen sie ihr liebstes Urlaubsfoto (oder ein anderes .jpg file) ein und konvertieren sie
es in ein Grauwertbild (Grauwert Y eines Pixels ergibt sich aus den Pixel Farbkanalen ¨
RGB als Y = 0.5G + 0.3R + 0.2B). Schreiben sie eine Function smooth.m, der sie eine
Pixelposition und eine Nachbarschaftsgrosse ¨ ubergeben. Diese Funktion berechnet ¨
den Mittelwert der Grauwerte in einem 3x3, 5x5, oder 7x7 Fenster der Y Werte wobei
die ubergebene Pixelposition im Zentrum des Fensters liegt, dieser Mittelwert ist der ¨
Ruckgabewert der Funktion. smooth.m soll auf alle Pixel des Bildes angewendet ¨
werden (wobei jeder Pixel durch den Ruckgabewert ersetzt wird) und die drei ¨
Ergebnisse sollen mit fprintf in je ein File geschrieben werden, sodass korrekt
formatierte ascii .pgm Files entstehen (die dann mit einem Bildbearbeitungsprogramm
betrachtet werden sollen; dazu muss naturlich auch ein korrekter Header geschrieben ¨
werden). Zum Format dieser Files siehe google .pgm oder ahnlich.   
[ ACHTUNG: die Aufgabe ist natürlich in Mathematica zu programmieren, die Ausgabe der manipulierten Bilder kann durch eingebaute mathematica Funktionen vorgenommen werden. Abzugeben sind hier mathematica Notebook und die verwendeten und entstandenen Bilder. ]

**Paper:**   
* Latex-version eines "Papers" über die jeweiligen Präsentationen in .pdf Format, Gliederung und Struktur soll sich am im VP besprochenen Schema orientieren. Diese muss enthalten zumindest
  * ein Literaturverzeichnis, mit bibtex erzeugt, korrekte Einträge sind wichtig (d.h. was muss z.b. bei einem Buch alles angegeben werden), es muss zumindest jeder der besprochenen Publikationstypen 1x vorkommen (wenn nichts themenbezogenes gefunden wird, kann ein beliebiger Eintrag verwendet werden).
  * Es wird auch die Form des Dokuments beurteilt !
* Zusaetzlich erstellen sie bitte eine zweite Version als .ps file, wo sie den IEEE Konferenz stylefile verwenden (z.B. zu finden [hier]([https://duckduckgo.com](https://www.cosy.sbg.ac.at/~uhl/IEEEStyle.txt))).
* PDF-Slideshow der Präsentation, mit Latex Beamerpackage erzeugt
* Abgabeform: Latexdokument nach HTML konvertieren, sie schicken mir nur die URL dieses Dokuments. Am Anfang des Dokuments fuegen sie bitte links auf die PDF slideshow und auf ein Verzeichnis ein, in dem latex-source, .pdf file, .ps file, .bib file, sowie alle Files (inklusive Source-files) der vier Hausuebungen (jeweils in Unterverzeichnissen) liegen.
