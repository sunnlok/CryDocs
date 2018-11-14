Contributing to the Documentation
=================================

This page contains all relevant Information for contributing to this Documentation.

Github
------
The Source for this Documentation is hosted on `Github <https://github.com/sunnlok/CryDocs>`__ to allow easy collaboration via a standardized `Git Workflow <https://git-scm.com/>`__.

Reporting an Issue
^^^^^^^^^^^^^^^^^^
If you don't want to write whole articles or changes yourself, you can also submit Issues via the `Github Interface <https://github.com/sunnlok/CryDocs/issues>`__ to raise awareness about problems with the documentation,
or just to suggest new topics that should be covered. 


Making a Pull Request
^^^^^^^^^^^^^^^^^^^^^
If you want to directly contribute to the Documentation, you can do so via standard Github Pull Requests.

To do so, simply `fork the CryDocs repository <https://help.github.com/articles/fork-a-repo/>`__ and commit your changes to a new Branch.
Then you can submit a new `Pull Request <https://help.github.com/articles/about-pull-requests/>`__ to the main Repository and your changes will be evaluated.
Once your Pull Request has been approved, your name will be added to the List of contributors.


reStructuredText and Sphinx
---------------------------
This Documentation is written in reStructuredText and uses the Sphinx Tool to generate a viewable Html, Pdf or Epub version.
The syntax is similar to `Markdown <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>`__, but extends upojn it.

Installing Sphinx
^^^^^^^^^^^^^^^^^
Sphinx requires a working `Python <https://www.python.org/>`__ installation on your machine.
From there its as simple as running:

.. code-block:: bash

    pip install -U sphinx

Installing the RTD Theme
^^^^^^^^^^^^^^^^^^^^^^^^
To offer a modern look and feel for the documentation we are using the RTD Sphinx Theme.
The conf.py is already set up to use it, so it needs to be installed on the local machine as well.

.. code-block:: bash

    pip install sphinx_rtd_theme

`The Documentation for the Theme can be found here. <https://sphinx-rtd-theme.readthedocs.io/en/latest/index.html>`__

Building the Documentation
^^^^^^^^^^^^^^^^^^^^^^^^^^

To view your changes, simply use the make file or the windows bat script in the project root to build the html documentation.
This can then be viewed in the browser. A reStructuredText extension for Visual Studio Code is available as well.

Make:

.. code-block:: bash

    make html

Windows:

.. code-block:: bash

    make.bat html

Usefull Links
---------------------------

====================    ============================================================
Repository              https://github.com/sunnlok/CryDocs              
Github Issues           https://help.github.com/articles/creating-an-issue/
Github Forks            https://guides.github.com/activities/forking/
Github Pull Requests    https://help.github.com/articles/creating-a-pull-request/
reStructuredText        http://docutils.sourceforge.net/rst.html
Sphinx                  http://www.sphinx-doc.org/en/master/
Read the Docs Theme     https://sphinx-rtd-theme.readthedocs.io/en/latest/index.html
====================    ============================================================