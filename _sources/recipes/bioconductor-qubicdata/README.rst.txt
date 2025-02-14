:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qubicdata'
.. highlight: bash

bioconductor-qubicdata
======================

.. conda:recipe:: bioconductor-qubicdata
   :replaces_section_title:
   :noindex:

   Data employed in the vignette of the QUBIC package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/QUBICdata.html
   :license: Unlimited | file LICENSE
   :recipe: /`bioconductor-qubicdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qubicdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qubicdata/meta.yaml>`_

   The data employed in the vignette of the QUBIC package. These data belong to Many Microbe Microarrays Database and STRING v10.


.. conda:package:: bioconductor-qubicdata

   |downloads_bioconductor-qubicdata| |docker_bioconductor-qubicdata|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.17.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qubicdata

   and update with::

      conda update bioconductor-qubicdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qubicdata:<tag>

   (see `bioconductor-qubicdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qubicdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qubicdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qubicdata
   :alt:   (downloads)
.. |docker_bioconductor-qubicdata| image:: https://quay.io/repository/biocontainers/bioconductor-qubicdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qubicdata
.. _`bioconductor-qubicdata/tags`: https://quay.io/repository/biocontainers/bioconductor-qubicdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qubicdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qubicdata/README.html