Faster-LMM-D
========

A faster lmm for GWAS. It has multi-core and GPU support.

Usage:

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

    git clone https://github.com/genetics-statistics/faster_lmm_d
    make CUDA=1

Contribute
----------

- Issue Tracker: github.com/genetics-statistics/faster_lmm_d/issues
- Source Code: github.com/genetics-statistics/faster_lmm_d

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@google-groups.com

License
-------

This software is distributed under the GPL3 license.
