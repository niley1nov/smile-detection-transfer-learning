# smile-detection
smile detection from cropped faces using transfer learning in keras.

VGG16 pretrained model used for transfer learning.

keras model.fit_generator() is used to avoid loading whole dataset in RAM at once.

keras custom training loop and custom loss function is implemented to observe loss per epoch rather than batch average. This gives better insight of learning of model.

Train accuracy: 0.9989    Test accuracy: 0.9751

Dataset - https://data.mendeley.com/datasets/yz4v8tb3tp/5
