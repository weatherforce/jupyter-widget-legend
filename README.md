jupyter-widget-legend
===============================

A custom legend based on this example https://leafletjs.com/examples/choropleth/

Installation
------------

To install use pip:

    $ pip install jupyter_widget_legend
    $ jupyter nbextension enable --py --sys-prefix jupyter_widget_legend

To install for jupyterlab

    $ jupyter labextension install jupyter_widget_legend

For a development installation (requires npm),

    $ git clone https://github.com/weatherforce/jupyter-widget-legend.git
    $ cd jupyter-widget-legend
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix jupyter_widget_legend
    $ jupyter nbextension enable --py --sys-prefix jupyter_widget_legend
    $ jupyter labextension install js

When actively developing your extension, build Jupyter Lab with the command:

    $ jupyter lab --watch

This take a minute or so to get started, but then allows you to hot-reload your javascript extension.
To see a change, save your javascript, watch the terminal for an update.

Note on first `jupyter lab --watch`, you may need to touch a file to get Jupyter Lab to open.

