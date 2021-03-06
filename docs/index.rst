
Wn Documentation
================

Overview
--------

This package provides an interface to wordnet data, from simple lookup
queries, to graph traversals, to more sophisticated algorithms and
metrics. Features include:

- Support for wordnets in the
  `WN-LMF <https://globalwordnet.github.io/schemas/>`_ format
- A `SQLite <https://sqlite.org>`_ database backend for data
  consistency and efficient queries
- Accurate modeling of Words, Senses, and Synsets

Quick Start
-----------

.. code-block:: console

   $ pip install ...

.. code-block:: python

   >>> import wn
   >>> wn.download('ewn:2020')
   >>> wn.synsets('coffee')
   [Synset('ewn-04979718-n'), Synset('ewn-07945591-n'), Synset('ewn-07945759-n'), Synset('ewn-12683533-n')]


Guides
------

.. toctree::
   :maxdepth: 2

   guides/setup.rst
   guides/lexicons.rst
   guides/basic.rst
   guides/interlingual.rst
   guides/wordnet.rst

API Reference
-------------

.. toctree::
   :maxdepth: 1

   api/wn.rst
   api/wn.lmf.rst
   api/wn.project.rst
   api/wn.similarity.rst
