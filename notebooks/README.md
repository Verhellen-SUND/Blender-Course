# Notebooks

Jupyter, Quarto, or R Markdown notebooks. Numbered in teaching order.

## Naming convention

```
01-getting-started.ipynb
02-data-wrangling.ipynb
03-descriptors.ipynb
```

Same rules as slides: lowercase, hyphen-separated, zero-padded, ASCII.

## Outputs

**Clear outputs before committing** — or have them re-run fresh as part of a
build. Reasons:

- Diffs stay readable. Every commit doesn't include a thousand rerender lines.
- You don't accidentally leak secrets through old output cells.
- Students get a clean run the first time.

The easiest way: install [`nbstripout`](https://github.com/kynan/nbstripout)
once, and it strips outputs on every commit automatically.

## Opening in Colab

For each notebook, add an **Open in Colab** badge to the very first Markdown
cell:

```markdown
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/[[ your-org ]]/[[ your-repo ]]/blob/main/notebooks/01-getting-started.ipynb)
```

Students click, Colab spins up a VM, notebook runs. No local setup.

---

`01-getting-started.ipynb` is an example to delete or adapt.
