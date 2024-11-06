Author: Jeffrey Jackson

A simple library to create and use neural networks in c++ with the flexibility to create a broad range of configurations. Aim is to explore the details of artificial intelligence. Meant to use in future applications regarding basic projects like image recognition.

The first version of the library will utilize std::max(0, a) implementation of the ReLU activation function and will use manual calculation using std::vector for the sake of education and exploration. Later implementations will use a piecewise implementation of the ReLU and will use optimized linear algebra libraries(such as the Eigen library) for matrix calculation. 
