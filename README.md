# Chatbot-using-NLP-and-Intent-Recognition
This is a machine learning-based chatbot that understands user queries and responds appropriately. It can recognize various ways of asking similar questions using intent classification and pattern matching.

🎯 Objective
To develop a chatbot that:

Understands varied user queries using NLP
Predicts the intent using a trained neural network model
Returns an appropriate response from a predefined list

📂 Dataset
The chatbot supports two types of datasets:

✅ Download from Kaggle: Chatbots Intent Recognition Dataset
✅ Manually create a custom intents.json file with your own patterns, tags, and responses

💾 Data Storage
intents.json: Acts as a simple structured database of intents
words.pkl, classes.pkl: Save preprocessed vocabulary and labels
chatbot_model.h5: Stores the trained Keras model
No traditional database (like SQLite or MySQL) is used in this project.

🛠️ Technologies Used
Python
TensorFlow (Keras)
NLTK
NumPy
JSON
Pickle

🧠 Model Workflow
Preprocess the data (tokenization, lemmatization)
Convert to Bag of Words vector
Train a dense neural network model
Save the model and helper files
Use the model to predict user intent
Return a suitable response from the dataset

📁 File Structure
Chatbot-Intent-Classifier/
├── intents.json # Dataset of patterns and responses
├── train_chatbot.py # Code to preprocess and train the model
├── chatbot_model.h5 # Trained model
├── words.pkl # Vocabulary
├── classes.pkl # Intent labels
├── chat.py # Script to interact with the bot
└── README.md # Project documentation

🔮 Future Enhancements
Add Named Entity Recognition (NER)
Deploy with Flask/FastAPI
Enable context for multi-turn conversations
Use advanced language models (e.g., transformers)
👨‍💻 Author
Mutyala Rahul
📧 rahulmutyala258@gmail.com# ChatBot
