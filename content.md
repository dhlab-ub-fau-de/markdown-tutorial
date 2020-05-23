<!-- .element class="aligned-center title-page" -->

# Texte aufbereiten und publizieren mit Markdown und Pandoc 


---


## Text erstellen

Moderne Textprozessoren wie MS Word, Google Docs, OO Writer... 

- werden primär über eine GUI bedient
- bieten "WYSIWYG"
- haben einen großen Funktionsumfang
- stellen den "Industriestandard"
- sind (weitgehend) geschlossen
- sind ressourcenhungrig (schwergewichtig)
- haben eine fragliche Langzeitperspektive
- *verbergen das zugrundeliegende Textmodell*


---


## Text auszeichnen

Erscheinungsbild

_vs._

logische Struktur

- - -

Semantische Auszeichnung = logische Struktur


---


## Markdown

Markdown ist eine Konvention.<br>
(Quasi-Standard; kein Programm!)

Markdown definiert Regeln, wie logische Strukturelemente
in "reinen" Textdateien dargestellt werden.


---


## Exkurs: Was ist eine Textdatei?

- Textdateien enthalten _nur Schriftzeichen_, keine Formatierung <br>(alphanum. Zeichen, Zeilenumbrüche, Sonderzeichen)
- Kodierung / _Zeichensatz_: ASCII, Latin1, **UTF-8**
- Die Endung ist häufig _`.txt`_
- Viele Formate sind eigentlich Textdateien: XML, HTML, Shell-Skript, ...
- Texteditoren: Notepad++, Atom, ...


---


## Warum Markdown? Warum Textdateien

- Textmodell direkt sichtbar
- Reduzierung auf das Nötigste
- Werkzeug-unabhängig _und_ große Werkzeugauswahl
- leicht weiter- und wiederverwendbar
- zukunftssicher


---


## Alternativen

TEI: wissenschaftliche Aufbereitung von Texten

Latex: Professioneller Satz & Layout


---


## Varianten

Markdown ist nicht standardisiert.<br>
Es gibt verschiedenste Varianten/Flavors.

- Das Originale Markdown
- CommonMark
- [GitHub flavored Markdown](https://github.github.com/gfm/)
- ...


---


## Probieren geht über Studieren

Es gibt zahlreiche Webseiten zum Ausprobieren von Markdown.

Wir wählen die [markdown-it demo](https://markdown-it.github.io/)


---


## Pandoc

[Pandoc](http://pandoc.org/) ist ein Programm.

Es wandelt Markdown (und weitere Formate) in eine Reihe anderer Formate um:
HTML, TEI, Latex, PDF, Word, ...

Pandoc ist Open Source.

Pandoc wird über die Kommandozeile bedient.


---


## Pandoc-Beispiel 

Diese Folien als...
1. [HTML](content.html): `pandoc -o content.html content.md`
2. [PDF](content.pdf): `pandoc --toc -o content.pdf content.md`
3. [Word](content.docx): `pandoc -o content.docx content.md` 

Und im Original: [Markdown](content.md)


---


## Pandoc selbst ausprobieren

Die Webseite von Pandoc bietet eine [Demo](https://pandoc.org/try/)


---


## Anpassbarkeit

Pandoc versteht viele Formate:

`pandoc --list-input-formats`<br>
`pandoc --list-output-formats`

Pandoc kann weitreichend konfiguriert werden:

`pandoc --help`

Pandoc beachtet Metadaten für das Zieldokument.


---


## Markdown, Pandoc und Git

Markdown: Text verfassen

Pandoc: Publikation erstellen

Git: Versionieren und kollaborieren


---


## Beispiel: Programming Historian

Tutorials, an denen sich dieses Tutorial orientiert:

- [Getting Started with Markdown](https://programminghistorian.org/en/lessons/getting-started-with-markdown)
- [Sustainable Authorship in Plain Text using Pandoc and Markdown](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

Lektionen des Programming Historian werden in Markdown verfasst, über
[GitHub verwaltet](https://github.com/programminghistorian/jekyll/tree/gh-pages/en/lessons) und mit Pandoc publiziert.


