:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'hifiasm'
.. highlight: bash

hifiasm
=======

.. conda:recipe:: hifiasm
   :replaces_section_title:
   :noindex:

   Haplotype\-resolved assembler for accurate Hifi reads

   :homepage: https://github.com/chhylp123/hifiasm
   :license: MIT
   :recipe: /`hifiasm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hifiasm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/hifiasm/meta.yaml>`_

   


.. conda:package:: hifiasm

   |downloads_hifiasm| |docker_hifiasm|

   :versions:
      
      

      ``0.14-1``,  ``0.14-0``,  ``0.13-0``,  ``0.12-0``,  ``0.11-0``,  ``0.10-0``,  ``0.9-0``

      

   
   :depends libgcc-ng: ``>=9.3.0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install hifiasm

   and update with::

      conda update hifiasm

   or use the docker container::

      docker pull quay.io/biocontainers/hifiasm:<tag>

   (see `hifiasm/tags`_ for valid values for ``<tag>``)


.. |downloads_hifiasm| image:: https://img.shields.io/conda/dn/bioconda/hifiasm.svg?style=flat
   :target: https://anaconda.org/bioconda/hifiasm
   :alt:   (downloads)
.. |docker_hifiasm| image:: https://quay.io/repository/biocontainers/hifiasm/status
   :target: https://quay.io/repository/biocontainers/hifiasm
.. _`hifiasm/tags`: https://quay.io/repository/biocontainers/hifiasm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/hifiasm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/hifiasm/README.html