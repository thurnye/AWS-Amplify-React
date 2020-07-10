# AWS-Amplify-React


This auth starter implements a basic authentication flow for signing up signing in users as well as protected client side routing using [AWS Amplify](https://amplify.aws). Auth features:

- User sign up,
- User sign in,
- Multi-factor Authentication


# How to RUN LOCALLY
Create the project
git clone https://github.com/thurnye/AWS-Amplify-React.git
Change into the new directory
cd AWS-Amplify-React
Change into the new directory
yarn
# or
npm install
Install & configure the AWS Amplify CLI.
npm install -g @aws-amplify/cli

amplify configure
To see a video of how to configure the CLI, click  [here](https://www.youtube.com/watch?v=fWbM5DLh25U)

Create a new AWS Amplify Project
amplify init
Here, walk through the following steps:

Enter a name for the project YOURPROJECTNAME
Enter a name for the environment master
Choose your default editor: Visual Studio Code (or your editor of choice)
Choose the type of app that you're building javascript
What javascript framework are you using react
Source Directory Path: src
Distribution Directory Path: public
Build Command: npm run-script build
Start Command: npm run-script develop
Push the updated project configuration to AWS. It will deploy a CloudFormation template that has an Amazon Cognito resource that enables user authentication.
amplify push
Then you can run it by:
npm start
