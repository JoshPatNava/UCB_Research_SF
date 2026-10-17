## Environment Documentation

#### Create the environment

conda create -n scvelo_env python=3.11 -y

#### Activate the environment

conda activate scvelo_env

#### Update the tools

python -m pip install --upgrade pip setuptools wheel

#### Common packages

conda install -c conda-forge numpy scipy pandas matplotlib scikit-learn anndata scanpy h5py ipykernel jupyterlab notebook -y

#### Scvelo
python -m pip install scvelo

#### Cellrank

python -m pip install cellrank

#### For citeseq data

python -m pip install muon mudata loompy pyarrow openpyxl

## Environment Fixing

#### Reinstall the numpy
Had to reinstall an older package
pip install numpy==1.26.4