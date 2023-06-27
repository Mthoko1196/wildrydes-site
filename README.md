# wildrydes-site
I created a simple serverless web application that allows users to request a unicorn ride on the Wild Rydes fleet similar to the Uber app.

By using the following AWS service:
- Amazon Amplify: Configure AWS Amplify to host your web application's static resources using built-in continuous delivery.
- Amazon Cognito: To manage your users' accounts.
- Amazon DynamoDB: Build a serverless backend to handle web application requests.
- Lambda and API Gateway: Deploy a RESTful API.

Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

This solution is perfect for businesses that don't want to spend time deploying, scaling, and maintaining servers.

![image](https://github.com/Mthoko1196/wildrydes-site/assets/92365100/dd5eb64a-486b-4716-92ee-55d51f553fee)


