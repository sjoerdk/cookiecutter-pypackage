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

* Uses github actions_ instead of Travis-CI for Continuous integration
* Optimized for pycharm: .idea ignored by default
* Supports only python 3.6 and higher in setup.py, dropped python 2
* Includes black formatting lib by default

.. _actions: https://github.com/features/actions
.. _Cookiecutter: https://github.com/audreyr/cookiecutter


Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/sjoerdk/cookiecutter-pypackage.git

Then:
    Follow the instructions in the original Cookiecutter_ template
