# ESLINT Config for react-native projects inside YOYO Holdings

This project is maintained by YOYO Holdings engineering team to have a single eslint configuration for all the react-native projects and maintain coding style standards. This eslint config also supports typescript code standards and best practices.

## How to use 

```sh
npm install --save-dev eslint-config-react-native-yoyo
```

Create a new file on your project called `.eslintrc`, then copy and paste this config inside

```json
{
    "extends": "react-native-yoyo", 
}
```

## How to contribute
1. Fork this repository 
2. Create changes on your forked repository
3. Open a full request with the description of what is changed and why we need to use that rule / plugin