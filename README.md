# STAT163 — Week 7 notebook: joining tables

One notebook, `01-joining-tables.ipynb`, in two halves: Parts 1 to 5 before the lecture
(about 50 minutes) and Parts 6 to 8 before the practice (about 20 minutes).

## Run it with nothing to install

[![Open the notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week7-pre-lecture/blob/main/01-joining-tables.ipynb) `01-joining-tables.ipynb`

**What Colab is.** Google Colab is a Jupyter notebook that runs in your browser, on a
computer at Google, instead of on your laptop. The cells, the order you run them in, and
pandas all work the way they do in a notebook on your laptop.

Two differences from a notebook on your laptop:

- **The computer at Google is temporary.** When you close the tab, it is gone. The notebook
  file in this repository does not change. To keep
  your edits, use **File → Save a copy in Drive**.
- **You cannot open the files on your laptop from it.** Here that does not matter: the
  notebook reads its data from this repository on the web.

## Or run it on your machine

You need [`uv`](https://docs.astral.sh/uv/) and [Git](https://git-scm.com/downloads).

```bash
git clone https://github.com/stat163-2026t1/week7-pre-lecture.git
cd week7-pre-lecture
uv sync
```

Then open the notebook in [Positron](https://positron.posit.co/) and, when it asks which
Python to use, choose the one inside `.venv`. Or run `uv run jupyter lab`.
