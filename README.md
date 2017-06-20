This repository is for bibliographies used in the Wong Research Group.

When we have multiple copies of a bibtex file we use `bibtool` (from `brew install bib-tool`) to merge and de-duplicate. For example, below we merge cara-main.bib and cara-main-Jake.bib into main.bib.

```
 bibtool -R -r bibtoolsettings.rsc -s -v cara-main.bib cara-main-Jake.bib -o main.bib
```
