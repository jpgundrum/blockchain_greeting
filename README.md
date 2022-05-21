# Greeting using Blockchain Techology

This is a simple project I created for [Badger Blockchain](https://www.badgerblockchain.com/) which is a club at UW-Madison. 

Once all dependencies are downloaded onto your machine you can run it by:
```
npx hardhat node
```
^^ This command starts the local EVM machine provided by the HardHat network.
```
npx hardhat run scripts/deploy.js --network localhost
```
^^ Run this command in a separate terminal. This deploys the smart contract to the local EVM network and sets a default greeting.

```
npm start
```
^^ This starts the react app and opens up the Greeting site that users can interact with.

## Errors
**NONCE ERROR??** Try resetting your Metamask account. (Majorirty of errors I run into disappear after resetting :joy:)

## References/Disclaimer
I am not responsible for the majority of this code! The blog post by Nader Dabit which is found [here](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13)
heavily inspried me. It is a well thought out tutorial. I recommend to read and watch his youtube video on the topic. Listening to him talk through the steps and give explanations is crucial for comphrension. [His repository](https://github.com/dabit3/full-stack-ethereum) was what I pulled down originally, to understand and eventually replicate his creation. I did use CSS and other React elements
to make it more of my own, so it doesn't look like a direct copy and paste. This is meant for education purposes to get college students exposed to blockchain technology.