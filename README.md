# Pet Shop DAPP :dog: :money_with_wings:

Code for the completed [Pet Shop](http://truffleframework.com/tutorials/pet-shop) tutorial from Truffle.

## Running the app

1. Ensure Truffle is installed: `$ npm install -g truffle`
2. Ensure dependencies are installed: `$ npm install`
3. Initialize a local development blockchain on port 7545 ([Ganache](http://truffleframework.com/ganache/) can be used to easily set this up)
3. Compile and migrate the smart contract: `$ truffle compile && truffle migrate`
4. Login with [Metamask](https://metamask.io/) and connect to the local development network (see instructions [here](http://truffleframework.com/tutorials/pet-shop#installing-and-configuring-metamask))
6. Start the web server: `$ npm run dev`

The app will be available at `http://localhost:3000`

# Testing
`$ truffle test`
