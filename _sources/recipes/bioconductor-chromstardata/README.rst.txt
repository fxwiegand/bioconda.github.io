:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chromstardata'
.. highlight: bash

bioconductor-chromstardata
==========================

.. conda:recipe:: bioconductor-chromstardata
   :replaces_section_title:
   :noindex:

   ChIP\-seq data for Demonstration Purposes

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/chromstaRData.html
   :license: GPL-3
   :recipe: /`bioconductor-chromstardata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromstardata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chromstardata/meta.yaml>`_

   ChIP\-seq data for demonstration purposes in the chromstaR package.


.. conda:package:: bioconductor-chromstardata

   |downloads_bioconductor-chromstardata| |docker_bioconductor-chromstardata|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.16.0-1</code>,  <code>1.16.0-0</code>,  <code>1.15.0-0</code>,  <code>1.14.0-0</code>,  <code>1.12.0-0</code>,  <code>1.10.0-1</code>,  <code>1.10.0-0</code>,  <code>1.8.0-0</code>,  <code>1.6.0-0</code>,  </span></summary>
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.15.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chromstardata

   and update with::

      conda update bioconductor-chromstardata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chromstardata:<tag>

   (see `bioconductor-chromstardata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chromstardata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chromstardata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chromstardata
   :alt:   (downloads)
.. |docker_bioconductor-chromstardata| image:: https://quay.io/repository/biocontainers/bioconductor-chromstardata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chromstardata
.. _`bioconductor-chromstardata/tags`: https://quay.io/repository/biocontainers/bioconductor-chromstardata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chromstardata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chromstardata/README.html