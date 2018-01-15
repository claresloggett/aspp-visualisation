
These notebooks were created for the Visualisation and Tidy Data workshop, part of the Advanced Scientific Programming in Python Summer School.

To get started quickly **if** you already have all relevant packages installed:

```
git clone https://github.com/claresloggett/aspp-visualisation
cd aspp-visualisation
jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000
```

We'll use the notebooks in the order:
* Matplotlib_and_tidy_data.ipynb
* Seaborn.ipynb
* Plotly.ipynb

You can create and activate a conda environment from the `environment.yml` file using

```
conda env create -f environment.yml
source activate aspp-visualisation-env
```

Depending on what version of Jupyter you're running, you may need to launch this notebook with a higher data rate limit so that visualisation libraries are not throttled in communicating with the browser, e.g.

```jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000```

This issue is referenced [here](https://github.com/jupyter/notebook/issues/2287).
README.md (END)

