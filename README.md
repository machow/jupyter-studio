Jupyter Studio
==============

Notes on my jupyter lab setup for data analysis.

Table of Contents
-----------------

- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Extensions](#extensions)
- [Setup Instructions](#setup-instructions)

Keyboard Shortcuts
------------------

`CMD + ,` - open shortcuts menu

![](images/shortcuts-shortcut-menu.png)

`CMD + B` - toggle sidebar

![](images/shortcuts-toggle-sidebar-1200.gif)

Extensions
----------

```shell
# Handy table of contents
jupyter labextension install @jupyterlab/toc

# Black formatter
jupyter labextension install @ryantam626/jupyterlab_code_formatter
python3 -m pip install jupyterlab_code_formatter
jupyter serverextension enable --py jupyterlab_code_formatter

# Jump to where a variable is defined
jupyter labextension install @krassowski/jupyterlab_go_to_definition

# Easy file opening
pip install jupyterlab-quickopen
jupyter labextension install @parente/jupyterlab-quickopen

# Variable inspector
jupyter labextension install @lckr/jupyterlab_variableinspector

# Git in jupyter lab
jupyter labextension install @jupyterlab/git
pip install --upgrade jupyterlab-git

# qgrid
pip install qgrid
jupyter nbextension enable --py --sys-prefix qgrid
jupyter labextension install qgrid

```

### jupyterlab-toc


Setup Instructions
------------------

Contributing
------------

Tools used for 

* Screencasts - Kap: https://github.com/wulkano/kap
* Keystroke Viz - KeyCastr: https://github.com/keycastr/keycastr

Screencasts are saved to `images` folder, using the format `{category}-{name}-{resolution}.gif`.
