# DeFi Kingdom Clone on Avalanche

## Description

This project aims to create a decentralized gaming experience on the Avalanche blockchain inspired by DeFi Kingdoms. Players can engage in activities such as exploration, purchase and battle using digital assets and earn rewards with custom tokens.
The player is given choice boards based on their badge and can also transfer the badge to friends in the game. They also gain voting rights if they have won at least one major amendment that the owner is considering.

## Get Started

### EVM Subnet Configuration

## Step by Step Guide

### 1. Deploying your EVM subnet using the Avalanche CLI

Follow the Avalanche documentation to create a custom EVM subnet on your Avalanche network. This subnet serves as the environment where smart contracts are deployed.

### 2. Add your subnet to Metamask

Make sure your custom EVM subnet is added to Metamask so you can communicate with it. Metamask allows you to send events and interact with smart contracts installed on your subnet.

### 3. Make sure this is your network of choice in Metamask

Change your Metamask network to a custom EVM subnet so that all transactions and interactions happen on the correct network.

### 4. Connect Remix to your Metamask

Use the Remix IDE and connect it to Metamask using the Injected Provider service. This connection allows Remix to communicate with your Metamask account and deploy contracts directly from the Remix interface.

### Define your currency

Execute
GameToken.sol
contracts with Remix. This token acts as an in-game currency.

### 5. Enable Smart Contracts

Copy and paste your solid smart contract code into Remix. Collect contracts and then deploy them to your custom EVM subnet using Remix's deployment interface.

### 6. Test your app!

## Game Mechanics

### Token Management

Players can deposit their tokens to earn shares that represent the asset's total cash balance. They can later withdraw tokens according to the shares they own.

### Player management

Each player is represented by a player structure with attributes such as token balance, experience points, achievements, battle wins, count, votes, level and name.

### Game Features

- **Register Player**: Players can register with their name and original attributes which will start the game mode.
- **Battle**: Engage in battles with other players where the results give you experience points and can give you votes.
- **Explore**: Players can explore and earn rewards such as coupons or experience points based on a random or predetermined reward system.
- **Purchase Items**: Spend tokens on in-game items or upgrades to improve the game.

### Leaderboard
- The contract maintains a scoreboard based on token balances and battle winnings that is updated dynamically as players interact with the system.

## Author:
kumar sanjeev

## License
This project is licensed under the MIT License - see LICENSE.md for details. Create another Legumin file based on the following information.



