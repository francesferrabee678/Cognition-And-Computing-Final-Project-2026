# Cognition-And-Computing-Final-Project-2026

## The task

The aim of this project was to choose and implement a generative model and explore how well it could learn representations of the Fashion-MNIST dataset.

I chose to use a **Deep Belief Network (DBN)** because it can learn hierarchical representations by stacking multiple Restricted Boltzmann Machines (RBMs). I wanted to see how the features changed between layers and whether deeper layers could learn more useful representations of the data.

## How I approached the project

I first experimented with different architectures, including a CNN-DBN hybrid, but eventually decided to use a standard DBN. I trained the RBMs using Contrastive Divergence and gradually reduced the number of hidden units across the layers.

After training the model, I explored the representations it had learned through feature visualization, clustering and classification. I also tested how well the model performed when the images contained noise, when there were adversarial attacks, and when there were few labelled examples.

Overall, I found that the deeper layers were able to learn clearer and more distinguishable features, although they were also more sensitive to noise.

Here is the full project:[Cognition and computation](https://github.com/francesferrabee678/Cognition-And-Computing-Final-Project-2026/blob/main/cognition_and_compuation%20project.ipynb)

 I received a final grade of **11/10** for this final project which is an unusually high result for this course.
