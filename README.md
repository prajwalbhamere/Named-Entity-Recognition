# Named-Entity-Recognition
NER involves identifying and extracting specific information from unstructured text data, such as the names of people, organizations, locations, and other entities. 
The project was focused on building a BiLSTM-LSTM model for NER using Python and modern deep learning libraries.

The main objective of the project was to develop a BiLSTM-LSTM model for NER using Python and deep learning libraries. 
The scope of the project included:
1) Preprocessing and cleaning of data
The input text data was preprocessed by tokenizing the sequences and padding
them to a fixed length using the pad sequences function from the Keras library.
2) Mapping of tokens and tags to integer indices
The tokens and tags were mapped to their respective indices using a dictionary
mapping function. 
3) Splitting of data into training and testing sets
The data was split into training and testing sets using the train test split function
from the scikitlearn library.
4) Building and training the BiLSTM-LSTM model
The BiLSTM-LSTM model was developed using the TensorFlow library, with suit-
able layers such as Embedding, Bidirectional LSTM, LSTM, and TimeDistributed
Dense.
5) Evaluating the model’s performance on test data
The model was trained on the training set for multiple epochs, and its perfor-
mance was evaluated on the testing set using suitable evaluation metrics such as
accuracy and F1 score.
Scope:
1) The focus of this project is on developing a model for NER using the
BiLSTM-LSTM architecture and training it on the Annotated Corpus for Named
Entity Recognition dataset.
2) The evaluation of the model will be limited to standard evaluation metrics such
as precision, recall, and F1 score.
3) The project aims to investigate the impact of different hyper-parameters on the
performance of the model.
4


Dataset Used: https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus?resource=download&select=ner_dataset.csv
