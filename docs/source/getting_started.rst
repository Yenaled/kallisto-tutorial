Getting started
===============

Overview
^^^^^^^^

The tools:

* **kallisto**: Maps RNA-seq reads to a reference transcriptome and stores the results in a BUS file.

* **bustools**: Processes the results in the BUS file to correct barcodes, deduplicate UMIs, and generate quantification files (e.g. count matrices).

* **kb-python**: A wrapper around kallisto and bustools that facilitates usage of those tools and facilitates the generation of a reference transcriptome. The kallisto and bustools binaries come packaged in kb-python.

Installation
^^^^^^^^^^^^

Installing kb-python
~~~~~~~~~~~~~~~~~~~~

To install the latest version of the software, which should be sufficient for most purposes, all you have to do is run the following:

.. code-block:: shell

  pip install kb_python

If you need to install a specific version of kb-python, you can specify the version in the pip install. For example, for version 0.28.2 of kb-python:

.. code-block:: shell

  pip install kb_python==0.28.2

.. seealso::

  If you want to install kallisto and bustools from source, please visit the section :ref:`Advanced Installation`


Usage
^^^^^

There are two main kb-python commands that cover most use cases: ``kb ref`` and ``kb count``, for building an index from a transcriptome reference and mapping/quantifying sequencing reads, respectively.

To run those commands, you can just type them into the command-line after install kb-python:

.. code-block:: shell

  kb ref ...
  kb count ...

Replace ... with whatever parameters you wish to supply to those commands.

