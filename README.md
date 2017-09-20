# Master thesis

## Perceptual Hashing using Convolutional Neural Networks for Large Scale Reverse Image Search 

This document is my Masterarbeit written at the University of Passau, Germany.

## Abstract
In this master thesis, we present our study on Convolutional Neural Networks Features and Perceptual Hashing for Large Scale Reverse Image Search. We especially focus our attention on robustness of such systems against common modifications (Gaussian blur, color filter, resize, compression, rotation, cropping). In a first part, we design a benchmark to evaluate the speed and accuracy of several existing techniques. These techniques have very good retrieval performances except against rotation and cropping. In a second part, we investigate the use of CNN Features for reverse image search. Experiments show that they are considerably robust against modifications. To efficiently perform a nearest neighbor search we advocate the use of hashing into short binary codes. In a third part, we propose a supervised method for learning a binary hash function that preserve similarity. This method is based on LSH with random projection and Minimal Loss Hashing, we propose a new approach to optimize the hash function in a continuous space. Experiments show that this approach is valid and promising for hashing CNN Features.

## Build with TeXnicCenter

- Build
- BibTex
- Rebuild

License
-------
See the LICENSE file.