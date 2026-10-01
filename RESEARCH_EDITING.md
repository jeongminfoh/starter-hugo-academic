# Updating research

Add or edit one `content/publication/<paper-slug>/index.md` file. The Research overview selects the latest journal article automatically, lists the six newest articles, and includes every working paper. Older articles remain in All publications.

```yaml
---
title: "Full paper title"
date: 2026-10-01
authors: ["Surname, A.", "oh_j", "Surname, B."]
publication_types: ["2"]
publication: "*Journal name*, *Accepted*"
doi: "10.xxxx/example"
abstract: "Paper abstract"
---
```

- Use `"2"` for journal articles and `"3"` for working papers. Keep the actual review/publication status in `publication`.
- Coauthor names can be entered directly. No author profile files are required. Use `oh_j` to retain Jeongmin's existing highlighted name.
- Enter a bare DOI, without `https://doi.org/`.
- Optional artwork belongs to its paper: add `research_image: /images/example.png` and a descriptive `research_image_alt`. Put the image in `static/images/`. A newer paper without artwork gets a text-only feature; it never inherits an unrelated older illustration.
- Omit an unknown date; the interface will not display the year 0001.
- The early-stage project text remains in `content/research/workinprogress.md`.

The election cybersecurity artwork is a generated conceptual illustration of the paper's subject, not a figure or empirical finding from the paper.
