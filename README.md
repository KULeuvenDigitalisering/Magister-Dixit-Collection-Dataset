# Magister-Dixit-Collection-Dataset
Full dataset from the Magister Dixit Collection (handwritten lecture notes of the Old University of Leuven) offered as open data for digital humanities and other creative engagement

# KU Leuven Libraries on GitHub
Read [here](https://github.com/KU-Leuven-Libraries/Welcome-to-KU-Libraries-OpenGLAM) a brief introduction of KU Leuven Libraries on GitHub.

# The Magister Dixit Collection
The Magister Dixit Collection currently contains 552 manuscripts of lecture notes of the Old University of Leuven (1425-1797). The manuscripts, which are kept in different libraries, were fully digitised and virtually collected as part of the [Magister Dixit project](http://lectio.ghum.kuleuven.be/lectio/magister-dixit). <br>
The collection is an extraordinary source for the history of the Old University of Leuven, offering a vivid picture of the University organization, its curricula and subjects. <br>
Most of the manuscripts that have been preserved come from the Faculty of Arts, corresponding to the first academic degree, necessary to get access to the “high” faculties such as Medicine, Theology or Law.  The Faculty of Arts was divided into four Pedagogies (the Castle, the Lily, the Pig, the Falcon), whose affiliation determined the student life at the time. Moreover, the lecture notes include information about the individuals, students, professors and professionals who worked or collaborated with the University (engravers, printers, illustrators). <br>
The digitisation project so far (i.e; April 2020) involved the manuscripts kept at [KU Leuven Libraries](https://bib.kuleuven.be/english), [UCL](https://uclouvain.be/en/libraries/about.html), [KBR](https://www.kbr.be/en/), [Museum M Leuven](https://www.mleuven.be/nl/content/home), [Abdij van Berne Heeswijk](https://www.abdijvanberne.nl/), as well as other private collectors. The collection is still growing.

# The dataset

## Repository type
The Magister Dixit Collection Dataset is a repository of descriptive metadata representing all 552 manuscripts of the current virtual collection. The digitized collection can be explored through the LIMO [Libraries’ Curated Collections](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81386064490001488&lang=en_US) discovery interface, within the thematic collection [Lecture notes from the Old University of Leuven](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81411248550001488&lang=en_US), or alternatively, through the Lectio page [Magister Dixit Collection](http://lectio.ghum.kuleuven.be/lectio/magister-dixit-collection).

## Who can use it
The repository is designated as a free resource for digital humanities research, for scholars, students and teachers. It is intended for creative reuse, data visualisation and algorithmic processing.

## Provenance
The dataset is fully based on the library catalogue metadata. It holds the descriptive metadata as well as URL links to the digital representation in the Teneo viewer. The data, which were provided by the Alma digital preservation environment of KU Leuven Libraries, was previously cleaned, transformed and refined with the OpenRefine application software.  

## Technical Aspects
The CSV file (Magister_Dixit_Collection_Dataset.csv) contains 552 records in rows and 27 columns with the following metadata:
| Column | Content type | Instance | Description/MARC 21 reference |
|-|-|-|-|
| 1 | Record ID | 9985450340101488 | Unique key = record id in original cataloging system |
| 2 | URL Limo | https://limo.libis.be/primo-explore/search?query=any,contains,9985450340101488&tab=all_content_tab&search_scope=ALL_CONTENT&vid=KULeuven | Direct url to record in Limo |
| 3 | Date type | m | Encoded indication of type of date, https://www.loc.gov/marc/bibliographic/bd008a.html |
| 4 | Date 1 | 1613 | Date of creation |
| 5 | Date 2 | 1616 | Date of end |
| 6 | Main title | Scripta de sacramentis | Field 246 13: $a main title of the publication https://www.loc.gov/marc/bibliographic/bd245.html |
| 7 | Varying title(s) | Dialectices sive Manuductio ad logicam Lovaniensem ::: Dialectices sive Manuductio ad logicam Lovaniensem a Reverendo in Christo Patro Francisco Vrancx F. M. prædicatore ac Phil: Professore Scripta a Peril: P. F. Eq: D. R: D: L: &orum &orum Die aprilis 24 | https://www.loc.gov/marc/bibliographic/bd246.html#:~:text=Varying%20forms%20of%20the%20title,further%20identification%20of%20the%20item. |
| 8 | Physical extent | 341 p.$bill. | Field 300: $a Description of physical object, varying parameters depending on the nature of the objects, https://www.loc.gov/marc/bibliographic/bd300.html |
| 9 | Binding | Parchment binding ; manuscript title in black ink "[...] Scripta de sacramentis Viggers" ; remnants of ties | https://www.loc.gov/marc/bibliographic/bd563.html |
| 10 | Description of graphic material | \\$ePaper | Material and colors of graphic material, https://www.loc.gov/marc/bibliographic/bd340.html |
| 11 | General notes | Title created by cataloguer ::: F. 0r : Ad usum fratris Leonardi Bosch | https://www.loc.gov/marc/bibliographic/bd500.html |
| 12 | Details | Tractatus sine dictata commentaria in primam partem secundae angelici doctoris$gf. 0r-278v :::* Praefatio$gf. 1r :::* Nota tractatus de beatitudine$gf. 1r-39v :::* Tractatus secundus$gf. 40r-77r :::* Tractatus de libero arbitrio$gf. 77r-119r :::* Tractatus de conscientia$gf. 119r-157v :::* Tractatus de peccatis$gf. 158r-278v ::: Tractatus de sacramentis [incomplete?]$g1*r-10*v | https://www.loc.gov/marc/bibliographic/bd505.html |
| 13 | Genre/form | Manuscripts ::: Lecture notes | https://www.loc.gov/marc/archive/2009-2010/concise/bibliographic/bd655.html |
| 14 | Illustrations | f. 1/3r :$bengraved titlepage$cMetaphysica, Physica, with signs of the Lily, the Falcon, the Castle and the Pig ::: \\$af. 1/30v : pasted on$bengraving(s)$cportrait of a lady ::: f. 1/121v : pasted on$bengraving(s)$cportrait of a veiled lady with book ::: f. 1/128r : pasted on$bengraving(s)$cMusica ::: f. 2/1r :$bengraved titlepage$cMetaphysica, Physica, with signs of the Lily, the Falcon, the Castle and the Pig ::: f. 2/1r : page with$bornamental initials | https://www.loc.gov/marc/bibliographic/bd008b.html |
| 15 | Contributors | Malderus, Joannes$cbishop of Antwerp$d1563-1633$4pfs ::: Mercier, Jean$d? - 1570$4pfs ::: Viggers, Joannes$4pfs ::: Vanden Dael, Paulus$4stu ::: Bosch, Leonardus$4stu ::: Cuyckius, Leonardus$4stu ::: Wierix, Jeronimus$d1553-1619$4egr ::: de Mallery, Charles$d1571-after 1635$gFlemish engraver, active in Antwerpen and Paris$4egr | 700: ‘Personal names’ and its sub-fields https://www.loc.gov/marc/bibliographic/bd700.html |
| 16 | Professor | Malderus, Joannes $cbishop of Antwerp $d1563-1633 ::: Mercier, Jean $d? - 1570 ::: Viggers, Joannes | 700: ‘Personal names’ sorted by sub-field ‘$pfs’ |
| 17 | Student | Vanden Dael, Paulus ::: Bosch, Leonardus ::: Cuyckius, Leonardus | 700: ‘Personal names’ sorted by sub-field ‘$stu’ |
| 18 | Author original work | de Ferrière, Claude Joseph $d1680?-1748? | 700: ‘Personal names’ sorted by sub-field ‘$aow’ |
| 19 | Other | Melchior Stralensis | 700: ‘Personal names’ sorted by sub-field ‘$oth’ |
| 20 | Printer | de Gosen, Hieronymus Iacobus | 700: ‘Personal names’ sorted by sub-field ‘$prt’ |
| 21 | Engraver | Wierix, Jeronimus$d1553-1619 ::: de Mallery, Charles $d1571-after 1635 $gFlemish engraver, active in Antwerpen and Paris | 700: ‘Personal names’ sorted by sub-field ‘$egr’ |
| 22 | Illustrator | Gravelot, Hubert François $d1699-1773 $gFrench book illustrator, engraver, draughtsman and painter | 700: ‘Personal names’ sorted by sub-field ‘$ill’ |
| 23 | Etcher | Harrewijn, François $d1700-1764 $gFlemish etcher, bookseller ::: Denique, Petrus Augustinus $cLeuven $d1721?-1769 | 700: ‘Personal names’ sorted by sub-field ‘$etc’ |
| 24 | Adapter | Haye, Michael $d?-1676 $gFlemish printmaker, draftsman and publisher | 700: ‘Personal names’ sorted by sub-field ‘$adp’ |
| 25 | Artist | Rubens, Peter Paul $d1577-1640 ::: Titiaan $dca. 1485-1576 $gItalian painter | 700: ‘Personal names’ sorted by sub-field ‘$art’ |
| 26 | Place of production 1 | Leuven (Louvain) Pedagogie onbekend | Field 952: $d place, $e name of Pedagogy (in Dutch) https://www.loc.gov/marc/bibliographic/bd264.html |
| 27 | Place of production 2 | Faculty of Arts, pedagogy unknown | Field 952:  $f name of  Pedagogy  in English and Latin  |
| 28 | IE | IE5052929 |  |
| 29 | URL | http://resolver.libis.be/IE5052929/representation | Direct url to image viewer |
| 30 | Label | Abdij van Berne Heeswijk Ms. F11 | Physical object location |
| 31 | Collection | BERNE HEESWIJK | Library collection |


The Discovery Interface Limo also includes three extra fields: ‘Shelf location’, ‘Provenance’, and ‘Acquisition details’ which are not present in this dataset. <br>

## Cite this dataset
When referring to or using the data repository in research publications and documentation, consider citing the dataset with its digital object identifier (DOI) that is minted in Zenodo. Citing the data repository of the Magister Dixit collection creates a mapping of attribution and supports efforts to release other datasets in the future. It also reduces the amount of "orphaned data," helping to retain source links. <br>
Cite the repository as: KU Leuven Libraries, Digitisation Department. (2020). Magister Dixit Collection Metadata[Dataset]. Zenodo. http://doi.org/

## License
The Magister Dixit Collection repository is licensed under a [Public Domain Mark (PDM)](https://creativecommons.org/share-your-work/public-domain/pdm/). PDM operates as a label indicating that the dataset is no longer restricted by copyright and can be freely used by everyone. 
KU Leuven Libraries follows an open images policy that allows its public domain digitised heritage collections to be freely copied, modified, distributed and reused, only by mentioning “KU Leuven. Magister Dixit Collection” without asking for further permission. For a detailed view of the library’s legal compliances read [here](https://bib.kuleuven.be/BD/digitalisering-en-document-delivery/digitalisering/gebruiksvoorwaarden).

## Code of Conduct
The GitHub repository of KU Leuven Libraries follows the CNCF [Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md), as a way to be overt in our openness, welcoming all people to contribute, and pledging in return to value them. In order to make our open communities welcoming, diverse and inclusive, we are encouraging the adaptation of the Contributor Covenant as a means to express and codify those values. Any unacceptable behavior as trolling, insulting/derogatory comments, personal or political attacks will not be tolerated. The Contributor Covenant is released under the Creative Commons Attribution 4.0 International Public License.

## Project Attribution
[KU Leuven Libraries](https://bib.kuleuven.be/english) <br>
- Nele Gabriëls: Digitisation Department (project supervisor) <br>
- Bruno Vandermeulen: Digitisation Department (project advisor) <br>
- Diederik Lanoye: Metadata Services and Acquisitions <br>

[Advanced Master of Digital Humanities](https://onderwijsaanbod.kuleuven.be/opleidingen/e/CQ_52330579.htm#activetab=diploma_omschrijving) (MSc), KU Leuven <br>
- Martina Verna: Intern, KU Leuven Digitisation Department, thesis project

## Contributors
This project follows the all-contributors specification. KU Leuven Libraries recognises contributions and engagement for its open data repository through emoji key✨, in a way to reward every contribution, not only code. Contributions of any kind like questions, ideas, link to videos, translations and many more will be automatically acknowledged through the all-contributors bot 🤖.



