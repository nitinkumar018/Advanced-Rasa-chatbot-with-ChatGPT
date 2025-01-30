# Project: Build an advanced Rasa chatbot with ChatGPT-4 
## Rasa chatbot with ChatGPT-4 is created on anaconda prompt 
## chatgpt is a large language model (LLM) developed by openAI that uses machine learning algorithm to generate human like responses to the user inputs
## gpt-4/ text-davinci-004 is a LLM model from openAI's GPT-4 which excels in text generation, question answers and many NLP tasks
## sign up for openAI to get your API key (API key use to get response from the chatgpt)
## create a virtual environment on Anaconda Prompt and then install necessary libraries: openai, rasa
## set your API key on Anaconda Prompt using command: export OPENAI_API_KEY
## once we create a basic chatbot, we can implement chatgpt in the actions.py file of your Rasa project. This will generate responses to user queries using chatgpt
## actions.py: it defines custom actions for your chatbot (custom actions are the actions that your chatbot performs during conversation) 
## credentials.yml: it has API key for chatgpt. However, due to security concern, Rasa does not support to store API key in this file. Instead handle API key in actions.py file 
## data folder (nlu.yml, stories.yml, rules.yml) has training data for your chatbot (we usually prefer stories.yml over rules.yml)
## nlu.yml: it includes intents with examples 
## domain.yml: it lists intents, actions and responses. This serves as a blueprint for chatbot
## stories.yml: it defines the flow of interaction between the user and chatbot by mapping intents to actions in a conversational sequence
## config.yml: it has configuration settings for your Rasa project such as pipeline 

## Once we integrate custom actions into Rasa chatbot's workflow, then, test the chatbot to ensure it properly interacts with chatgpt

