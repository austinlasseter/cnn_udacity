Notebook: CNNs in PyTorch
Now, you're ready to define and train an CNN in PyTorch.

To open this notebook, you have two options:

Go to the next page in the classroom (recommended).
Clone the repo from Github and open the notebook cifar10_cnn_exercise.ipynb in the convolutional-neural-networks > cifar-cnn folder. You can either download the repository with git clone https://github.com/udacity/deep-learning-v2-pytorch.git, or download it as an archive file from this link.
Instructions
Define a CNN model for classifying CIFAR10 images
Train it for some number of epochs and test your model to see how well it generalizes and measure its accuracy.
This is a self-assessed lab. If you need any help or want to check your answers, feel free to check out the solutions notebook in the same folder, or by clicking here.

GPU Workspaces
The next workspace is GPU-enabled, which means you can select to train on a GPU instance. The recommendation is this:

Load in data, test functions and models (checking parameters and doing a short training loop) while in CPU (non-enabled) mode
When you're ready to extensively train and test your model, enable GPU to quickly train the model!
All models, and the data they see as input, will have to be moved to the GPU device, so take note of the relevant movement code in the model creation and training process.
