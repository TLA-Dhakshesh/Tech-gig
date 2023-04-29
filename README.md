Intel One Maven Hackathon

Front End Code is attached above. Commands to be executed after cloning:

1. npm install
2. npm start

Backend code: https://github.com/venkadesh004/Tech-Gig-backend

Commands to be executed after cloning:

1. python app.py

Deep Learning Model Link: https://github.com/TLA-Dhakshesh/Tech-gig

Team Members:

Dhakshesh T L A - dhakshesh@student.tce.edu
Dinesh Kumaar M S - dineshkumaar@student.tce.edu
Venkadesh S - venkadesh@student.tce.edu

Project Model details :
1. This code uses implicitly OneDNN and OneMKL oneAPI Intel Librariesa and also uses TensorFlow and Keras to create a sentiment analysis model.
2. It first loads a dataset of reviews from a CSV file, and splits it into training and test sets.
3. The text data is then tokenized and padded to a fixed length.
4. A neural network model is defined using the Keras Sequential API, with an embedding layer, a global average pooling layer, two dense layers with ReLU activation and a   dropout layer, and a final sigmoid activation layer.
5. The model is compiled with binary crossentropy loss and the Adam optimizer.
6. The model is trained on the training data for 10 epochs, with validation on the test set.
7. The model's accuracy is evaluated on the test data.
8. The user is prompted to enter a review, which is preprocessed using the same tokenization and padding as the training data.
9. The model predicts the sentiment of the user's review as a value between 0 and 1.
10. Based on the predicted sentiment value, the program outputs a sentiment label of Positive, Neutral, or Negative.
