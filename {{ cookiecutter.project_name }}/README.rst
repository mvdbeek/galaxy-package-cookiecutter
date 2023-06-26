
.. image:: https://badge.fury.io/py/{{ cookiecutter.project_name }}.svg
   :target: https://pypi.org/project/{{ cookiecutter.project_name }}/



Overview
--------

Scripts to create new Galaxy_ releases.

* Code: https://github.com/galaxyproject/{{ cookiecutter.project_name }}

.. _Galaxy: http://galaxyproject.org/

Development
-----------

Tests can be executed with `tox`.

Release Checklist
-----------------

* Update HISTORY.rst
* Update version number in setup.cfg
* Run `make dist`
* Tag a new version and create a release from the GitHub interface
