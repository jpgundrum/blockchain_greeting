# Greeting using Blockchain Techology

This is a simple project I created for [Badger Blockchain](https://www.badgerblockchain.com/) which is a club at UW-Madison. 

## Dependencies
1. Download the most recent recommended version of nodejs which can be found [here](https://nodejs.org/en/)
2. In order to obtain this interface on your local machine you must first pull down the repository. You can do this in your vscode terminal 
with the following command:
```
git clone https://github.com/jpgundrum/blockchain_greeting.git
```
Open the folder you just created in vscode (or editor of your choice) to see the files.

3. Next you will need to install the following dependencies:

**npm**
```
npm install
```
**HardHat**
```
npm install --save-dev hardhat
```
**HardHat packages**
```
npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers
```

## Start your first local blockchain!
To start your local EVM machine (HardHat network) you must type the cmd:
```
npx hardhat node
```
The next command deploys the smart contract to the local EVM network and sets a default greeting.
Run this script in a different terminal because you EVM needs to be running.
```
npx hardhat run scripts/deploy.js --network localhost
```

Go into the frontend folder which contains Javascript, CSS, and React elements used in the webpage.
Then finally start the server!
```
cd frontend
npm start
```
Congratulations! Your first web3 site is active! 

## Errors
**NONCE ERROR??** Try resetting your Metamask account. (Majorirty of errors I run into disappear after resetting)
**Anything else?** Inspect webpage and go to console to see specific error message. Google and debug.

Contact jpgundrum@wisc.edu if you run into errors/find issues with the code or instruction

## References/Disclaimer
I am not responsible for the majority of this code! The blog post by Nader Dabit which is found [here](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13)
heavily inspried me. It is a well thought out tutorial. I recommend to read and watch his youtube video on the topic. Listening to him talk through the steps and give explanations is crucial for comphrension. [His repository](https://github.com/dabit3/full-stack-ethereum) was what I pulled down originally, to understand and eventually replicate his creation. I did use CSS and other React elements
to make it more of my own, so it doesn't look like a direct copy and paste. This is meant for education purposes to get college students exposed to blockchain technology.