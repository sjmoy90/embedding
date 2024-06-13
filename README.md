# Getting started

## (1) Clone repo
`git clone https://github.com/sjmoy90/embedding.git`

## (2) Make requirements

### (2a) Change directory:
`cd embedding`

### (2b) Create a virtual environment (here, it is called "env"):
`virtualenv env -p python3`

### (2c) Activate the virtual environment:
`source env/bin/activate`

### (2d) Then install the required packages
`pip install -r requirements.txt`

## (3) Create a new kernel to use with iPython / Jupyter Notebook
`python -m ipykernel install --user --name env_embedding --display-name "embedding"`

## (4) Open Jupyter notebook, change kernel, then run!
`jupyter notebook embedding_example.ipynb`

Then change the kernel to the one you created in (2b). After that, you can run the notebook!
