# Dogs_and_Cats_CNN
Image Classification - is it a cat or a dog?

The ultimate goal of this project is to create a system that can detect cats and dogs. While our goal is very specific (cats vs dogs), ImageClassifier can detect anything that is tangible with an adequate dataset.

Dataset: Dogs vs Cats

Description: Binary classification. Classify dogs and cats.

Training: 20,000 images (10,000 per class)

Validation: 5,000 images (2,500 per class)

Testing: 12,500 unlabeled images


# Model Architecture:
Input Data Shape: 64x64x3
# Layer 1:

Convolutional Layer 32 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

# Layer 2:

Convolutional Layer 32 filter Filter shape: 3x3

Activation Function: ReLu

Max Pooling Pool shape: 2x2

Classification:

# Flatten

# Dense Size: 128

Activation Function: ReLu

Dropout Rate: 0.5

# Dense Size: 1

Activation Function: Sigmoid
