:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xvector'
.. highlight: bash

bioconductor-xvector
====================

.. conda:recipe:: bioconductor-xvector
   :replaces_section_title:
   :noindex:

   Foundation of external vector representation and manipulation in Bioconductor

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/XVector.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-xvector <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xvector>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xvector/meta.yaml>`_
   :links: biotools: :biotools:`xvector`, doi: :doi:`10.1038/nmeth.3252`

   Provides memory efficient S4 classes for storing sequences \"externally\" \(e.g. behind an R external pointer\, or on disk\).


.. conda:package:: bioconductor-xvector

   |downloads_bioconductor-xvector| |docker_bioconductor-xvector|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.30.0-1</code>,  <code>0.30.0-0</code>,  <code>0.28.0-0</code>,  <code>0.26.0-0</code>,  <code>0.24.0-1</code>,  <code>0.22.0-0</code>,  <code>0.20.0-0</code>,  <code>0.18.0-0</code>,  <code>0.16.0-0</code>,  </span></summary>
      

      ``0.30.0-1``,  ``0.30.0-0``,  ``0.28.0-0``,  ``0.26.0-0``,  ``0.24.0-1``,  ``0.22.0-0``,  ``0.20.0-0``,  ``0.18.0-0``,  ``0.16.0-0``,  ``0.14.1-0``,  ``0.12.1-0``,  ``0.10.0-1``,  ``0.10.0-0``,  ``0.8.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-zlibbioc: ``>=1.36.0,<1.37.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xvector

   and update with::

      conda update bioconductor-xvector

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xvector:<tag>

   (see `bioconductor-xvector/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xvector| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xvector.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xvector
   :alt:   (downloads)
.. |docker_bioconductor-xvector| image:: https://quay.io/repository/biocontainers/bioconductor-xvector/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xvector
.. _`bioconductor-xvector/tags`: https://quay.io/repository/biocontainers/bioconductor-xvector?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xvector/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xvector/README.html