:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-ggbiplot'
.. highlight: bash

r-ggbiplot
==========

.. conda:recipe:: r-ggbiplot
   :replaces_section_title:
   :noindex:

   A biplot based on ggplot2

   :homepage: http://github.com/vqv/ggbiplot
   :license: GPL-2
   :recipe: /`r-ggbiplot <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-ggbiplot>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-ggbiplot/meta.yaml>`_

   


.. conda:package:: r-ggbiplot

   |downloads_r-ggbiplot| |docker_r-ggbiplot|

   :versions:
      
      

      ``0.55-4``,  ``0.55-3``,  ``0.55-2``,  ``0.55-1``

      

   
   :depends libgcc-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-devtools: 
   :depends r-ggplot2: 
   :depends r-gridbase: 
   :depends r-plyr: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-ggbiplot

   and update with::

      conda update r-ggbiplot

   or use the docker container::

      docker pull quay.io/biocontainers/r-ggbiplot:<tag>

   (see `r-ggbiplot/tags`_ for valid values for ``<tag>``)


.. |downloads_r-ggbiplot| image:: https://img.shields.io/conda/dn/bioconda/r-ggbiplot.svg?style=flat
   :target: https://anaconda.org/bioconda/r-ggbiplot
   :alt:   (downloads)
.. |docker_r-ggbiplot| image:: https://quay.io/repository/biocontainers/r-ggbiplot/status
   :target: https://quay.io/repository/biocontainers/r-ggbiplot
.. _`r-ggbiplot/tags`: https://quay.io/repository/biocontainers/r-ggbiplot?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-ggbiplot/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-ggbiplot/README.html