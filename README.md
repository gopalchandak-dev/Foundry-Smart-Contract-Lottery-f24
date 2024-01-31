# Proveably Random Raffle Contracts

## ABOUT

**This code is to create a proveably random raffle lottery.**

## What we want to do?

1. Users canenter by paying for tickets
        The ticket fee are going to go to the winner during the draw
2. After the X period of time, the lottery will automatically draw a winner
        And this will be done programatically
3. Using chainlink VRF & Chainlink Automation
        -> Chainlink VRF -> Randomness
        -> Chainlink Automation -> Time based trigger


## Tests!

1. Write some deploy scripts
2. Write our tests
   1. Works on local chain
   2. Works on Forked Testnet
   3. Works on Forked Mainnet 