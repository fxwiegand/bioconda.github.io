:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'decifer'
.. highlight: bash

decifer
=======

.. conda:recipe:: decifer
   :replaces_section_title:
   :noindex:

   DeCiFer simultaneously selects mutation multiplicities and clusters SNVs by their corresponding descendant cell fractions \(DCF\)

   :homepage: https://github.com/raphael-group/decifer
   :license: BSD-3
   :recipe: /`decifer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/decifer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/decifer/meta.yaml>`_

   DeCiFer is an algorithm that simultaneously selects mutation multiplicities and clusters SNVs by their corresponding descendant cell fractions \(DCF\)\, a statistic that quantifies the proportion of cells which acquired the SNV or whose ancestors acquired the SNV. DCF is related to the commonly used cancer cell fraction \(CCF\) but further accounts for SNVs which are lost due to deleterious somatic copy\-number aberrations \(CNAs\)\, identifying clusters of SNVs which occur in the same phylogenetic branch of tumour evolution.


.. conda:package:: decifer

   |downloads_decifer| |docker_decifer|

   :versions:
      
      

      ``1.0.0-0``,  ``0.0.2-1``,  ``0.0.2-0``

      

   
   :depends lemon: ``>=1.3.1,<1.3.2.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends numpy: ``>=1.16.1``
   :depends pandas: 
   :depends python: ``>=2.7,<2.8.0a0``
   :depends python_abi: ``2.7.* *_cp27mu``
   :depends scipy: ``>=1.2.1``
   :depends seaborn: ``>=0.7.1``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install decifer

   and update with::

      conda update decifer

   or use the docker container::

      docker pull quay.io/biocontainers/decifer:<tag>

   (see `decifer/tags`_ for valid values for ``<tag>``)


.. |downloads_decifer| image:: https://img.shields.io/conda/dn/bioconda/decifer.svg?style=flat
   :target: https://anaconda.org/bioconda/decifer
   :alt:   (downloads)
.. |docker_decifer| image:: https://quay.io/repository/biocontainers/decifer/status
   :target: https://quay.io/repository/biocontainers/decifer
.. _`decifer/tags`: https://quay.io/repository/biocontainers/decifer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/decifer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/decifer/README.html