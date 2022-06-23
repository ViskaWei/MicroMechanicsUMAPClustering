# MicroMechanicsUMAPClustering
If using this code for research or industrial purposes, please cite:

A UMAP-based Clustering Method for Multi-scale Damage Analysis of Laminates. Applied Mathematical Modelling





# Before Running the Code

The 'data_Kmatrix.csv' in 'data' folder information of every element in the unit cell (each row represent one element). 

If you want to run your own data, put your own .csv file in 'data' folder. Please set the first row (i.e. 'Number', 'k11'...,'vol') in your .csv exactly same as in 'data_Kmatrix.csv', otherwise the code won't run.

'Number'column represent the element number. 'k11~k66' represent 36 elements in K matrix defined in Eq.8 in the papaer. The last column 'vol' stands for the volume (area) of this element. 

Code will be public once the paper is published.


1. For those who are familiar with basic computer science knowledge, follow the 'Instruction' section below, download the code and run it in Linux. 

2. For those who are not familiar with Linux system, the code can be run directly on google colab: https://colab.research.google.com/drive/1rKWBU73XQN4fKByDSpMiiwynw9U7IGEb?usp=sharing

If you want to use your own data on google colab, simply upload your own .csv data file on '/MicroMechanicsUMAPClustering/data' folder in colab, and change the file name in the code (Line 7). Please set the first row (i.e. 'Number', 'k11'...,'vol') in your .csv data file exactly same as in 'data_Kmatrix.csv', otherwise the code won't run. The calculation time will be longer (might take a few minutes) than running the code in your local server, but it will do the job.

# The Results Generated by Running the Code

The code will generate a excel file containing element of K matrix representing each cluster (center of each cluster) and the volume of each cluster.




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
