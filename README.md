Tutorial on Machine Learning for Theorem Proving
================================================

Demostration accompanying the [NeurIPS 2023 Tutorial on Machine Learning for Theorem Proving](https://machine-learning-for-theorem-proving.github.io/).

## TODOs

* Add Docker
* Add Colab
* See if Albert and Emily have things to add


## Part I: Training and Evaluating LLMs for Theorem Proving


### Requirements

```bash
conda create --yes --name ml4tp python=3.10 ipython numpy
conda activate ml4tp
conda install pytorch cpuonly -c pytorch  # System-dependent, see https://pytorch.org/ for details. You do not need a GPU to run this tutorial.
pip install notebook ipywidgets transformers lean-dojo
```



## Part II: LLMs as Copilots for Theorem Proving

### Requirements


## Other Resources

[Sean Welleck's IJCAI 2023 tutorial on neural theorem proving](https://github.com/wellecks/ntptutorial)


## Citation

If you find this tutorial useful, please cite:
```bibtex
@misc{ml4tptutorial2023,
  author = {First, Emily and Jiang, Albert and Yang, Kaiyu},
  title = {{NeurIPS} Tutorial on Machine Learning for Theorem Proving},
  year = {2023},
  howpublished = {\url{https://machine-learning-for-theorem-proving.github.io}},
}
```



```bibtex
@inproceedings{yang2023leandojo,
  title={{LeanDojo}: Theorem Proving with Retrieval-Augmented Language Models},
  author={Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima},
  booktitle={Neural Information Processing Systems (NeurIPS)},
  year={2023}
}
```

```bibtex
```