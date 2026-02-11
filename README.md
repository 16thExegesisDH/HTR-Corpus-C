
# HTR-Corpus-C

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)


# Guideline for Beatrice 

## I. Guideline for Segmentation

* specific cases of the corpus

### Ontology
- **RunningTitleZone** for the running header at the top of the page
- **GraphicZone** for all decorations (illustrations, ornamentation, etc)
- **MainZone:Head** for intermediate headings and biblical verses when they are emphasized by the layout
- **MainZone:P** for a paragraph
- **MainZone:Continued** for the continuation of an interrupted paragraph
- **NumberingZone** for numbering (pagination or foliation)
- **DropCapitalZone** for drop capitals at the beginning of a section
- **QuireMarkZone** or the organization of quires
- **MarginTextZone-Note** for marginal comments

### Examples

| Description | Example |
| -------- | ------- |
| **RunningTitleZone**: viola <br/> **MainZone:Head**: orange <br/> **MainZone:P**: yellow <br/> **MainZone:Continued**: red <br/> **NumberingZone**: light blue <br/> **QuireMarkZone**: dark blue <br/>**MarginTextZone-Note**: green | <img src="/pictures/segmentationGL/bugenhagen_rm.png" width="300"/> |
| **RunningTitleZone**: pink <br/> **DropCapitalZone**: dark viola <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:Continued**: light blue <br/> **NumberingZone**: rosa for "456", "II", "III" <br/> **QuireMarkZone**: viola <br/> **MarginTextZone-Note**: pink | <img src="/pictures/segmentationGL/Bucer_Rm_1.png" width="300"/> |
| **RunningTitleZone**: pink for "VII" (Epistle number) and "Col" (Epistle name) <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:Continued**: light blue <br/> **NumberingZone**: rosa for "7", "8", "184" | <img src="/pictures/segmentationGL/Lefevre_1.png" width="300"/> |
| **RunningTitleZone**: pink for "COM" <br/> **DropCapitalZone**: dark viola <br/> **MainZone:Head**: yellow <br/> **MainZone:P**: dark green <br/> **MainZone:Continued**: light blue <br/> **NumberingZone**: rosa for "1", "C4", "D4", "5", "6" | <img src="/pictures/segmentationGL/Lefevre_2.png" width="300"/> |
| **RunningTitleZone**: red <br/> **MainZone:Continued**: viola <br/> **GraphicZone**: rosa </br>**DropCapitalZone**: viola<br/> **MainZone:Head** : light green <br/> **MainZone:P** : blue <br> **NumberingZone** : rosa <br/> **QuireMarkZone** : rosa | <img src="/pictures/segmentationGL/Lamb-Tim.png" width="300"/> |
| **TitlePageZone**: light light viola <br/> **MarginTextZone-ManuscriptAddendum** red <br/> _for the manuscript annotation around the text_ <br/> | <img src="/pictures/segmentationGL/TitlePage.png" width="300"/> |

