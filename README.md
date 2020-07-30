# Explaining the Unique Nature of Individual Gait Patterns with Deep Learning

![overview figure](./figures/overview.png)

This repository contains the python code for training and evaluation of models as presented in
[Explaining the unique nature of individual gait patterns with deep learning](https://doi.org/10.1038/s41598-019-38748-8)
```
@article{horst2019explaining,
  author = {Horst, Fabian and Lapuschkin, Sebastian and Samek, Wojciech and M{\"u}ller, Klaus-Robert and Sch{\"o}llhorn, Wolfgang I.},
  title = {Explaining the Unique Nature of Individual Gait Patterns with Deep Learning},
  journal = {Scientific Reports},
  publisher = {Nature Publishing Group},
  year = {2019},
  number = {9},
  pages = {2391},
  doi = {10.1038/s41598-019-38748-8},
  url = {https://doi.org/10.1038/s41598-019-38748-8}
}
```


Folder `figures` contains code and data for (generating) the figures shown in the paper.

Folder `python` contains code for model training and evaluation, based on python2, as a derivation of the python sub-package of the [LRP Toolbox (version 1.2.0)](https://github.com/sebastian-lapuschkin/lrp_toolbox). Should you use or extend this implementation please consider citing the toolbox, as well as our paper mentioned above.
```
@article{lapuschkin2016toolbox,
    author  = {Lapuschkin, Sebastian and Binder, Alexander and Montavon, Gr{\'e}goire and M\"uller, Klaus-Robert and Samek, Wojciech},
    title   = {The LRP Toolbox for Artificial Neural Networks},
    journal = {Journal of Machine Learning Research},
    year    = {2016},
    volume  = {17},
    number  = {114},
    pages   = {1-5},
    url     = {http://jmlr.org/papers/v17/15-618.html}
}
```

The recorded gait data used in the paper is available from [the Mendeley Data Repository](http://dx.doi.org/10.17632/svx74xcrjr.1), or in compact vector format in the file `python/Gait_GRF_JA_Label.mat`, which is part of this repository.
When using or refering to that data, please cite
```
@misc{horst2018public,
	author = {Horst, Fabian and Lapuschkin, Sebastian and Samek, Wojciech and M\"uller, Klaus-Robert and Sch\"ollhorn, Wolfgang I},
	title = {A public dataset of overground walking kinetics and full-body kinematics in healthy individuals},
	year = {2018},
	howpublished = {Mendeley Data Repository},
	note = {\url{http://dx.doi.org/10.17632/svx74xcrjr.1}}
}
```


Files describing the training, validation and test splits, the trained models on different feature sets (in part not discussed in the paper) and target labels (in part not discussed in the paper), as well as the model outputs, scores and analyses obtained via LRP and perturbation analysis can be downloaded from the following locations, grouped by model type:

+ [linear.tar.gz (61G)](https://datacloud.hhi.fraunhofer.de/nextcloud/s/kcXRTa3QAKFHbyb) 
+ [2-layer-mlp.tar.gz (58G)](https://datacloud.hhi.fraunhofer.de/nextcloud/s/W6ekYr2w49PHmA7) 
+ [3-layer-mlp.tar.gz (59G)](https://datacloud.hhi.fraunhofer.de/nextcloud/s/9eg4x3L3YTw75si) 
+ [cnns.tar.gz (45G)](https://datacloud.hhi.fraunhofer.de/nextcloud/s/oRnCfqEjzMRRPgZ) 

