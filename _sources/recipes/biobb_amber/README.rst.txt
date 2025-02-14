:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'biobb_amber'
.. highlight: bash

biobb_amber
===========

.. conda:recipe:: biobb_amber
   :replaces_section_title:
   :noindex:

   Biobb\\\_amber is a BioBB category for AMBER MD package.

   :homepage: https://github.com/bioexcel/biobb_amber
   :license: APACHE / Apache Software License
   :recipe: /`biobb_amber <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biobb_amber>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biobb_amber/meta.yaml>`_

   Biobb amber is a BioBB category for AMBER MD package.
   Biobb \(BioExcel building blocks\) packages are Python building blocks that
   create new layer of compatibility and interoperability over popular
     bioinformatics tools.
   The latest documentation of this package can be found in our readthedocs site\: \[\!\[\]\(http\:\/\/biobb\_amber.readthedocs.io\/en\/latest\/\)\]\(http\:\/\/biobb\_amber.readthedocs.io\/en\/latest\/\).



.. conda:package:: biobb_amber

   |downloads_biobb_amber| |docker_biobb_amber|

   :versions:
      
      

      ``3.5.0-0``

      

   
   :depends ambertools: ``20.0``
   :depends biobb_common: ``3.5.1``
   :depends python: ``3.7.*``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install biobb_amber

   and update with::

      conda update biobb_amber

   or use the docker container::

      docker pull quay.io/biocontainers/biobb_amber:<tag>

   (see `biobb_amber/tags`_ for valid values for ``<tag>``)


.. |downloads_biobb_amber| image:: https://img.shields.io/conda/dn/bioconda/biobb_amber.svg?style=flat
   :target: https://anaconda.org/bioconda/biobb_amber
   :alt:   (downloads)
.. |docker_biobb_amber| image:: https://quay.io/repository/biocontainers/biobb_amber/status
   :target: https://quay.io/repository/biocontainers/biobb_amber
.. _`biobb_amber/tags`: https://quay.io/repository/biocontainers/biobb_amber?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/biobb_amber/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/biobb_amber/README.html