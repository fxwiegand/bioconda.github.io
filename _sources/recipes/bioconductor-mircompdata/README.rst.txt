:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mircompdata'
.. highlight: bash

bioconductor-mircompdata
========================

.. conda:recipe:: bioconductor-mircompdata
   :replaces_section_title:
   :noindex:

   Data used in the miRcomp package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/miRcompData.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-mircompdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mircompdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mircompdata/meta.yaml>`_

   Raw amplification data from a large microRNA mixture \/ dilution study. These data are used by the miRcomp package to assess the performance of methods that estimate expression from the amplification curves.


.. conda:package:: bioconductor-mircompdata

   |downloads_bioconductor-mircompdata| |docker_bioconductor-mircompdata|

   :versions:
      
      

      ``1.20.0-1``,  ``1.20.0-0``,  ``1.19.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.14.0-0``,  ``1.12.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mircompdata

   and update with::

      conda update bioconductor-mircompdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mircompdata:<tag>

   (see `bioconductor-mircompdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mircompdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mircompdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mircompdata
   :alt:   (downloads)
.. |docker_bioconductor-mircompdata| image:: https://quay.io/repository/biocontainers/bioconductor-mircompdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mircompdata
.. _`bioconductor-mircompdata/tags`: https://quay.io/repository/biocontainers/bioconductor-mircompdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mircompdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mircompdata/README.html