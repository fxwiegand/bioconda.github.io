:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'binsanity'
.. highlight: bash

binsanity
=========

.. conda:recipe:: binsanity
   :replaces_section_title:
   :noindex:

   Method to cluster contigs based a biphasic method with coverage and composition

   :homepage: https://github.com/edgraham/BinSanity
   :license: GPL3 / GPL3
   :recipe: /`binsanity <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/binsanity>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/binsanity/meta.yaml>`_

   


.. conda:package:: binsanity

   |downloads_binsanity| |docker_binsanity|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.5.3-0</code>,  <code>0.4.4-1</code>,  <code>0.4.4-0</code>,  <code>0.4.2-0</code>,  <code>0.4.1-0</code>,  <code>0.3.8-0</code>,  <code>0.3.6-0</code>,  <code>0.3.4-0</code>,  <code>0.3.1-0</code>,  </span></summary>
      

      ``0.5.3-0``,  ``0.4.4-1``,  ``0.4.4-0``,  ``0.4.2-0``,  ``0.4.1-0``,  ``0.3.8-0``,  ``0.3.6-0``,  ``0.3.4-0``,  ``0.3.1-0``,  ``0.2.9.5-0``,  ``0.2.9.4-0``,  ``0.2.9.2-0``,  ``0.2.9.1-0``,  ``0.2.9-0``,  ``0.2.8.2-0``,  ``0.2.7.1-0``,  ``0.2.6.3-0``,  ``0.2.6.1-2``,  ``0.2.6.1-1``,  ``0.2.6.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends biopython: 
   :depends checkm-genome: 
   :depends pandas: ``>=0.13.0``
   :depends python: 
   :depends scikit-learn: ``>=0.23``
   :depends scipy: ``>=0.13.0``
   :depends subread: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install binsanity

   and update with::

      conda update binsanity

   or use the docker container::

      docker pull quay.io/biocontainers/binsanity:<tag>

   (see `binsanity/tags`_ for valid values for ``<tag>``)


.. |downloads_binsanity| image:: https://img.shields.io/conda/dn/bioconda/binsanity.svg?style=flat
   :target: https://anaconda.org/bioconda/binsanity
   :alt:   (downloads)
.. |docker_binsanity| image:: https://quay.io/repository/biocontainers/binsanity/status
   :target: https://quay.io/repository/biocontainers/binsanity
.. _`binsanity/tags`: https://quay.io/repository/biocontainers/binsanity?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/binsanity/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/binsanity/README.html