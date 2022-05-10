
# Healthcare chatbot Using machine learning and natural language prcessing

Healthcare is very important to lead a good life. However, it is very difficult to obtain a
consultation with a doctor for every health problem. The idea is to create a medical chatbot
using Artificial Intelligence that can diagnose the disease and provide basic details about the
disease before consulting a doctor. This will help to reduce healthcare costs and improve
accessibility to medical knowledge through medical chatbots


## Run Locally

Clone the project

```bash
  git clone https://github.com/robinsingh051/Healthcare-chatbot
```

Go to the project directory

```bash
  cd Healthcare-chatbot
```

Install dependencies

```bash
  pip install rasa
```
```bash
  pip install flask
```
```bash
  pip install requests
```
Go to rasabot directory
```bash
  cd rasabot
```
open terminal in this directory and run the following command to start rasa server
```bash
  rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml
```
Go to web_app directory
```bash
  cd web_app
```
open terminal in this directory and run the following command to start flask server
```bash
    flask run
```



## Technologies used

**Client:** HTML,CSS,Javascript

**Server:** Python Flask

**Chatbot framework:** Rasa


## Team

- [Robin Singh](https://github.com/robinsingh051)
- [Sanjana Pradhan](https://github.com/Sanjana27-11)
- [Prithvi Vasanth](https://github.com/prithvivasanth)

