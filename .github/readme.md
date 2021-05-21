# News_feed Dapp
#### Description:
Dapp using truffle.js framework for posting news with solidity contracts.
# Quick Start
* cd into project repro</br>
   `cd Ethereum_Dapp`
*  download node libraries</br>
   `npm install`
* Download/Start ganache</br>
https://truffleframework.com/ganache
* Compiling contracts</br>
    `truffle compile`
* Migrating to ganache</br>
**Note: depending on ganache cli/gui, you may need to change truffle.js port settings Currently listening on port : 7545**</br>
` truffle migrate --network development  --reset --all`
*  Start FrontEnd DApp on ganache</br>
`  npm run dev`
