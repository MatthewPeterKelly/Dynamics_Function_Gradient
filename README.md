# Dynamics Function Gradients

Suppose that you have a function:
f(x) = A(x)\b(x)

You know the gradients of A and b with respect to x, but how to compute the gradient of f with respect to x? 

This collection of files shows one way to solve this problem, while still vectorizing most of the calcualtion. This techinque is particularily useful for fast optimization of complicated systems.

The key file is computeGradientOfBackSlash.m, and the other files show how to use it.

