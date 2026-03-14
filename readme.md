# Guidance: The Principles of the Lutheran Free Church

An English translation of *Deiledning — Den lutherske Frikirkes Principer* (1914), a collection of articles and essays by **Georg Sverdrup** and **Sven Oftedal**, edited by John O. Evjen and published by The Free Church Book Concern, Minneapolis, 1914.

---

## About the Book

This volume gathers writings originally published in *Folkebladet* between 1893 and 1896, during a defining controversy within Norwegian-American Lutheranism. Sverdrup and Oftedal — professors at Augsburg Seminary in Minneapolis — argued consistently for one central principle: **the local congregation, not the church body or its clergy, is the fundamental unit of the Church**.

The essays address ordination rights, pastoral independence, Inner Mission, the nature of church fellowship, and the meaning of a free church. Together they form a coherent theological and ecclesiological vision that gave shape to the Lutheran Free Church.

---

## Translation Status

| Folder    | English Title                                                        | Author        | Source / Date                        | Status    |
|-----------|----------------------------------------------------------------------|---------------|--------------------------------------|-----------|
| Text_7    | Concepts of Church Fellowship and the Union in 1890                  | Sven Oftedal  | *Folkebladet*, September 20, 1893    | ✅ Complete |
| Text_12   | On Inner Mission                                                     | Georg Sverdrup| *Folkebladet*, November 22, 1893     | ✅ Complete |
| Text_13   | Are the Pastors the "Society's" Servants?                            | Georg Sverdrup| *Folkebladet*, March 7, 1894         | ✅ Complete |
| Text_16   | Open Letter to Augsburg's Friends                                    | Georg Sverdrup| *Folkebladet*, August 8, 1894        | ✅ Complete |
| Text_19   | The Program of the Minority                                          | —             | Minneapolis Meeting, October 1894    | ✅ Complete |
| Text_21   | Augsburg and the Minority                                            | Sven Oftedal  | *Folkebladet*, July 25, 1894         | ✅ Complete |
| Text_23   | Ordination Refusal and the Constitution of the United Church         | Georg Sverdrup| *Folkebladet*, January 16, 1895      | ✅ Complete |
| Text_25   | The Congregations' Right to Call and the Refusals of Ordination      | Georg Sverdrup| *Folkebladet*, February 6, 1895      | ✅ Complete |
| Text_29   | Lutherdom and Church Polity                                          | Georg Sverdrup| *Folkebladet*, September 30, 1896    | ✅ Complete |
| Text_31   | The Free Church and the Congregation                                 | —             | —                                    | 🔄 Pending |
| Text_36   | The Visible Congregation                                             | —             | —                                    | 🔄 Pending |
| Text_39   | The Lutheran Free Church                                             | —             | —                                    | 🔄 Pending |

---

## Repository Structure

Each `Text_XX` folder contains:

- `Norwegian.txt` — original Norwegian source text
- `Hazard.txt` — reference / working translation draft
- `Text_XX.tex` — final LaTeX translation (when complete)
- `FIXME.md` — notes on outstanding issues (where present)

The master LaTeX file `WORKFLOW.tex` compiles all completed sections into a single typeset document.

---

## Building the PDF

With a standard LaTeX distribution installed (e.g., TeX Live or MiKTeX):

```bash
pdflatex WORKFLOW.tex
```

The compiled PDF will be output as `WORKFLOW.pdf`.

---

## Authors

**Georg Sverdrup** (1848–1907) was a Norwegian-American theologian and president of Augsburg Seminary. He is regarded as the principal architect of the free-congregation principle in Norwegian-American Lutheranism.

**Sven Oftedal** (1844–1911) was a professor at Augsburg Seminary and a close collaborator of Sverdrup in the movement for congregational freedom.

---

## License

This translation is in the public domain. The original 1914 Norwegian text is likewise in the public domain.