.. {{ cookiecutter.hyphenated }} documentation master file, created by
   sphinx-quickstart.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

{{ cookiecutter.hyphenated }}: {{ cookiecutter.description }}
{% for char in cookiecutter.hyphenated %}={% endfor %}=={% for char in cookiecutter.description %}={% endfor %}

.. toctree::
    :maxdepth: 2
    :caption: Contents:

    api


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
