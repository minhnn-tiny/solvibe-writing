# What Does a Passing Regression Test Tell Us About a Solidity Repair?

This is the first anonymous research-paper draft for ISSTA 2027. It contains observed development and case-construction results and a prospective design for the expanded repair experiment. The main experiment and human admissions are pending.

## Open in Overleaf

Choose **New Project → Upload Project** and select the source ZIP. Set **main.tex** as the main document and select **pdfLaTeX** if prompted. Recompile. The project uses BibTeX and its bibliography is included. [Overleaf upload instructions](https://docs.overleaf.com/managing-projects-and-files/uploading-a-project)

## Use with GitHub

Unzip the project and place its **contents** at the root of a private manuscript repository, so that `main.tex`, `sections/` and `references.bib` sit at the top level. With GitHub synchronization available on your Overleaf plan, link your GitHub account and choose **New Project → Import from GitHub**. ZIP upload also works independently of GitHub synchronization. Use an anonymous artifact or anonymous supplementary upload for double-anonymous review. [Overleaf GitHub synchronization](https://docs.overleaf.com/integrations-and-add-ons/git-integration-and-github-synchronization/github-synchronization)

## Build locally

Use a TeX Live installation with the ACM fonts, pdfLaTeX, BibTeX and latexmk.

```sh
latexmk -pdf -bibtex -interaction=nonstopmode -halt-on-error -file-line-error -outdir=build main.tex
```

The output is `build/main.pdf`. The manuscript uses the conference’s single-column `acmsmall,screen,review,anonymous` options. The class, reference style, source provenance, sample and license are included. The editable text lives in `sections/`. Reviewers should open `main.tex` at the project root. [ISSTA author instructions](https://conf.researchr.org/track/issta-2027/issta-2027-research-papers) · [ACM template provenance](acm-template/SOURCE.md)
