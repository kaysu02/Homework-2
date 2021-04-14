## To Do

- Complete the [PyTorch Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html "PyTorch Blitz") tutorial.
- Create a neural network to classify the preloaded data in the Jupyter Notebook provided
    * Create data loader
    * Create model
    * Create criterion
    * Data loop over epochs and batches
    * Iterate over the minibatches in random order
    * Reset gradient and perform forward pass, backpropogation, and optimizer step
    * Validate on test set
- Push your code to submit your work
- Attend a mentor session to defend your implementation and answer questions

## Important Note
- If you do not want to use a Jupyter Notebook, use these commands to import the data: `data_train = torchvision.datasets.MNIST('./', download=True, train=True, transform = transform)`
`data_test = torchvision.datasets.MNIST('./', download=True, train=False, transform = transform)`
- Please pay attention when reading through the tutorial because the mentors will be asking you questions
- If you have issues with installation, post on Piazza first so that others can view possible solutions
