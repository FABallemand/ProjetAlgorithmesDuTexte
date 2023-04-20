# Projet Algorithmes Du Texte : Acquisition des Régions Fonctionnelles dans les Génomes

## 🧬 Description
The GenBank sequence database is an open access, annotated collection of all publicly available nucleotide sequences and their protein translations. It is produced and maintained by the National Center for Biotechnology Information (NCBI; a part of the National Institutes of Health in the United States) as part of the International Nucleotide Sequence Database Collaboration (INSDC). [[Wikipedia](https://en.wikipedia.org/wiki/GenBank)]  

This program is a utility tool to facilitate access to this database. The user-friendly graphic interface allows to browse organisms in the database and parse their DNA. The DNA parsing can be set-up in order to parse only relevant DNA sequences such as: CDS, centromere, intron, mobile element, telomere, ncRNA, rRNA, tRNA, 3'UTR, 5'UTR.
## 🧬 Description

<p align="center">
  <img src="screenshot.png" />
</p>

## 📂 Ressources

### 🔬 National Center for Biotechnology Information : National Library of Medicine
- [Présentation de GenBank](https://www.ncbi.nlm.nih.gov/genome/browse#!/overview/)
- [GenBank](https://ftp.ncbi.nlm.nih.gov/genomes/genbank/)
- [Recherche GenBank](https://www.ncbi.nlm.nih.gov/genome/)
- [GenBank: Homo sapiens Legacy Genome](https://www.ncbi.nlm.nih.gov/genome/?term=txid9606[orgn])

### 📚 Documentation
- [Biopython documentation](http://biopython.org/DIST/docs/tutorial/Tutorial.html#sec168)
- [Biopyhton GenBank](https://biopython.org/docs/1.76/api/Bio.GenBank.html)
- [Biopython examples](https://notebook.community/widdowquinn/Notebooks-Bioinformatics/Biopython_NCBI_Entrez_downloads)

## 🔧 Dependancies
- [Biopyhton](https://biopython.org/)
- [PyQt5](https://pypi.org/project/PyQt5/)
- [QtMAterial](https://pypi.org/project/qt-material/)

## 👥 Team
- ALLEMAND Fabien
- BONNAIL Julie
- COUTURE Louise
- LEBOT Samuel
- VLAYKOV Mathéo

## 👥 Logo
<p align="center">
  <img src="logo.png" />
</p>


## 📝 TO DO LIST !!!
- Julie & Louise:
    - [ ] Onglet README taille ajustable
    - [ ] Etat de l'analyse (x/y fichiers/organismes analysés)
    - [ ] Esthétique (taille du journal, couleur [application et journal], nom, onglet auteurs [file view sur README.md], logo dans la barre des tâches)
    - [ ] Documentation (code + README)

- Mathéo:
    - [ ] Tests
    - [ ] Documentation (code + README)

- Samuel & Fabien:
    - [ ] Niveaux de log
    - [ ] Arrêt du parsing
    - [ ] Fix UI *
    - [ ] Fix NC version
    - [ ] Documentation (code + README)