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
- haben eine fraglichliche Langzeitperspektive
- *verbergen das zugrundeliegende Textmodell*


---


## Text auszeichnen

Erscheinungsbild

_vs._

logische Struktur


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


## Pandoc

Pandoc ist ein Programm.

Es wandelt Markdown in eine Reihe anderer Formate um
- HTML, TEI, Latex, PDF, Word, ...


---


## Markdown, Pandoc und Git

Markdown: Text verfassen

Pandoc: Publikation erstellen

Git: Versionieren und kollaborieren



