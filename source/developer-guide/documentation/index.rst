=================================
Contributing to the Documentation
=================================

This documentation can easily be contributed to by forking our project
on GitHub and submitting a pull request:

    https://github.com/kolab-groupware/kolab-docs

.. IMPORTANT::

    The documentation is only as good as your willingness to contribute
    to it.

Other documentation included here:

.. toctree::
    :maxdepth: 1

    writing-documentation

Building the Documentation
==========================

Most of our more regular contributors clone the repository to their
local workstation, and then build the documentation before pushing back
changes to their fork of kolab-docs. To build the documentation, you
need to have `Sphinx`_ installed. You can also find some hints, tips and
tricks on their website, with regards to the `reStructuredText`_ format
the documentation is written in.

#.  Naturally, first clone the git repository.

    For anonymous users;

    .. parsed-literal::

        $ :command:`git clone https://github.com/kolab-groupware/kolab-docs`

    For GitHub users that have created a fork;

    .. parsed-literal::

        $ :command:`git clone git@github.com:YOURUSERNAME/kolab-docs`

    For existing Kolab contributors with permissions to push back
    directly;

    .. parsed-literal::

        $ :command:`git clone git@github.com:kolab-groupware/kolab-docs`

#.  Navigate in to the fresh clone:

    .. parsed-literal::

        $ :command:`cd kolab-docs`

#.  To build for real, and possibly also publish the results, pull in
    the sub-projects we include in to our builds.

    Executing this step is not necessary, but gives you the complete set
    of documentation as is published on `docs.kolab.org`_.

    .. parsed-literal::

        $ :command:`git submodule init`
        $ :command:`git submodule update`

    .. seealso::

        *   `Working with Git Submodules`_

Enjoy:

.. _Sphinx: http://sphinx-doc.org/
.. _reStructuredText: http://sphinx-doc.org/rest.html
.. _Working with Git Submodules: http://git-scm.com/book/en/Git-Tools-Submodules
.. _docs.kolab.org: https://docs.kolab.org
