========
canaries
========

Python library for choosing and loading dynamic library files compatible with the operating environment.

|pypi| |travis| |coveralls|

.. |pypi| image:: https://badge.fury.io/py/canaries.svg
   :target: https://badge.fury.io/py/canaries
   :alt: PyPI version and link.

.. |travis| image:: https://travis-ci.com/reity/canaries.svg?branch=master
    :target: https://travis-ci.com/reity/canaries

.. |coveralls| image:: https://coveralls.io/repos/github/reity/canaries/badge.svg?branch=master
   :target: https://coveralls.io/github/reity/canaries?branch=master

Purpose
-------
This tool can be used to automatically choose and load a dynamic library file that is compatible with the current operating environment.

Package Installation and Usage
------------------------------
The package is available on PyPI::

    python -m pip install canaries

The library can be imported in the usual way::

    import canaries
    from canaries import canaries

Testing and Conventions
-----------------------
All unit tests are executed and their coverage is measured when using `nose <https://nose.readthedocs.io/>`_ (see ``setup.cfg`` for configution details)::

    nosetests

Style conventions are enforced using `Pylint <https://www.pylint.org/>`_::

    pylint canaries

Contributions
-------------
In order to contribute to the source code, open an issue or submit a pull request on the GitHub page for this library.

Versioning
----------
The version number format for this library and the changes to the library associated with version number increments conform with `Semantic Versioning 2.0.0 <https://semver.org/#semantic-versioning-200>`_.
