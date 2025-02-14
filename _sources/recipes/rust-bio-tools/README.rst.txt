:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'rust-bio-tools'
.. highlight: bash

rust-bio-tools
==============

.. conda:recipe:: rust-bio-tools
   :replaces_section_title:
   :noindex:

   A growing collection of fast and secure command line utilities for dealing with NGS data
   implemented on top of Rust\-Bio.


   :homepage: https://github.com/rust-bio/rust-bio-tools
   :license: MIT
   :recipe: /`rust-bio-tools <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/rust-bio-tools>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/rust-bio-tools/meta.yaml>`_

   


.. conda:package:: rust-bio-tools

   |downloads_rust-bio-tools| |docker_rust-bio-tools|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.20.5-0</code>,  <code>0.20.4-0</code>,  <code>0.20.3-4</code>,  <code>0.20.3-3</code>,  <code>0.20.3-2</code>,  <code>0.20.3-1</code>,  <code>0.20.3-0</code>,  <code>0.20.2-0</code>,  <code>0.20.1-1</code>,  </span></summary>
      

      ``0.20.5-0``,  ``0.20.4-0``,  ``0.20.3-4``,  ``0.20.3-3``,  ``0.20.3-2``,  ``0.20.3-1``,  ``0.20.3-0``,  ``0.20.2-0``,  ``0.20.1-1``,  ``0.20.1-0``,  ``0.20.0-0``,  ``0.19.6-0``,  ``0.19.5-0``,  ``0.19.4-0``,  ``0.19.3-0``,  ``0.19.2-0``,  ``0.19.1-0``,  ``0.19.0-0``,  ``0.18.1-0``,  ``0.18.0-0``,  ``0.17.0-0``,  ``0.16.0-0``,  ``0.15.1-0``,  ``0.15.0-0``,  ``0.14.3-0``,  ``0.14.2-0``,  ``0.14.1-0``,  ``0.14.0-0``,  ``0.13.0-0``,  ``0.12.2-0``,  ``0.12.1-0``,  ``0.11.0-0``,  ``0.10.3-0``,  ``0.10.2-0``,  ``0.10.1-0``,  ``0.10.0-0``,  ``0.9.2-1``,  ``0.9.2-0``,  ``0.9.1-0``,  ``0.9.0-0``,  ``0.8.2-0``,  ``0.8.1-0``,  ``0.8.0-1``,  ``0.8.0-0``,  ``0.6.0-0``,  ``0.5.0-0``,  ``0.4.1-0``,  ``0.4.0-0``,  ``0.3.0-0``,  ``0.2.9-0``,  ``0.2.8-0``,  ``0.2.7-0``,  ``0.2.6-1``,  ``0.2.5-1``,  ``0.2.5-0``,  ``0.2.4-0``,  ``0.2.3-0``,  ``0.2.2-0``,  ``0.2.1-0``,  ``0.1.3-0``,  ``0.1.2-0``,  ``0.1.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends gsl: ``>=2.6,<2.7.0a0``
   :depends libcblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends openssl: ``>=1.1.1k,<1.1.2a``
   :depends starcode: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install rust-bio-tools

   and update with::

      conda update rust-bio-tools

   or use the docker container::

      docker pull quay.io/biocontainers/rust-bio-tools:<tag>

   (see `rust-bio-tools/tags`_ for valid values for ``<tag>``)


.. |downloads_rust-bio-tools| image:: https://img.shields.io/conda/dn/bioconda/rust-bio-tools.svg?style=flat
   :target: https://anaconda.org/bioconda/rust-bio-tools
   :alt:   (downloads)
.. |docker_rust-bio-tools| image:: https://quay.io/repository/biocontainers/rust-bio-tools/status
   :target: https://quay.io/repository/biocontainers/rust-bio-tools
.. _`rust-bio-tools/tags`: https://quay.io/repository/biocontainers/rust-bio-tools?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/rust-bio-tools/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/rust-bio-tools/README.html