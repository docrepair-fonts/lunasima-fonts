----

# Lunasima

[![][Fontbakery]](https://docrepair-fonts.github.io/lunasima-fonts/fontbakery/fontbakery-report.html)
[![][Universal]](https://docrepair-fonts.github.io/lunasima-fonts/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://docrepair-fonts.github.io/lunasima-fonts/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://docrepair-fonts.github.io/lunasima-fonts/fontbakery/fontbakery-report.html)
[![][Shaping]](https://docrepair-fonts.github.io/lunasima-fonts/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdocrepair-fonts%2Flunasima-fonts%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdocrepair-fonts%2Flunasima-fonts%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdocrepair-fonts%2Flunasima-fonts%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdocrepair-fonts%2Flunasima-fonts%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdocrepair-fonts%2Flunasima-fonts%2Fgh-pages%2Fbadges%2FUniversal.json

Lunasima is a DocRepair font intended for improving document compatibility with the ISO/IEC 29500 standard. Lunasima is based on Noto Sans, which is an unmodulated (“sans serif”) design.

## About

Office Open XML a zipped, XML-based file format developed by Microsoft for representing spreadsheets, charts, presentations and word processing documents. 
The format has been used by Microsoft Office since version 2000–2003, and was standardized by ISO and IEC as ISO/IEC 29500 in 2006. 

Various implementations that support ISO 29500 exist. Full interoperability between apps that support the standard is hampered by the fact that documents created in Microsoft Office use proprietary fonts by default. If a document is created, which uses fonts that are only available on a specific platform, and then the document is opened on another platform where the fonts are not available, the text reflows. 

The DocRepair project improves compliance with the ISO 29500 standard by providing a set of fonts that minimize the reflow of such documents.
For a variety of popular fonts, which are common in OOXML documents, the DocRepair project provides alternative fonts. Implementers can use the alternative font as a substitute if the used font is not available.

The DocRepair fonts are licensed under the SIL Open Font License version 1.1 (OFL). 

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://docrepair-fonts.github.io/lunasima-fonts.

## Changelog

**29 March 2023**
- MAJOR Initial publication

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
