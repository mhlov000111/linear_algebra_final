# Linear Algebra Final Project

main.ipynb contains all the code used to prepare the data and train the classifier.

*There's one error in the file, main.ipynb: in the comment describing the model architecture of the twice nonlinear model, it describes the linear transformation as softmax(B(ReLU(Ax))) = y; instead, the architecture should be: softmax softmax(C(ReLU(B(ReLU(Ax))))) = y
