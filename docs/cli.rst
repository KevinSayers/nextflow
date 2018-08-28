.. _cli-page:

*************
Command Line Interface
*************

Command line
==================

Nextflow has different command line arguments that can be used to modify the execution of workflows or interact with existing runs.  


Nextflow Docker
--------------

Nextflow can be launched using a provided Docker container. This container has been modified to allow additional sibling containers to be launched from within the Nextflow container. Nextflow can be run in this manner using the `-d` option::

    nextflow -d run main.nf

