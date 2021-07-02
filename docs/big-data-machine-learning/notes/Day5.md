# Linear Regression

Linear regression is the statistical model that learns from $X$ and predicts $Y$. Model is usually formulated in the following setup. 

Suppose we are given $X_1$ and $X_2$, i.e. call $X = \{X_1, X_2\}$. Suppose also we want to predict $Y$. The term regression comes from regress which means the goal is to minimize the following:
$$\mathbb{E}(Y - \mathbb{E}(Y|X))$$