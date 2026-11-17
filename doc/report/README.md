# Project reports

| Folder | Content |
| --- | --- |
| `latex_template/` | Analysis report (September), with its figures |
| `final_report/` | Final report: `main.tex` and one file per section in `sections/` |
| `img/` | Diagrams shared by the reports |

The final report reuses the figures of the analysis report (`\graphicspath` in `main.tex`).

## Build the final report

From `doc/report/final_report`:

```bash
pdflatex main.tex
pdflatex main.tex
```

(Run it twice so that the table of contents and the references are filled.) On Overleaf, upload
the whole `doc/report` folder and set `final_report/main.tex` as the main document.

## Still to do before submitting

- [ ] Each member writes their individual assessment (`sections/08_appendices.tex`)
- [ ] Proofread, and check the planning figures against what really happened
