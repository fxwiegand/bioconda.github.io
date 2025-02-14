:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chipsim'
.. highlight: bash

bioconductor-chipsim
====================

.. conda:recipe:: bioconductor-chipsim
   :replaces_section_title:
   :noindex:

   Simulation of ChIP\-seq experiments

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ChIPsim.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-chipsim <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipsim>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipsim/meta.yaml>`_
   :links: biotools: :biotools:`chipsim`, doi: :doi:`10.1038/nmeth.3252`

   A general framework for the simulation of ChIP\-seq data. Although currently focused on nucleosome positioning the package is designed to support different types of experiments.


.. conda:package:: bioconductor-chipsim

   |downloads_bioconductor-chipsim| |docker_bioconductor-chipsim|

   :versions:
      
      

      ``1.44.0-1``,  ``1.44.0-0``,  ``1.42.0-0``,  ``1.40.0-0``,  ``1.38.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-shortread: ``>=1.48.0,<1.49.0``
   :depends bioconductor-xvector: ``>=0.30.0,<0.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chipsim

   and update with::

      conda update bioconductor-chipsim

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chipsim:<tag>

   (see `bioconductor-chipsim/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chipsim| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chipsim.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chipsim
   :alt:   (downloads)
.. |docker_bioconductor-chipsim| image:: https://quay.io/repository/biocontainers/bioconductor-chipsim/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chipsim
.. _`bioconductor-chipsim/tags`: https://quay.io/repository/biocontainers/bioconductor-chipsim?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chipsim/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chipsim/README.html