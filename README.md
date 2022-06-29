# Assignment 3

## 183.663 Deep Learning for Visual Computing (2022S)

**Group 9**
* Yu Kinoshita (01623806)
* Michael Köpf (01451815)

## General Remarks

For this exercise, we experimented with two different Deep Learning tasks:

* Object Detection
* Generative Adversarial Networks (GAN)

## File Organization

| File/Directory         | Description                  |
|------------------------|------------------------------|
| `src/object_detection` | Object detection experiments |
 | `src/GAN`              | GAN experiments              |

## System Requirements

* *nix based system or WSL (on Windows), so all shell commands in the notebooks can be executed
* `git`
* `Python` (we recommend >= 3.7)

## Notes on the Experiments

In case you want to reproduce the experiments, we strongly recommend to setup a new virtual environment for each Jupyter notebook to avoid version conflicts.

To run the notebooks, `notebook` or `jupyterlab` has to be installed in the virtual environment.

```bash
pip3 install notebook
```

```bash
pip3 install jupyterlab
```

All other dependencies are installed "on-the-fly" in the notebooks.

Further notes:
* The notebooks in `src/GAN` have been executed on Google Colab.
* The notebook in `src/object_detection` has been executed on a desktop with an NVIDIA RTX 3060 GPU.

