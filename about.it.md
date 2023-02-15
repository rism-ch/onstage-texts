# Progetto _onstage_
_onstage_ è un progetto di valorizzazione documentaria che nasce dalle varie attività proposte dall'HEMU-CL per la celebrazione del suo 150° anniversario. Nel 2015, il Conservatorio di Ginevra e l'Haute Ecole de Musique de Genève hanno aderito al progetto integrando i loro programmi di concerti. Nel 2016 è stata aggiunta alla banca dati la collezione dell'Associazione Freunde alter Musik Basel. Infine, nel 2020, ha seguito la collezione de La Musicale de la Bibliothèque de Genève.

## _Onstage_ in numeri

### Collezione di Losanna

* 865 attività
* 1'069 compositori e interpreti
* 243 audizioni
* 298 concerti
* 117 conferenze
* 405 attività legate ai cicli di concerti ("giovedì al conservatorio", "pranzo-concerto" ...)
* 1'650 pagine scansionate

### Collezione di Ginevra – Conservatoire

* 8'904 programmi
* 6'954 compositori e interpreti
* 19'499 pagine scansionate

### Collezione di Basilea

* oltre 400 programmi
* oltre 2'400 compositori e interpreti
* circa 3'000 pagine scansionate

### Collezione di Ginevra – La Musicale de la Bibliothèque de Genève

* una selezione di circa 2'300 documenti (su 20'000)
* dal 1861 al 1945
* Sale di Ginevra, principalmente: Victoria Hall, Cattedrale di Saint-Pierre, Conservatorio di Ginevra, Salle de la Réformation, Théâtre Pitoëff (Salle communale de Plainpalais)

## Responsabili del progetto
### Responsabile della collezione del Conservatorio e della Haute Ecole de Musique de Lausanne

* Biblioteca HEMU-CL – bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (collaboratrice scientifica)

### Responsabile della collezione del Conservatorio di Ginevra e dell'Alta Scuola di Musica di Ginevra

* Biblioteca del Conservatoire de Musique – biblio@cmg.ch

### Responsabile della collezione Freunde alter Musik Basel

* Archivio dell'Associazione Freunde alter Musik Basel – info@famb.ch

### Responsabile della collezione La Musicale de la Bibliothèque de Genève

* La Musicale de la Bibliothèque de Genève – bmus@ville-ge.ch

### IT & digitalizzazione

* Ufficio svizzero del RISM - info@rism-ch.org

## Contatto
Per maggiori informazioni: onstage@rism-ch.org

## Realizzazione
Il database onstage è composto da tre elementi principali: una versione digitalizzata dei programmi dei concerti, l'indicizzazione manuale del loro contenuto e una trascrizione automatica non corretta dell'OCR per la ricerca del testo completo. Questi tre elementi sono riuniti nell'interfaccia di ricerca e di presentazione del progetto onstage.

## Digitalizzazione
I programmi sono stati digitalizzati sotto la supervisione del RISM Svizzera. I parametri di scansione sono 300/400 dpi a colori in formato TIFF non compresso.

## Indicizzazione
Tutti i programmi sono stati indicizzati a mano. Il formato di indicizzazione sottostante è il TEI (Text Encoding Initiative), un formato XML utilizzato per la marcatura del testo (www.tei-c.org). I dati indicizzati sono i seguenti:

* Nomi di persona
* Sedi (sale da concerto)
* Serie di concerti
* Date dei concerti

[tei-esempio](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
#### Estratto dal contenuto di un indice in TEI

## OCR
Per offrire agli utenti una ricerca a testo completo, a tutti i programmi è stato applicato un software di riconoscimento dei caratteri (OCR). I software utilizzati sono ABBYY FineReader 11 Pro (www.abbyy.com) e Tesseract (https://tesseract-ocr.github.io). Non vengono eseguiti controlli o correzioni manuali e la ricerca del testo completo viene eseguita su una versione grezza del risultato dell'OCR.

## Interfaccia
La ricerca per indice viene effettuata direttamente sui file TEI (XML) utilizzando le query XPath (via PHP). Le immagini scansionate dai programmi vengono visualizzate utilizzando il display diva.js appositamente progettato per le immagini ad alta risoluzione (https://diva.simssa.ca/). Permette una consultazione fluida di più pagine, qualunque sia il livello di zoom scelto. Le immagini del programma possono essere scaricate anche in formato PDF.
