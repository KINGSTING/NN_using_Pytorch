# 📝 Short Description of Activity 2

This activity provided practical mastery over the foundational elements of deep learning using PyTorch.

1. PyTorch Core Mechanics

    Tensors & Data Flow: Confirmed Tensors as the universal data structure. Learned to manage input shapes (e.g., y.unsqueeze(1)) and convert NumPy data to torch.FloatTensor for use with the framework.

    Automatic Differentiation (autograd): Understood that loss.backward() and optimizer.step() automate backpropagation by dynamically computing and applying gradients, which is crucial for efficient training.

2. Model Architecture and Training

    Network Structure: Successfully built a neural network using nn.Module with two ReLU hidden layers for non-linearity and an output layer suitable for binary classification.

    Loss Function: Used nn.BCEWithLogitsLoss, which provides numerical stability by combining the Sigmoid activation and the Binary Cross-Entropy loss internally.

    Optimization: Employed the Adam optimizer to efficiently adjust weights based on the calculated gradients, ensuring the model converges to a good minimum.

3. Pipeline Essentials

    Data Scaling: Learned that Min-Max scaling the input features (X) is vital for model stability and accelerating training convergence.

    Evaluation: Recognized that for classification, Accuracy is insufficient. Metrics like Precision, Recall, and F1-Score are necessary to fully assess performance, particularly in imbalanced scenarios.

    Visualization: Confirmed the utility of Loss Curves (to monitor convergence) and the Decision Boundary plot (to visualize the model's learned classification rule in the feature space).
