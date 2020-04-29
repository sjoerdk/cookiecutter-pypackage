======================
Cookiecutter PyPackage
======================

.. image:: https://pyup.io/repos/github/sjoerdk/cookiecutter-pypackage/shield.svg
     :target: https://pyup.io/repos/github/sjoerdk/cookiecutter-pypackage/
     :alt: Updates

.. image:: https://travis-ci.org/sjoerdk/cookiecutter-pypackage.svg?branch=master
    :target: https://travis-ci.org/sjoerdk/cookiecutter-pypackage

Fork of audryr's Cookiecutter_ template for a Python package. Uses github actions.

* GitHub repo: https://github.com/sjoerdk/cookiecutter-pypackage/
* Free software: BSD license

Features
--------

Differences with original Cookiecutter_ template:

* Uses github actions_ instead of Travis-CI for Continuous integration (has default github build workflow)
* Optimized for pycharm: .idea ignored by default
* Supports only python 3.6 and higher in setup.py, dropped python 2
* Includes black formatting lib by default
* Includes tests/.__init__ BASE_PATH and RESOURCE_PATH so you can use ``from tests import RESOURCES_PATH``
* Uses factory-boy_ by default if you use pytest. Because its just so useful.

.. _actions: https://github.com/features/actions
.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _factory-boy: https://factoryboy.readthedocs.io

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/sjoerdk/cookiecutter-pypackage.git


If you are deploying to pypi::

    * Push your project to pypi once (see https://packaging.python.org/tutorials/packaging-projects/)
    * Generate an API key for your project on https://pypi.org/
    * Save this API key in your github secrets under key `pypi_password`

    This will push each tagged commit to pypi

Then:
    Follow the instructions in the original Cookiecutter_ template
