# data-science-environment
starter kit for data science


### environment setup
install anaconda (anaconda is best for creating virtual environments for data science)

switch to python 3.6.5 (if you haven't already) <br>
`brew switch python3 3.6.5`

create a python3 virtual environment named `ds`<br>
`conda env create -f ds.yaml`

activate the virtual environment <br>
`conda activate ds`

add vm as a jupyter kernel <br>
`python -m ipykernel install --user --name ds --display-name "Python (ds)"`

clean the conda installation <br>
`conda clean --all`

install bq helper <br>
`pip install -e git+https://github.com/SohierDane/BigQuery_Helper#egg=bq_helper` <br>

start the jupyter notebook (make sure you switch to the correct kernell) <br>
`jupyter notebook`
