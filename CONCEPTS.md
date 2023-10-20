<h1 align = 'center', id = "VIT">  Vision Transformer (ViT) </h1>

ViT is a model architecture that treats an image as a sequence of fixed-size patches, linearly embeds them, and then processes them in a manner similar to text sequences in transformers. Unlike conventional convolutional neural networks (CNNs), ViTs use self-attention mechanisms to consider global interactions between image patches.

<h1 align = 'center', id = "SSL"> Self-supervised Learning </h1>

This is a training paradigm where the learning algorithm generates its own supervisory signal, usually from the input data, eliminating the need for labeled datasets. It's a type of unsupervised learning but is structured to mimic supervised learning.

<h1 align = 'center', id = "DINO"> Self-Distillation with No Labels (DINO) </h1>

DINO is a specific method of applying self-supervised learning to ViT. Instead of using explicit labels, DINO uses the knowledge present in different layers of the same network to generate soft targets, essentially making the model teach itself.

<h1 align = 'center', id = "seg"> Semantic Segmentation </h1>

This is a computer vision task where the objective is to classify each pixel in an image into a specific category or class. The discovery that self-supervised ViT features inherently contain information about semantic segmentation suggests that these features capture a deep and nuanced understanding of the image content.

<h1 align = 'center', id = "KNN"> k-NN Classifiers (KNN) </h1>

k-Nearest Neighbors (k-NN) is a simple, non-parametric classification technique. The fact that the extracted ViT features function effectively as k-NN classifiers indicates that the features are not just semantically rich but also distinguishable and clusterable in the feature space.
