# decision-trees
An easy-to-use library to generate classification and regression trees (CART) for datasets. The software provides flexibility when designing the predictor, with options to set and tune various hyperparameters, as well as to apply bagging (to reduce variance) and random feature selection (to prevent correlation between different sampled trees in bagging).

## Installation
Simply download the four header files in the 'src' folder. Ensure that all four files are saved in the same location on your computer.

## Creating a Classification Tree
To create a classification tree called 'classTree', define the object `ClassificationTree<T, U> classTree(in, out)`, where `in` is a collection of inputs of type `std::vector< std::vector<T> >` and `out` is the collection of corresponding outputs of type `std::vector<U>`.
