# COMP3308 Assignment 2

This repository contains source code and .csv files that are required to complete this assignment.

## Getting Started

There are (or there should be) 3 main directories.

### Code

This directory contains the source code and binaries for the program which the assignment will test the k-Nearest Neighbour classifier and the Naive Bayes classifier.

To compile the source code you can either run the build.sh shell script:

```
./build.sh
```

or you can compile manually using:

```
java -d bin/ src/*java
```

The usage of the program is as follows.
```
java -cp bin/ MyClassifier <the training file> <the testing file> <classifier>
```

### COMP3308-assignment2-2018

This directory contains the origin .names and .data file as well as the assignment PDF found on canvas. It may also contain other files as a result of the work done on weka.
