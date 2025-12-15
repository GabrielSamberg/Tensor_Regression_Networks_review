# Tensor_Regression_Networks_review
In modern day Data Science one can often stumble upon natural data sets from fields like biology or medicine in which the data is naturally organized as high order tensors. Many Machine Learning or Deep Learning models (especially the ones that are designed for the task of classification) have what is called fully connected layers as part of the model. such layers require the flattening of the high order activation tensors and as a by product, the multi modal topology of the tensor is being lost. An additional drawback of this approach of flattening multi modal tensors and passing them through fully connected layers is due to the fact that fully connected layers require a large number of parameters.

To address these drawbacks the authors of the paper suggesting to utilize the tools introduced in Tensorial Algebra and incorporate them into a new type of end to end trainable layer that can replace the traditional components of the model that result in the loss of the multimodal structure. The new suggested layers preserve the multimodal structure of the activation tensors and cost altogether in much less parameters while preserving high levels of overall accuracy of the model.

Here is a [detailed pdf](./Tensor_Regression_Networks_paper_review-2.pdf) describing the mathematical framework, implementation detail and experiment reproduction done by me.

Below you can find a Colab notebook containing documented implementation of this review.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/GabrielSamberg/Tensor_Regression_Networks_review/blob/main/Tensor_Regression_Networks.ipynb
)

![Alt text](./Tensor%20Networks%20experiment%20reproduction.png)

