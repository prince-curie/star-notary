# star-notary

star-notary is a practice on the building of a non-fungible-token. Built on the ethereum smart contract. 
- Token name = CurieToken
- Token symbol = CTN
- Token address = 0x8Dc99B11Df6957e0BcC7C54239216F638e8931DD

## Tools
- Solidity
- HTML
- JavaScript
- web3.js
- Truffle v5.1.67
- openzeppelin-solidity v2.1.2

## Installation
- Clone the git repo
```bash
git clone https://github.com/prince-curie/star-notary.git
```

- Use the package manager [npm](https://www.npmjs.com/get-npm) to install needed packages.
```bash
npm install -g truffle
```

```bash
npm install
```

- change into the app directory 
```bash
cd app
```
- install packages in this directory
```bash
npm install
```
- Have a metamask wallet with two funded accounts on the Rinkeby network
- create a file name `.secret` in the root of your project folder.
- Paste your wallet seed in the `.secret` file.
- Go to [infura](https://www.infura.io)infura.io and set up an account.
- Create a project, open the project, go to settings, copy the project id
- In the code open the `truffle-config.js` file, on line 26 equate infuraKey to your id formatted as a string. 

## Usage
- run the command `truffle compile` to compile the contract source code
- run the command `truffle migrate --reset --network rinkeby` to deploy to the rinkeby network.
- run the command `truffle test` to ensure that everything is setup properly on the rinkeby network.
- change directory to the `/app` directory.
- run the command `npm run dev` to start up the server for the frontend application.
- copy the url into the use the application.
