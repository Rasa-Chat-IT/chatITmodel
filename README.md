# ChatIT-Model

This repository contains the model used for the ChatIT Android app using rasa model.

## 🗒️ Pre-requisites
- Python 3.7 to 3.8
- Pip installer (included with Python 3.7 - Python 3.8)

## 👾 How to Try the Chatbot

### Installation
```
pip install -r requirements.txt
```

### Running the Chatbot Locally
1. Navigate to the chatbot directory:
```
cd chatbot
```
2. Start the chatbot in the terminal:
```
python3 -m rasa shell
```

## 👾 How to Run the Chatbot Server

### Installation
```
pip install -r requirements.txt
```

### Running the Server
1. Navigate to the chatbot directory:
```
cd chatbot
```
2. Run the chatbot server with the pre-trained model:
```
python3 -m rasa run --enable-api -m models/20231202-190337-rectilinear-meter.tar.gz
```

or 

1. You can run the server without specifying a pre-trained model:
```
python3 server.py
```
The server will be accessible at `localhost:5005` by default.