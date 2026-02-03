# sphinx_deployment_of_webpages

This repo explain how to deploy a github repo into webpahe throug sphinx. 

Step 0 — Install the basics on your desktop

Step 1 — Clone your repo to your desktop
cd ~/Desktop
git clone https://github.com/mahnoormahnoorr/Quantization.git
cd Quantization

Step 2 — Create a virtual environment + install Sphinx

macOS / Linux
python -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
pip install sphinx sphinx-rtd-theme myst-parser

Step 3 — Create the Sphinx project inside your repo
From the repo root (Quantization/):
mkdir docs
sphinx-quickstart docs

When Sphinx asks questions, choose these (recommended):
Separate source and build directories → y
Project name → Quantization
Author → your name
Language → en
This will create something like:
docs/
  source/
  build/
  make.bat
  Makefile


Step 4 — Configure Sphinx (important)
Open: docs/source/conf.py and edit/add these lines.
4.1 Add theme + Markdown support

Demo: extensions = [
    "myst_parser",
]

html_theme = "sphinx_rtd_theme"

source_suffix = {
    ".rst": "restructuredtext",
    ".md": "markdown",
}

4.2 Make your README show up as the homepage
Create a file: docs/source/index.md

Demo: 

# Quantization

```{toctree}
:maxdepth: 2
:caption: Contents

readme
```
Now create `docs/source/readme.md` and copy/paste your repo `README.md` content into it.

> Why do this? Sphinx can render Markdown via `myst-parser`, so your README becomes a nice website page.

---

## Step 5 — Build the site locally (on your desktop)

make -C docs html

Your generated website will be here:
docs/build/html/index.html
Open that index.html in your browser to confirm it looks right.

Run:
open docs/build/html/index.html









