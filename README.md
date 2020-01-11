# Convolutional Neural Network - MNIST Digits dataset
## Requirements
Quite a lot of libraries are required
Google them to install them depending on your OS

    * keras / tensorflow
    * numpy
    * PIL
    * cv2
    * ...

## RUN
Go to your file directory, and run this command :
```bash
python3 main.py
```
By default it just apply the model, if you want to train it again
uncomment the function ```build_model()```

## Data
    * Load for MNIST
    * Data volume : 60000
    * Input shape is 28x28x1 (Gray Scale Image)
![alt text](model/data_sample.png "Sample")


## Architecture
![alt text](model/model.png "Model")

## Hyperparameters

    * loss = categorical_crossentropy
    * optimizer = Adadelta
    * batch_size=200
    * epochs = 2
