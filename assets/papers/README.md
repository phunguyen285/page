# Papers (downloadable PDFs)

Drop a paper's PDF in this folder, then point a publication entry at it from
`cv-data/ref.bib` using a `pdf` field. The website turns that into a
**"PDF ↓"** download button next to the entry.

Example (a working paper under review):

```bibtex
@misc{Working3,
    title={Your Paper Title.},
    author={\textbf{Nguyen, P.} and Co-Author, A.},
    howpublished={Under Review},
    year={n.d.},
    pdf={assets/papers/your-paper.pdf},
    keywords={R}
}
```

Notes:
- `pdf={...}` is read only by the website (`index.html`); it is ignored by the
  CV generator, so it is always safe to add.
- The `pdf` field works on **any** entry type, not just working papers.
- Use a relative path from the site root, e.g. `assets/papers/your-paper.pdf`.
