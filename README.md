**Logistic Function in Python**

**This repository demonstrates a simple implementation of the Logistic (Sigmoid) Function using Python and NumPy. The logistic function is widely used in machine learning, especially in logistic regression and neural networks, to map input values to probabilities between 0 and 1.**

**📌 Description**

**The logistic (sigmoid) function is defined as:
It takes any real-valued input and maps it to a value between 0 and 1, making it useful for binary classification problems.**

**🛠 Requirements with code explanation:**

**Python 3.x and NumPy**



**import numpy as np**

**def logistic\_function(z):
"""
Computes the Logistic (Sigmoid) function for a given input z.
"""
return 1 / (1 + np.exp(-z))**

# 

**z = np.array(\[0, 1, -1, 5])  # Example inputs
result = logistic\_function(z)
print("Logistic function output:", result)**

**z=\[0,1,-1,5]**



**Logistic function output:  \[0.5        0.73105858 0.26894142 0.99330715]**

**🧠 Explanation**

**np.exp(-z) computes the exponential of -z**

**The function works with:**

**Scalars**

**Lists**

**NumPy arrays**

**NumPy broadcasting allows element-wise computation efficiently**

**🎯 Applications**

**Logistic Regression**

**Binary Classification**

**Neural Network Activation Functions**

**Probability Estimation**

