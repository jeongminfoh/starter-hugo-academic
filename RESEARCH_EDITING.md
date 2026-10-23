# Updating research

Add or edit one `content/publication/<paper-slug>/index.md` file. The Research overview selects the latest journal article automatically, lists all journal articles, and includes every working paper with publication type `"3"`.

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

For a main-findings graphic on a paper's detail page, add `static/images/<paper-slug>-key-findings.svg`, preserving the exact capitalization of its content folder. The publication template automatically displays this graphic before the abstract, in preference to older artwork. Each SVG includes its own accessible title and description and scales to the page without cropping. No additional front matter is needed. Featured artwork on the Research overview still uses `research_image` from the featured paper.

Use the hurricane graphic's ivory background, forest-green text, two-panel layout and concise wording. Check each claim against the paper's results and preserve the actual outcome (for example, intentions, ratings or approval rates). Describe associations and observed patterns without implying causation, and keep the figure free of separate methodological disclaimers. Include a short study-context footer. The working-paper graphics summarize the available manuscripts; update them when findings change.
