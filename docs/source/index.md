Last login: Tue Feb  3 15:54:40 on ttys000
mmahnoor@apro13-76JFJ4C ~ % cd Desktop 
mmahnoor@apro13-76JFJ4C Desktop % cd quant
mmahnoor@apro13-76JFJ4C quant % ls
Quantization			llm-inference-using-aitta
mmahnoor@apro13-76JFJ4C quant % cd Quantization 
mmahnoor@apro13-76JFJ4C Quantization % ls
AWQ		BitsAndBytes	GPTQ		README.md	docs
mmahnoor@apro13-76JFJ4C Quantization % open docs/build/html/index.html
mmahnoor@apro13-76JFJ4C Quantization % ls
AWQ		BitsAndBytes	GPTQ		README.md	docs
mmahnoor@apro13-76JFJ4C Quantization % cd docs 
mmahnoor@apro13-76JFJ4C docs % ls
Makefile	build		make.bat	source
mmahnoor@apro13-76JFJ4C docs % cd source 
mmahnoor@apro13-76JFJ4C source % ls
AWQ.md		GPTQ		_static		conf.py		index.rst
BitsAndBytes.md	GPTQ.md		_templates	index.md	readme.md
mmahnoor@apro13-76JFJ4C source % cd index.md 
cd: not a directory: index.md
mmahnoor@apro13-76JFJ4C source % nano index.md 
mmahnoor@apro13-76JFJ4C source % cd ..
mmahnoor@apro13-76JFJ4C docs % cd ..
mmahnoor@apro13-76JFJ4C Quantization % cd ..
mmahnoor@apro13-76JFJ4C quant % mkdir test
mmahnoor@apro13-76JFJ4C quant % cd test
mmahnoor@apro13-76JFJ4C test % python -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
pip install sphinx sphinx-rtd-theme myst-parser
zsh: command not found: python
source: no such file or directory: .venv/bin/activate
zsh: command not found: python
zsh: command not found: pip
mmahnoor@apro13-76JFJ4C test % python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -U pip
pip install sphinx sphinx-rtd-theme myst-parser
Requirement already satisfied: pip in ./.venv/lib/python3.9/site-packages (21.2.4)
Collecting pip
  Using cached pip-26.0-py3-none-any.whl (1.8 MB)
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 21.2.4
    Uninstalling pip-21.2.4:
      Successfully uninstalled pip-21.2.4
Successfully installed pip-26.0
Collecting sphinx
  Using cached sphinx-7.4.7-py3-none-any.whl.metadata (6.1 kB)
Collecting sphinx-rtd-theme
  Using cached sphinx_rtd_theme-3.1.0-py2.py3-none-any.whl.metadata (4.5 kB)
Collecting myst-parser
  Using cached myst_parser-3.0.1-py3-none-any.whl.metadata (5.5 kB)
Collecting sphinxcontrib-applehelp (from sphinx)
  Using cached sphinxcontrib_applehelp-2.0.0-py3-none-any.whl.metadata (2.3 kB)
Collecting sphinxcontrib-devhelp (from sphinx)
  Using cached sphinxcontrib_devhelp-2.0.0-py3-none-any.whl.metadata (2.3 kB)
Collecting sphinxcontrib-jsmath (from sphinx)
  Using cached sphinxcontrib_jsmath-1.0.1-py2.py3-none-any.whl.metadata (1.4 kB)
Collecting sphinxcontrib-htmlhelp>=2.0.0 (from sphinx)
  Using cached sphinxcontrib_htmlhelp-2.1.0-py3-none-any.whl.metadata (2.3 kB)
Collecting sphinxcontrib-serializinghtml>=1.1.9 (from sphinx)
  Using cached sphinxcontrib_serializinghtml-2.0.0-py3-none-any.whl.metadata (2.4 kB)
Collecting sphinxcontrib-qthelp (from sphinx)
  Using cached sphinxcontrib_qthelp-2.0.0-py3-none-any.whl.metadata (2.3 kB)
Collecting Jinja2>=3.1 (from sphinx)
  Using cached jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting Pygments>=2.17 (from sphinx)
  Using cached pygments-2.19.2-py3-none-any.whl.metadata (2.5 kB)
Collecting docutils<0.22,>=0.20 (from sphinx)
  Using cached docutils-0.21.2-py3-none-any.whl.metadata (2.8 kB)
