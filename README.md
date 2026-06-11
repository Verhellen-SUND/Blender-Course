<!--
  ┌─────────────────────────────────────────────────────────────────────────┐
  │  YOU ARE LOOKING AT A COURSE TEMPLATE.                                 │
  │                                                                         │
  │  1. Click the green "Use this template → Create a new repository"      │
  │     button at the top of this page on GitHub.                          │
  │  2. Name your repo something like  chem-informatics-2026                │
  │  3. Then replace every  [[ BRACKETED PLACEHOLDER ]]  in this README    │
  │     with your own course details.                                       │
  │  4. Delete this HTML comment block when you're done.                    │
  │                                                                         │
  │  Field guide → https://cpdse-edux.github.io/cpdse-teaching-github/      │
  └─────────────────────────────────────────────────────────────────────────┘
-->

# From Atoms to Animation: 3D Molecular Visualisation with Blender

> Turn molecular data from the PDB and molecular dynamics simulations into animation with blender.

**Part of [CPDSE](https://cpdse.dk) — Center for Pharmaceutical Data Science Education.**

---

## At a glance

|                      |                                          |
| -------------------- | ---------------------------------------- |
| **Level**            | PhD / Lifelong Learning   |
| **ECTS**             | Variable                     |
| **Language**         | English                  |
| **Next run**         | July 2026     (ULLA summer school)               |
| **Prerequisites**    | Basic knowledge of the PDB |
| **Teacher**          | Jonas Verhellen · Icaro A. Simon      |

---

## Learning outcomes

By the end of this course, students will be able to:

- Explain the common usecases of Blender in scientific visualisation. 
- Use the basic interface of Blender to generate images and animations.
- Use geometry nodes to procedurally generate scenes in Blender. 
- Use molecular nodes to load in and process molecular data in Blender.

---

## How to use this repository

```
.
├── README.md            You are here.
├── LICENSE              Content licence (CC BY 4.0).
├── LICENSE-code         Code licence (MIT).
├── CITATION.cff         How to cite this course.
├── CHANGELOG.md         What changed each semester.
├── slides/              Lecture PDFs, numbered in order.
├── notebooks/           Jupyter / Quarto notebooks, numbered in order.
├── data/                Small example datasets + data/README.md explaining each.
├── assignments/         Student-facing exercise briefs (Markdown).
├── solutions/           Instructor-only reference answers (often a separate repo).
└── images/              Reusable figures, diagrams, logos.
```

---

## How to run the notebooks

The easiest path, for students:

1. Open any notebook under `notebooks/` directly on GitHub to read it.
2. To run it, click the **Open in Colab** badge at the top of each notebook, or:
   ```bash
   git clone https://github.com/[[ your-org ]]/[[ your-repo ]].git
   cd [[ your-repo ]]
   pip install -r requirements.txt   # if you add a requirements file
   jupyter lab
   ```

---

## Licence

- **Teaching content** (slides, notebooks, assignments, text) — [CC BY 4.0](LICENSE).
  Free to reuse and adapt, with credit.
- **Code** (scripts, notebook code cells) — [MIT](LICENSE-code).

If your institution mandates different licences, swap them in — but keep *something*.

---

## How to cite

See [`CITATION.cff`](CITATION.cff). GitHub renders it as a "Cite this repository" button
in the right-hand sidebar.

```
[[ Your-name ]]. ([[ Year ]]). [[ Course title ]].
CPDSE — Center for Pharmaceutical Data Science Education.
https://github.com/[[ your-org ]]/[[ your-repo ]]
```

---

## Contributing / spotting an error

Students and colleagues: if you find a typo, a broken link, or an unclear
explanation, please **open an
[issue](../../issues)** — it's the fastest way to get a fix in for next year.

---

## Acknowledgements

Based on the [CPDSE course template](https://github.com/CPDSE-EDUX/cpdse-course-template).
Field guide: https://cpdse-edux.github.io/cpdse-teaching-github/
