:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bactopia'
.. highlight: bash

bactopia
========

.. conda:recipe:: bactopia
   :replaces_section_title:
   :noindex:

   Bactopia is a flexible pipeline for complete analysis of bacterial genomes.

   :homepage: https://bactopia.github.io/
   :developer docs: https://github.com/bactopia/bactopia/
   :license: MIT
   :recipe: /`bactopia <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bactopia>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bactopia/meta.yaml>`_
   :links: biotools: :biotools:`bactopia`, doi: :doi:`10.1128/mSystems.00190-20`

   


.. conda:package:: bactopia

   |downloads_bactopia| |docker_bactopia|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.6.5-1</code>,  <code>1.6.5-0</code>,  <code>1.6.4-0</code>,  <code>1.6.3-0</code>,  <code>1.6.2-2</code>,  <code>1.6.2-1</code>,  <code>1.6.2-0</code>,  <code>1.6.1-0</code>,  <code>1.6.0-1</code>,  </span></summary>
      

      ``1.6.5-1``,  ``1.6.5-0``,  ``1.6.4-0``,  ``1.6.3-0``,  ``1.6.2-2``,  ``1.6.2-1``,  ``1.6.2-0``,  ``1.6.1-0``,  ``1.6.0-1``,  ``1.6.0-0``,  ``1.5.6-0``,  ``1.5.5-0``,  ``1.5.4-1``,  ``1.5.4-0``,  ``1.5.3-0``,  ``1.5.2-0``,  ``1.5.1-0``,  ``1.5.0-0``,  ``1.4.11-1``,  ``1.4.11-0``,  ``1.4.10-0``,  ``1.4.9-0``,  ``1.4.8-0``,  ``1.4.7-0``,  ``1.4.6-0``,  ``1.4.5-0``,  ``1.4.4-0``,  ``1.4.3-0``,  ``1.4.2-0``,  ``1.4.1-0``,  ``1.4.0-0``,  ``1.3.1-0``,  ``1.3.0-0``,  ``1.2.4-0``,  ``1.2.2-0``,  ``1.2.1-0``,  ``1.2.0-0``,  ``1.1.0-1``,  ``1.1.0-0``,  ``1.0.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends ariba: ``>=2.14.6``
   :depends beautifulsoup4: 
   :depends biopython: 
   :depends blast: ``>=2.11.0``
   :depends bowtie2: 
   :depends cd-hit: 
   :depends conda: 
   :depends coreutils: 
   :depends executor: 
   :depends lxml: 
   :depends mash: 
   :depends ncbi-amrfinderplus: ``3.10.1.*``
   :depends ncbi-genome-download: 
   :depends nextflow: 
   :depends openjdk: ``11.0.8.*``
   :depends pysam: ``>=0.15.3``
   :depends python: ``>3.6``
   :depends requests: 
   :depends sed: 
   :depends tbb: ``2020.2.*``
   :depends unzip: 
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bactopia

   and update with::

      conda update bactopia

   or use the docker container::

      docker pull quay.io/biocontainers/bactopia:<tag>

   (see `bactopia/tags`_ for valid values for ``<tag>``)


.. |downloads_bactopia| image:: https://img.shields.io/conda/dn/bioconda/bactopia.svg?style=flat
   :target: https://anaconda.org/bioconda/bactopia
   :alt:   (downloads)
.. |docker_bactopia| image:: https://quay.io/repository/biocontainers/bactopia/status
   :target: https://quay.io/repository/biocontainers/bactopia
.. _`bactopia/tags`: https://quay.io/repository/biocontainers/bactopia?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bactopia/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bactopia/README.html