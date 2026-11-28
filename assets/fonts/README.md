# Fonts

The page serves its own fonts, so a visit makes no request to a third party.
Both families are under the SIL Open Font License 1.1; the licence texts sit
beside this file.

| Family | Used for | Files | Taken from |
|---|---|---|---|
| Source Serif 4 (variable, roman and italic) | all content: names, titles, entries, prose | `source-serif-4-*.woff2` | npm `@fontsource-variable/source-serif-4` 5.3.0 — upstream [adobe-fonts/source-serif](https://github.com/adobe-fonts/source-serif) |
| Inter (variable) | the interface: navigation, years, labels | `inter-*.woff2` | npm `@fontsource-variable/inter` 5.2.8, the build SuReSuite ships — upstream [rsms/inter](https://github.com/rsms/inter) |

Each family comes in three subsets — `latin`, `latin-ext`, `vietnamese`. The
`unicode-range` lines in `index.html` let the browser download only the subsets
a page actually uses; today that is `latin` alone.
