# OpenGovLD

This page is work in progress and will be translated to English. So far there exists a Wiki page: https://github.com/OpenGovLD/specs/wiki

The main part of the specification will be *machine readable*. Therefore only a small amount of text of the specification will _only_ be readable by humans.

The specification will enable <img src="http://lab.linkeddata.deri.ie/2010/lod-badges/img/data-badge-5.png" alt="five star open Web data" />-conformance.

***

In diesem Repository wird die Spezifikation erarbeitet. OpenGov spezifiziert eine einheitliche Schnittstelle zum Abruf von
öffentlichen Informationen aus parlamentarischen Informationssystemen.


Original: Editieren, Änderungen nachvollziehen
----------------------------------------------

Wenn Du Dich für die Quellen des Dokuments sowie für das Nachvollziehen von Änderungen an den Quellen interessierst, findest Du dies im Ordner:

    dokument/master

Die Quelldateien sind reine Textdateien (Zeichensatz: UTF-8) mit Markdown-Formatierung (Dateiendung: .md).

Änderungswünsche am Dokument können in Form von Pull Requests beigesteuert werden. Dazu erzeugst Du zunächst einen Fork dieses Repositories. Dann committest Du Änderungen an Deinem Fork. Danach kannst Du am einzelnen Commit die Funktion "Send Pull Request" auslösen.

**Übrigens:** [prose.io](http://prose.io/) ist ein fantastischer Web-basierter Editor, mit dem Du die Markdown-Dateien in Deinem eigenen Repository spielend im Browser bearbeiten kannst.

Änderungsinfos können übrigens in Form eines [Atom Feeds](https://github.com/OpenGovLD/specs/commits/master.atom) abonniert werden.

Derivate: Bequemes Lesen auf verschiedenen Geräten
--------------------------------------------------

Es stehen Versionen des Dokuments in vielen Formaten zur Verfügung:

*ACHTUNG*: Gegenwärtig sind dies noch unmodifizierte Kopien der OParl-Dokumente. (Eine einfache Textersetzung von "OParl" durch "OpenGovLD" ist erst sinnvoll, wenn ein Teil der Texte manuell überarbeitet ist. Das betrifft z.B. die Historie.)

* [PDF](https://github.com/OpenGovLD/specs/blob/master/dokument/pdf/document.pdf?raw=true)
* [OpenOffice/LibreOffice](https://github.com/OpenGovLD/specs/blob/master/dokument/odt/document.odt?raw=true)
* [Microsoft Word](https://github.com/OpenGovLD/specs/blob/master/dokument/docx/document.docx?raw=true)
* [LaTeX](https://github.com/OpenGovLD/specs/blob/master/dokument/epub/document.epub?raw=true)
* [Nur Text](https://github.com/OpenGovLD/specs/blob/master/dokument/plain/document.txt?raw=true)

Die Derivate werden mit [Pandoc](http://johnmacfarlane.net/pandoc/) erzeugt. Das Script unter 'scripts/create_documents.sh' automatisiert diesen Vorgang.
