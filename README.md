# Achievement Contract: Achievement System for the FTM ecosystem

![Fantom Opera](https://fantomfoundation-prod-wp-website.s3.ap-southeast-2.amazonaws.com/wp-content/uploads/2021/01/19225127/Fantom-1.png)

FTM Achievement is a project that aim to create a general purpose achievement system to increase the user’s engagement and long term longevity of of the interaction between the user and platform smart contract like Games, DeFi protocols and DAOs.

## Contract code

Contract and tests can be found here: https://github.com/StErMi/achievement-system-contract

## How to run the POC

1. Clone the project
2. Install dependecies `yarn install`
3. Open Terminal 1 and run: `yarn chain` to start the hardhat chain
4. Open Terminal 2 and run `yarn start` to start the React app
5. Open Terminal 3 and run `yarn deploy` to deploy all contracts
6. Open http://localhost:3000/ to interact with it

Contract to interact with:

- `Archievement.sol` -- An ERC721 contract with all the general purpose archievement management system
- `utils/FTMGame.sol` -- A crypto Game Smart contract that showcase how to leverage the Achievement system to increase user engagement and longevity
- `utils/Greeting.sol` -- A smart contract that interact with the Achievement system and the FTMGame unlocking functionalities only if the user's owns a specific achievement awarded by the FTMGame
