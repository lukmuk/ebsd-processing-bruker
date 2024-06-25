# EBSD Processing with Bruker Systems

EBSD processing scripts and notes for data acquired on Bruker systems.

### Convert bcf to hdf5

Extract raw diffraction patterns for processing in other software.
Use this [guide](https://lukmuk.github.io//posts/2024/05/blog-ebsd-bcf/) to extract the data from the bcf.  
Then, we can use [this notebook](https://github.com/lukmuk/ebsd-processing-bruker/tree/main/kikuchipy-bcf2hdf5-converter) to clean up and shrink the data.
