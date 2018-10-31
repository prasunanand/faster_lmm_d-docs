Faster-LMM-D
========

A faster lmm for GWAS. It has multi-core and GPU support.

Usage:


..  highlight :: guess
    ./faster_lmm_d --control=data/genenetwork/BXD.json --pheno=data/genenetwork/104617_at.json --geno=data/genenetwork/BXD.csv --cmd=rqtl

Features
--------

- LD Pruning
- Kinship Calculation
- Linear Regression
- Logistic Regression
- Linear Mixed Models
- Multivariate Linear Mixed Models (WIP)
- Supports CUDA/OpenCL and Multi-core CPUs

Installation
------------

Install faster_lmm_d by running:

..  code-block:: guess
    git clone https://github.com/genetics-statistics/faster_lmm_d
    make CUDA=1

Contribute
----------

- Issue Tracker: https://github.com/genetics-statistics/faster_lmm_d/issues
- Source Code: https://github.com/genetics-statistics/faster_lmm_d

Support
-------

If you are having issues, please let us know.

License
-------

This software is distributed under the GPL3 license.
