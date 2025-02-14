:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'crispresso2'
.. highlight: bash

crispresso2
===========

.. conda:recipe:: crispresso2
   :replaces_section_title:
   :noindex:

   A software pipeline designed to enable rapid and intuitive interpretation of genome editing experiments

   :homepage: https://github.com/pinellolab/CRISPResso2
   :license: Partners
   :recipe: /`crispresso2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/crispresso2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/crispresso2/meta.yaml>`_

   


.. conda:package:: crispresso2

   |downloads_crispresso2| |docker_crispresso2|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.1.0-1</code>,  <code>2.1.0-0</code>,  <code>2.0.45-1</code>,  <code>2.0.45-0</code>,  <code>2.0.44-0</code>,  <code>2.0.43-0</code>,  <code>2.0.42-0</code>,  <code>2.0.40-0</code>,  <code>2.0.39-0</code>,  </span></summary>
      

      ``2.1.0-1``,  ``2.1.0-0``,  ``2.0.45-1``,  ``2.0.45-0``,  ``2.0.44-0``,  ``2.0.43-0``,  ``2.0.42-0``,  ``2.0.40-0``,  ``2.0.39-0``,  ``2.0.38-0``,  ``2.0.32-0``,  ``2.0.31-0``,  ``2.0.30-0``,  ``2.0.29-0``,  ``2.0.28-0``,  ``2.0.27-3``,  ``2.0.23-1``,  ``2.0.23-0``

      
      .. raw:: html

         </details>
      

   
   :depends argparse: ``>=1.3,<=1.4``
   :depends bowtie2: 
   :depends flash: 
   :depends jinja2: ``2.10``
   :depends libgcc-ng: ``>=9.3.0``
   :depends matplotlib-base: ``>=1.3.1,<=2.2.3``
   :depends numpy: ``>=1.9,<=1.16.6``
   :depends pandas: ``>=0.15,<=0.24``
   :depends python: ``>=2.7,<2.8.0a0``
   :depends python_abi: ``2.7.* *_cp27mu``
   :depends samtools: 
   :depends scipy: ``1.1.0.*``
   :depends seaborn: ``>0.7.1,<0.10``
   :depends trimmomatic: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install crispresso2

   and update with::

      conda update crispresso2

   or use the docker container::

      docker pull quay.io/biocontainers/crispresso2:<tag>

   (see `crispresso2/tags`_ for valid values for ``<tag>``)


.. |downloads_crispresso2| image:: https://img.shields.io/conda/dn/bioconda/crispresso2.svg?style=flat
   :target: https://anaconda.org/bioconda/crispresso2
   :alt:   (downloads)
.. |docker_crispresso2| image:: https://quay.io/repository/biocontainers/crispresso2/status
   :target: https://quay.io/repository/biocontainers/crispresso2
.. _`crispresso2/tags`: https://quay.io/repository/biocontainers/crispresso2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/crispresso2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/crispresso2/README.html