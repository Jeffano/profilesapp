The project is a basic full-stack web application built using AWS Amplify, a cloud-based platform that simplifies the process of deploying, managing, and scaling web applications. The application is a React-based frontend hosted on AWS, integrated with backend services that include authentication, a GraphQL API, and a serverless function to manage user data in a DynamoDB table. The primary goal of the application is to enable users to sign up, log in, and manage their profiles, with all data being securely handled and stored in the cloud.

What I Did:

Hosted a React Application: I built and deployed a React application to the AWS global content delivery network (CDN) using AWS Amplify's Git-based CI/CD workflow.
Implemented Authentication: I added authentication to the application using AWS Amplify's Auth module, enabling users to sign up, sign in, and reset their passwords.
Integrated a Real-Time API and Database: I created a data model using GraphQL and integrated it with Amazon DynamoDB to persist user data. This included setting up IAM roles to securely manage interactions between services.
Configured a Serverless Function: I developed an AWS Lambda function triggered upon user sign-up. This function captures the user's email and stores it in the DynamoDB table via the GraphQL API.
Linked the Serverless Function to the App: I connected the Lambda function to the Amplify Auth resources, ensuring that it is invoked automatically after user sign-up to store user data.
Connected Frontend to Backend: I updated the frontend of the application to interact with the cloud backend, allowing the display of user profiles and enabling sign-in/sign-out functionalities through the Amplify UI components.


Tools I Used:
AWS Amplify: I used AWS Amplify for hosting the React application, managing authentication, and orchestrating backend services like the GraphQL API, Lambda functions, and DynamoDB.
AWS Lambda: I utilized AWS Lambda to run the serverless function that captures and stores user emails in the DynamoDB table upon sign-up.
GraphQL API: I defined the data model and provided a real-time API for interacting with the DynamoDB database using GraphQL.
Amazon DynamoDB: I used Amazon DynamoDB, a NoSQL database, to store user profile data.
IAM (Identity and Access Management): I managed permissions and access securely between the Lambda function, GraphQL API, and DynamoDB using IAM.


![ProfilesApp-1](https://github.com/user-attachments/assets/11eee150-c5c9-4e2c-9e70-954daa642ea5)
![ProfilesApp-2](https://github.com/user-attachments/assets/c73a6c8b-3552-442a-814a-2b552bad786a)
![ProfilesApp-3](https://github.com/user-attachments/assets/ab89a2ef-ce8b-4193-bf43-80112c010f32)
