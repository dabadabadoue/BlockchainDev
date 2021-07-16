# BlockchainDev Example Code

1. Download Visual Studio Code: https://code.visualstudio.com/download
2. Download the solidity extension for VSCode: https://marketplace.visualstudio.com/items?itemName=JuanBlanco.solidity
3. Open the folder you cloned in VSCode: BlockchainDev
4. Have npm and node installed (instructions here: https://nodejs.org/en/download/. Make sure node is on your path if you run into issues using npm/node)
5. Run `npm install -g truffle`
6. Now to run the code:
   1. `truffle compile`
   2. `truffle develop`
   3. In the truffle console that appears, run the following `migrate`
   4. `HelloWorldContract.deployed().then(_app => { hello = _app })`
   5. `hello.greet()`
   6. To close the truffle console, hit "Ctrl+d"
