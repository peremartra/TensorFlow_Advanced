# TensorFlow Advanced Techniques

It is a series of notebooks about some “beyond the basics” or mid-advanced techniques with TensorFlow and Keras. 

It could be said that these notebooks pick up where the TensorFlow Developer Certified exam leaves off.

It is not a course or tutoria, just a colletion of notebooks and articles explaining some interesting techniques that you can use with TensorFlow and Keras. 

## Improve TensorFlow performance with Graps Mode. 
Using the *cats_vs_dogs* dataset we are going to explore hot to use the Graph Mode and how it can improve the performance in our Notebooks. 
* Notebook: [graph-mode-vs-eager-mode-in-tensorflow.ipynb](https://github.com/peremartra/TensorFlow_Advanced/blob/main/graph-mode-vs-eager-mode-in-tensorflow.ipynb)
* Article: [Improve the Performance Easily in TensorFlow Using Graph Mode](https://medium.com/towards-artificial-intelligence/improve-the-performance-easily-in-tensorflow-using-graph-mode-288ee35dddae)

## Multiple Outputs with Keras Functional API. 
Using the functional API and a non sequential Model we are going to learn ho to create a model able to predict more than one variable. The Datased used is the *Wine_quality* and we will predict a Classification Variable to classify the wine, and a Regression variable to qualify the wine. 
* Notebook: [guide-multiple-outputs-with-keras-functional-api.ipynb](https://github.com/peremartra/TensorFlow_Advanced/blob/main/guide-multiple-outputs-with-keras-functional-api.ipynb)
* Article: [How To Predict Multiple Variables With One Model? And Why!](https://medium.com/towards-artificial-intelligence/how-to-predict-multiple-variables-with-one-model-and-why-31e6a8efc09e)

## How to create a siamese network with Tensorflow. 
we are going to build a Siamese Model with Tensorflow able to compare images and return a difference between them, identifying when the images are of the same type.
* Notebook: [how-to-create-a-siamese-network-to-compare-images.ipynb](https://github.com/peremartra/TensorFlow_Advanced/blob/main/how-to-create-a-siamese-network-to-compare-images.ipynb)
* Article: [How To Create a Siamese Network With Keras to Compare Images](https://medium.com/towards-artificial-intelligence/how-to-create-a-siamese-network-with-keras-to-compare-images-5713b3ee7a28)

## Using Multiple GPUs with TensorFlow  on Kaggle. 
Recently, Kaggle has introduced the possibility of using two GPUs in our notebooks. We are going to see how to use them in a simple way with TensorFlow.

The technique of using more than one GPU on a single machine is called MirroredStrategy. It is the one we are going to use in Kaggle. Or on our machine if we had more than one GPU.
* Notebook: [using-multiple-gpu-s-with-keras-on-kaggle.ipynb](https://github.com/peremartra/TensorFlow_Advanced/blob/main/using-multiple-gpu-s-with-keras-on-kaggle.ipynb)

By the moment, that's all!

If you want to continue your learning path, I recommend you my [repository about GANs](https://github.com/peremartra/GANs) with 4 notebooks organized as an Introductory course to GenerativeAI. 
