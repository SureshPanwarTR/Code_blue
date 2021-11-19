#Enabling voice-based search in TR products
What is this?
A serverless application that sets up a lambda function to consume data from a DynamoDB Stream. A frontend built to recognize the voice search to feed the customer data back.

#The Architecture
Serverless framework is used to build and deploy the services to AWS
The DynamoDB noSQL database holding customer data and the developed search engine serves the data back to the client as depicted in below workflow diagram.
A lambda function is responsible for consuming records from DynamoDB Streams.
Python is used as lambda function language
API gateway used a trigger for lambda.
HTML and JS codes are used as frontend for voice search engine.


#Tech Stack
Serverless Framework
Serverless Python Requirements
Amazon DynamoDB
AWS Lambda
AWS API Gateway
Amazon OpenSearch
Prerequisite
Serverless framework
Python
HTML
JavaScript
