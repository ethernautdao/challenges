# Ethernaut challenges
![amir-zand-thumb1](https://user-images.githubusercontent.com/550409/136199654-67467daa-fd9a-4f6a-9c07-969626d5ae53.jpg)
Image by [Amir Zand](https://www.artstation.com/amirzand)

Welcome Ethernauts! This repo contains a list of challenges you may want to try to conquer while learning Solidity and Web3 development. Please feel free to PR new challenges, and share your solutions in our discord.

## Challenge 1 - Diamond Hands

*Difficulty*
* Solidity: Easy
* dApp: n/a

*Objectives*
* Build a diamond hands contract that allows users to deposit ETH. Every time they deposit ETH, it will be locked for two years.
* After two years, they will be able to withdraw the ETH.
* Your implementation should run unit tests on the contract, and actually confirm all of its functionality.

*Hints*
* Use hardhat - it has everything you need to compile, run a local chain, run unit tests, skip forward in time, etc.

## Challenge 2 - AAVE Ejector

*Difficulty*
* Solidity: Medium
* dApp: n/a

*Objectives*
* Build a contract that can help you close an AAVE position with multiple collateral and borrow asset types.
* You may use AAVE's "pay with colalteral" feature, or flash loans.
* Full unit test coverage
* Ability to test your solution against any AAVE position via mainnet forking and account impersonation.

*Hints*
* Use hardhat - it has everything you need for this task.
