.. raw:: html

   <div align="center">
     <a href="https://github.com/frootlab/pandora">
       <img src="https://raw.githubusercontent.com/frootlab/motley/master/docs/logo/Motley-256.png">
     </a>
     <br>
   </div>

Motley
======

.. image:: https://travis-ci.org/frootlab/motley.svg?branch=master
  :target: https://travis-ci.org/frootlab/motley
  :alt: Building Status

.. image:: https://readthedocs.org/projects/motley/badge/?version=latest
  :target: https://motley.readthedocs.io/en/latest/?badge=latest
  :alt: Documentation Status

.. image:: https://badge.fury.io/py/motley.svg
  :target: https://badge.fury.io/py/motley
  :alt: PIP Version

*Motley* is a planed catalog server for algorithm storage and evaluation and
based on GIT. Motley aims to serve as an algorithm catalog to allow the usage
of abstract **currently best fitting** (CBF) algorithms, as required by the
**Cloud-Assisted Meta Programming** (CAMP) paradigm.

Thereby Motley is required to host and deliver algorithms as well es to
cyclically evaluate and index them with respect to their corresponding metrics,
using `Nemoa`_. An example for such a metric would be the average prediction
accuracy within a fixed set of gold standard samples of the respective domain of
application (e.g. latin handwriting samples, spoken word samples, TCGA gene
expression data, etc.). Consequently Motley is also required to host or connect
these samples by using `Pandora`_.

Due to this approach motley allows the implementation of *enterprise analytics*
projects, that are automatically kept up-to-date by a minimum of maintenance
costs. Also motley supports scientific applications, by facilitating a local
(workgroup, lab, institution) or global publication, application and evaluation
of algorithms, e.g. developed within a PhD-position or program.

Motley is `open source`_, based on the `Python`_ programming language and
actively developed as part of `Project Infimum`_ at `Frootlab`_.

Current Development Status
--------------------------

Motley currently is in late *Planning* stage, which immediately is followed by
the *Pre-Alpha* stage. This means, that the projects directives, requirements
and goals are mostly settled but so far only hardly implemented.

Installation
------------

Comprehensive information and installation support is provided within the
`online manual`_. If you already have a Python environment configured on your
computer, you can install the latest distributed version by using pip::

    $ pip install motley

Documentation
-------------

The latest Motley documentation is available as an `online manual`_ and for
download in the formats `PDF`_, `Epub`_ and `HTML`_.

Contribute
----------

Contributors are very welcome! Feel free to report bugs and feature requests to
the `issue tracker`_ provided by GitHub.

Contribute
----------

Contributors are very welcome! Feel free to report bugs and feature requests to
the `issue tracker`_ provided by GitHub. Currently, as the Frootlab Developers
team still is growing, we do not provide any Contribution Guide Lines to
collaboration partners. However, if you are interested to join the team, we
would be glad, to receive an informal `application`_.


License
-------

Motley is `open source`_ and available free for any use under the `GPLv3
license`_::

   © 2019 Frootlab Developers:
     Patrick Michl <patrick.michl@gmail.com>

.. _Python: https://www.python.org/
.. _Project Infimum: https://github.com/orgs/frootlab/projects
.. _Frootlab: https://github.com/frootlab
.. _Nemoa: https://github.com/frootlab/nemoa
.. _Pandora: https://github.com/frootlab/pandora
.. _online manual: https://motley.readthedocs.io/en/latest/
.. _PDF: https://readthedocs.org/projects/motley/downloads/pdf/latest/
.. _Epub: https://readthedocs.org/projects/motley/downloads/epub/latest/
.. _HTML: https://readthedocs.org/projects/motley/downloads/htmlzip/latest/
.. _issue tracker: https://github.com/frootlab/motley/issues
.. _application: patrick.michl@gmail.com
.. _open source: https://github.com/frootlab/motley
.. _GPLv3 license: https://www.gnu.org/licenses/gpl.html
