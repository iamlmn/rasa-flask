# rasa-flask integration
```
pip install ujson==1.35 # if rasa fails to install with ujson build failure
pip install rasa
rasa init --no-prompt # This will create a basic template of a chatbot.
rasa train # train your chatbot.
rasa shell --debug # After training the chatbot run the command
rasa run -m models --enable-api  # this command lets you make HTTP requests in http://localhost:5005
```

# setup flask server 
```
cd app
python app.py / flask run app.py
```