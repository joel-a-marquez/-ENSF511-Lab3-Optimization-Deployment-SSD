<!-- ABOUT THE LAB -->
# ENSF 511 (W2022) - Lab 3: Model Optimization, Deployment, and SSD Models

The primary objective of the lab is to look into the techniques to optimize and reduce computational 
and storage resource using tensorflow model optimization ([link](https://www.tensorflow.org/model_optimization/guide)).
We will also look into SD-Mobilenet-v1 and see how it performs on real videos.
The repository will be split into three folders tackling each assignment as mentioned in the guideline in the slide:

    Part 1) – Investigate some of the options in TensorFlow
    https://www.tensorflow.org/lite/performance/model_optimization (quantization
    methods, pruning, and clustering) and evaluate the performance vs model size of the
    Mobilenet-v2 classification model presented in the Lab.
  
    Part 2) – Evaluate the performance of the Mobilenet-v2 classification model when trained
    with images of 112x112 instead of 224x224.
  
    Part 3) – Evaluate the accuracy of the SSD-Mobilenet-v1 model with the 2000 bobcat and
    2000 cat images. How does it perform on real videos?

Each folder will contain jupyter notebooks to answer the assignment. A separate notebook for results
and discussion will also be included to reflect on the results obtained (in the format of *Lab3_Part#_(Discussion).ipynb)*.
The models produced in the training will not be provided in the repository.
