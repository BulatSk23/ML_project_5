# ML_project_5
## Non-negative Matrix Factorization for Input Convex Neural Networks

#### Abstract
Input Convex Neural Networks (ICNNs) serve a variety of purposes, such as data inputting, structured prediction, reinforcement learning. The main quality of such networks is that some of their weight matrices contain only non-negative weights. The idea behind this project is to use Non-negative Matrix Factorization (NNMF) to compress ICNNs. The performance of the resulting network is tested on multi-label classification and face image completion tasks, as well as on toy examples.

## Structure of the repository:

  "Toy_examples" - testing ICNN performance on Toy Examples
  
  "Multi_label_classification" - using ICNN for multy-label classification task
  
  "Face_completion" - using ICNN for face image completion task
  
  "NNMF_with_ICNN" - using NNMF with ICNN for all tasks

## Setup and Dependencies:

+ Python/numpy
+ Pytorch (we used 1.4.0)

## Image Completion

This image shows the test set completions on the Olivetti faces dataset over
the 1000 epochs.

![](/images/completion.gif)
