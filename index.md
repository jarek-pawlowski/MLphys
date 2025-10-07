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
1. Preliminary problems
- simple perceptron networks
- Universal Approximation Theorem
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/18a24dcba8536ed4d1218c9a7bbd3eab/preliminary_problems.ipynb)
2. Handwritten digits classification using MNIST dataset with Pytorch
- models: perceptron, deep fully-connected network, generic CNN
- various activations
- overfitting
- regularization, early stopping
- generalization on wallpaper dataset
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/8c785dbedd66f26d9ba95a78303e6668/mnist_in_3_flavours.ipynb)
<!--
- take MNIST dataset, apply some simple geometric transformations, and check if such dataset extending improves accuracy:
    * use simple transformations (e.g. flip, rotate, translate, scale) using [scikit-image](https://scikit-image.org/docs/dev/api/skimage.transform.html), or [open-cv](https://docs.opencv.org/4.x/da/d6e/tutorial_py_geometric_transformations.html)
    * or use [albumentations](https://github.com/albumentations-team/albumentations) library, demo: https://demo.albumentations.ai/
    * verify if applying flips or rotations > 45 deg improve accuracy or not, why?
-->
3. ECG signal classification
- classifiers comparison: SVM, decision trees, random forests
- feature vectors and dimensionality reduction (PCA)
- scikit-learn library
- [Colab notebook](https://colab.research.google.com/gist/jarek-pawlowski/982ff9d80cbf2c442bf478cf37549733/ecg_classification.ipynb)
4. Group equivariant CNNs
5. Physics-informed NNs
6. Transformer encoder or GANs?

## proposed seminar topics
- [list of proposed topics](https://github.com/jarek-pawlowski/MLA2025/blob/main/seminar_project_topics.pdf)
