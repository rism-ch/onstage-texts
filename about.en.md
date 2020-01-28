# Project _onstage_
onstage is a documentary enhancement project that stems from the various activities proposed by the HEMU-CL for the celebration of its 150th anniversary. In 2015, the Geneva Conservatory and the Haute Ecole de Musique de Genève joined the project by integrating their concert programmes. In 2016, the collection of the Association Freunde alter Musik Basel was added to the database.

## Project leaders
### Responsible for the collection of the Conservatoire and the Haute Ecole de Musique de Lausanne

* HEMU-CL Library - bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (scientific collaborator)

### Responsible for the collection of the Geneva Conservatory and Haute Ecole de Musique de Genève

* Music Conservatory Library - biblio@cmg.ch

### Responsible for the collection Freunde alter Musik Basel

* Archiv des Vereins Freunde alter Musik Basel - info@famb.ch

### IT & digitisation managers

* Swiss IMSN Office - info@rism-ch.org

## Contact
For more information: onstage@rism-ch.org

## Realization
The onstage database consists of three main elements: a digitized version of the concert programs, manual indexing of their content and an automatic uncorrected OCR transcription for full-text search. These three elements are brought together in the search and presentation interface of the onstage project.

## Digitization
The programs were digitized under the supervision of RISM Switzerland. The scanning parameters are 300/400dpi in colour in uncompressed TIFF format.

## Indexing
All programs have been indexed by hand. The underlying indexing format is TEI (Text Encoding Initiative), an XML format used for text markup (www.tei-c.org). The data that has been indexed is as follows:

* The names of persons
* Venues (concert halls)
* The concert series
* Concert dates

[tei-example](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
#### Extract from the contents of an index in TEI

## OCR
In order to offer users a full-text search, character recognition software (OCR) has been applied to all programs. The software used is ABBYY FineReader 11 Pro (www.abbyy.com). No manual checks or corrections are performed, and the full-text search is performed on a raw version of the OCR result.

## Interface
The index search is done directly on the TEI (XML) files using XPath queries (via PHP). Scanned images from the programs are displayed using the diva.js display specifically designed for high-resolution images (ddmal.music.mcgill.ca/diva/). It allows a fluid consultation of several pages, whatever the chosen zoom level. Program images are also available for download in PDF format.
