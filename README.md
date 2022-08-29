# SNGuess

SNGuess is a machine learning supervised classification model designed to find young extragalactic astronomical transients from astronomical alert data.

## Install SNGuess

SNGuess can be installed from PyPI:

```bash
pip install snguess
```

Notebook [snguess_ztf_alert.ipynb](notebooks/snguess_ztf_alert.ipynb) additionally requires to install for its execution a yet unreleased version of [Ampel-HU-astro](https://github.com/AmpelProject/Ampel-HU-astro/). A build from commit `0c17865` has been tested to work correctly. To install with `pip`, simply run:

```bash
pip install git+https://github.com/AmpelProject/Ampel-HU-astro.git@0c1786565c003a5208237f4b6099d3145488a526
```

## Notebooks

The [notebooks folder](notebooks/) contains Jupyter notebooks with examples and code for generating the results shown in the SNGuess article.

## Article

Please see:

N. Miranda, J.C. Freytag, J. Nordin, R. Biswas, V. Brinnel, C. Fremling, M. Kowalski, A. Mahabal, S. Reusch and J. van Santen
**SNGuess: A method for the selection of young extragalactic transients**
_Astronomy & Astrophysics_, Forthcoming article.
[doi:10.1051/0004-6361/202243668](https://doi.org/10.1051/0004-6361/202243668).
_arXiv preprint_ [arXiv:2208.06534](https://arxiv.org/abs/2208.06534).