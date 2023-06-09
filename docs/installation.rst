.. highlight:: shell

============
Installation
============

Stable release
--------------

To install stupidb, run this command in your terminal:

.. code-block:: console

   $ pip install stupidb

If you don't have `pip`_ installed, this `Python installation guide`_ can guide
you through the process.

.. _pip: https://pip.pypa.io
.. _Python installation guide: http://docs.python-guide.org/en/latest/starting/installation/

From sources
------------

The sources for stupidb can be downloaded from the `GitHub repository`_.

You need to have `poetry`_ installed.

The only supported way to install from source is inside of a virtual environment.

You can either clone the public repository:

.. code-block:: console

   $ git clone https://github.com/cpcloud/stupidb

Or download and unpack the `tarball`_:

.. code-block:: console

   $ curl -sL https://github.com/cpcloud/stupidb/tarball/main | tar xvzf

Once you have a copy of the source, ``cd`` into source directory and install
``stupidb``:

.. code-block:: console

   $ poetry install


.. _GitHub repository: https://github.com/cpcloud/stupidb
.. _tarball: https://github.com/cpcloud/stupidb/tarball/main
.. _poetry: https://python-poetry.org
