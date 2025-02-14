:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'tigmint'
.. highlight: bash

tigmint
=======

.. conda:recipe:: tigmint
   :replaces_section_title:
   :noindex:

   Correct misassemblies using linked reads

   :homepage: https://bcgsc.github.io/tigmint/
   :documentation: https://github.com/bcgsc/tigmint#readme
   
   :developer docs: https://github.com/bcgsc/tigmint
   :license: GPL3 / GNU General Public v3 (GPLv3)
   :recipe: /`tigmint <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tigmint>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tigmint/meta.yaml>`_
   :links: doi: :doi:`10.1101/304253`

   


.. conda:package:: tigmint

   |downloads_tigmint| |docker_tigmint|

   :versions:
      
      

      ``1.2.2-1``,  ``1.2.2-0``,  ``1.2.1-0``,  ``1.1.2-0``

      

   
   :depends bwa: 
   :depends intervaltree: 
   :depends make: 
   :depends minimap2: 
   :depends pybedtools: 
   :depends pysam: ``>=0.15.3``
   :depends python: ``>=3``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install tigmint

   and update with::

      conda update tigmint

   or use the docker container::

      docker pull quay.io/biocontainers/tigmint:<tag>

   (see `tigmint/tags`_ for valid values for ``<tag>``)


.. |downloads_tigmint| image:: https://img.shields.io/conda/dn/bioconda/tigmint.svg?style=flat
   :target: https://anaconda.org/bioconda/tigmint
   :alt:   (downloads)
.. |docker_tigmint| image:: https://quay.io/repository/biocontainers/tigmint/status
   :target: https://quay.io/repository/biocontainers/tigmint
.. _`tigmint/tags`: https://quay.io/repository/biocontainers/tigmint?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/tigmint/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/tigmint/README.html