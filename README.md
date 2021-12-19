# Probabilistic Linear Discriminant Analysis

__Demo with MNIST Handwritten Digits Data__

See [mnist_demo/mnist_demo.ipynb](./mnist_demo/mnist_demo.ipynb).

## Installation

__Installing with `pip`__.

1. Make sure you have the dependencies in [environment.yml](./environment.yml).
2. `pip install https://github.com/RaviSoji/plda/tarball/master`

__Easy install__.

If you are new to programming, research, or sharing remote machines, 
 you will save yourself a lot of headache by installing the following software:
 [`git`](https://git-scm.com/downloads) and 
 [`conda`](https://github.com/conda/conda).

You can make a new conda environment called `myenv` with both this package and 
 its python dependencies automatically installed with the following steps. 

1. `cd` into your favorite directory.
2. `git clone https://github.com/RaviSoji/plda.git`
3. `conda env create -f plda/environment.yml -n myenv`

__Uninstall__

```bash
pip uninstall plda
```

## Testing the software

See [tests/README.md](./tests/README.md).

## Credit and disclaimers

__Paper Citation__

[Ioffe S. (2006) Probabilistic Linear Discriminant Analysis. 
 In: Leonardis A., Bischof H., Pinz A. (eds) Computer Vision – ECCV 2006. 
 ECCV 2006.](ioffe2006plda.pdf)

__More thanks__!

[@seandickert](https://github.com/seandickert) and 
 [@matiaslindgren](https://github.com/matiaslindgren) pushed for and 
 implemented the same-different discrimination and the pip install, 
 respectively!

__Disclaimers__

1. Parameters are estimated via empirical Bayes.
2. I wrote this code while working on an Explainable Artificial Intelligence 
    (XAI) project at the 
    [CoDaS Laboratory](http://shaftolab.com/people.html), 
    so it keeps parameters in memory that are unnecessary for simple 
    classification problems.
   It's intended to be readable to researchers.
