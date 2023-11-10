# Toxic Comment Classifier
*<h4>Toxic comments classification employing Recurrent Neural Networks (RNNs) is a powerful approach in natural language processing. The provided code showcases the creation of an RNN model trained to identify toxic language in text data. By leveraging sequential information processing, RNNs capture contextual dependencies within sentences, enabling the model to discern offensive content. The architecture incorporates an embedding layer for word representation, followed by LSTM layers for sequential learning. Trained on a labeled dataset, the model aims to categorize comments into predefined toxicity classes. The project integrates visualization techniques to illustrate training history and employs evaluation metrics such as accuracy. Beyond the provided code, the methodology allows for further exploration of advanced RNN variants, diverse datasets, and optimization strategies to continually refine the model's ability to discern and mitigate toxic language online.</h4>*


# Implementation
* Download the python file, which is attached to this repository.
* Upload the given file in your google drive.
* Download the Training Datasets and Testing Datasets in the given link Below:
  >Training Datasets : [Training](https://www.dropbox.com/scl/fi/tcfw9v463q1x8mja9cjp4/train.zip?rlkey=a8jsu7kmhqsc6rxdrlkl4ufmb&dl=0).
  >Testing Datasets :  [Testing](https://www.dropbox.com/scl/fi/rui574d9yw0wl8poxi406/test.zip?rlkey=6wcgpbt4rh7s1si00gxjc5mj7&dl=0)
* Rename These files accordingly:
  - Training dataset : train.csv.zip
  - Testing Dataset : test.csv.zip
* Open a new notebook in Google Colab and open the python file in the notebook created.
* Upload these renamed zip files in the file section available on the left side individually.
* Click on the Runtime section provided by Google Colab, in that click Run all.
* During the runtime The model gets trained and tested.
* The model is tested with sentence as input for prediction on toxicity levels.
* At the end you are provided a basic output with six classes stating the toxic, severe toxic, obscene, threat, insult, and identity hate for the given input.
* The performance of the model is calculated based on the validation set that is produced during the training and testing of the model.
* The accuracy and epochs is provided in the form of graph. The Model will attain a accuracy of 99.45% over the other models created using CNN Architectire which proveds a accuracy of 98.5 and below.


# Performance and Accuracy of the model:
 ![image](https://github.com/dhanush1021/Toxic_Comment_Classifier/assets/114675054/bdd51374-2e7e-4058-91df-1a88841ffb48)

 # Architecture Diagram:
 ![image](https://github.com/dhanush1021/Toxic_Comment_Classifier/assets/114675054/918dc984-f3cf-4fc5-93b5-22e0edc430d9)
