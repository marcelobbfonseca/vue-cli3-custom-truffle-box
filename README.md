[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com) [![Build Status](https://travis-ci.com/marcelobbfonseca/vue-cli3-custom-truffle-box.svg?branch=master)](https://travis-ci.com/marcelobbfonseca/vue-cli3-custom-truffle-box) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![Greenkeeper badge](https://badges.greenkeeper.io/marcelobbfonseca/vue-cli3-custom-truffle-box.svg)](https://greenkeeper.io/)


# vue-truffle-box

This Version comes with vuex, routers and Mocha for unit test.
For simplified version go to marcelobbfonseca/vue-cli3-truffle-box.


This project is a truffle box for vue-cli3. Truffle Boxes are helpful boilerplates that allow you to work with the Ethereum Virtual Machine (EVM) and focus on what makes your dapp unique. In addition to Truffle, Truffle Boxes can contain other helpful modules, Solidity contracts & libraries, front-end views and more; all the way up to complete example dapps.


## Project setup

at first install vue-cli3(latest) and truffle.

```
npm install -g @vue/cli
npm install -g truffle
```

this project uses:

	Vue 3.1.3
	Truffle 4.1.14

Now you just have to run this to start a new project. easy peasy lemon queezy:

```
truffle unbox marcelobbfonseca/vue-cli3-custom-truffle-box
```

## Commands list:

### Truffle commands:
```
    truffle compile # Compile contracts
    truffle migrate # Migrate contracts
    truffle test 	# Run Tests for your contracts
```
### Vue-Cli3 commands:
```
    npm run serve # Run dev server
    npm run build # Build for production
    npm run lint  # Lints and fixes files
    npm run test:unit # run test unit
```

For more info in truffle configuration check the oficial docs here:
https://truffleframework.com

and for Vue configuration 
See [Configuration Reference](https://cli.vuejs.org/config/).
