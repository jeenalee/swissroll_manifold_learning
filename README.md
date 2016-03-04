# Manifold Learning on Swissroll Data

This script generates swissroll data using scikit-learn built-in data generating function, and applies different manifold learning methods to the data. You can specify the noise level you want to introduce to the data in the script. With noise level of zero, the script generates an image like below:
![alt sample_image](https://github.com/jeenalee/swissroll_manifold_learning/blob/master/sample_image.png)
The first image on the first row is the original swissroll data, and the other images are the results of different manifold learning methods. Number of component is set to two so that the 2-dimensional plot can accurately capture the manifold learning results.

With increased noise, some manifold learning methods start to fail, as you can see in the gif below:
![alt sample_gif](https://github.com/jeenalee/swissroll_manifold_learning/blob/master/manifold_noise.gif)
The gif was created by making plots with different noise level, and using a gif making website.
