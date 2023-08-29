## Vectorgrad

Welcome to Vectorgrad, a spin-off of the original [micrograd](https://github.com/karpathy/micrograd).

This is an automatic differentiation library that supports tensor operations and calculus. Here's why I built it:
1) It's much more lightweight and readable compared to bigger libraries such as PyTorch and TensorFlow, this simplified source code allows users to get a much better grasp of how everything works

2) It's orders of magnitude more computationally efficient than its predecessor micrograd as it leverages statically typed numpy arrays
and operations to bundle parameters and leverage parallelism and SIMD calculations

3) It includes a dynamic and customizable neural network library that can build neural networks of arbitrary size and complexity,
and also allows users to choose the activation function at each layer to allow for a more robust model architecture
