# Amazon Lex Chatbot - BankerBot

## Description

BankerBot is designed to help users check their bank balance through a conversational interface. Using Amazon Lex for natural language understanding and AWS Lambda for backend processing, this chatbot demonstrates the integration of various AWS services to build a dynamic and responsive application.

## Features

- **Amazon Lex Integration:** Utilizes Amazon Lex to build a sophisticated chatbot capable of voice and text interactions.
- **AWS Lambda Connection:** Connects to AWS Lambda to perform backend tasks, such as retrieving and returning the user's bank balance.
- **Serverless Architecture:** Demonstrates the use of serverless computing to handle dynamic responses and actions within the chatbot.

## Setup Instructions

1. **Setup Amazon Lex:**
   - Go to the Amazon Lex console.
   - Create a new bot and configure the intents and slots as required.
   - Define the `CheckBalance` intent for checking the bank balance.

2. **Create AWS Lambda Function:**
   - Go to the AWS Lambda console.
   - Create a new Lambda function in Python.
   - Save and deploy the function.

3. **Connect Lex to Lambda:**
   - In the Amazon Lex console, go to the Alias page of your chatbot.
   - Connect your chatbot alias to the latest version of the AWS Lambda function.
   - Configure code hooks to invoke the Lambda function for the `CheckBalance` intent.

## Key Learnings

- **Serverless Computing:** AWS Lambda allows running code without provisioning or managing servers, charging only for the compute time consumed.
- **Integration of Services:** Connecting Amazon Lex with AWS Lambda using code hooks demonstrates how to handle more complex actions during conversations.
- **Dynamic Responses:** Using Lambda functions to generate dynamic responses based on user input and other conditions.

## Future Enhancements

- **Context Carryover:** Enhance BankerBot to remember key details like the user's birthday during a session for a smoother experience.
- **Database Integration:** Connect the Lambda function to a real database to fetch actual bank balances.
- **Additional Intents:** Add more intents to handle other banking tasks such as transferring money, checking transaction history, etc.

## Project Details

- **Author:** Kanika Mathur
- **GitHub**: [KanikaGenesis](https://github.com/KanikaGenesis)
- **LinkedIn**: [Kanika Mathur](https://www.linkedin.com/in/kanika-mathur-083080121)

## Final Thoughts

This project demonstrates the powerful capabilities of integrating Amazon Lex with AWS Lambda to build responsive and efficient chatbots. The serverless architecture simplifies the deployment and management of the application, making it a versatile solution for various conversational AI needs.
