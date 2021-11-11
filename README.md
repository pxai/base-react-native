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

Then:

```shell
amplify add auth0
```


npm run-script build
npm run-script start

Other useful commands
- "amplify status" will show you what you've added already and if it's locally configured or deployed
- "amplify add <category>" will allow you to add features like user login or a backend API
- "amplify push" will build all your local backend resources and provision it in the cloud
- "amplify console" to open the Amplify Console and view your project status
- "amplify publish" will build all your local backend and frontend resources (if you have hosting category added) and provision it in the cloud