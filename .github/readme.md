# News_feed Dapp
#### Description:
Dapp using truffle.js framework for posting news with solidity contracts.
# Quick Start
1. cd into project repro
   ```cd Ethereum_Dapp```
2. download node libraries
   ```npm install```
3. Download/Start ganache
https://truffleframework.com/ganache
 Compiling contracts
    `truffle compile`
    4. Migrating to ganache
**Note depending on ganache cli/gui you may need to change truffle.js port settings Current listing on port : 7545**
` truffle migrate --network development  --reset --all`
5. Start FrontEnd DApp on ganache
`  npm run dev`
