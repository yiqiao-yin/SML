# Representation Learning

There are three major types of *Representation Learning*.

## Artificial Neural Network

The architecture of a basic Artificial Neural Network (ANN) is the following
$$
\underbrace{\begin{bmatrix}
\vdots
\end{bmatrix}}_\text{input}
\rightarrow
\underbrace{\begin{bmatrix}
\vdots
\end{bmatrix}}_\text{output}
$$

- *Regressor*: This type of ANN learns from $X$ and produces an estimated value of $Y$ while $Y$ is continuous. The common loss function is [MSE](https://towardsdatascience.com/https-medium-com-chayankathuria-regression-why-mean-square-error-a8cad2a1c96f).
- *Classifier*: This type of ANN learns from $X$ and produes an estimated probability of $Y$ that is a particular discrete value (aka factor or class). The common loss function is [binary cross-entropy](https://towardsdatascience.com/understanding-binary-cross-entropy-log-loss-a-visual-explanation-a3ac6025181a).
- *Optimizer*: The architecture of an ANN consists of input layer (which is the explanatory variables), hidden layer (if any), the output layer (tailored to the type of problems, regressor or classifier), and a loss function. Once the architecture is setup we can use an optimizer to find the weights that are used in the optimizer. A famous optimizer is called [gradient descent](https://towardsdatascience.com/gradient-descent-explained-9b953fc0d2c).

## Convolutional Neural Network

Some additional sources:
- Computer Vision Feature Extraction: [post](https://towardsdatascience.com/computer-vision-feature-extraction-101-on-medical-images-part-1-edge-detection-sharpening-42ab8ef0a7cd)

## Recurrent Neural Network