Django Dataset for Code Translation Tasks
=========================================

This repository contains the *Django* dataset used in the paper
[*"Learning to Generate Pseudo-Code from Source Code Using Statistical Machine Translation"*](http://ieeexplore.ieee.org/document/7372045/),
Oda et al., ASE, 2015.

Contents
--------

* Directory **django**: contains the raw data of the Django dataset.
* Directory **src**: contains code to extract Python AST (with some modifications) and their leaf nodes.

Citation
--------

Please cite the following paper in your publication when you used this dataset:

```bibtex
@inproceedings{oda2015ase:pseudogen1,
 author = {Oda, Yusuke and Fudaba, Hiroyuki and Neubig, Graham and Hata, Hideaki and Sakti, Sakriani and Toda, Tomoki and Nakamura, Satoshi},
 title = {Learning to Generate Pseudo-code from Source Code Using Statistical Machine Translation},
 booktitle = {Proceedings of the 2015 30th IEEE/ACM International Conference on Automated Software Engineering (ASE)},
 series = {ASE '15},
 month = {November},
 year = {2015},
 isbn = {978-1-5090-0025-8},
 pages = {574--584},
 numpages = {11},
 url = {https://doi.org/10.1109/ASE.2015.36},
 doi = {10.1109/ASE.2015.36},
 acmid = {2916173},
 publisher = {IEEE Computer Society},
 address = {Lincoln, Nebraska, USA}
}
```
