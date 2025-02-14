:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ddocent'
.. highlight: bash

ddocent
=======

.. conda:recipe:: ddocent
   :replaces_section_title:
   :noindex:

    dDocent is  an interactive bash wrapper to QC\, assemble\, map\, and call SNPs from all types of RAD data

   :homepage: http://ddocent.com
   :license: The MIT License (MIT)
   :recipe: /`ddocent <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ddocent>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ddocent/meta.yaml>`_

   


.. conda:package:: ddocent

   |downloads_ddocent| |docker_ddocent|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.8.13-1</code>,  <code>2.8.13-0</code>,  <code>2.8.12-0</code>,  <code>2.7.8-4</code>,  <code>2.7.8-3</code>,  <code>2.7.8-2</code>,  <code>2.7.8-1</code>,  <code>2.7.8-0</code>,  <code>2.7.7-0</code>,  </span></summary>
      

      ``2.8.13-1``,  ``2.8.13-0``,  ``2.8.12-0``,  ``2.7.8-4``,  ``2.7.8-3``,  ``2.7.8-2``,  ``2.7.8-1``,  ``2.7.8-0``,  ``2.7.7-0``,  ``2.7.6-0``,  ``2.6.0-2``,  ``2.6.0-1``,  ``2.6.0-0``,  ``2.5.6-0``,  ``2.5.5-0``,  ``2.5.2-1``,  ``2.5.2-0``,  ``2.5.1-0``,  ``2.3.8-0``,  ``2.2.25-2``,  ``2.2.25-1``,  ``2.2.25-0``,  ``2.2.20-0``,  ``2.2.19-0``,  ``2.2.16-0``,  ``2.2.15-0``,  ``2.2.13-0``,  ``2.2.8-0``,  ``2.2.7-0``,  ``2.2.4-0``,  ``2.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends bedtools: ``>=2.26.0``
   :depends bwa: ``>=0.7.13``
   :depends cd-hit: 
   :depends coreutils: ``>=8.22``
   :depends curl: 
   :depends fastp: 
   :depends freebayes: ``>=1``
   :depends gnuplot: 
   :depends grep: 
   :depends mawk: 
   :depends parallel: 
   :depends pear: 
   :depends rainbow: 
   :depends samtools: ``>=1.3``
   :depends sed: 
   :depends seqtk: ``>=1.3``
   :depends unzip: 
   :depends vcflib: ``>=0.1.11``
   :depends vcftools: ``>=0.1.15``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install ddocent

   and update with::

      conda update ddocent

   or use the docker container::

      docker pull quay.io/biocontainers/ddocent:<tag>

   (see `ddocent/tags`_ for valid values for ``<tag>``)


.. |downloads_ddocent| image:: https://img.shields.io/conda/dn/bioconda/ddocent.svg?style=flat
   :target: https://anaconda.org/bioconda/ddocent
   :alt:   (downloads)
.. |docker_ddocent| image:: https://quay.io/repository/biocontainers/ddocent/status
   :target: https://quay.io/repository/biocontainers/ddocent
.. _`ddocent/tags`: https://quay.io/repository/biocontainers/ddocent?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ddocent/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ddocent/README.html