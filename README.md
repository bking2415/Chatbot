# Chatbot
Chatbot uses deep learning techniques to interact with customers via chat graphical user interface.

## Instructions
1. Make sure all the proper libraries are imported (i.e _tensorflow, keras_) and packages are installed.
2. Run `chatBot_training.py` to train the model.
3. Run `chatBot_GUI.py` to interact with chatBot.


## How do Chatbots Work?
All chatbots use some type of NLP (Natural Language Processing) concepts. NLP is composed of two things:

- **NLU (Natural Language Understanding)**: The ability of machines to understand human language like English.
- **NLG (Natural Language Generation)**: The ability of a machine to generate text similar to human written sentences.

## Project Structure 

- `chatBot_GUI.py` -- Graphical user interface to chat with the trained chatbot.
- `chatBot_training.py` -- Deep learning model used to train, classify, and identify what the user is asking about.
- `chatbot_model.h5` -- Used to store the weights and the architecture of the trained model.
- `classes.pkl` -- Stores all teh tag names to classify when predictin the message.
- `intents.json`-- The file used to train the model. It contains all the patterns and responses
- `words.pkl` -- Stores all the distinct words that are the diction within the model.
