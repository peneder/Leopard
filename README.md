## Leopard: fast decoding cell type-specific transcription factor binding landscape at single-nucleotide resolution

Please contact (hyangl@umich.edu or gyuanfan@umich.edu) if you have any questions or suggestions.

![Figure1](figure/fig1.png?raw=true "Title")

---

## Installation
Git clone a copy of code:
```
git clone https://github.com/GuanLab/Leopard.git
```
## Required dependencies

* [python](https://www.python.org) (3.6.5)
* [numpy](http://www.numpy.org/) (1.13.3). It comes pre-packaged in Anaconda.
* [pyBigWig](https://github.com/deeptools/pyBigWig) A package for quick access to and create of bigwig files. It can be installed by:
```
conda install pybigwig -c bioconda
```
* [tensorflow](https://www.tensorflow.org/) (1.14.0) A popular deep learning package. It can be installed by:
```
conda install tensorflow-gpu
```
* [keras](https://keras.io/) (2.2.5) A popular deep learning package using tensorflow backend. It can be installed by:
```
conda install keras
```

## Dataset
The DNase-seq data were downloaded from the ENCODE-DREAM challenge website:
[filtered alignment](https://www.synapse.org/#!Synapse:syn6176232)

The ChIP-seq data were downloaded from the ENCODE-DREAM challenge website:
[conservative peaks](https://www.synapse.org/#!Synapse:syn6181337) and [fold enrichment](https://www.synapse.org/#!Synapse:syn6181334)
and the [ENCODE project](https://www.encodeproject.org/)(The accession numbers are provided in Supplementary Table 4.)




