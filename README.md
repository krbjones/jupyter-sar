# jupyter-sar
<h1>SAR Analysis with CATALYST library and open data from Sentinel-1</h1>

To properly install and configure Jupyter Notebook:

1) Download a base conda environment
- recommendation: use Miniconda3 with Python 3.8 from: 
https://docs.conda.io/en/latest/miniconda.html#windows-installers). 

2) Create a properly configured Jupyter Notebook Environment (Miniconda shell)<br>
- use the yml file attached, after installing conda, run the following command:<br>
$ conda env create -f pcienv_v02.yml 

3) Once the notebook is installed, you must activate it:<br>
$ conda activate pci2-env

To deactivate an active environment, use<br>
$ conda deactivate pci2-env

4) To open the Jupyter, type:<br>
$ jupyter notebook

5) Once in Jupyter, you can load the notebook:<br>
"SAR_Changes.ipynb"
