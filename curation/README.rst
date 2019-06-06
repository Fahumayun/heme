Heme Knowledge
==============
This folder is the location for curation of a terminology surrounding heme biology, its mechanistic
knowledge, and related quantitative kinetic information.

Installation
------------
To install the ``heme_knowledge`` python package for programmatic access to the BEL files
in this repository, use the following code in your shell:

.. code-block:: sh

    $ git clone https://gitlab.scai.fraunhofer.de/daniel.domingo.fernandez/heme.git
    $ cd heme/curation
    $ pip install -e .

To compile all of the BEL files, use

.. code-block:: sh

    $ heme-knowledge compile


Curation Guidelines
-------------------
This section describes the guidelines used for the curation of the BEL documents.

Annotations
~~~~~~~~~~~
1. TimePoint.
2. Species.
3. Concentration.
