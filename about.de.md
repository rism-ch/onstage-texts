# Projekt _onstage_
onstage ist ein Projekt zur Valorisierung von Dokumenten, welches aus den verschiedenen Aktivitäten der HEMU-CL für die Feier des 150-jährigen Bestehen entstanden ist. Im Jahr 2015 ist das Conservatoire et Haute Ecole de Musique in Genf dem Projekt beigetreten und hat ihre Konzertprogramme integriert. Im Jahr 2016 wurde die Sammlung des Vereins Freunde alter Musik Basel der Datenbank hinzugefügt.

## Projektverantwortliche
Verantwortlich für die Sammlung Conservatoire et Haute Ecole de Musique de Lausanne

* Bibliothek der HEMU-CL – bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (wissenschaftliche Mitarbeiterin)

## Verantwortlich für die Sammlung Conservatoire et Haute Ecole de Musique de Genève

* Bibliothek des Conservatoire de Musique de Genève – biblio@cmg.ch
* Archiv des Vereins Freunde Musik Basel – info@famb.ch

## Informatik und Digitalisierung

* RISM Schweiz – info@rism-ch.org

## Kontakt
Für weitere Informationen: onstage@rism-ch.org

## Realisierung
Die onstage Datenbank besteht aus drei Hauptkomponenten: eine digitale Version der Konzertprogramme, eine manuelle Indexierung ihrer Inhalte und die automatische, unkorrigierte OCR-Transkription für die Volltextsuche. Diese drei Elemente sind in der Suchoberfläche und Präsentation von onstage integriert.

## Digitalisierung
Die Programme wurden unter Aufsicht von RISM Schweiz digitalisiert. Die Scaneinstellungen sind 300 / 400 dpi, in Farbe, im unkomprimierten TIFF-Format.

## Indexierung
Alle Programme wurden manuell indexiert. Das zugrunde liegende Index-Format ist das TEI (Text Encoding Initiative), ein XML-Format für die Kodierung von Texten (www.tei-c.org). Die Daten wurden in verschiedenen Registern indiziert:

* Personennamen
* Veranstaltungsorte (Konzertsäle)
* Konzertreihen

## Konzertdaten

![tei-example](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
###### Ausschnitt aus dem Inhalt eines Index in TEI

## OCR
Um den Nutzern eine Volltextsuche zu erlauben, wurde eine Software zur automatischen Zeichenerkennung (OCR) auf alle Programme angewendet. Die verwendete Software ist ABBYY Finereader 11 Pro (www.abbyy.com). Es wurde keine Überprüfung oder Korrektur manuell durchgeführt, und die Volltextsuche greift auf eine nicht weiter verarbeitete Version des OCR-Ergebnisses zu.

## Schnittstelle
Die Recherche in den Indizes geschieht direkt in den TEI-Dateien (XML), mittels XPath-Abfragen (via PHP). Die gescannten Bilder der Programme werden durch diva.js angezeigt, ein speziell für hochauflösende Bilder entwickelter Anzeigetool (ddmal.music.mcgill.ca/diva). Dies ermöglicht eine reibungslose Betrachtung von mehreren Seiten, unabhängig von der ausgewählten Zoomstufe. Die Bilder der Programme stehen zum Download im PDF-Format zur Verfügung.
