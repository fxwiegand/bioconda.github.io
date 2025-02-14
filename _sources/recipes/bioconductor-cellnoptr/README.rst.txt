:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cellnoptr'
.. highlight: bash

bioconductor-cellnoptr
======================

.. conda:recipe:: bioconductor-cellnoptr
   :replaces_section_title:
   :noindex:

   Training of boolean logic models of signalling networks using prior knowledge networks and perturbation data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/CellNOptR.html
   :license: GPL-3
   :recipe: /`bioconductor-cellnoptr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cellnoptr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cellnoptr/meta.yaml>`_
   :links: biotools: :biotools:`cellnoptr`, doi: :doi:`10.1186/1752-0509-6-133`

   This package does optimisation of boolean logic networks of signalling pathways based on a previous knowledge network and a set of data upon perturbation of the nodes in the network.


.. conda:package:: bioconductor-cellnoptr

   |downloads_bioconductor-cellnoptr| |docker_bioconductor-cellnoptr|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.36.0-1</code>,  <code>1.36.0-0</code>,  <code>1.34.0-0</code>,  <code>1.32.0-0</code>,  <code>1.30.0-1</code>,  <code>1.28.0-0</code>,  <code>1.26.0-0</code>,  <code>1.24.1-0</code>,  <code>1.23.0-0</code>,  </span></summary>
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.1-0``,  ``1.23.0-0``,  ``1.22.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-graph: ``>=1.68.0,<1.69.0``
   :depends bioconductor-rbgl: ``>=1.66.0,<1.67.0``
   :depends bioconductor-rgraphviz: ``>=2.34.0,<2.35.0``
   :depends graphviz: ``>=2.47.0,<3.0a0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-hash: 
   :depends r-igraph: 
   :depends r-rcurl: 
   :depends r-stringi: 
   :depends r-stringr: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cellnoptr

   and update with::

      conda update bioconductor-cellnoptr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cellnoptr:<tag>

   (see `bioconductor-cellnoptr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cellnoptr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cellnoptr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cellnoptr
   :alt:   (downloads)
.. |docker_bioconductor-cellnoptr| image:: https://quay.io/repository/biocontainers/bioconductor-cellnoptr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cellnoptr
.. _`bioconductor-cellnoptr/tags`: https://quay.io/repository/biocontainers/bioconductor-cellnoptr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cellnoptr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cellnoptr/README.html