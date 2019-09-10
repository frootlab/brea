<div align="center">
  <img src="https://www.frootlab.org/images/fig/motley.svg" width=350px>
</div>

Motley
======

[![Building Status](https://travis-ci.org/frootlab/motley.svg?branch=master)](https://travis-ci.org/frootlab/motley)
[![Documentation Status](https://readthedocs.org/projects/motley/badge/?version=latest)](https://motley.readthedocs.io/en/latest/?badge=latest)
[![PIP Version](https://badge.fury.io/py/motley.svg)](https://badge.fury.io/py/motley)

*Motley* is a planed catalog server for algorithm storage and evaluation and
based on [GIT](https://git-scm.com/). Motley aims to serve as an algorithm
catalog to allow the usage of abstract **currently best fitting** (CBF)
algorithms, as required by the **Cloud-Assisted Meta Programming** (CAMP)
paradigm.

Thereby Motley is required to host and deliver algorithms as well es to
cyclically evaluate and index them with respect to their corresponding metrics,
using [Rian](https://www.frootlab.org/rian). An example for such a metric
would be the average prediction accuracy within a fixed set of gold standard
samples of the respective domain of application (e.g. latin handwriting samples,
spoken word samples, TCGA gene expression data, etc.). Consequently Motley is
also required to host or connect these samples by using
[Deet](https://www.frootlab.org/deet).

Due to this approach motley allows the implementation of *smart analytics*
projects, that are automatically kept up-to-date by a minimum of maintenance
costs. Also motley supports scientific applications, by facilitating a local
(workgroup, lab, institution) or global publication, application and evaluation
of algorithms, e.g. developed within a PhD-position or program.

Motley is open source, based on the [Python](https://www.python.org/)
programming language and actively developed as part of the [Liquid
Code](https://www.frootlab.org/liquid) framework at
[Frootlab](https://www.frootlab.org).

Current Development Status
--------------------------

Motley currently is in late *Planning* stage, which immediately is followed by
the *Pre-Alpha* stage. This means, that the projects directives, requirements
and goals are mostly settled but so far only hardly implemented.

Installation
------------

Comprehensive information and installation support is provided within the
[online manual](https://motley.readthedocs.io/en/latest/). If you already have a
Python environment configured on your computer, you can install the latest
distributed version by using pip:

    $ pip install motley

Documentation
-------------

The latest Motley documentation is available as an [online
manual](https://motley.readthedocs.io/en/latest/) and for download in the
formats [PDF](https://readthedocs.org/projects/motley/downloads/pdf/latest/),
[EPUB](https://readthedocs.org/projects/motley/downloads/epub/latest/) and
[HTML](https://readthedocs.org/projects/motley/downloads/htmlzip/latest/).

Contribute
----------

Contributors are very welcome! Feel free to report bugs and feature requests to
the [issue tracker](https://github.com/frootlab/motley/issues) provided by
GitHub. Currently, as the Frootlab Developers team still is growing, we do not
provide any Contribution Guide Lines to collaboration partners. However, if you
are interested to join the team, we would be glad, to receive an informal
[application](mailto:application@frootlab.org).

License
-------

Motley is open source and available free for any use under the
[GPLv3](https://www.gnu.org/licenses/gpl.html) license:

    © 2019 Frootlab Developers:
      Patrick Michl <patrick.michl@frootlab.org>
