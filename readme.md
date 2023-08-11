# Index

## Demistifying E(3)-equivariant neural networks!

Check out the website: https://killiansheriff.github.io/DemistifyingE3NN/index.html

Welcome to our blog post on demistifying E(3)-equivariant neural networks! This blog aim to introduces the following concepts, in order to understand the mathematical tools leading to learnable equivariant operations:

1. Group_representation
1. Irreducible Representations
1. Transformation under Euclidean Symmetries
1. Spherical Harmonics
1. Principle of Equivariance and Polynomials
1. Learnable Tensor Products
1. MLIAP and Data Efficiency

## Disclaimer

This post serves as an explanation of the paper by ``Geiger et al [1]``. It was written as a final project for the ``Fall 2022 Final Project`` section of the ``6.S898: Deep Learning`` course at the ``Massachusetts Institute of Technology``. Needless to say that the intuition presented herein are heavily influenced by the explanations of Geiger et al.

## References 
1. Geiger, M. & Smidt, T. e3nn: Euclidean Neural Networks. Arxiv (2022).

## JupyterBook
```bash
jupyter-book create blog/
jupyter-book build blog/
```
<!-- Inside blog directory to publish online ghp-import -n -p -f _build/html -->

## Citation
If used, please cite: 

```citation
@software{killian_sheriff_2022_7430281,
  author       = {Killian Sheriff and
                  Yifan Cao},
  title        = {killiansheriff/blog\_e3nn: blog\_e3nn},
  month        = dec,
  year         = 2022,
  publisher    = {Zenodo},
  version      = {blog\_e3nn},
  doi          = {10.5281/zenodo.7430281},
  url          = {https://doi.org/10.5281/zenodo.7430281}
}
```
