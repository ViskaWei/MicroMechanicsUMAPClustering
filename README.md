# MicroMechanicsUMAPClustering
If using this code for research or industrial purposes, please cite:

A UMAP-based Clustering Method for Multi-scale Damage Analysis of Laminates. Applied Mathematical Modelling

The 'data_Kmatrix.csv' in 'data' folder contains each row contains information of one element. 

'k11~k66' represent 36 elements in K matrix defined in Eq.8 in the papaer. The last column 'vol' stands for the volume of this element. 

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
