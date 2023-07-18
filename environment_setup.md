# Set up your python environment


Create Conda environment : Run below command

```
conda create -n fastapi-deployment python=3.8.5
```

Activate your virtual environment

```
conda activate fastapi-deployment
```

Install all the packages in your environment

### Note: In MACOS we need a dependency for lightgbm
```
brew install libomp
```

pip install -r requirements.txt

Create kernel

python -m ipykernel install --user --name fastapi --display-name fastapi-kernel

Launch Jupyter notebook
jupyter lab

Connect jupyter to kernel fastapi-kernel