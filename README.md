# Empirical Analysis of Boosting Error Bound

This is a repository for the [report](https://arxiv.org/abs/2302.00880) on the AdaBoost algorithm's error bound. We provide an empirical verification of the theoretical error bound of the algorithm, by testing it on synthetic and real data. We conclude that the bound holds in both cases.

## Repository Map

`data` — Values we obtained throughout the experiments.

`figs` — Figures we present in the manuscript.

`synthetic.ipynb` — Experiments on synthetic data.

`real_d.ipynb`, `real_m.ipynb` — Experiments on real data. The dataset we used can be found [here](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset).

`manuscript.pdf` — The manuscript itself.

## Citation
```
@inproceedings{inproceedings,
  author={Arman Bolatov, Kaisar Dauletbek},
  title={{Empirical Analysis of Boosting Error Bound}},
  year=2022,
}
```

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/armanbolatov/adaboost_error_bound/blob/main/LICENCE)
