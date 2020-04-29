contract address(SolnSquareVerifier): 0x6Fa6a9220EcC39A175d409f6bed92678Bf4cC7aa (https://rinkeby.etherscan.io/address/0x6fa6a9220ecc39a175d409f6bed92678bf4cc7aa)

token address(Bitcoin BC) :- https://rinkeby.etherscan.io/token/0x6fa6a9220ecc39a175d409f6bed92678bf4cc7aa


Transaction - https://rinkeby.etherscan.io/tx/0x3ed06b09fc4fa9708d2d98dfacb3865d419d9d69c0b2a007965416db690ed210


Listed 5 tokens with id 1,11,12,13,14 by address 0xd8bc1ceeB01FB68Fb9856E504c5402Df19931270
Purchased these 5 tokens by address 0x133cBE0ca6B3B2E0328Db20Fad3aD9c68D75A997 on OpenSea 
(https://rinkeby.opensea.io/assets/0x6fa6a9220ecc39a175d409f6bed92678bf4cc7aa/1)



To install, download or clone the repo, then:

npm install

Start Ganache like below .
ganache-cli

In a separate terminal window,from inside the directory eth-contracts/ Compile smart contracts:

truffle compile

This will create the smart contract artifacts in folder build\contracts.

Then compile and deploy with truffle.

truffle migrate --network development --reset --compile-all

Testing
To run truffle tests from inside the directory eth-contracts/:

truffle test

Deployment :-

Create an account in Infura
Create a project in Infura and get the Address for deploying in Rinkeby test network
Copy the endpoint address and update the Rinkeby network information with the mnemonic and endpoint address in Truffle.js file
Fund the metamask wallet by posting a tweet in https://faucet.rinkeby.io. The post should have the address “ Requesting faucet funds into ……. On the Rinkeby Ethereum test network” Then copy the tweet in the above website and click Give me Ether.
Then deploy it using `truffle deploy - -network rinkeby`. If needed to deploy again use `truffle migrate - -network rinkeby - - reset - -compile-all`.


Contract ABI
All contract API are in the build folder (eth-contracts\build\contracts). Please check it out.


