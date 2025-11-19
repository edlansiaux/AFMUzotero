[![Using Zotero Plugin Template](https://img.shields.io/badge/Using-Zotero%20Plugin%20Template-blue?style=flat-round&logo=github)](https://github.com/windingwind/zotero-plugin-template)
[![Latest release](https://img.shields.io/github/release/edlansiaux/AFMUzotero)](edlansiaux/AFMUzotero/releases)
![Release Date](https://img.shields.io/github/release-date/edlansiaux/AFMUzotero?color=9cf)
[![License](https://img.shields.io/github/license/edlansiaux/AFMUzotero)](https://github.com/edlansiaux/AFMUzotero/blob/master/LICENSE)
![Downloads latest release](https://img.shields.io/github/downloads/edlansiaux/AFMUzotero/latest/total?color=yellow)

# Zotero package for A.F.M.U. submission

Zotero CSL package to automate citation formatting when submitting to [Annales Françaises de Médecine d'Urgence](https://www.jle.com/fr/revues/fmu/revue.phtml).

This package implements the **Vancouver format** adapted for AFMU specifications.

## Installation

1. Download the .csl file in this repository.
2. Make sure Zotero is open.
3. Go into the "Edition" menu.
4. Open Zotero preferences. Click Cite, then Styles, then the "+" button, and select the style you downloaded (a .CSL file).
5. Click "OK" in the popup to add the citation style to Zotero.

It should be added automatically!

## Usage

You need to uncheck the automatic button searching for journal abbreviations in Medline.

### Reference

Please if you use this package for research, quote it as this:

Lansiaux E. Un nouvel outil pour le formatage des citations destinées aux Annales françaises de médecine d'urgence à l'aide de Zotero. *Ann Fr Med Urgence* 2025;15:1-2. doi: 10.1684/afmu.2025.0653

### Reporting errors

If this CSL style doesn't give the expected output, first make sure that you are running the latest version of Zotero and have the most recent version of the style installed from the Zotero Style Repository. Once you have made sure that the style deviates from the style guide, instructions for authors, or published examples, report the error in the [Zotero Forums](https://www.zotero.org/forum). For your post, use the title "Style Error: [Name of style]", and give a link to, or excerpt from, the style guide that shows that the CSL style is wrong. You can also try to edit the style yourself.

Furthermore, you could contact [here](mailto:edouard.lansiaux@orange.fr) the AFMUZotero package author in order to solve it.

## Rules for the A.F.M.U. (Format Vancouver)

The bibliography is written on a separate file and includes only the references cited in the article. References are arranged in the order of appearance in the text and numbered. The bibliographic reference is made directly in the text, by the reference number in square brackets.

### Citation in text

References are cited using numbers in square brackets, e.g., [7] or [1, 3-5].

### For journal articles

**Format:** Auteurs. Titre de l'article. *Nom de la revue abrégé en italique* année;volume:pages.

**Author rules:**
- All authors if 7 or fewer
- First three authors followed by "et al." if more than 7 authors
- Format: Last name followed by initials (no space between initials)

**Example:** Riou B, Funck-Brentano C, Godeau B, Veber B. Comment éviter les revues prédatrices ? *Ann Fr Med Urgence* 2024;14:145-8.

### For book chapters

**Format:** Noms et initiales des auteurs. Titre de l'article. In: Noms et initiales des auteurs/éditeurs (eds). *Titre du livre en italique*. Ville: nom de l'éditeur, année: p. première-dernière page.

**Example:** Mettam GR, Adams LB. How to prepare an electronic version of your article. In: Jones BS, Smith RZ (eds). *Introduction to the electronic age*. New York: E-Publishing Inc, 2009: p. 281-304.

### For books

**Format:** Noms et initiales des auteurs/éditeurs. *Titre du livre en italique*. Édition. Ville: nom de l'éditeur, année.

**Example:** Strunk Jr W, White EB. *The elements of style*. 4th ed. New York: Longman, 2000.

### For Internet references

You must provide, at minimum, the complete URL and the date you last accessed the reference. All other information, if known (DOI, author names, dates, reference to a source publication, etc.) should also be mentioned.

**Example:** World Health Organization. Global tuberculosis report 2023. https://www.who.int/publications/i/item/9789240083851 Dernier accès le 15 janvier 2024.

### Important notes

- Journal names should be abbreviated and in italics
- Year only (no month or day) for journal articles
- Volume number (no issue number) followed by colon and page numbers
- Abstracts older than 3 years cannot be cited as references
