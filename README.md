# Setup environment

## Setup by uv
```bash
# clone repo
git clone https://github.com/Ccccraz/alyx_data_tianming.git

# cd to project dir
cd alyx_data_tianming

# sync environment
uv sync
```

## Setup by conda
```bash
# clone repo
git clone https://github.com/Ccccraz/alyx_data_tianming.git

# cd to project dir
cd alyx_data_tianming

# create conda env
conda create -n alyx_data python=3.9

# activate conda env
conda activate alyx_data

# install requirements
pip install .
```

## Get Start

At first, you need to run `setup_alyx.ipynb` to initialize the alyx and one-api settings.

We only need to pay attention to the alyx address and alyx username and password, and the other settings can be set to default.

When you finish the setup, you can use `main.ipynb` to get the data