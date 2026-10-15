# CHEMPROP

> Anticloud offline package — upstream: chemprop/chemprop @ `main`.

## What This Project Does

Message Passing Neural Networks for Molecule Property Prediction

**Topics:** chemistry, drug-discovery, machine-learning, neural-networks

## Upstream README

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/source/_static/images/logo/chemprop_logo_dark_mode.svg">
  <img alt="Chemprop Logo" src="docs/source/_static/images/logo/chemprop_logo.svg">
</picture>

# Chemprop

[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/chemprop)](https://badge.fury.io/py/chemprop)
[![PyPI version](https://badge.fury.io/py/chemprop.svg)](https://badge.fury.io/py/chemprop)
[![Anaconda-Server Badge](https://anaconda.org/conda-forge/chemprop/badges/version.svg)](https://anaconda.org/conda-forge/chemprop)
[![Build Status](https://github.com/chemprop/chemprop/workflows/tests/badge.svg)](https://github.com/chemprop/chemprop/actions/workflows/tests.yml)
[![Documentation Status](https://readthedocs.org/projects/chemprop/badge/?version=main)](https://chemprop.readthedocs.io/en/main/?badge=main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Downloads](https://static.pepy.tech/badge/chemprop)](https://pepy.tech/project/chemprop)
[![Downloads](https://static.pepy.tech/badge/chemprop/month)](https://pepy.tech/project/chemprop)
[![Downloads](https://static.pepy.tech/badge/chemprop/week)](https://pepy.tech/project/chemprop)

Chemprop is a repository containing message passing neural networks for molecular property prediction.

Documentation can be found [here](https://chemprop.readthedocs.io/en/main/).

There are tutorial notebooks in the [`examples/`](https://github.com/chemprop/chemprop/tree/main/examples) directory.

Chemprop recently underwent a ground-up rewrite and new major release (v2.0.0). A helpful transition guide from Chemprop v1 to v2 can be found [here](https://docs.google.com/spreadsheets/u/3/d/e/2PACX-1vRshySIknVBBsTs5P18jL4WeqisxDAnDE5VRnzxqYEhYrMe4GLS17w5KeKPw9sged6TmmPZ4eEZSTIy/pubhtml). This includes a side-by-side comparison of CLI argument options, a list of which arguments will be implemented in later versions of v2, and a list of changes to default hyperparameters.

**License:** Chemprop is free to use under the [MIT License](LICENSE.txt). The Chemprop logo is free to use under [CC0 1.0](docs/source/_static/images/logo/LICENSE.txt).

**References**: Please cite the appropriate papers if Chemprop is helpful to your research.

- **Version 1**: [Chemprop: A Machine Learning Package for Chemical Property Prediction](https://doi.org/10.1021/acs.jcim.3c01250).
- **Version 2**: [Chemprop v2: An Efficient, Modular Machine Learning Package for Chemical Property Prediction](https://doi.org/10.1021/acs.jcim.5c02332).
- **Theory**: The theory underpinning Chemprop was initially described in the papers [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) for molecules and [Machine Learning of Reaction Properties via Learned Representations of the Condensed Graph of Reaction](https://doi.org/10.1021/acs.jcim.1c00975) for reactions.
- **Interpretability**:

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
