
## ML_project_5
### Non-negative Matrix Factorization for Input Convex Neural Networks

#### Abstract
Input Convex Neural Networks (ICNNs) serve a variety of purposes, such as data inputting, structured prediction, reinforcement learning. The main quality of such networks is that some of their weight matrices contain only non-negative weights. The idea behind this project is to use Non-negative Matrix Factorization (NNMF) to compress ICNNs. The performance of the resulting network is tested on multi-label classification and face image completion tasks, as well as on toy examples.

### Structure of the repository:

  "Toy_examples" - testing ICNN performance on Toy Examples (with and without NNMF)
  
  "Multi_label_classification" - using ICNN for multy-label classification task (with and without NNMF)
  
  "Face_completion" - using ICNN for face image completion task

### Examples:

#### ICNN decision boundaries on Moons (top), Circles (middle) and 2-class classification (bottom) datasets:
<img
src="https://github.com/ffuntik/ML_project_5/blob/master/pictures/TOY1.png"
max-width=50%;
raw=true
alt="Subject Pronouns"
style="margin-right: 10px;"
/>



#### Examples of Olivetti faces image completion with ICNN (on the test set) over the 1000 epochs:
<img
src="https://github.com/ffuntik/ML_project_5/blob/master/pictures/faces-4.png"
max-width=50%;
raw=true
alt="Subject Pronouns"
style="margin-right: 10px;"
/>
