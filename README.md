# What Does a Passing Regression Test Tell Us About a Solidity Repair?

Anonymous working manuscript for the ISSTA 2027 Research Papers track. The evidence cut is 23 November 2026. The paper reports historical development and case qualification. The expanded repair study awaits signed cases and assigned sessions.

## Overleaf and GitHub

Upload the supplied ZIP using **New Project → Upload Project**. Use **main.tex** as the main document, pdfLaTeX as the compiler, and BibTeX for references. For a private GitHub project, place the contents of this directory at the repository root. The same layout works when imported into Overleaf. Keep the editable sources and the accompanying ACM class license together.

## Local build

From this directory, run the following command with TeX Live and latexmk installed.

```sh
latexmk -pdf -bibtex -interaction=nonstopmode -halt-on-error -outdir=build main.tex
```

The PDF is written to build/main.pdf. Editorial records and protected study materials are kept outside this source project. The three tables contain aggregate evidence only. The bibliography is in references.bib. The bundled ACM class, bibliography style and license are documented in acm-template/SOURCE.md.

[ISSTA 2027 Research Papers](https://conf.researchr.org/track/issta-2027/issta-2027-research-papers)
