Machine Learning in Physics


## lecture notes:
- [machine learning fundamentals](https://drive.google.com/file/d/1ysLemtBLL8Sd6wpi9yyezvCUjNfEOwj9/view?usp=sharing)
- [deep neural networks](https://drive.google.com/file/d/127NxAYWDIMIDwmcQWJzI3ZpSfj2SMNEC/view?usp=sharing)
- [convolutional NNs](https://drive.google.com/file/d/1dL26N0g8p0Tobawi9phNQi7jT18ZfxCw/view?usp=sharing)
- [recurrent neural nets](https://drive.google.com/file/d/1YTWyIBv0TdUaxAJAxMVmxD0vYtd9UpFn/view?usp=sharing)
- [attention and transformers](https://drive.google.com/file/d/17W0Mgn6iOQuZN3kJXyOWqgerW-6YuSqq/view?usp=sharing)
- [autoencoders and GANs](https://drive.google.com/file/d/1oMxmBSDfuG9Ai6GGI-oIGMfNx5rbpxiy/view?usp=sharing)
- [graph CNNs](https://drive.google.com/file/d/1PI0tto1nzdDd2xXpTJzu_UcHWCtiI19w/view?usp=sharing)
- [group-equivariant CNNs](https://drive.google.com/file/d/1Ngsl_LjXYV83iYb5LRwh0Ipwzr_1XUIJ/view?usp=sharing)
- [physics informed NNs](https://drive.google.com/file/d/1VS_wbXDIK5yFyTffE2S5JuO0cPDGSZyf/view?usp=sharing)
- [self- and semi-supervised learning](https://drive.google.com/file/d/1Yb50fLPV3GE8vt8Qntm3RdOBJLWR6_60/view?usp=sharing)

## laboratory classes:

#### 1. Preliminary problems
- simple perceptron networks
- Universal Approximation Theorem
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/18a24dcba8536ed4d1218c9a7bbd3eab/preliminary_problems.ipynb), see also [updated notebook](preliminary_problems_v2.ipynb)

#### 2. Image classification using *MNIST* dataset
- models: perceptron, deep fully-connected network, generic CNN
- overfitting, regularization, early stopping
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/7049be85d3e424693cd899a336a3511e/mnist_in_3_flavours.ipynb)

Extra task - **augmentation**: apply some simple geometric transformations (see e.g. [here](https://drive.google.com/file/d/1yt_euw4TQZT1g1OTepu9vtJ9cYrnbObi/view?usp=sharing)), and check if such dataset extending improves accuracy:
- use simple transformations (e.g. flip, rotate, translate, scale) using [scikit-image](https://scikit-image.org/docs/dev/api/skimage.transform.html), or [open-cv](https://docs.opencv.org/4.x/da/d6e/tutorial_py_geometric_transformations.html),
- or use [TorchVision](https://docs.pytorch.org/vision/0.13/transforms.html) library *online*, during the training.
- Verify if applying flips or rotations > 45 deg improve accuracy or not, why?

Extra task - generalization on **wallpaper groups** [dataset](https://drive.google.com/file/d/1BUz9eZdU-8wMGkEEmPk1IIUi05pH5ZUK/view?usp=sharing):
- repeat the classifier training for a 2D crystallographic structures dataset;
- can we extract similarities between the classes from the confusion matrix?

#### 3. ECG signal classification
- classifiers comparison: SVM, decision trees, random forests
- feature vectors and dimensionality reduction (PCA)
- *scikit-learn* library
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/38b38f6566048c5a5b30e691d22c14b4/ecg_classification.ipynb)

#### 4. Group equivariant CNNs

#### 5. Physics-informed NNs

#### 6. Transformer encoder

## Literature: 
- KP Murphy, [Probabilistic Machine Learning: An Introduction](https://github.com/probml/pml-book/releases/latest/download/book1.pdf)
- KP Murphy, [Probabilistic Machine Learning: Advanced Topics](https://github.com/probml/pml2-book/releases/latest/download/book2.pdf)
- MM Bronstein et al., [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)

## proposed seminar topics
- [list of proposed topics](https://github.com/jarek-pawlowski/MLA2025/blob/main/seminar_project_topics.pdf)
