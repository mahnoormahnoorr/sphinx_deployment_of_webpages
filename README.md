# sphinx_deployment_of_webpages

This repository explains how to deploy a GitHub repository into a webpage using **Sphinx**.

---

## Step 0 — Install the basics on your desktop

Make sure Python and Git are installed on your system.

---

## Step 1 — Clone your repo to your desktop

```bash
cd ~/Desktop
git clone https://github.com/mahnoormahnoorr/Quantization.git
cd Quantization
```

Step 2 — Create a virtual environment + install Sphinx

```bash

python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -U pip
pip install sphinx sphinx-rtd-theme myst-parser
```

Step 3 — Create the Sphinx project inside your repo

From the repo root (Quantization/):
```bash
mkdir docs
sphinx-quickstart docs
```

When Sphinx asks questions, choose these (recommended):
- Separate source and build directories → y
- Project name → Quantization
- Author → your name
- Language → en
  
This will create something like:

```bash
docs/
  source/
  build/
  make.bat
  Makefile
```


Step 4 — Configure Sphinx (important)

Open the file:

```bash
docs/source/conf.py 
```

4.1 Add theme + Markdown support

```bash
extensions = [
    "myst_parser",
]

html_theme = "sphinx_rtd_theme"

source_suffix = {
    ".rst": "restructuredtext",
    ".md": "markdown",
}
```

4.2 Make your README show up as the homepage
Create a file: 

```bash
docs/source/index.md
```
Add the following content:

```bash

# Quantization

```{toctree}
:maxdepth: 2
:caption: Contents

readme
```
Now create `docs/source/readme.md` and copy/paste your repo `README.md` content into it.

> **Why do this?**  
> Sphinx can render Markdown using `myst-parser`, so your README becomes a nicely formatted webpage.

---

## Step 5 — Build the site locally (on your desktop)

Run:

```bash
make -C docs html
```

Your generated website will be located at:

```bash
docs/build/html/index.html
```

Open it in your browser to confirm it looks correct:

```bash
open docs/build/html/index.html
```