Collecting snowballstemmer>=2.2 (from sphinx)
  Using cached snowballstemmer-3.0.1-py3-none-any.whl.metadata (7.9 kB)
Collecting babel>=2.13 (from sphinx)
  Using cached babel-2.18.0-py3-none-any.whl.metadata (2.2 kB)
Collecting alabaster~=0.7.14 (from sphinx)
  Using cached alabaster-0.7.16-py3-none-any.whl.metadata (2.9 kB)
Collecting imagesize>=1.3 (from sphinx)
  Using cached imagesize-1.4.1-py2.py3-none-any.whl.metadata (1.5 kB)
Collecting requests>=2.30.0 (from sphinx)
  Using cached requests-2.32.5-py3-none-any.whl.metadata (4.9 kB)
Collecting packaging>=23.0 (from sphinx)
  Using cached packaging-26.0-py3-none-any.whl.metadata (3.3 kB)
Collecting importlib-metadata>=6.0 (from sphinx)
  Using cached importlib_metadata-8.7.1-py3-none-any.whl.metadata (4.7 kB)
Collecting tomli>=2 (from sphinx)
  Using cached tomli-2.4.0-py3-none-any.whl.metadata (10 kB)
Collecting sphinxcontrib-jquery<5,>=4 (from sphinx-rtd-theme)
  Using cached sphinxcontrib_jquery-4.1-py2.py3-none-any.whl.metadata (2.6 kB)
Collecting markdown-it-py~=3.0 (from myst-parser)
  Using cached markdown_it_py-3.0.0-py3-none-any.whl.metadata (6.9 kB)
Collecting mdit-py-plugins~=0.4 (from myst-parser)
  Using cached mdit_py_plugins-0.4.2-py3-none-any.whl.metadata (2.8 kB)
Collecting pyyaml (from myst-parser)
  Using cached pyyaml-6.0.3-cp39-cp39-macosx_11_0_arm64.whl.metadata (2.4 kB)
Collecting mdurl~=0.1 (from markdown-it-py~=3.0->myst-parser)
  Using cached mdurl-0.1.2-py3-none-any.whl.metadata (1.6 kB)
Collecting zipp>=3.20 (from importlib-metadata>=6.0->sphinx)
  Using cached zipp-3.23.0-py3-none-any.whl.metadata (3.6 kB)
Collecting MarkupSafe>=2.0 (from Jinja2>=3.1->sphinx)
  Using cached markupsafe-3.0.3-cp39-cp39-macosx_11_0_arm64.whl.metadata (2.7 kB)
Collecting charset_normalizer<4,>=2 (from requests>=2.30.0->sphinx)
  Using cached charset_normalizer-3.4.4-cp39-cp39-macosx_10_9_universal2.whl.metadata (37 kB)
Collecting idna<4,>=2.5 (from requests>=2.30.0->sphinx)
  Using cached idna-3.11-py3-none-any.whl.metadata (8.4 kB)
Collecting urllib3<3,>=1.21.1 (from requests>=2.30.0->sphinx)
  Using cached urllib3-2.6.3-py3-none-any.whl.metadata (6.9 kB)
Collecting certifi>=2017.4.17 (from requests>=2.30.0->sphinx)
  Using cached certifi-2026.1.4-py3-none-any.whl.metadata (2.5 kB)
