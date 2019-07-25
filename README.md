# PyTorch-_CNN_Model

In this exercise I implemented PyTorch model.
I trained a model to classify a speech command using speech data, each speech utterance is ∼ 1 sec long.
The provided dataset contains 30 different categories of commands, my task was to train a classifier that classifies this data,
using ML techniques like DropOut, BatchNorm, MaxPool and RelU activation function.
My project includes few files:
* ex4.py - My CNN model.
* gcommand loader.py - My data loader.

The data set:
* https://github.com/orsanawwad/ML4_dataset/tree/master/data -The data set was to big to load and run on basic laptop,
all the data was saved to github, and i used google colab to run the algorithm on my GPU. 

On google colab change runtime type, hardware accelerator, to GPU for reasonable runtime.
Run this on as a code block in google colab first:
* ! rm -rf ./sample_data
* ! git clone https://github.com/orsanawwad/ML4_dataset.git
* ! mv ./ML4_dataset/* ./
* ! rm -rf ./ML4_dataset
* ! pip install soundfile
* ! python3 ex4.py

info.pdf includes my convolutional and neural network details so as my model results, you are more then welcome to take a look.
