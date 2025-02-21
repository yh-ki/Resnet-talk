# Resnet Demo

### How to Run

Download the notebook file and upload it to the Google Colab. Before you run the code, select Running Time -> Changing Runtime Type then choose GPU. Run "!nvidia-smi", the GPU is available if you get an output table about GPU information. Then you can run all code to train the resnet model with CIFAR-10 dataset. If you want to train the model with different datasets,
you need to update the "Load Data Set" section and update the number of classes in output function in the "Setup Model Architecture" section. 
