# Comparison-of-Chatbot-models

A conversational agent (chatbot) is a machine-learned dialogue model designed to simulate human conversations. In this study we will start by understanding what neural network is and how Recurrent Neural Network (RNN) and Sequence-to-Sequence (Seq2Seq) model are related to it. Then, we will talk about ways through which RNN and Seq2Seq can be improved such as by adding LSTMs and Attention mechanism. Finally, we will talk about a more developed model such as the Transformer model for chatbots. In this project, we will use the Cornell Movie-Dialogs Corpus to train our models. We will build Seq2Seq LSTM model, Seq2Seq LSTM model with Attention mechanism, and the Transformer model. Finally, we aim at comparing the performance of these dialogue models using the Bleu score and human judgement metrics to determine which model would be a better suggestion

### This project mainly contains a detailed report, and 3 different model files namely: 
- model_1.py: Seq2Seq LSTM model 
- model_2.py: Seq2Seq LSTM model with Attention mechanism
- model_3.py: Seq2Seq Transformer model

### Instruction to run the models: 
• All the models are stored in the zip file. 
• The zip file contains the models and a ‘data’ folder (it contains the Movie-Dialogs Corpus
dataset, trained model weights and training logs. 
• To run the model, type the following command in the terminal: 
```
python “model_py_file” “data_folder_location” 
```
Here, “data_folder_location” is sys.arg[1] which takes Path of the data folder as input. 

The names of the 3 models are ‘model_1.py’, ‘model_2.py’ and ‘model_3.py 
