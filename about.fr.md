# Projet _onstage_
onstage est un projet de valorisation documentaire qui découle des différentes activités proposée par l’HEMU-CL pour la célébration de son 150ème anniversaire. En 2015, le Conservatoire et la Haute Ecole de Musique de Genève ont rejoint le projet en intégrant leurs programmes de concerts. En 2016, la collection de l’Association Freunde alter Musik Basel s’est ajoutée à la base-données. Enfin, en 2020, a suivi la collection de La Musicale de la Bibliothèque de Genève.

## _Onstage_ en chiffres

### Fonds Haute Ecole de Musique - Conservatoire de Lausanne

* 865 activités
* 1'069 compositeurs et interprètes
* 243 auditions
* 298 concerts
* 117 conférences
* 405 activités liées à des cycles de concerts (« jeudis du conservatoire », « midi-concerts »…)
*1'650 pages numérisées

### Fonds Conservatoire de Musique de Genève

* 8'904 programmes
* 6'954 compositeurs et interprètes
* 19'499 pages numérisées

### Fonds Freunde Alter Musik Basel

* plus de 400 programmes
* plus de 2'400 compositeurs et interprètes
* ca. 3'000 pages numérisées

### Fonds La Musicale de la Bibliothèque de Genève

* une sélection d'environ 2'300 documents (sur 20'000)
* de 1861 à 1945
* salles genevoises, principalement : Victoria Hall, Cathédrale de Saint-Pierre, Conservatoire de Genève, Salle de la Réformation, Théâtre Pitoëff (Salle communale de Plainpalais)

## Responsables du projet
### Responsables collection Conservatoire et Haute Ecole de Musique de Lausanne

* Bibliothèque HEMU-CL – bibliotheque@hemu-cl.ch
* Violeta Struijk Van Bergen (collaboratrice scientifique)

### Responsables collection Conservatoire et Haute Ecole de Musique de Genève

* Bibliothèque Conservatoire de Musique – biblio@cmg.ch

### Responsables collection Freunde alter Musik Basel

* Archiv des Vereins Freunde alter Musik Basel – info@famb.ch

### Responsables collection La Musicale de la Bibliothèque de Genève

* La Musicale de la Bibliothèque de Genève – bmus@ville-ge.ch

### Responsables informatique & numérisation

* Bureau Suisse du RISM – info@rism-ch.org

## Contact
Pour plus d’informations : onstage@rism-ch.org

## Réalisation
La base de données onstage est constituée de trois éléments principaux : une version numérisée des programmes de concerts, une indexation manuelle de leur contenu et une transcription automatique OCR non corrigée pour la recherche plein-texte. Ces trois éléments sont réunis dans l’interface de recherche et de présentation du projet onstage.

## Numérisation
Les programmes ont été numérisés sous la supervision du RISM Suisse. Les paramètres de numérisation sont 300/400dpi en couleur au format TIFF non compressé.

## Indexation
Tous les programmes ont été indexés à la main. Le format d’indexation sous-jacent est la TEI (Text Encoding Initiative), un format XML utilisé pour le balisage de textes (www.tei-c.org). Les données qui ont été indexées sont les suivantes :

* Les noms de personnes
* Les lieux (salles de concert)
* Les séries de concert
* Les dates de concert

![tei-example](https://raw.githubusercontent.com/rism-ch/onstage-texts/master/images/tei-example.png)
###### Extrait du contenu d'un indexe en TEI

## OCR
Pour pouvoir proposer aux utilisateurs une recherche plein-texte, un logiciel de reconnaissance de caractère (OCR) a été appliqué à l’ensemble des programmes. Les logiciels utilisés sont ABBYY FineReader 11 Pro (www.abbyy.com) et Tesseract (https://tesseract-ocr.github.io). Aucune vérification ou correction n’a été effectuée manuellement et la recherche plein-texte se fait sur une version brute du résultat OCR.

## Interface
La recherche sur les indexes se fait directement sur les fichiers TEI (XML) au moyen de requêtes XPath (via PHP). Les images numérisées des programmes sont affichées au moyen de l’afficheur diva.js spécifiquement conçu pour les images en haute résolution (https://diva.simssa.ca/). Il permet une consultation fluide de plusieurs pages et ce quelque soit le niveau de zoom choisi. Les images des programmes sont également disponibles en téléchargement au format PDF.
