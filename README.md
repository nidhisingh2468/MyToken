##MY TOKEN

This program demonstrates how we can create our own token. The purpose of this program is that we can learn about public variables, mapping, mint function and burn function. Also we learn that burn function makes sure that balance of "sender" should be greater than or equal to the amount that is supposed to be burned.

##Description

This program is a contract written in Solidity, a programming language used for developing smart contracts on the Ethereum block chain. This contract helps us to know about various functions and their use.

##Getting Started


##Executing Program


REMIX DEFAULT WORKSPACE

Remix default workspace is present when: 
i. Remix loads for the very first time 
ii. A new workspace is created with 'Default' template 
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

'contracts': Holds three contracts with increasing levels of complexity.
'scripts': Contains four typescript files to deploy a contract. It is explained below.
'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.
SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly in the file deploy_with_ethers.ts or deploy_with_web3.ts

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled. Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules. For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin. For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.

##Authors


Nidhi Singh
bhavnap2468@gmail.com

##License

Unlicensed
