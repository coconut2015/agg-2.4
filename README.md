Anti-grain Geometry 2.4
=======================

This is an unofficial mirror of agg version 2.4 source code from
https://sourceforge.net/projects/agg/ r132 with some modifications.

AGG Official Sites
==================

* http://www.antigrain.com/
* https://sourceforge.net/projects/agg/

Modifications
=============

* Demo related code was removed.
* Agg2D was removed.
* GPC, which is not in a permissive license, was removed.
* Makefiles and CMakefiles are removed as well.
* Simplified directory structure so that only include/ and src/ remains.
* The file ``copying`` was renamed to ``LICENSE.txt``.
* doc/ and some other non-essential files are removed.

These changes are intended to make it easy to integrate agg source code
into another project.
