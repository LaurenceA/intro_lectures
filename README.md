<h1> intro_lectures </h1>

I am giving these lectures from IPython Notebooks.  I strongly suggest you open them up and play with them yourself!

<h2> Google Colab </h2>
The easiest approach to getting the notebooks working is by uploading them to <a href="https://colab.research.google.com/">Google Colab</a>.  You can either download the notebook, and upload it.  Or you can even load it directly from GitHub by going to "GitHub" instead of "Upload", and pasting in a link to the notebook, e.g.
https://gith<i></i>ub.com/LaurenceA/intro_lectures/blob/master/Lecture_1.ipynb

Note that you may have to delete the
```python
%matplotlib widget
```
line in the first code block in Google Colab.

<h2> Anaconda Python </h2>
If you want to get the notebooks running locally, I advise that you start by installing <a href="https://www.anaconda.com/distribution/">Anaconda Python distribution</a>, which is available on all operating systems, and comes with all the major numerical programming libraries.

In addition, you need to install [PyTorch](https://pytorch.org),
```bash
conda install pytorch torchvision -c pytorch
```
And <a href="https://github.com/matplotlib/jupyter-matplotlib">jupyter-matplotlib</a>, using
```bash
conda install -c conda-forge ipympl

# If using the Notebook
conda install -c conda-forge widgetsnbextension

# If using JupyterLab
conda install nodejs
jupyter labextension install @jupyter-widgets/jupyterlab-manager
jupyter labextension install jupyter-matplotlib
```
