# Lottery-game-with-chainlink-VRF

![image](https://user-images.githubusercontent.com/63971790/233211007-e39f9ce5-d4c6-483d-bda5-2108a26ba633.png)


This is a blockchain lottery game built using Chainlink VRF and Graph Protocol. The game allows a maximum number of players to participate and compete for a single prize. After the maximum number of players has been reached, one winner is chosen at random using Chainlink VRF. The winner gets the total amount of ether, which is equal to the maximum number of players multiplied by the entry fee.

## Getting Started

This is a basic blockchain lottery game built using Chainlink VRF and Graph Protocol. It allows a maximum number of players and the winner is chosen at random using Chainlink VRF. The game data is using Graph Protocol, which allows players to easily access information about ongoing and past games. The game is deployed on the Mumbai testnet network and can be accessed using [the website](https://lottery-game-with-chainlink-vrf.vercel.app/).

## How to Play

* The contract deployer should arrange the maximum number of players to participate.
* The contract deployer should start the game.
* Each player should pay an entry fee to join the game.
* After the maximum number of players have joined, the game should choose a winner at random using Chainlink VRF.

## Run the development server:

Open terminal and go `/my-app` directory.

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [localhost](http://localhost:3000) with your browser to see the result.

For more info: [LearnWeb3 Junior Track](https://github.com/LearnWeb3DAO/Junior-Track/blob/main/Lottery-Game-Chainlink-VRF.md)
