[![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](<https://vu-intropython.github.io/TAs-Material/intro.html>)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/VU-IntroPython/TAs-Material.git/master)

## Compile the workbook locally:
* You must use Python 3.8; I tested with Python 3.9 and it doesn't work.
* Install `pip install -U jupyter-book`

To compile the project you must run the following commands (assuming you're at the root of the repo):

`jupyter-book build workbook`

_Note_: The book's content is inside `workbook/notebooks`. To add a new notebook to the book, you must place the notebook inside this folder, and you **must** include it in the table of contents (`workbook/_toc.yml`).

