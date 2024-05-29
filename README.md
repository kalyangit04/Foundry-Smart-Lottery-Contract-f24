# Provably Random Raffle Contracts

## About

This code is to create a provable random smart contract lottery system independent of a single entity.

## What we want it to do?

1. Users can enter, by paying the entry fee.
    1. The ticket fee collected is going to go to the winner during the mega draw.
2. After X period of time, the lottery will automatically draw a winner.
    1. And this will be done programatically
3. By using Chainlink VRF & Chainlink Automation
    1. Chainlink VRF -> Randomness
    2. Chainlink Automation -> TIme Based Trigger


## Tests!

1. Write some deploy contracts
2. Write our tests
    1. Work on Local Chain
    2. Forked Testnet
    3. Forked Mainnet