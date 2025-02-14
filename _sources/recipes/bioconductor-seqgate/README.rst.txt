:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-seqgate'
.. highlight: bash

bioconductor-seqgate
====================

.. conda:recipe:: bioconductor-seqgate
   :replaces_section_title:
   :noindex:

   Filtering of Lowly Expressed Features

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/SeqGate.html
   :license: GPL (>= 2.0)
   :recipe: /`bioconductor-seqgate <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-seqgate>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-seqgate/meta.yaml>`_

   Filtering of lowly expressed features \(e.g. genes\) is a common step before performing statistical analysis\, but an arbitrary threshold is generally chosen. SeqGate implements a method that rationalize this step by the analysis of the distibution of counts in replicate samples. The gate is the threshold above which sequenced features can be considered as confidently quantified.


.. conda:package:: bioconductor-seqgate

   |downloads_bioconductor-seqgate| |docker_bioconductor-seqgate|

   :versions:
      
      

      ``1.0.1-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-biocmanager: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-seqgate

   and update with::

      conda update bioconductor-seqgate

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-seqgate:<tag>

   (see `bioconductor-seqgate/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-seqgate| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-seqgate.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-seqgate
   :alt:   (downloads)
.. |docker_bioconductor-seqgate| image:: https://quay.io/repository/biocontainers/bioconductor-seqgate/status
   :target: https://quay.io/repository/biocontainers/bioconductor-seqgate
.. _`bioconductor-seqgate/tags`: https://quay.io/repository/biocontainers/bioconductor-seqgate?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-seqgate/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-seqgate/README.html