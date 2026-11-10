# Evidence-graded power rankings of fictional characters

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CSAyush/tidytuesday-fiction/main)

A [TidyTuesday](https://github.com/rfordatascience/tidytuesday) project using the
[2026-11-10 dataset](https://github.com/rfordatascience/tidytuesday/blob/main/data/2026/2026-11-10/readme.md):
power rankings of characters across 21 franchises from [Cited Feats](https://citedfeats.com),
where every placement is backed by citations graded **shown**, **stated** or **scaled**.

## Questions

| Notebook | Question | Author |
|---|---|---|
| [`q1-stated-evidence.ipynb`](q1-stated-evidence.ipynb) | Which franchises lean most on "stated" evidence, and does it depend on the medium? | |
| [`q5-upsets.ipynb`](q5-upsets.ipynb) | How often does a lower-ranked character kill a higher-ranked one (an "upset")? | |

## Data

The CSVs in [`data/`](data/) are copied unchanged from TidyTuesday. See
[`data/readme.md`](data/readme.md) for the data dictionary. Data from Cited Feats,
licensed CC BY 4.0.

## Running locally

```bash
pip install -r requirements.txt jupyterlab
jupyter lab
```

Or click the Binder badge above to run the notebooks in your browser.