* more information concerning transcription [here](https://github.com/16thExegesisDH/HTR_Paul_corpus/tree/main)

The main documentation for the layout is here: [Annotation Guide on GitHub](https://github.com/DEFI-COLaF/LADaS/blob/main/AnnotationGuide.md).


## Data
Silver-standard corpus; reviewed segmentation, corrected verses-level OCR

The data can be found at `./data/**/*xml` in ALTO format and follow [SegmOnto segmentation standards](https://segmonto.github.io). All data is produced using the eScriptorium interface and cataloged on [HTR-United](https://htr-united.github.io). The ALTO files have undergone manual correction, and the segmentation and transcription from the HTR are currently under review.

## Corpus 

* Corpus-C 

file in csv : [`Corpus C.csv`](corpus/Corpus_C_priority_1.csv)

 - 1.st part of Corpus-C : 4233 images 

| Identifier | Segmentation | Transcription | Page | Author | Title | Printer | Date | Place | Library & Call number |
|-----------|--------------|---------------|------|--------|-------|---------|------|-------|----------------------|
| Bugenhagen_Rm       | no           | no            | 374  | Johannes Bugenhagen    | In epistolam Pauli ad Romanos Interpretatio                           | Johannes Secerius | 1527 | Hagenau     | [Österreichische Nationalbibliothek – 77.K.55 ALT PRUNK](https://data.onb.ac.at/rep/10AC1F79)                             |
| Calvin_Rm           | no           | no            | 461  | Jean Calvin            | Commentarij in Epistolam Pauli ad Romanos                             | Rihel             | 1540 | Strassbourg | [Regensburg, Staatliche Bibliothek – 999/Theol.syst.1101(1](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb11119106-3) |
| Erasmus_Cor         | no           | no            | 224  | Desiderius Erasme      | Paraphrasis in duas epistolas Pauli ad Corinthios                     | Froben            | 1519 | Basel       | [Universitätsbibliothek Basel – UBH FC* III 8:2](https://doi.org/10.3931/e-rara-3172)                                     |
| Hemmingsen_Rm       | no           | no            | 530  | Niels Hemmigsen        | Commentarius in epistolam Pauli ad Romanos                            | Voegelin Ernst    | 1562 | Leipzig     | [München, Bayerische Staatsbibliothek – Exeg. 470](http://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb10176721-0)           |
| Knopken_Rm          | no           | no            | 182  | Andreas Knopken        | In epistolam ad Romanos interpretatio                                 | Johann Petreius   | 1524 | Nuernberg   | [Österreichische Nationalbibliothek – 79.Ee.102 ALT PRUNK](https://onb.digital/result/109892B3)                           |
| Major_Rm            | no           | no            | 288  | Georg Maior            | Series et dispositio orationis in epistola Pauli ad Romanos           | Hans Luft         | 1556 | Wittenberg  | [München, Bayerische Staatsbibliothek – Exeg. 730#Beibd.1](https://www.digitale-sammlungen.de/en/details/bsb10176888)     |
| Megander_Eph        | no           | no            | 282  | Kaspar Megander        | In epistolam Pauli ad Ephesios commentarius                           | Henrichus Petri   | 1534 | Basel       | [München, Bayerische Staatsbibliothek – Exeg. 700 m](https://www.digitale-sammlungen.de/en/details/bsb00036972)           |
| Melanchthon_Rom-Cor | no           | no            | 314  | Philipp Melanchthon    | Annotationes in epistolam Pauli ad Romanos unam et ad Corinthios duas | Johannes Herwagen | 1523 | Strassburg  | [Staatsbibliothek zu Berlin – Bt 2552](https://digital.staatsbibliothek-berlin.de/werkansicht/?PPN=PPN773861106)          |
| Oekolampadius_Rom   | no           | no            | 220  | Johannes Oekolampadius | In epistolam B. Pauli apost. ad Rhomanos adnotationes                 | Cratander         | 1525 | Basel       | [Zentralbibliothek Zürich – C 283,2](https://doi.org/10.3931/e-rara-8160)                                                 |
| Oekolampadius_Hebr  | no           | no            | 382  | Johannes Oekolampadius | In Epistolam Ad Hebraeos explanationes                                | —                 | 1534 | Basel       | [München, Bayerische Staatsbibliothek – Hom. 1112#Beibd.1](https://www.digitale-sammlungen.de/en/details/bsb10180052)     |
| Olevian_Eph         | no           | no            | 304  | Kaspar Olevian         | Notae in epistolam Pauli apostoli ad Ephesios                         | Christoph Corvin  | 1588 | Herborna    | [München, Bayerische Staatsbibliothek – Exeg. 816](https://www.digitale-sammlungen.de/en/details/bsb10176929)             |
| Rollock_Eph         | no           | no            | 448  | Robert Rollock         | In Epistolam S. Pauli apostoli ad Ephesios                            | François le Preux | 1593 | Genève      | [Universitätsbibliothek Basel – UBH Frey-Gryn G VI 22:1](https://doi.org/10.3931/e-rara-1263)                             |
| Bucer_Eph_test      | no           | no            | 224  | Martin Bucer           | Epistolam ad Ephesios                                                 | Anonymus          | 1527 | Strassburg  | [München, Bayerische Staatsbibliothek – Polem. 408 Beibd.2](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb00035303-6) |

---

# File Nomenclature Guide

## 1. Directory Naming Convention

```
[exegete's name]_[epistle abbreviation]_[optional suffix]
```
### Components 

| Component | Description | Examples |
|-----------|-------------|----------|
| **Exegete's name** | Commentator name | `Aretius`, `Bucer`, `Bullinger` |
| **Epistle** | Abbreviated Latin Vulgate name | `1-Tim`, `Eph`, `Rm` |
| **Optional suffix** | Additional specification | `C_2`, `01`, `test` |

### Optional Suffix Types

- **`C_[chapter number]`** → For commentaries focusing on a single chapter
  - Example: `C_2` (Chapter 2)
  
- **`test`** → For PhD student dataset
  - Example: `test`

- **`[number]`** →  for iteration of the same commentary with the same author
  - Example: `01`, `02`
---

### Directory Examples

```
Aretius_1-Tim 
	└─Aretius commentary on 1 Timothy

Aretius_1-Tim_01
   └─ Aretius commentary on 1 Timothy, version 1

Bucer_Eph_test
   └─ Bucer commentary on Ephesians, test dataset

Bullinger_1-Tim_C_2
   └─ Bullinger commentary on 1 Timothy, Chapter 2
```
---
##  2. File Naming Convention

* Source: MDZ (Münchener Digitalisierungs Zentrum) : [URN of book]_[URN of page].xml
* Source: e-rara : [URN of page].xml

### File example 

| Source | Pattern | Example |
|--------|---------|---------|
| **MDZ** | `[book]_[page].xml` | `bsb10313792_00016.xml` |
| **e-rara** | `[page].xml` | `16892668.xml` |

---

## How to cite 

```bibtex
@misc{Goy_HTR-Corpus-A_16thExegesis,
  author={Floriane Goy, Béatrice Dupuis },
  title={HTR of Latin printed book from 16th Century},
  version={1.0},
  address={Genève},
  publisher={université de Genève},
  year={2023-2026},
  url={https://github.com/16thExegesisDH/HTR-Corpus-C},
}
```


