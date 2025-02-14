:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-globalseq'
.. highlight: bash

bioconductor-globalseq
======================

.. conda:recipe:: bioconductor-globalseq
   :replaces_section_title:
   :noindex:

   Global Test for Counts

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/globalSeq.html
   :license: GPL-3
   :recipe: /`bioconductor-globalseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-globalseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-globalseq/meta.yaml>`_
   :links: biotools: :biotools:`globalseq`

   The method may be conceptualised as a test of overall significance in regression analysis\, where the response variable is overdispersed and the number of explanatory variables exceeds the sample size. Useful for testing for association between RNA\-Seq and high\-dimensional data.


.. conda:package:: bioconductor-globalseq

   |downloads_bioconductor-globalseq| |docker_bioconductor-globalseq|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.18.0-1</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  <code>1.14.0-0</code>,  <code>1.12.0-1</code>,  <code>1.12.0-0</code>,  <code>1.10.1-0</code>,  <code>1.8.0-0</code>,  <code>1.6.0-0</code>,  </span></summary>
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.1-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.2-0``

      
      .. raw:: html

         </details>
      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-globalseq

   and update with::

      conda update bioconductor-globalseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-globalseq:<tag>

   (see `bioconductor-globalseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-globalseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-globalseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-globalseq
   :alt:   (downloads)
.. |docker_bioconductor-globalseq| image:: https://quay.io/repository/biocontainers/bioconductor-globalseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-globalseq
.. _`bioconductor-globalseq/tags`: https://quay.io/repository/biocontainers/bioconductor-globalseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-globalseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-globalseq/README.html