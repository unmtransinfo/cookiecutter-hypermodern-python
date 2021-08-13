UNM Translational Informatics Python Cookiecutter
=================================================

.. toctree::
   :hidden:
   :maxdepth: 1

   Quickstart <quickstart>
   guide
   contributing
   contributors
   Code of Conduct <codeofconduct>
   License <license>
   Changelog <https://github.com/unmtransinfo/cookiecutter-unmtransinfo-python/releases>

.. rst-class:: badges

.. include:: ../README.rst
   :start-after: badges-begin
   :end-before: badges-end

Cookiecutter_ template for UNM Translational Informatics Python packages
based on the `Hypermodern Python`_ article series.


Usage
-----

.. code:: console

   $ cookiecutter gh:unmtransinfo/cookiecutter-unmtransinfo-python \
     --checkout="2021.6.15"


Features
--------

.. include:: ../README.rst
   :start-after: features-begin
   :end-before: features-end


FAQ
---

  *What is this project about?*

This template implements
enable current best practices
through for Python tooling
used in the UNM Translational Informatics Division.

Our goals are:

- Focus on simplicity and minimalism
- Promote code quality through automation
- Provide reliable and repeatable processes
- Implement UNM Translational Informatics branding

The project template is centered around the following tools:

- Poetry_ for packaging and dependency management
- Nox_ for automation of checks and other development tasks
- `GitHub Actions`_ for continuous integration and delivery


.. include:: ../README.rst
   :start-after: references-begin
   :end-before: references-end

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _Poetry: https://python-poetry.org/
.. _Nox: https://nox.thea.codes/
.. _GitHub Actions: https://github.com/features/actions
