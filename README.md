# A path to better science through co-creation and open infrastructure
#### Commentaries for AGU Earth and Space Science published using Notebooks Now!
[![Made with MyST](https://img.shields.io/badge/made%20with-myst-orange)](https://mystmd.org)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Notebooks-Now/submission-myst-full/HEAD?labpath=notebooks/data-screening.ipynb)

**Summary:** Proprietary development solutions are often perceived as being delivered more quickly and easily than open methods, fueling the misconception that they inherently produce better overall outcomes. However, we argue that open development practices can lead to both efficient and maximally impactful outcomes and that one successful strategy for accelerating open approaches in the geosciences is co-creation. This collaborative flywheel dynamic -- pioneered in the geosciences by the Pangeo project -- encourages teamwork, standardizes access to shared infrastructure, and facilitates iterations of stakeholder feedback and development to accelerate solution finding.

## Notebooks Now! Submission Template

This submission template was used to create this markdown-based publication.

### Source files

The primary source file for this template is a MyST markdown article (`article.md`). 

### Supplementary images

Images for figures and banner are specified in `images/` directory.

### Bibliography

Bibliography entries are specified by convention in the file `references.bib`.

### MyST configuration

A `myst.yml` file is provided to configure notebook metadata and exports based on [mystmd frontmatter](https://mystmd.org/guide/frontmatter). The book produced and build time is laid out based on _toc.yml, though because this book only has one document, it really isn't needed.

### Building output artifacts

To build PDF/JATS output from your source data, you must have the MyST Markdown CLI installed

```bash
npm install -g mystmd
```

Then build all exports defined in the `myst.yml` file:

```bash
myst build --all
```

#### Please provide feedback via GitHub issues if you find any errors in this repo.