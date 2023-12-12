Tutorial on Machine Learning for Theorem Proving
================================================

Demonstration accompanying the [NeurIPS 2023 Tutorial on Machine Learning for Theorem Proving](https://machine-learning-for-theorem-proving.github.io/).

## Part I: Training and Evaluating LLMs for Theorem Proving


### Requirements

```bash
conda create --yes --name ml4tp python=3.10 ipython numpy
conda activate ml4tp
conda install --yes -c pytorch -c nvidia pytorch pytorch-cuda=11.8  # System-dependent, see https://pytorch.org/ for details. You do not need a GPU to run this tutorial.
pip install notebook ipywidgets tqdm transformers[torch] datasets lean-dojo
```
