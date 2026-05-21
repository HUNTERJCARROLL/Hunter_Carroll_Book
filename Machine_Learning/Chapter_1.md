---
title: Introduction to Machine Learning
author: Hunter Carroll
description: Introductory notes on machine learning.
---

Machine learning is the process of building systems that learn patterns from data and use those patterns to make predictions, classifications, or decisions.

Some other definitions but they really are just communicating the same thing: 

* "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E." - Tom Mitchell

* "Machine learning can be conceptualized as a teacher-student framework, where the teacher provides examples, training data, or feedback. The student, represented by the machine learning model, aims to learn patterns from this input and apply that knowledge to provide answers to new problems." - Farhad Pourkamali’s

Before starting a machine learning project, it is useful to define the core components of the system.

## The Components of Machine Learning

### Data

Data is the information used to train, validate, and test a machine learning model.

Examples include:

- Text, such as emails, articles, or clinical notes
- Images, such as X-rays or photographs
- Numerical datasets, such as prices, lab values, or sensor readings

The quality, quantity, and structure of the data strongly influence how well a model can learn.

### Model

A model is an algorithmic structure that learns patterns from data.

The model takes input data, processes it using internal parameters, and produces an output. For example, a model might take an image as input and output a predicted label, such as “cat” or “dog.”

### Training

Training is the process of showing data to the model so it can adjust its internal parameters.

During training, the model compares its predictions to the correct answers and updates itself to reduce error. Over time, the model should become better at capturing useful patterns in the data.

### Evaluation

Evaluation measures how well the trained model performs on data it has not seen before.

This is important because a model should not only memorize the training data. It should generalize to new examples.

Common evaluation questions include:

- How accurate is the model?
- Does it perform well on unseen data?
- Does it make certain types of mistakes more often than others?
- Is it useful for the task it was designed to solve?

### Iteration

Machine learning projects are usually iterative. After evaluation, you may need to improve the data, adjust the model, tune the training process, or choose a different evaluation method.

A typical workflow looks like this:

1. Collect and prepare data
2. Choose a model
3. Train the model
4. Evaluate performance
5. Improve and repeat
