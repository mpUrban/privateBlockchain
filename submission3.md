# Project 2 -  Private Blockchain

## Files:

blockClass.js - block class <br>
blockchainClass.js - block class <br>
levelFunctions.js - contains all functions using levelDB <br>
privateBlockchain.js - contains loop to add blocks, corrupt blocks, and test <br>

## Folders:

chainData - contains the current chain data <br> 
chaindata_allGood - contains a set of 10 valid blocks <br>
chaindata_B2inv - contains 10 blocks where block 2 is invalid <br>

## Dependencies:

LevelDB
crypto-js

## Submission number: 3

## Submission changes

Modified validateChain() : <br>
* moved final error log read out of loop
* forced validateBlock() call to resolve