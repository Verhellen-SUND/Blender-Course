# Data

Every file in this folder must appear in the table below — with its source,
licence, and column definitions. **Undocumented data is not FAIR.**

If you can't easily fill a row, you don't understand the dataset well enough
to teach from it. That's useful to notice.

## Datasets

| File          | Source                                            | Licence    | Rows | Key columns                                   |
| ------------- | ------------------------------------------------- | ---------- | ---- | --------------------------------------------- |
| `example.csv` | Synthetic, generated for this course              | CC0        | 10   | `id`, `compound`, `ic50_nM`, `assay`          |

---

## example.csv

A toy table of ten fictional compounds with IC50 values. Used by
[`notebooks/01-getting-started.ipynb`](../notebooks/01-getting-started.ipynb)
to demonstrate the toolchain.

**None of these IC50 values are real.** Do not cite this file.

### Columns

| Column     | Type   | Unit | Description                                                    |
| ---------- | ------ | ---- | -------------------------------------------------------------- |
| `id`       | string |  —   | Stable row identifier (`CPD-001`, `CPD-002`, …).               |
| `compound` | string |  —   | Fictional compound short name.                                 |
| `ic50_nM`  | float  |  nM  | Half-maximal inhibitory concentration.                         |
| `assay`    | string |  —   | Assay code (`A1` cell-based, `B2` biochemical).                |

---

## Large datasets

**GitHub is not for multi-gigabyte data.** The hard cap is 100 MB per file,
and even 50 MB is heavy. Instead:

1. Upload the dataset to [Zenodo](https://zenodo.org), your institution's
   repository, or a public database (PubChem, ChEMBL, UniProt, …).
2. Get a DOI or stable URL.
3. Record it here, in the table above.
4. Add loader code to the notebook that fetches it:

```python
import pandas as pd
url = "https://zenodo.org/record/XXXXX/files/my-dataset.csv"
df = pd.read_csv(url)
```

*A course that links to canonical data is more FAIR than one that bundles it.*
