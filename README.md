# clementine
clementine is an abstract repository to build custom integrations for abotkit

# Quickstart

```zsh
npm i
npm start # or npm run dev 
```
# Abstract repository 

clementine itself is just boilerplate code to explain all api endpoints and steps you need to fulfill to implement your custom integration. Take a look at our [Website Integration](https://github.com/abotkit/website-integration) to see an clementine implementation. 

## Create a fork 

You can simply use the github fork button above :blush:
  
Hint: if there is already a fork of clementine in your account/organization the fork button will be hidden so you need to clone and set the upstream repository manually:
  ```zsh
  git clone https://github.com/abotkit/clementine new_integration
  cd new_integration
  git remote set-url origin https://github.com/userName/new_integration
  git remote add upstream https://github.com/abotkit/clementine
  git push origin main
  ```

# Environment variables

|         name        |        description             |    default           |
|---------------------|--------------------------------|----------------------|
| ABOTKIT_MAEVE_PORT | port of a running maeve instance | 3000 |
| ABOTKIT_MAEVE_URL | url of a running maeve instance | http://localhost |
| ABOTKIT_CLEMENTINE_PORT  | port for starting clementine        |   3030               |
| ABOTKIT_CLEMENTINE_LOG_LEVEL | log level (debug, info, warn, error) | 'info' |

# Issues

We use our [main repository](https://github.com/abotkit/abotkit) to track our issues. Please use [this site](https://github.com/abotkit/abotkit/issues) to report an issue. Thanks! :blush:
