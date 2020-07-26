# VASC
#### Variational autoencoder for single cell RNA-seq datasets

Single cell RNA sequencing (scRNA-seq) is a powerful technique to analyze the transcriptomic heterogeneities in single cell level. It is an important step for studying the cell sub-populations and lineages from scRNA-seq data by finding an effective low-dimensional representation and visualization of the original data. The scRNA-seq data are more “noisy” than traditional bulk RNA-seq: in the single cell level, the transcriptional fluctuations are much larger than the average of a cell population and the low amount of RNA transcripts will increase the rate of technical dropout events. In this study, we proposed VASC (deep Variational Autoencoder for SCRNA-seq data), a deep multi-layer generative model, for the dimension reduction and visualization. It can do nonlinear hierarchical feature representations and model the dropout events of scRNA-seq data. Tested on more than twenty datasets, VASC show better performances in most cases and higher stability compared with several dimension reduction methods. VASC successfully re-establishes the embryo pre-implantation cell lineage and its associated genes based on the 2D representation of a large-scale scRNA-seq from human embryos.

## Prerequisites
+ Python 3.5+
+ numpy 1.12.1
+ h5py 2.7.0
+ sklearn 0.18.1
+ tensorflow 1.1.0
+ keras 2.0.6

We recommend to install the newest Anaconda from https://www.continuum.io/downloads.

## Codes
Two python files are included:
- vasc.py: contains a class VASC and a function vase
- helpers.py: auxiliary functions

## Demo
We gave a demo.py and config.py to demonstrate the use of VASC.

## Data
A small dataset from Biase is included for demonstration.
