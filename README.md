# Chatbot Using Dialogflow-RESTful API
This repository consists of a project based on API using Express JS, Node JS, and MongoDB and Ngrok for simulate a conversation (or a chat) with a user in natural language through messaging applications.
## Problem Statement
This project aims at buliding a simulate conversation between a user and the machine(messaing application) for solving the issues faced by the user through service. They can chat directly in application by mentioning their issue, based on their issue chatbot generate a ticket and tells why they are facing the issue.
## Implementation and project details
## MongoDB Database
The database "Chatbot" consists of two collections:
1. "user_table"
2. "user_issues"
The issues.txt file contains the database schema of major issues  by the user made into the database.
## Ngrok
I have used Ngrok To communicate with APIs we need to create a webhook. This webhook is triggered by an event. if a user sends a message to your page, the Messenger API sends a POST request to your webhook.it’s a tunneling package that makes your localhost accessible online.
