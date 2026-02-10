# HTR-Corpus-C

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

## Data
Silver-standard corpus; reviewed segmentation, corrected verses-level OCR

The data can be found at `./data/**/*xml` in ALTO format and follow [SegmOnto segmentation standards](https://segmonto.github.io). All data is produced using the eScriptorium interface and cataloged on [HTR-United](https://htr-united.github.io). The ALTO files have undergone manual correction, and the segmentation and transcription from the HTR are currently under review.

## Corpus 

* Corpus-C 

file in csv : [`Corpus C.csv`](corpus/Corpus_C.csv)

| Identifier | Segmentation | Transcription | Page | Author | Title | Printer | Date | Place | Library & Call number |
|-----------|--------------|---------------|------|--------|-------|---------|------|-------|----------------------|
| Lefevre_1-Tim_C2 | gold | gold | 3 | Jacques Lefèvre d'Etaples | Commentarii in epistolas d. Pauli | Anonymus | 1512 | Paris | [Regensburg SB – 999/2Script.801](https://mdz-nbn-resolving.de/urn:nbn:de:bvb:12-bsb11059254-9) |


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


