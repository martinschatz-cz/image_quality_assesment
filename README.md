# Image Quality Assesment

The tested package pyimg is available on GitHub [https://github.com/sakoho81/pyimagequalityranking](https://github.com/sakoho81/pyimagequalityranking).

The purpose of this tool is to extract image-quality related statistics from a series of images (a dataset) that can then be used to sort/rank the images according to their relative quality. Such tool could be used for example to find the highest-quality images in a dataset, or to identify and discard low-quality images. The purpose of the software is to figure out, whether certain images were clearly better than the rest in the dataset, or vice versa.

In this repository you can find my test done in Jupyter Hub on data available as test data in original repository. You can find even larger dataset there.

## Jupyter Lab preparation
```
conda install mamba -c conda-forge
mamba create --name imQA python=3.9 jupyterlab -c conda-forge
conda activate imQA
pip install pyimq
```
optional: Code Formatting Jupyter Notebooks with Black
```
mamba install -c conda-forge jupyterlab_code_formatter black isort
```
