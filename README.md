# Assistants API - Code Examples

....

## **Table of Contents**

- [1] - Assistant API - Quickstart
- [2] - Assistant API - Code Interpreter
- [3] - Assistant API - Knowledge Retrieval \
- [4] - Assistant API & Chatbot - Function Calling with Streamlit and the [Openweathermap.org API](https://openweathermap.org/)

## Requirements:

### **Install Python** !

[Python](img/python_65.png)

A [Quick Guide for Installing](https://github.com/PackeTsar/Install-Python/blob/master/README.md#install-python-) Python on Common Operating Systems

....

**openai** : [OpenAI](https://openai.com/) is an artificial intelligence research laboratory consisting of the for-profit corporation OpenAI LP and its parent company, the non-profit OpenAI Inc. The company, considered a competitor to DeepMind, conducts research in the field of artificial intelligence (AI) with the stated aim to promote and develop friendly AI in such a way as to benefit humanity as a whole.

**python-dotenv** : [python-dotenv](https://pypi.org/project/python-dotenv/) reads key-value pairs from a .env file and can set them as environment variables. It is great for managing app settings during development and in production using 12-factor principles.

**streamlit** : [streamlit](https://pypi.org/project/streamlit/) is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science.

**streamlit-chat** : [streamlit-chat](https://pypi.org/project/streamlit-chat/) is a streamlit component for building chatbots.

### Create a virtual environment :

**MacOS/Linux**:

```
python3 -m venv env
```

**Windows**:

```
python -m venv env
```

### Activate the virtual environment :

```
source env/bin/activate
```

### Installation:

**MacOS/Linux**:

```
pip3 install -r requirements.txt
```

**Windows**:

```
pip install -r requirements.txt
```

### Get an API Key - [🔗](https://platform.openai.com/account/api-keys)

#### Set the key as an environment variable:

`export OPENAI_API_KEY='sk-brHeh...A39v5iXsM2'`

.env file:

```
OPENAI_API_KEY=sk-brHeh...A39v5iXsM2
```

### start assistant

**MacOS/Linux**:

```
python3 main.py
```

**Windows**:

```
python main.py
```

### start Streamlit app

```
streamlit run main.py
```
