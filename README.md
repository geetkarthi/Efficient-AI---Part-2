# Efficient-AI---Part-2

The two pruning methods used in the project are Fine-grained pruning and Vector-level Pruning.
The enclosed code contains the accuracy graph for the pruning methods over different percentages of pruning, along with other factors of performance. 
These factors include Memory size, Training time and Inference Speed.
These factors have been compared in a graph, and these graphs have been shown in the final results. 
The code uses the CIFAR-10 dataset, and a custom deep learning neural network - upon which the two pruning methods have been applied.
The fine-grained pruning method is based on weight magnitude, which means the low weight neurons have been pruned. 
The vector-level pruning considers the entire vector for each filter, and just removed them - again based on weight magnitude. 
