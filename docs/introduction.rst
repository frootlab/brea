Introduction
============

*Motley* is a planed catalog server for algorithm storage and evaluation. Motley
aims to serve as an algorithm catalog for `nemoa`_ to allow the client-side
automatic usage of current *state-of-the-art* (STOA) algorithms. Thereby any
respectively used STOA algorithm is determined server-sided by it's category and
a chosen metric. An example for such a metric would be the average prediction
accuracy within a fixed set of *gold standard samples* of the respective domain
of application (e.g. latin handwriting samples, spoken word samples, TCGA gene
expression data, etc.). Nevertheless also the metric by itself can be a STOA
algorithm.

Due to this approach motley allows the implementation of *enterprise analytics*
projects, that are automatically kept up-to-date by a minimum of maintenance
costs. Also motley supports scientific applications, by facilitating a local
(workgroup, lab, institution) or global publication, application and evaluation
of algorithms, e.g. developed within a PhD-position or program.

.. _Python: https://www.python.org/
.. _GPLv3 license: https://www.gnu.org/licenses/gpl.html
.. _issue tracker: https://github.com/frootlab/motley/issues
.. _frootlab: https://github.com/frootlab
.. _nemoa: https://github.com/frootlab/nemoa
