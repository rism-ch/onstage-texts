# Projekt _onstage_
_onstage_ ist ein Projekt zur Valorisierung von Dokumenten, welches aus den verschiedenen Aktivitäten der HEMU-CL für die Feier des 150-jährigen Bestehen entstanden ist. Im Jahr 2015 ist das Conservatoire et Haute Ecole de Musique in Genf dem Projekt beigetreten und hat ihre Konzertprogramme integriert. Im Jahr 2016 wurde die Sammlung des Vereins Freunde alter Musik Basel der Datenbank hinzugefügt. 2020 folgte die Sammlung La Musicale de la Bibliothèque de Genève.

## _Onstage_ in Zahlen

### Sammlung Haute Ecole de Musique - Conservatoire de Lausanne

* 865 Aktivitäten
* 1'069 Komponisten und Interpreten
* 243 Auditionen
* 298 Konzerte
* 117 Vorträge
* 405 Aktivitäten in Verbindung mit Konzertzyklen (“jeudis du conservatoire”, “midi-concerts”…)
* 1'650 digitalisierte Seiten

### Sammlung Conservatoire de Musique de Genève

* 8'904 Programme
* 6'954 Komponisten und Interpreten
* 19'499 digitalisierte Seiten

### Sammlung Freunde Alter Musik Basel

* mehr als 400 Programme
* mehr als 2'400 Komponisten und Interpreten
* ca. 3'000 digitalisierte Seiten

### Sammlung La Musicale de la Bibliothèque de Genève

* eine Auswahl von etwa 2'300 Dokumenten (von 20'000)
* von 1861 bis 1945
* Genfer Säle, hauptsächlich : Victoria Hall, Kathedrale Saint-Pierre, Konservatorium Genf, Salle de la Réformation, Théâtre Pitoëff (Salle communale de Plainpalais)

## Projektverantwortliche
### Verantwortlich für die Sammlung Conservatoire et Haute Ecole de Musique de Lausanne

* Bibliothek der HEMU-CL – bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (wissenschaftliche Mitarbeiterin)

### Verantwortlich für die Sammlung Conservatoire et Haute Ecole de Musique de Genève

* Bibliothek des Conservatoire de Musique de Genève – biblio@cmg.ch

### Verantwortlich für die Sammlung Freunde Alter Musik Basel

* Archiv des Vereins Freunde Musik Basel – info@famb.ch

### Verantwortlich für die Sammlung La Musicale de la Bibliothèque de Genève

* La Musicale de la Bibliothèque de Genève – bmus@ville-ge.ch

### Informatik und Digitalisierung

* RISM Schweiz – info@rism.digital

## Kontakt
Für weitere Informationen: onstage@rism.digital

## Realisierung
Die onstage Datenbank besteht aus drei Hauptkomponenten: eine digitale Version der Konzertprogramme, eine manuelle Indexierung ihrer Inhalte und die automatische, unkorrigierte OCR-Transkription für die Volltextsuche. Diese drei Elemente sind in der Suchoberfläche und Präsentation von onstage integriert.

## Digitalisierung
Die Programme wurden unter Aufsicht von RISM Schweiz digitalisiert. Die Scaneinstellungen sind 300 / 400 dpi, in Farbe, im unkomprimierten TIFF-Format.

## Indexierung
Alle Programme wurden manuell indexiert. Das zugrunde liegende Index-Format ist das TEI (Text Encoding Initiative), ein XML-Format für die Kodierung von Texten (www.tei-c.org). Die Daten wurden in verschiedenen Registern indiziert:

* Personennamen
* Veranstaltungsorte (Konzertsäle)
* Konzertreihen
* Konzertdaten

![tei-example](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
###### Ausschnitt aus dem Inhalt eines Index in TEI

## OCR
Um den Nutzern eine Volltextsuche zu erlauben, wurde eine Software zur automatischen Zeichenerkennung (OCR) auf alle Programme angewendet. Die verwendeten Software sind ABBYY Finereader 11 Pro (www.abbyy.com) und Tesseract (https://tesseract-ocr.github.io). Es wurde keine Überprüfung oder Korrektur manuell durchgeführt, und die Volltextsuche greift auf eine nicht weiter verarbeitete Version des OCR-Ergebnisses zu.

## Schnittstelle
Die Recherche in den Indizes geschieht direkt in den TEI-Dateien (XML), mittels XPath-Abfragen (via PHP). Die gescannten Bilder der Programme werden durch diva.js angezeigt, ein speziell für hochauflösende Bilder entwickelter Anzeigetool (https://diva.simssa.ca/). Dies ermöglicht eine reibungslose Betrachtung von mehreren Seiten, unabhängig von der ausgewählten Zoomstufe. Die Bilder der Programme stehen zum Download im PDF-Format zur Verfügung.
