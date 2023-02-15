# Project _onstage_
_onstage_ is a document enhancement project that originates from the various activities proposed by the HEMU-CL for the celebration of its 150th anniversary. In 2015, the Geneva Conservatory and the Haute Ecole de Musique de Genève joined the project by integrating their concert programmes. In 2016, the collection of the Association Freunde alter Musik Basel was added to the database. In 2020 followed the collection of La Musicale de la Bibliothèque de Genève.  

## _Onstage_ in Figures

### Lausanne

* 865 activities
* 1'069 composers and performers
* 243 auditions
* 298 concerts
* 117 conferences
* 405 concert series activities (« jeudis du conservatoire », « midi-concerts »…)
* 1'650 pages digitalized

### Genève – Conservatoire

* 8'904 programmes
* 6'954 composers and performers
* 19'499 pages digitalized

### Basel

* more than 400 programmes
* more than 2'400 composers and performers
* ca. 3'000 pages digitalized

### Genève - La Musicale de la Bibliothèque de Genève

* a selection of about 2'300 documents (out of 20'000)
* from 1861 to 1945
* Geneva halls, mainly: Victoria Hall, Saint-Pierre Cathedral, Geneva Conservatory, Salle de la Réformation, Théâtre Pitoëff (Salle communale de Plainpalais)

## Project leaders
### Responsible for the collection of the Conservatoire and the Haute Ecole de Musique de Lausanne

* HEMU-CL Library – bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (scientific collaborator)

### Responsible for the collection of the Geneva Conservatory and Haute Ecole de Musique de Genève

* Library of the Conservatoire de Musique de Genève – biblio@cmg.ch

### Responsible for the collection Freunde alter Musik Basel

* Archive of the Verein Freunde alter Musik Basel – info@famb.ch

### Responsible for the collection La Musicale de la Bibliothèque de Genève

* La Musicale de la Bibliothèque de Genève – bmus@ville-ge.ch

### IT & digitisation managers

* Swiss RISM Office – info@rism-ch.org

## Contact
For more information: onstage@rism-ch.org

## Realization
The onstage database consists of three main elements: a digitized version of the concert programmes, manual indexing of their content and an automatic uncorrected OCR transcription for full-text search. These three elements are brought together in the search and presentation interface of the onstage project.

## Digitization
The programs were digitized under the supervision of RISM Switzerland. The scanning parameters are 300/400 dpi in colour in uncompressed TIFF format.

## Indexing
All programs have been indexed by hand. The underlying indexing format is TEI (Text Encoding Initiative), an XML format used for text markup (www.tei-c.org). The data has been indexed as follows:

* Personal names
* Venues (concert halls)
* Concert series
* Concert dates

[tei-example](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
#### Extract from the contents of an index in TEI

## OCR
In order to offer users a full-text search, character recognition software (OCR) has been applied to all programmes. The softwares used are ABBYY FineReader 11 Pro (www.abbyy.com) and Tesseract (https://tesseract-ocr.github.io). No manual checks or corrections are performed, and the full-text search is performed on a raw version of the OCR result.

## Interface
The index search is done directly on the TEI (XML) files using XPath queries (via PHP). Scanned images from the programmes are displayed using the diva.js display specifically designed for high-resolution images (https://diva.simssa.ca/). It allows a fluid consultation of several pages, whatever the chosen zoom level. Programme images are also available for download in PDF format.
