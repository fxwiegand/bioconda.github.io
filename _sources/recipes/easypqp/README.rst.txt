:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'easypqp'
.. highlight: bash

easypqp
=======

.. conda:recipe:: easypqp
   :replaces_section_title:
   :noindex:

   EasyPQP\: Simple library generation for OpenSWATH

   :homepage: https://github.com/grosenberger/easypqp
   :license: BSD / BSD License
   :recipe: /`easypqp <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/easypqp>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/easypqp/meta.yaml>`_

   EasyPQP\: Simple library generation for OpenSWATH
   \=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=\=

   EasyPQP is a Python package that provides simplified and fast peptide query parameter generation for OpenSWATH. It can process input from MSFragger or other database search engines in pepXML format. Statistical validation can be conducted either using PyProphet or PeptideProphet\/iProphet. Retention times are calibrated using an internal or external standard. In addition to a cumulative library\, run\-specific libraries are generated for non\-linear RT alignment in OpenSWATH.

   Installation
   \=\=\=\=\=\=\=\=\=\=\=\=

   We strongly advice to install EasyPQP in a Python \[\*virtualenv\*\]\(https\:\/\/virtualenv.pypa.io\/en\/stable\/\). EasyPQP is compatible with Python 3.

   Install the development version of \*easypqp\* from GitHub\:

   \`\`\`\`
       \$ pip install git\+https\:\/\/github.com\/grosenberger\/easypqp.git\@master
   \`\`\`\`

   Running EasyPQP
   \=\=\=\=\=\=\=\=\=\=\=\=\=\=\=

   \*EasyPQP\* is not only a Python package\, but also a command line tool\:

   \`\`\`\`
      \$ easypqp \-\-help
   \`\`\`\`

   or\:

   \`\`\`\`
      \$ easypqp convert \-\-help
      \$ easypqp library \-\-help
   \`\`\`\`

   Docker
   \=\=\=\=\=\=

   EasyPQP is also available from Docker \(automated builds\)\:

   Pull the development version of \*easypqp\* from DockerHub \(synced with GitHub\)\:

   \`\`\`\`
       \$ docker pull grosenberger\/easypqp\:latest
   \`\`\`\`





.. conda:package:: easypqp

   |downloads_easypqp| |docker_easypqp|

   :versions:
      
      

      ``0.1.11-0``,  ``0.1.10-0``,  ``0.1.9-0``,  ``0.1.8-0``,  ``0.1.7-0``,  ``0.1.6-0``,  ``0.1.5-0``,  ``0.1.0-0``

      

   
   :depends biopython: 
   :depends click: 
   :depends matplotlib-base: 
   :depends numpy: 
   :depends pandas: 
   :depends pyopenms: 
   :depends pyprophet: 
   :depends python: ``>=3.6``
   :depends scipy: 
   :depends seaborn: 
   :depends statsmodels: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install easypqp

   and update with::

      conda update easypqp

   or use the docker container::

      docker pull quay.io/biocontainers/easypqp:<tag>

   (see `easypqp/tags`_ for valid values for ``<tag>``)


.. |downloads_easypqp| image:: https://img.shields.io/conda/dn/bioconda/easypqp.svg?style=flat
   :target: https://anaconda.org/bioconda/easypqp
   :alt:   (downloads)
.. |docker_easypqp| image:: https://quay.io/repository/biocontainers/easypqp/status
   :target: https://quay.io/repository/biocontainers/easypqp
.. _`easypqp/tags`: https://quay.io/repository/biocontainers/easypqp?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/easypqp/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/easypqp/README.html