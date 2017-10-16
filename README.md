# Lawyer Bot

Lawyer Bot is an AI Chatbot designed to keep website visitors engaged in an automated conversation with the goal of increasing the probability for conversion from inquiry to lead generation.

It is built for [Sting Marketing](http://sting.net) as a Minimum Viable Product (MVP) in order to validate the ability for conversational user experience platform (such as Dialogflow) to engage website visitors in an automated conversation and capture data from the conversation.

## Demo



## Architecture

![architecture](images/architecture.png)

Lawyer Bot consists of 4 components
* REST API
  * [https://github.com/lukitos/lawyerbot-api](https://github.com/lukitos/lawyerbot-api)
* AI Chatbot
  * [https://github.com/lukitos/lawyerbot-aichat](https://github.com/lukitos/lawyerbot-aichat)
* Lawyer Dashboard for CRM Lite
  * [https://github.com/lukitos/lawyerbot-crm-dashboard](https://github.com/lukitos/lawyerbot-crm-dashboard)
* Lawyer Mobile app for CRM Extra Lite
  * [https://github.com/lukitos/lawyerbot-crm-mobile](https://github.com/lukitos/lawyerbot-crm-mobile)

![technology](images/technology.png)

#### REST API
* Node.js
* Express
* PostgreSQL

#### AI Chatbot
* Dialogflow
* Socket.IO
* Bootstrap

```
Note: API.AI has been recently renamed to Dialogflow
```

#### Dashboard
* React/Redux
* Firebase (authentication)
* Bootstrap
* Chart.js

#### Mobile app
* React Native

## How it works

In order to best demonstrate Lawyer Bot, I'd like to introduce a scenario of a Personal Injury Law Firm with 2 roles:
* Potential Customer
* Personal Injury Lawyer

![scenario](images/scenario.png)



![components](images/howitworks.png)
