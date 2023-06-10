This repository is for ERA V1 Assigment 5: PyTorch 101
--------------------------------------------------------------------

Taks Assigned were as follows:
1. Re-look at the code that we worked on in Assignment 4 (the fixed version). 
2. Move the contents of the code to the following files:
     model.py
     utils.py
     S5.ipynb
3. Make the whole code run again. 
4. Upload the code with the 3 files + README.md file (total 4 files) to GitHub. README.md (look at the spelling) must have details about this code and how to read your code (what file does what). Heavy negative scores for not formatting your markdown file into p, H1, H2, list, etc. 

--------------------------------------------------------------------

As the assignment was to modularize the code. I have moved block 7 is moved to model.py and block 9 is moved to utils.py

All the three codes are provided comments against each step.  

------------------------------------------------------------------------

As per my understanding the function of different block as of now is:

In the **first code block**, various modules and packages are imported, including torch, torch.nn, torch.optim, torchvision, sys, os, and the custom modules "model" and "utils".

In the **second code block**, the availability of CUDA (GPU) is checked and the device (CPU or GPU) is set accordingly.

In the **third code block**, data transformation pipelines are defined for the training and testing data. These pipelines include operations like center cropping, resizing, rotation, tensor conversion, and normalization.

The **fourth code block** creates instances of the MNIST dataset for training and testing, using the defined transformations.

The **fifth code block** sets up data loaders for batch processing, with specified batch size, shuffle, and other parameters.

The **sixth code block** visualizes a batch of training data using matplotlib.

The **eighth code block** initializes a dictionary to store incorrectly predicted images and their corresponding ground truths and predicted values.

In the **tenth code block**, a neural network model is created (assuming the "Net" class is defined in the "model" module). The optimizer, scheduler, criterion (loss function), and number of epochs are also set. A training loop is then executed for the specified number of epochs, where the model is trained using the train function (not shown) and evaluated using the test function (not shown). The learning rate is adjusted using the scheduler.

The **eleventh code block** plots four graphs: training loss, training accuracy, test loss, and test accuracy.

The **Last code** block installs the torchsummary package and uses it to print a summary of the model's architecture.

--------------------------------------------------------------------------------------------------------------------

Above the code block three, I have used the proxy settings as I was working on this code on local system.

