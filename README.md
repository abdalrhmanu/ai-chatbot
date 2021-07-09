<h1 align="center" style="margin-bottom: 0;">
AI Chatbot
</h1>
<p align="center">
  <strong>An intelligent chatbot that learns and answer your questions!</strong>
</p>

### Demo



### General
The chatbot is trained from the dictionary of information found in the intents.json file. The file is divided into:


| Name | Description                    |
| ------------- | ------------------------------ |
| `tag`      | Tags attached to word list.       |
| `patterns`   | Group of input that the chatbot is trained on.     |
| `responses`   | The exact responses that the chatbot will respond with.    |

To train the chatbot with your own required information, please update the json file accordingly.

### Training
After adding information into the intents.json file, run this code to train the model.

`python training.py`


### Running The Chatbot
To start the chatbot, run the next command.

`python chatbot.py`
