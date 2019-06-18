# RBMIsing

## Description:
RBMIsing studies how does unsupervised learning acquire features from the prospective of physics. 
I trained a Restrictive Boltzmann Machine (RBM) to extract features of stochastic binary values on a grid and identify the phase transition without prior knowledge of the stochastic distributions.
The learning of RBM is compared with the coarse-graining process in renormalization group. I demonstrated the hidden state of RBM is not the proper counterpart of the coarse-grained input as the original proposition in arXiv:1410.3831, but the RBM reconstructed visual state is the counterpart of the rescaled and coarse-grained input.

## Contents:
This project RBMIsing has three parts in separate colab documents. 
1. [MCMC Ising Model](https://drive.google.com/open?id=1GTzxGebfb-vao0J4q_CzSwC3SPmWakAd) generates spin distributions from the 2D Ising model with Markov Chain Monte Carlo method. 
2. [Temp Classifier](https://drive.google.com/open?id=10qLExy89EIOC-xR3hcRo_ltklT51bdJC) classifies spin distributions into given temperature labels. 
3. [RBM Ising Model](https://drive.google.com/open?id=1kEoVz9gX-RKd6VXEmARyT5RmSOA1ah3q) extracts features of spin distributions with RBMs.

## Usage:
RBMIsing entirely runs on Google's colab. With an available google drive, users simply execute the code cells sequentially. It is recommended to first download and unzip the file, **IsingModel**, in the google drive, so one can skip the parts of generating dataset and training models. 
If one wishes to run RBMIsing somewhere else, e.g., for longer runtime or stronger computation power, one needs to rewrite the save/load parts spreading in RBMIsing.

## File: 
**IsingModel** is a zipped folder including datasets of spin distributions, temperature classifiers, and trained RBMs.


## MIT License
Copyright (c) [2019] [Ken Yeh]
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
