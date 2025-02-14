:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-affyilm'
.. highlight: bash

bioconductor-affyilm
====================

.. conda:recipe:: bioconductor-affyilm
   :replaces_section_title:
   :noindex:

   Linear Model of background subtraction and the Langmuir isotherm

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/affyILM.html
   :license: GPL-3
   :recipe: /`bioconductor-affyilm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affyilm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affyilm/meta.yaml>`_
   :links: biotools: :biotools:`affyilm`, doi: :doi:`10.1186/1748-7188-4-15`

   affyILM is a preprocessing tool which estimates gene expression levels for Affymetrix Gene Chips. Input from physical chemistry is employed to first background subtract intensities before calculating concentrations on behalf of the Langmuir model.


.. conda:package:: bioconductor-affyilm

   |downloads_bioconductor-affyilm| |docker_bioconductor-affyilm|

   :versions:
      
      

      ``1.42.0-1``,  ``1.42.0-0``,  ``1.40.0-0``,  ``1.38.0-0``,  ``1.36.0-1``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-0``,  ``1.28.0-0``

      

   
   :depends bioconductor-affxparser: ``>=1.62.0,<1.63.0``
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-gcrma: ``>=2.62.0,<2.63.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-affyilm

   and update with::

      conda update bioconductor-affyilm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-affyilm:<tag>

   (see `bioconductor-affyilm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-affyilm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-affyilm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-affyilm
   :alt:   (downloads)
.. |docker_bioconductor-affyilm| image:: https://quay.io/repository/biocontainers/bioconductor-affyilm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-affyilm
.. _`bioconductor-affyilm/tags`: https://quay.io/repository/biocontainers/bioconductor-affyilm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-affyilm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-affyilm/README.html