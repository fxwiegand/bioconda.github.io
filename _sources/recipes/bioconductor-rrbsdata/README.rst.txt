:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rrbsdata'
.. highlight: bash

bioconductor-rrbsdata
=====================

.. conda:recipe:: bioconductor-rrbsdata
   :replaces_section_title:
   :noindex:

   An RRBS data set with 12 samples and 10\,000 simulated DMRs

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/RRBSdata.html
   :license: LGPL-3
   :recipe: /`bioconductor-rrbsdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rrbsdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rrbsdata/meta.yaml>`_

   RRBS data set comprising 12 samples with simulated differentially methylated regions \(DMRs\).


.. conda:package:: bioconductor-rrbsdata

   |downloads_bioconductor-rrbsdata| |docker_bioconductor-rrbsdata|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-biseq: ``>=1.30.0,<1.31.0``
   :depends curl: ``>=7.76.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rrbsdata

   and update with::

      conda update bioconductor-rrbsdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rrbsdata:<tag>

   (see `bioconductor-rrbsdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rrbsdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rrbsdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rrbsdata
   :alt:   (downloads)
.. |docker_bioconductor-rrbsdata| image:: https://quay.io/repository/biocontainers/bioconductor-rrbsdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rrbsdata
.. _`bioconductor-rrbsdata/tags`: https://quay.io/repository/biocontainers/bioconductor-rrbsdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rrbsdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rrbsdata/README.html