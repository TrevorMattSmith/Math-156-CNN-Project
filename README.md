# Math-156-CNN-Project
In this project, we developed a Convolutional Neural Network (CNN) for classifying traffic signs into 43 distinct categories. The model architecture contains two convolutional layers with ReLU activations and max pooling, followed by a fully connected layer with a softmax output. The CNN was trained with the Adam optimizer and cross-entropy loss, and the hyperparameters were tuned via Keras Tuner. After training our model, we achieved a test accuracy of 99.9\%, with almost perfect precision and recall in most classes. The evaluation metrics we used included  confusion matrix and classification report, which reveal a strong ability to generalize, even under varying image conditions. Our results demonstrate how effective CNNs can be for traffic sign classification, indicating a strong potential for use in automated vehicles. 

Important Note on the data set:
Due to the size of the data set we were unable to import it to GitHub. To access the data, download the light version at this link: https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-1-million-images-for-classification?select=dataset_ts_light_version.hdf5
and then import the data to your local Google Drive and then mount your drive to the Notebook.

