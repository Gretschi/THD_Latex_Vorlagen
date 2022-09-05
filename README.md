# THD LaTeX Vorlagen

In diesem Repository befinden sich diverse LaTeX Vorlagen zur freien Verwendung
für Kollegen an der THD. Konstruktive Kritik und Beiträge sind gerne willkommen.

## Briefvorlage

Dieses Verzeichnis enthält eine Briefvorlage. Für die eigene Verwendung müssen die Einträge
in `Stammdaten.lco` einmalig angepasst werden. Für das Aufsetzen eines neuen Briefes bietet
es sich dann an, eine Kopie des Verzeichnisses zu erstellen und `brief.tex` entsprechend
anzupassen. Wird das Projekt anschließend mit `make` kompiliert, dann erhält das Ausgabe-PDF
denselben Namen wie das Projektverzeichnis.

## Studienarbeiten

Die [Vorlage für Studienarbeiten](https://mygit.th-deg.de/thd-latex/studienarbeiten) wurde in ein eigenes Repository ausgelagert.

## Beamer_Slides

Die [Vorlage für LaTeX/Beamer Präsentationen](https://mygit.th-deg.de/thd-latex/beamer-template) wurde in ein eigenes Repository ausgelagert.

## Klausuren

Dieses Verzeichnis enthält eine Vorlage für Klausuren. Die Vorlage basiert auf dem
[LaTeX `exam.cls` Package](https://ctan.org/pkg/exam?lang=de) und orientiert sich
im Design an der Vorgabe durch das Studienzentrum. Modifikationen müssen nur in der
Datei `exam.tex` erfolgen. Es können die normalen Kommandos aus der `exam` Klasse
verwendet werden (das Handbuch findet sich [hier](http://mirrors.ctan.org/macros/latex/contrib/exam/examdoc.pdf "Using the exam document class")).
Mittels `make` kann anschließend das PDF erstellt werden.

---
[Andreas Fischer](mailto:andreas.fischer@th-deg.de "Mail an Andreas Fischer")

