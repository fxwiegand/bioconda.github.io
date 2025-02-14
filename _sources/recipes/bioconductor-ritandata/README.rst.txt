:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ritandata'
.. highlight: bash

bioconductor-ritandata
======================

.. conda:recipe:: bioconductor-ritandata
   :replaces_section_title:
   :noindex:

   This package contains the annotation and network data sets

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/RITANdata.html
   :license: file LICENSE
   :recipe: /`bioconductor-ritandata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ritandata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ritandata/meta.yaml>`_

   Data such as is contained in these two R data files in this package are required for the RITAN package. Users may use their own or additional resources in conjunction with RITANdata. See the RITAN vignettes for more information.


.. conda:package:: bioconductor-ritandata

   |downloads_bioconductor-ritandata| |docker_bioconductor-ritandata|

   :versions:
      
      

      ``1.14.0-1``,  ``1.14.0-0``,  ``1.13.0-0``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ritandata

   and update with::

      conda update bioconductor-ritandata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ritandata:<tag>

   (see `bioconductor-ritandata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ritandata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ritandata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ritandata
   :alt:   (downloads)
.. |docker_bioconductor-ritandata| image:: https://quay.io/repository/biocontainers/bioconductor-ritandata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ritandata
.. _`bioconductor-ritandata/tags`: https://quay.io/repository/biocontainers/bioconductor-ritandata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ritandata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ritandata/README.html