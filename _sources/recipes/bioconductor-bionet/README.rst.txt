:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bionet'
.. highlight: bash

bioconductor-bionet
===================

.. conda:recipe:: bioconductor-bionet
   :replaces_section_title:
   :noindex:

   Routines for the functional analysis of biological networks

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/BioNet.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-bionet <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bionet>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bionet/meta.yaml>`_
   :links: biotools: :biotools:`bionet`

   This package provides functions for the integrated analysis of protein\-protein interaction networks and the detection of functional modules. Different datasets can be integrated into the network by assigning p\-values of statistical tests to the nodes of the network. E.g. p\-values obtained from the differential expression of the genes from an Affymetrix array are assigned to the nodes of the network. By fitting a beta\-uniform mixture model and calculating scores from the p\-values\, overall scores of network regions can be calculated and an integer linear programming algorithm identifies the maximum scoring subnetwork.


.. conda:package:: bioconductor-bionet

   |downloads_bioconductor-bionet| |docker_bioconductor-bionet|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.50.0-1</code>,  <code>1.50.0-0</code>,  <code>1.47.0-0</code>,  <code>1.46.0-0</code>,  <code>1.44.0-1</code>,  <code>1.42.0-0</code>,  <code>1.40.0-0</code>,  <code>1.38.0-0</code>,  <code>1.36.0-0</code>,  </span></summary>
      

      ``1.50.0-1``,  ``1.50.0-0``,  ``1.47.0-0``,  ``1.46.0-0``,  ``1.44.0-1``,  ``1.42.0-0``,  ``1.40.0-0``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-graph: ``>=1.68.0,<1.69.0``
   :depends bioconductor-rbgl: ``>=1.66.0,<1.67.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-igraph: ``>=1.0.1``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bionet

   and update with::

      conda update bioconductor-bionet

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bionet:<tag>

   (see `bioconductor-bionet/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bionet| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bionet.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bionet
   :alt:   (downloads)
.. |docker_bioconductor-bionet| image:: https://quay.io/repository/biocontainers/bioconductor-bionet/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bionet
.. _`bioconductor-bionet/tags`: https://quay.io/repository/biocontainers/bioconductor-bionet?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bionet/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bionet/README.html