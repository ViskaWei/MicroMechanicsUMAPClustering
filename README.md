# MicroMechanicsUMAPClustering
A UMAP-based Clustering Method for Multi-scale Damage Analysis of Laminates

Please refer to 'UMAP_Clustering.ipynb' to see the results in paper.

Code will be public once the paper is published.




# Instruction
### Install and setup virtual environment
```sudo apt-get install python3-venv ```
```mkdir -p ~/venv```
```cd ~/venv```
```python3 -m venv mmuc```
```source ~/venv/mmuc/bin/activate```

### Upgrade setuptools 
```pip3 install --upgrade setuptools```

### Install MMUC
```python3 setup.py install```

### Run test
```mmuc-test ```

### Clean 
```python3 setup.py clean --all ```
