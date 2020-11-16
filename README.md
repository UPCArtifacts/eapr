# E-APR (Explainable Automated Program Repair)

This repository contains the data and scripts of the [paper](https://arxiv.org/abs/2002.03968 ):

```
E-APR: Mapping the Effectiveness of Automated Program Repair. Aldeida Aleti and Matias Martinez. 
arXiv:2002.03968  (2020)
```

If you use the data and/or scripts, please cite the paper. 

```
@techreport{eapr2020,
 title = {E-APR: Mapping the Effectiveness of Automated Program Repair},
 year = {2020},
 author = {Aldeida Aleti and Matias Martinez},
 url = {http://arxiv.org/pdf/2002.03968},
 number = {2002.03968},
 institution = {arXiv},
 }
```


## Repository organization

### Features Folder

We consider 3 sets of features: 1) [object-oriented features from ckjm_ext](features/oo_features.md), 2) [java features from jct](features/java_method_features.md), and 3) [code features from Coming](features/code_features.md).  

### Plots

We present 3 sets of plots:

#### Plot included in the paper
[Footprints all repaired bugs from RepairThemAll: 5 bug benchmarks 11 repair tools](plots/plots-RepairThemAll-all-patches-11-repair-tools/readme.md)

#### Additional plots from experiments not included in the paper

[Footprints all correctly repaired bugs from RepairThemAll: 5 bug benchmarks 11 repair tools](plots/plots-correctness-RepairThemAll-11-repair-tools/readme.md)


[Footprints all correctly repaired bugs from Defects4J bug benchmark and 16 repair tools](plots/plots-correctness-16-repair-tools/readme.md)


## Contact:

Aldeida Aleti <aldeida.aleti@monash.edu>

Matias Martinez <matias.sebastian.martinez@gmail.com>




