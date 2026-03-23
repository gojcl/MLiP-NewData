# Extra Data for Model Training

## Overview

This repository contains experimental code developed during our participation in the Akkadina Deep Past challenge. The goal of this code was to generate additional data to potentially improve the core model's performance.

## Motivation

We aimed to enhance the model by increasing the amount of training data through augmentation or synthetic generation. The idea was that more data could:

* Improve model generalization
* Strengthen overall performance
* Provide more diverse training examples

## Approach

We implemented a pipeline to generate additional data and incorporated it into the training process. The model was then trained and fine-tuned using this expanded dataset.

## Outcome


Using the extended dataset consistently led to **out-of-memory (OOM)** errors during training and fine-tuning.

* Training with the larger dataset exceeded available memory
* Fine-tuning became unstable or infeasible
* The approach could not be successfully integrated into the workflow

## Conclusion

Although increasing the dataset size was intended to improve the model, in practice it introduced significant computational constraints. Due to repeated OOM issues, this approach was ultimately not viable and was not included in the final solution.


## Notes

This repository represents an **experimental attempt** and is included as part of our development and exploration process.
