# YipCode

YipCode is an AWS serverless app designed to solve the problem of people moving addresses and forgetting to update their registered postal address with various online companies. This app utilizes AWS services, such as Lambda, API Gateway, DynamoDB, and Cognito, to provide a seamless experience for end-users and businesses alike.

## Incompleteness

The app is not feature complete to support an MVP.

## Features

- End-users can register and maintain their postal addresses with YipCode. They can then share this address with online companies and services, reducing the need for repetitive data entry.
- YipCode stores end-users' postal address details in a DynamoDB database, ensuring that the data is secure and highly available.
- Businesses can integrate YipCode's API to validate and maintain their customers' addresses. This reduces the risk of sending mail to outdated or incorrect addresses.

## Development Details

- The frontend is built using React and Typescript, providing a user-friendly and responsive UI.
- The backend is entirely serverless, using AWS Lambda and API Gateway to provide a scalable and cost-effective solution.
- The app's data is stored in a DynamoDB database, which provides fast and reliable access to data.
- Authorization and authentication are handled by AWS Cognito, ensuring that the data remains secure.

## Adoption

If you're interested in adopting this organisation, get in touch. Currently I'm not working on it.
