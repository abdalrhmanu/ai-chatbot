<h1 align="center" style="margin-bottom: 0;">
AI Chatbot
</h1>
<p align="center">
  <strong>An intelligent chatbot that learns and answer your questions!</strong>
</p>

### Demo

![C__Windows_System32_cmd exe - chatbot py 2021-07-09 15-27-03](https://user-images.githubusercontent.com/67197269/125082391-d74e0a00-e0cf-11eb-8a78-0272fc84819b.gif)


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
