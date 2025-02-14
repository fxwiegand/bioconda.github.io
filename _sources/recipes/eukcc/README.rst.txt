:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'eukcc'
.. highlight: bash

eukcc
=====

.. conda:recipe:: eukcc
   :replaces_section_title:
   :noindex:

   Check eukaryotic genomes or MAGs for completeness and contamination

   :homepage: https://github.com/Finn-Lab/EukCC/
   :documentation: https://eukcc.readthedocs.io/en/latest/
   
   :license: GPL3 / GNU General Public v3 (GPLv3)
   :recipe: /`eukcc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/eukcc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/eukcc/meta.yaml>`_

   


.. conda:package:: eukcc

   |downloads_eukcc| |docker_eukcc|

   :versions:
      
      

      ``0.3-0``,  ``0.2-1``,  ``0.2-0``,  ``0.1.5.1-0``,  ``0.1.4.6-0``

      

   
   :depends configargparse: 
   :depends ete3: 
   :depends hmmer: ``>=3.2``
   :depends pplacer: 
   :depends pyfaidx: 
   :depends pygmes: 
   :depends python: ``>=3.6``
   :depends pyyaml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install eukcc

   and update with::

      conda update eukcc

   or use the docker container::

      docker pull quay.io/biocontainers/eukcc:<tag>

   (see `eukcc/tags`_ for valid values for ``<tag>``)


.. |downloads_eukcc| image:: https://img.shields.io/conda/dn/bioconda/eukcc.svg?style=flat
   :target: https://anaconda.org/bioconda/eukcc
   :alt:   (downloads)
.. |docker_eukcc| image:: https://quay.io/repository/biocontainers/eukcc/status
   :target: https://quay.io/repository/biocontainers/eukcc
.. _`eukcc/tags`: https://quay.io/repository/biocontainers/eukcc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/eukcc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/eukcc/README.html