:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-viscorvar'
.. highlight: bash

r-viscorvar
===========

.. conda:recipe:: r-viscorvar
   :replaces_section_title:
   :noindex:

   Overlaying of Correlation Circles and Network of Correlated Variables

   :homepage: https://gitlab.com/bilille/viscorvar
   :license: GPL3
   :recipe: /`r-viscorvar <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-viscorvar>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-viscorvar/meta.yaml>`_

   visCorVar does analysis from data integration with the 
   function block.splsda \(mixOmics package\). visCorVar 
   performs the overlaying of correlation circles and a zoom
   in a rectangle to retrieve correlated variables. visCorVar 
   can create a network of correlated variables.



.. conda:package:: r-viscorvar

   |downloads_r-viscorvar| |docker_r-viscorvar|

   :versions:
      
      

      ``0.7-1``,  ``0.7-0``,  ``0.6-1``,  ``0.6-0``

      

   
   :depends bioconductor-mixomics: ``6.12``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ellipse: 
   :depends r-igraph: 
   :depends r-knitr: 
   :depends r-rcolorbrewer: 
   :depends r-rmarkdown: 
   :depends r-testthat: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-viscorvar

   and update with::

      conda update r-viscorvar

   or use the docker container::

      docker pull quay.io/biocontainers/r-viscorvar:<tag>

   (see `r-viscorvar/tags`_ for valid values for ``<tag>``)


.. |downloads_r-viscorvar| image:: https://img.shields.io/conda/dn/bioconda/r-viscorvar.svg?style=flat
   :target: https://anaconda.org/bioconda/r-viscorvar
   :alt:   (downloads)
.. |docker_r-viscorvar| image:: https://quay.io/repository/biocontainers/r-viscorvar/status
   :target: https://quay.io/repository/biocontainers/r-viscorvar
.. _`r-viscorvar/tags`: https://quay.io/repository/biocontainers/r-viscorvar?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-viscorvar/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-viscorvar/README.html