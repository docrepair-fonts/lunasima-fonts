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

Lunasima is a DocRepair font, intended to improve compliance with the ISO/IEC
29500 standard by providing fallback that minimizes text reflow in Office Open
XML documents. Lunasima is based on Noto Sans, which is an unmodulated (“sans
serif”) design.

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
