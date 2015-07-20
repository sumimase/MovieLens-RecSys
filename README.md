# MovieLens-RecSys
Recommender System algorithm based on MovieLens 1M dataset
## Introduction
Realisation of basic UserCF and ItemCF algorithm.
The programs are tested on Movielens 1M dataset. You can download this dataset by this link [ml-1m.zip](http://files.grouplens.org/datasets/movielens/ml-1m.zip).
## How to run?
1. Put the "ml-1m" folder in the directory MovieLens-RecSys.
2. Simply run command:
```shell
python usercf.py
```
or if you are in Linux:
```shell
python usercf.py > run.log 2>&1 &
```
This command will allow the program to run in back stage and run.log will record all outputs of the program.
## Attention
The program will generate a matrix which size is about 6000*6000 in me