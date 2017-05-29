proteinfeatureview-jupyter
===============================

Jupyter widget to display sequences using a Protein Feature View widget

Installation
------------

To install use pip:

    $ pip install proteinfeatureview-jupyter
    $ jupyter nbextension enable --py --sys-prefix proteinfeatureview-jupyter


For a development installation (requires npm),

    $ git clone https://github.com/sbliven/proteinfeatureview-jupyter.git
    $ cd proteinfeatureview-jupyter
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix proteinfeatureview-jupyter
    $ jupyter nbextension enable --py --sys-prefix proteinfeatureview-jupyter
