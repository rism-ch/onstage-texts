# Progetto _onstage_
on stage è un progetto di valorizzazione documentaria che nasce dalle varie attività proposte dall'HEMU-CL per la celebrazione del suo 150° anniversario. Nel 2015, il Conservatorio di Ginevra e l'Haute Ecole de Musique de Genève hanno aderito al progetto integrando i loro programmi di concerti. Nel 2016 è stata aggiunta alla banca dati la collezione dell'Associazione Freunde alter Musik Basel.

## Capi progetto
### Responsabile della collezione del Conservatorio e della Haute Ecole de Musique de Lausanne

* Biblioteca HEMU-CL - bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (collaboratrice scientifica)

### Responsabile della collezione del Conservatorio di Ginevra e dell'Alta Scuola di Musica di Ginevra

* Biblioteca del Conservatorio di Musica - biblio@cmg.ch

### Responsabile della collezione Freunde alter Musik Basel

* Archiv des Vereins Freunde alter Musik Basel - info@famb.ch

### IT & digitalizzazione manager

* Ufficio svizzero IMSN - info@rism-ch.org

## Contatto
Per maggiori informazioni: onstage@rism-ch.org

## Realizzazione
Il database sul palco è composto da tre elementi principali: una versione digitalizzata dei programmi dei concerti, l'indicizzazione manuale del loro contenuto e una trascrizione automatica non corretta dell'OCR per la ricerca del testo completo. Questi tre elementi sono riuniti nell'interfaccia di ricerca e di presentazione del progetto sul palco.

## Digitalizzazione
I programmi sono stati digitalizzati sotto la supervisione del RISM Svizzera. I parametri di scansione sono 300/400 dpi a colori in formato TIFF non compresso.

## Indicizzazione
Tutti i programmi sono stati indicizzati a mano. Il formato di indicizzazione sottostante è il TEI (Text Encoding Initiative), un formato XML utilizzato per la marcatura del testo (www.tei-c.org). I dati che sono stati indicizzati sono i seguenti:

* I nomi delle persone
* Sedi (sale da concerto)
* La serie di concerti
* Date dei concerti

[tei-esempio](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
#### Estratto dal contenuto di un indice in TEI

## OCR
Per offrire agli utenti una ricerca a testo completo, a tutti i programmi è stato applicato un software di riconoscimento dei caratteri (OCR). Il software utilizzato è ABBYYY FineReader 11 Pro (www.abbyy.com). Non vengono eseguiti controlli o correzioni manuali e la ricerca del testo completo viene eseguita su una versione grezza del risultato dell'OCR.

## Interfaccia
La ricerca dell'indice viene effettuata direttamente sui file TEI (XML) utilizzando le query XPath (via PHP). Le immagini scansionate dai programmi vengono visualizzate utilizzando il display diva.js appositamente progettato per le immagini ad alta risoluzione (ddmal.music.mcgill.ca/diva/). Permette una consultazione fluida di più pagine, qualunque sia il livello di zoom scelto. Le immagini del programma possono essere scaricate anche in formato PDF.