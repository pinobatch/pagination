This repository contains all the supplementary material accompanying the paper [_Algorithms for the Bin Packing Problem with Overlapping Items_](http://arxiv.org/abs/1605.00558), to appear in _Computers & Industrial Engineering_ (full reference at  https://authors.elsevier.com/tracking/article/details.do?aid=4952&jid=CAIE&surname=Grange). It comprises:

- A [dataset](gauss) of 10986 random instances distributed in 1831 JSON files.
- The Python 2.7 implementation of our algorithms, partly ported to Python 3.3 by Damian Yerrick. This code was mainly written for internal use. It is provided _as is_, without any guarantee, maintenance or further support.
- Our [numerical analysis of this dataset](http://nbviewer.jupyter.org/github/pagination-problem/pagination/blob/master/analysis.ipynb). This so-called Jupyter Notebook is self-contained and interactive. Reevaluating its cells, testing another ideas or carrying out your own experiments may require some installations on your machine. We recommend using the [Anaconda Distribution](https://www.continuum.io/downloads), which installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.
- The [MIT License](LICENSE).
- This document.

The whole repository can either be retrieved as a zipped archive <kbd>Clone or download / Download ZIP</kbd>, or cloned on your computer if you intend to keep it up to date without downloading the whole thing each time and writing over your own changes.

To use this pagination solver in your own Python programs, add `solve_overload_and_remove_presort.py` and `solver_tools.py` to your project, and then use it as illustrated in the example `solver_tools.py`.