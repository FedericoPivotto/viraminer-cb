# ViraMiner-CB: Deep Learning Architecture Inspired from GoogleLeNet for Robust Identification of Viral DNA Sequences
Our study propose a new branch that implements an enhancement of the strategies utilized in the branches of ViraMiner.

The new branch modifies the first convolutional layer to simultaneously extract diverse types of information by employing two different convolutional operations: the first applies a 1D convolution and the second a 2D convolution. This innovation is inspired by the architecture of GoogleLeNet, which represents the first implementation and application of the Inception Layer.

We suggest that the developed model can effectively capture diverse types of genetic information and thereby enhance the performance of the previously proposed ViraMiner network.

# Authors
- Federico Pivotto, 2121720
- Fabrizio Genilotti, 2119281
- Leonardo Egidati, 2106370

# Note
To run the notebooks successfully, ensure that both the base directory (of the notebook) and the ```/pretrained``` directory do not contain any trained model.
Running the notebook involves training all models for validation.

It is possible to run the notebooks by skipping the cells of the sections "Learning curve" and "Accuracy curve".