Using cached sphinx-7.4.7-py3-none-any.whl (3.4 MB)
Using cached alabaster-0.7.16-py3-none-any.whl (13 kB)
Using cached docutils-0.21.2-py3-none-any.whl (587 kB)
Using cached sphinx_rtd_theme-3.1.0-py2.py3-none-any.whl (7.7 MB)
Using cached sphinxcontrib_jquery-4.1-py2.py3-none-any.whl (121 kB)
Using cached myst_parser-3.0.1-py3-none-any.whl (83 kB)
Using cached markdown_it_py-3.0.0-py3-none-any.whl (87 kB)
Using cached mdit_py_plugins-0.4.2-py3-none-any.whl (55 kB)
Using cached mdurl-0.1.2-py3-none-any.whl (10.0 kB)
Using cached babel-2.18.0-py3-none-any.whl (10.2 MB)
Using cached imagesize-1.4.1-py2.py3-none-any.whl (8.8 kB)
Using cached importlib_metadata-8.7.1-py3-none-any.whl (27 kB)
Using cached jinja2-3.1.6-py3-none-any.whl (134 kB)
Using cached markupsafe-3.0.3-cp39-cp39-macosx_11_0_arm64.whl (12 kB)
Using cached packaging-26.0-py3-none-any.whl (74 kB)
Using cached pygments-2.19.2-py3-none-any.whl (1.2 MB)
Using cached requests-2.32.5-py3-none-any.whl (64 kB)
Using cached charset_normalizer-3.4.4-cp39-cp39-macosx_10_9_universal2.whl (209 kB)
Using cached idna-3.11-py3-none-any.whl (71 kB)
Using cached urllib3-2.6.3-py3-none-any.whl (131 kB)
Using cached certifi-2026.1.4-py3-none-any.whl (152 kB)
Using cached snowballstemmer-3.0.1-py3-none-any.whl (103 kB)
Using cached sphinxcontrib_htmlhelp-2.1.0-py3-none-any.whl (98 kB)
Using cached sphinxcontrib_serializinghtml-2.0.0-py3-none-any.whl (92 kB)
Using cached tomli-2.4.0-py3-none-any.whl (14 kB)
Using cached zipp-3.23.0-py3-none-any.whl (10 kB)
Using cached pyyaml-6.0.3-cp39-cp39-macosx_11_0_arm64.whl (174 kB)
Using cached sphinxcontrib_applehelp-2.0.0-py3-none-any.whl (119 kB)
Using cached sphinxcontrib_devhelp-2.0.0-py3-none-any.whl (82 kB)
Using cached sphinxcontrib_jsmath-1.0.1-py2.py3-none-any.whl (5.1 kB)
Using cached sphinxcontrib_qthelp-2.0.0-py3-none-any.whl (88 kB)
Installing collected packages: zipp, urllib3, tomli, sphinxcontrib-serializinghtml, sphinxcontrib-qthelp, sphinxcontrib-jsmath, sphinxcontrib-htmlhelp, sphinxcontrib-devhelp, sphinxcontrib-applehelp, snowballstemmer, pyyaml, Pygments, packaging, mdurl, MarkupSafe, imagesize, idna, docutils, charset_normalizer, certifi, babel, alabaster, requests, markdown-it-py, Jinja2, importlib-metadata, sphinx, mdit-py-plugins, sphinxcontrib-jquery, myst-parser, sphinx-rtd-theme
Successfully installed Jinja2-3.1.6 MarkupSafe-3.0.3 Pygments-2.19.2 alabaster-0.7.16 babel-2.18.0 certifi-2026.1.4 charset_normalizer-3.4.4 docutils-0.21.2 idna-3.11 imagesize-1.4.1 importlib-metadata-8.7.1 markdown-it-py-3.0.0 mdit-py-plugins-0.4.2 mdurl-0.1.2 myst-parser-3.0.1 packaging-26.0 pyyaml-6.0.3 requests-2.32.5 snowballstemmer-3.0.1 sphinx-7.4.7 sphinx-rtd-theme-3.1.0 sphinxcontrib-applehelp-2.0.0 sphinxcontrib-devhelp-2.0.0 sphinxcontrib-htmlhelp-2.1.0 sphinxcontrib-jquery-4.1 sphinxcontrib-jsmath-1.0.1 sphinxcontrib-qthelp-2.0.0 sphinxcontrib-serializinghtml-2.0.0 tomli-2.4.0 urllib3-2.6.3 zipp-3.23.0
(.venv) mmahnoor@apro13-76JFJ4C test % ls
(.venv) mmahnoor@apro13-76JFJ4C test % mkdir docs
sphinx-quickstart docs
Welcome to the Sphinx 7.4.7 quickstart utility.

Please enter values for the following settings (just press Enter to
accept a default value, if one is given in brackets).

Selected root path: docs

You have two options for placing the build directory for Sphinx output.
Either, you use a directory "_build" within the root path, or you separate
"source" and "build" directories within the root path.
> Separate source and build directories (y/n) [n]: y

The project name will occur in several places in the built documentation.
> Project name: mahh
> Author name(s): mahnoor
> Project release []: jj

If the documents are to be written in a language other than English,
you can select a language here by its language code. Sphinx will then
translate text that it generates into that language.

