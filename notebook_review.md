# How to review RADPS Notebooks

All feature development for RADPS will be accompanied by an example notebook to demonstrate the functionality. Below we describe several mechanisms for interacting with the resulting notebooks ranging from very simple to more complex.

## Colab method

This method requires the least amount of effort, but is also the least flexible. To review notebooks via colab, do the following

1. Go to the docs directory in the relevant repository. For the PI2, the most relevant directory is:  https://github.com/casangi/astroviper/tree/main/docs/core_tutorials/imaging 
2. Click on the notebook you are interested in.
[Notebook shown in github with link to colab](notebook_example_github.png)
3. Click on the colab link in the introduction to the notebook.
[Notebook viewed in colab](notebook_sample_colab.png)

## RADPS Hub Method

This method is more complex, but allows the user to interact with the RADPS-Hub infrastructure. It requires the user to be on a VPn or NRAO network.

1. Request connection information from @jsteeb.
2. Navigate to the sprint notebooks in shared. [RADPS Hub interface](radps_hub_interface.png)
3. Copy the sprint notebook you are interested in from the shared folder into your top directory. *Please do not run the notebook in the shared folder to avoid running into resource issues.*

## Locally using a Virtual Environment

### Install from Wheel
1. conda create --name astroviper python=3.13 --no-default-packages
2. conda activate astroviper
3. pip install astroviper

### Build from source and make it editable (how we develop)
1. conda create --name astroviper python=3.13 --no-default-packages
2. conda activate astroviper
3. git clone https://github.com/casangi/astroviper.git
4. cd astroviper
5. pip install -e .


