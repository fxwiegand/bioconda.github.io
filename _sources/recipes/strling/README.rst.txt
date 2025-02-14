:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'strling'
.. highlight: bash

strling
=======

.. conda:recipe:: strling
   :replaces_section_title:
   :noindex:

   STRling \(pronounced like “sterling”\) is a method to detect large STR expansions from short\-read sequencing data.

   :homepage: https://github.com/quinlan-lab/STRling
   :license: MIT
   :recipe: /`strling <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/strling>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/strling/meta.yaml>`_

   


.. conda:package:: strling

   |downloads_strling| |docker_strling|

   :versions:
      
      

      ``0.4.2-1``,  ``0.4.2-0``,  ``0.4.1-1``,  ``0.4.1-0``,  ``0.4.0-0``,  ``0.3.0-0``,  ``0.2.1-0``,  ``0.1.0-0``

      

   
   :depends biopython: 
   :depends bpipe: 
   :depends htslib: ``>=1.12,<1.13.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends pandas: 
   :depends pysam: 
   :depends pytest: 
   :depends pytest-runner: 
   :depends python: ``>=3.7``
   :depends scikit-learn: 
   :depends seaborn: 
   :depends statsmodels: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install strling

   and update with::

      conda update strling

   or use the docker container::

      docker pull quay.io/biocontainers/strling:<tag>

   (see `strling/tags`_ for valid values for ``<tag>``)


.. |downloads_strling| image:: https://img.shields.io/conda/dn/bioconda/strling.svg?style=flat
   :target: https://anaconda.org/bioconda/strling
   :alt:   (downloads)
.. |docker_strling| image:: https://quay.io/repository/biocontainers/strling/status
   :target: https://quay.io/repository/biocontainers/strling
.. _`strling/tags`: https://quay.io/repository/biocontainers/strling?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/strling/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/strling/README.html