For a list of supported codes, see
https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language.
> Project language [en]: en

Creating file /Users/mmahnoor/Desktop/quant/test/docs/source/conf.py.
Creating file /Users/mmahnoor/Desktop/quant/test/docs/source/index.rst.
Creating file /Users/mmahnoor/Desktop/quant/test/docs/Makefile.
Creating file /Users/mmahnoor/Desktop/quant/test/docs/make.bat.

Finished: An initial directory structure has been created.

You should now populate your master file /Users/mmahnoor/Desktop/quant/test/docs/source/index.rst and create other documentation
source files. Use the Makefile to build the docs, like so:
   make builder
where "builder" is one of the supported builders, e.g. html, latex or linkcheck.

(.venv) mmahnoor@apro13-76JFJ4C test % ls
docs
(.venv) mmahnoor@apro13-76JFJ4C test % cd docs 
(.venv) mmahnoor@apro13-76JFJ4C docs % ls
Makefile	build		make.bat	source
(.venv) mmahnoor@apro13-76JFJ4C docs % cd build 
(.venv) mmahnoor@apro13-76JFJ4C build % ls
(.venv) mmahnoor@apro13-76JFJ4C build % cd ..
(.venv) mmahnoor@apro13-76JFJ4C docs % cd ..
(.venv) mmahnoor@apro13-76JFJ4C test % cd ..
(.venv) mmahnoor@apro13-76JFJ4C quant % cd Quantization 
(.venv) mmahnoor@apro13-76JFJ4C Quantization % cd docs 
(.venv) mmahnoor@apro13-76JFJ4C docs % cd source 
(.venv) mmahnoor@apro13-76JFJ4C source % ls
AWQ.md		GPTQ		_static		conf.py		index.rst
BitsAndBytes.md	GPTQ.md		_templates	index.md	readme.md
(.venv) mmahnoor@apro13-76JFJ4C source % nano index.md 

  UW PICO 5.09                              File: index.md                                 

# Quantization


This repository explores **quantization methods for Large Language Models (LLMs)**.
Quantization is a key technique for reducing model size and inference cost, enabling LLMs $

We provide examples and experiments for:

- **[BitsAndBytes (bnb)](https://github.com/mahnoormahnoorr/Quantization/tree/main/bitsand$
- **[AWQ (Activation-aware Weight Quantization)](https://github.com/mahnoormahnoorr/Quanti$
- **[GPTQ (Gradient Post-training Quantization)](https://github.com/mahnoormahnoorr/Quanti$

---

## 📖 What to Expect in This Repo

1. **Implementation Examples**
   - Scripts for loading, quantizing, and saving models.
   - Examples include small models (for example; `facebook/opt-125m`) so you can try thing$

2. **Benchmarks**
   - Inference time comparisons before and after quantization.
   - Model size reduction (disk footprint in MB).


3. **Guides & Utilities**
   - Helper functions for measuring model size, timing inference, and testing the quantize$
   - Notes on how to run the examples on Puhti, Mahti and LUMI.




---

```{toctree}
---
maxdepth: 1
caption: Contents
---

GPTQ.md
AWQ.md
BitsAndBytes.md




```

## See also


[LUMI Documentation](https://docs.lumi-supercomputer.eu/)

## Credits

![](img/eurocc.svg)
![](img/coderefinery.svg)

This project has received funding from the European High-Performance Computing
Joint Undertaking (JU) under grant agreement No 101101903.

The lesson file structure and browsing layout is inspired by and derived from
[work](https://github.com/coderefinery/sphinx-lesson) by [CodeRefinery](https://coderefine$
[MIT license](https://opensource.org/licenses/mit-license.html). We have copied and adapted
most of their license text.

### Instructional Material

This instructional material is made available under the
[Creative Commons Attribution license (CC-BY-4.0)](https://creativecommons.org/licenses/by$
The following is a human-readable summary of (and not a substitute for) the
[full legal text of the CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/leg$
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit, provide a
  [link to the license](https://creativecommons.org/licenses/by/4.0/), and indicate if cha$
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.


^G Get Help    ^O WriteOut    ^R Read File   ^Y Prev Pg     ^K Cut Text    ^C Cur Pos     
^X Exit        ^J Justify     ^W Where is    ^V Next Pg     ^U UnCut Text  ^T To Spell    
