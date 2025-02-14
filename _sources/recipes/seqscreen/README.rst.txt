:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'seqscreen'
.. highlight: bash

seqscreen
=========

.. conda:recipe:: seqscreen
   :replaces_section_title:
   :noindex:

   SeqScreen was created to sensitively assign taxonomic classifications\, functional annotations\, and biological processes of interest to single\, short DNA sequences \(50bp\-1\,000bp\).

   :homepage: https://gitlab.com/treangenlab/seqscreen/-/wikis/home
   :license: GPL3
   :recipe: /`seqscreen <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/seqscreen>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/seqscreen/meta.yaml>`_

   


.. conda:package:: seqscreen

   |downloads_seqscreen| |docker_seqscreen|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.5.0-0</code>,  <code>1.4.14-1</code>,  <code>1.4.14-0</code>,  <code>1.4.12-0</code>,  <code>1.4.11-0</code>,  <code>1.4.10-0</code>,  <code>1.4.9-0</code>,  <code>1.4.8-0</code>,  <code>1.4.7-0</code>,  </span></summary>
      

      ``1.5.0-0``,  ``1.4.14-1``,  ``1.4.14-0``,  ``1.4.12-0``,  ``1.4.11-0``,  ``1.4.10-0``,  ``1.4.9-0``,  ``1.4.8-0``,  ``1.4.7-0``,  ``1.4.6-0``,  ``1.4.5-0``,  ``1.4.4-0``,  ``1.4.3-0``,  ``1.4.2-0``,  ``1.4.1-0``,  ``1.4.0-1``,  ``1.4.0-0``,  ``1.3.1-0``,  ``1.3.0-1``,  ``1.3.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends biopython: 
   :depends bitarray: 
   :depends blast: ``>=2.9``
   :depends bowtie2: 
   :depends centrifuge-core: 
   :depends diamond: 
   :depends hmmer: 
   :depends jinja2: 
   :depends mummer: 
   :depends nextflow: 
   :depends python: ``>=3``
   :depends rapsearch: 
   :depends scikit-learn: 
   :depends scipy: 
   :depends time: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install seqscreen

   and update with::

      conda update seqscreen

   or use the docker container::

      docker pull quay.io/biocontainers/seqscreen:<tag>

   (see `seqscreen/tags`_ for valid values for ``<tag>``)


.. |downloads_seqscreen| image:: https://img.shields.io/conda/dn/bioconda/seqscreen.svg?style=flat
   :target: https://anaconda.org/bioconda/seqscreen
   :alt:   (downloads)
.. |docker_seqscreen| image:: https://quay.io/repository/biocontainers/seqscreen/status
   :target: https://quay.io/repository/biocontainers/seqscreen
.. _`seqscreen/tags`: https://quay.io/repository/biocontainers/seqscreen?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/seqscreen/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/seqscreen/README.html