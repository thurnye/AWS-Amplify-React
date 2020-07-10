# AWS-Amplify-React


This auth starter implements a basic authentication flow for signing up signing in users as well as protected client side routing using [AWS Amplify](https://amplify.aws). Auth features:

- User sign up,
- User sign in,
- Multi-factor Authentication


# How to RUN LOCALLY
1. Create the project

```sh
git clone https://github.com/thurnye/AWS-Amplify-React.git
```
2. Change into the new directory

```sh
cd AWS-Amplify-React
```
3. Change into the new directory

```sh
yarn
# or
npm install
```l

4. Install & configure the AWS Amplify CLI.

```sh
npm install -g @aws-amplify/cli

amplify configure
```

> Click [here](https://youtu.be/fWbM5DLh25U) to see a video of how to configure the CLI

5. Create a new AWS Amplify Project

```
amplify init
```

> Here, walk through the following steps:

- Enter a name for the project __YOURPROJECTNAME__
- Enter a name for the environment __master__
- Choose your default editor: __Visual Studio Code__ (or your editor of choice)
- Choose the type of app that you're building __javascript__
- What javascript framework are you using __react__
- Source Directory Path: __src__
- Distribution Directory Path: __public__
- Build Command: __npm run-script build__
- Start Command: __npm run-script develop__

6. Push the updated project configuration to AWS. It will deploy a CloudFormation template that has an Amazon Cognito resource that enables user authentication.

```sh
amplify push
```

7. Then you can run it by:
```sh
npm start
```
