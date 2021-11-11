# Template

- npm run android
- npm run ios
- npm run web

# Install amplify

```shell
npm i -g @aws-amplify/cli
```

```shell
amplify configure
```

```shell
amplify init
```

Then, you have to configure any 3rd party app id

```shell
amplify add auth
```

Then:
```shell
amplify push
```


npm run-script build
npm run-script start

Other useful commands
- "amplify status" will show you what you've added already and if it's locally configured or deployed
- "amplify add <category>" will allow you to add features like user login or a backend API
- "amplify push" will build all your local backend resources and provision it in the cloud
- "amplify console" to open the Amplify Console and view your project status
- "amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud


Creation log:

```
? Are you sure you want to continue? Yes
⠏ Updating resources in the cloud. This may take a few minutes...

UPDATE_IN_PROGRESS amplify-template-dev-133525 AWS::CloudFormation::Stack Thu Nov 11 2021 14:01:40 GMT+0100 (Central European Standard Time) User Initiated
⠋ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS authtemplatec112c6e9           AWS::CloudFormation::Stack Thu Nov 11 2021 14:01:46 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionRole AWS::IAM::Role             Thu Nov 11 2021 14:01:46 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionRole AWS::IAM::Role             Thu Nov 11 2021 14:01:47 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS authtemplatec112c6e9           AWS::CloudFormation::Stack Thu Nov 11 2021 14:01:47 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS amplify-template-dev-133525-authtemplatec112c6e9-FEZ8M16W0RBN AWS::CloudFormation::Stack Thu Nov 11 2021 14:01:47 GMT+0100 (Central European Standard Time) User Initiated
⠧ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UserPool AWS::Cognito::UserPool Thu Nov 11 2021 14:01:56 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPool AWS::Cognito::UserPool Thu Nov 11 2021 14:01:59 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UserPool AWS::Cognito::UserPool Thu Nov 11 2021 14:01:59 GMT+0100 (Central European Standard Time)                            
⠸ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE UpdateRolesWithIDPFunctionRole AWS::IAM::Role Thu Nov 11 2021 14:02:02 GMT+0100 (Central European Standard Time) 
⠇ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UserPoolClient    AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:03 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientWeb AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:03 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientWeb AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:05 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UserPoolClientWeb AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:05 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClient    AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:05 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UserPoolClient    AWS::Cognito::UserPoolClient Thu Nov 11 2021 14:02:05 GMT+0100 (Central European Standard Time)                            
⠏ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UserPoolClientRole AWS::IAM::Role Thu Nov 11 2021 14:02:09 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientRole AWS::IAM::Role Thu Nov 11 2021 14:02:10 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠹ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE UserPoolClientRole AWS::IAM::Role Thu Nov 11 2021 14:02:24 GMT+0100 (Central European Standard Time) 
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUICustomResource          AWS::Lambda::Function Thu Nov 11 2021 14:02:28 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientLambda            AWS::Lambda::Function Thu Nov 11 2021 14:02:28 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUIProvidersCustomResource AWS::Lambda::Function Thu Nov 11 2021 14:02:28 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUICustomResource          AWS::Lambda::Function Thu Nov 11 2021 14:02:30 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠙ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE HostedUICustomResource AWS::Lambda::Function Thu Nov 11 2021 14:02:31 GMT+0100 (Central European Standard Time) 
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUIProvidersCustomResource AWS::Lambda::Function Thu Nov 11 2021 14:02:32 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS UserPoolClientLambda            AWS::Lambda::Function Thu Nov 11 2021 14:02:32 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    HostedUIProvidersCustomResource AWS::Lambda::Function Thu Nov 11 2021 14:02:32 GMT+0100 (Central European Standard Time)                            
CREATE_COMPLETE    UserPoolClientLambda            AWS::Lambda::Function Thu Nov 11 2021 14:02:32 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUICustomResourcePolicy    AWS::IAM::Policy      Thu Nov 11 2021 14:02:34 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientLambdaPolicy      AWS::IAM::Policy      Thu Nov 11 2021 14:02:36 GMT+0100 (Central European Standard Time)                            
⠼ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUIProvidersCustomResourcePolicy AWS::IAM::Policy Thu Nov 11 2021 14:02:36 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUICustomResourcePolicy          AWS::IAM::Policy Thu Nov 11 2021 14:02:36 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠦ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUIProvidersCustomResourcePolicy AWS::IAM::Policy Thu Nov 11 2021 14:02:37 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS UserPoolClientLambdaPolicy            AWS::IAM::Policy Thu Nov 11 2021 14:02:37 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠇ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE HostedUICustomResourcePolicy          AWS::IAM::Policy Thu Nov 11 2021 14:02:49 GMT+0100 (Central European Standard Time) 
CREATE_COMPLETE HostedUIProvidersCustomResourcePolicy AWS::IAM::Policy Thu Nov 11 2021 14:02:51 GMT+0100 (Central European Standard Time) 
CREATE_COMPLETE UserPoolClientLambdaPolicy            AWS::IAM::Policy Thu Nov 11 2021 14:02:51 GMT+0100 (Central European Standard Time) 
⠏ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUICustomResourceLogPolicy          AWS::IAM::Policy Thu Nov 11 2021 14:02:53 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UserPoolClientLogPolicy                  AWS::IAM::Policy Thu Nov 11 2021 14:02:54 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUICustomResourceLogPolicy          AWS::IAM::Policy Thu Nov 11 2021 14:02:54 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS HostedUIProvidersCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:02:55 GMT+0100 (Central European Standard Time)                            
⠧ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUIProvidersCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:02:56 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS UserPoolClientLogPolicy                  AWS::IAM::Policy Thu Nov 11 2021 14:02:56 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠹ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE HostedUICustomResourceLogPolicy          AWS::IAM::Policy Thu Nov 11 2021 14:03:07 GMT+0100 (Central European Standard Time) 
CREATE_COMPLETE HostedUIProvidersCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:03:09 GMT+0100 (Central European Standard Time) 
CREATE_COMPLETE UserPoolClientLogPolicy                  AWS::IAM::Policy Thu Nov 11 2021 14:03:09 GMT+0100 (Central European Standard Time) 
⠸ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS HostedUICustomResourceInputs          Custom::LambdaCallout Thu Nov 11 2021 14:03:12 GMT+0100 (Central European Standard Time) 
CREATE_IN_PROGRESS UserPoolClientInputs                  Custom::LambdaCallout Thu Nov 11 2021 14:03:13 GMT+0100 (Central European Standard Time) 
CREATE_IN_PROGRESS HostedUIProvidersCustomResourceInputs Custom::LambdaCallout Thu Nov 11 2021 14:03:13 GMT+0100 (Central European Standard Time) 
⠧ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UserPoolClientInputs                  Custom::LambdaCallout      Thu Nov 11 2021 14:03:16 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UserPoolClientInputs                  Custom::LambdaCallout      Thu Nov 11 2021 14:03:17 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUIProvidersCustomResourceInputs Custom::LambdaCallout      Thu Nov 11 2021 14:03:17 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    HostedUIProvidersCustomResourceInputs Custom::LambdaCallout      Thu Nov 11 2021 14:03:17 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS HostedUICustomResourceInputs          Custom::LambdaCallout      Thu Nov 11 2021 14:03:17 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    HostedUICustomResourceInputs          Custom::LambdaCallout      Thu Nov 11 2021 14:03:18 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS IdentityPool                          AWS::Cognito::IdentityPool Thu Nov 11 2021 14:03:20 GMT+0100 (Central European Standard Time)                            
⠹ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS OAuthCustomResource AWS::Lambda::Function Thu Nov 11 2021 14:03:21 GMT+0100 (Central European Standard Time) 
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS IdentityPool        AWS::Cognito::IdentityPool Thu Nov 11 2021 14:03:22 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS OAuthCustomResource AWS::Lambda::Function      Thu Nov 11 2021 14:03:23 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    IdentityPool        AWS::Cognito::IdentityPool Thu Nov 11 2021 14:03:23 GMT+0100 (Central European Standard Time)                            
CREATE_COMPLETE    OAuthCustomResource AWS::Lambda::Function      Thu Nov 11 2021 14:03:24 GMT+0100 (Central European Standard Time)                            
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS IdentityPoolRoleMap       AWS::Cognito::IdentityPoolRoleAttachment Thu Nov 11 2021 14:03:27 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS OAuthCustomResourcePolicy AWS::IAM::Policy                         Thu Nov 11 2021 14:03:27 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS OAuthCustomResourcePolicy AWS::IAM::Policy                         Thu Nov 11 2021 14:03:29 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_IN_PROGRESS IdentityPoolRoleMap       AWS::Cognito::IdentityPoolRoleAttachment Thu Nov 11 2021 14:03:30 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    IdentityPoolRoleMap       AWS::Cognito::IdentityPoolRoleAttachment Thu Nov 11 2021 14:03:30 GMT+0100 (Central European Standard Time)                            
⠧ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE    OAuthCustomResourcePolicy    AWS::IAM::Policy Thu Nov 11 2021 14:03:42 GMT+0100 (Central European Standard Time) 
CREATE_IN_PROGRESS OAuthCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:03:46 GMT+0100 (Central European Standard Time) 
⠼ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS OAuthCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:03:47 GMT+0100 (Central European Standard Time) Resource creation Initiated
⠇ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE OAuthCustomResourceLogPolicy AWS::IAM::Policy Thu Nov 11 2021 14:04:00 GMT+0100 (Central European Standard Time) 
⠴ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS OAuthCustomResourceInputs Custom::LambdaCallout Thu Nov 11 2021 14:04:04 GMT+0100 (Central European Standard Time) 
⠙ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS OAuthCustomResourceInputs Custom::LambdaCallout Thu Nov 11 2021 14:04:08 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    OAuthCustomResourceInputs Custom::LambdaCallout Thu Nov 11 2021 14:04:08 GMT+0100 (Central European Standard Time)                            
⠹ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE amplify-template-dev-133525-authtemplatec112c6e9-FEZ8M16W0RBN AWS::CloudFormation::Stack Thu Nov 11 2021 14:04:12 GMT+0100 (Central European Standard Time) 
⠦ Updating resources in the cloud. This may take a few minutes...

CREATE_COMPLETE    authtemplatec112c6e9       AWS::CloudFormation::Stack Thu Nov 11 2021 14:04:27 GMT+0100 (Central European Standard Time) 
CREATE_IN_PROGRESS UpdateRolesWithIDPFunction AWS::Lambda::Function      Thu Nov 11 2021 14:04:29 GMT+0100 (Central European Standard Time) 
⠦ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UpdateRolesWithIDPFunction        AWS::Lambda::Function Thu Nov 11 2021 14:04:32 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UpdateRolesWithIDPFunction        AWS::Lambda::Function Thu Nov 11 2021 14:04:32 GMT+0100 (Central European Standard Time)                            
CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Thu Nov 11 2021 14:04:35 GMT+0100 (Central European Standard Time)                            
⠧ Updating resources in the cloud. This may take a few minutes...

CREATE_IN_PROGRESS UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Thu Nov 11 2021 14:04:39 GMT+0100 (Central European Standard Time) Resource creation Initiated
CREATE_COMPLETE    UpdateRolesWithIDPFunctionOutputs Custom::LambdaCallout Thu Nov 11 2021 14:04:39 GMT+0100 (Central European Standard Time)                            
✔ All resources are updated in the cloud

Hosted UI Endpoint: https://templatec112c6e9-c112c6e9-dev.auth.us-east-1.amazoncognito.com/
Test Your Hosted UI Endpoint: https://templatec112c6e9-c112c6e9-dev.auth.us-east-1.amazoncognito.com/login?response_type=code&client_id=61dqmf4llbrkin

```