.. _`swipe`:

swipe
=====

|downloads|

Tool for performing rapid local alignment searches in amino acid or nucleotide sequence databases. It is a highly optimized implementation of the Smith\-Waterman algoritm using SIMD parallel computing technology available on common CPUs.

============= ===========
Home          http://dna.uio.no/swipe
Versions      2.0.12
License       file
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes/swipe



Links         biotools: :biotools:`swipe`, doi: :doi:`10.1186/1471-2105-12-221`

============= ===========



Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install swipe

and update with::

   conda update swipe



|docker|

A Docker container is available at https://quay.io/repository/biocontainers/swipe.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/swipe/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/swipe/README.html
.. |downloads| image:: https://anaconda.org/bioconda/swipe/badges/downloads.svg
               :target: https://anaconda.org/bioconda/swipe
.. |docker| image:: https://quay.io/repository/biocontainers/swipe/status
                :target: https://quay.io/repository/biocontainers/swipe

