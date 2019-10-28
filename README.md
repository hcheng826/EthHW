# EthHW
Ethereum teaching materials HW2-2 for NTUEE Networking and Multimedia Lab (EE3002)
## Prequisites
node.js, npm, ganache-cli(or ganache), truffle
```
sudo apt install nodejs
sudo apt install npm
npm install -g ganache-cli
npm install -g truffle
```
## Quick start
```
~ $ git clone https://github.com/Vimalakirti/EthHW.git
~ $ cd EthHW/
```
## Table of contents
- [1_Hello](#1_hello)
- [2_Coin](#2_Coin)

## Notice
If your os is not **Windows**, please rename `truffle-config.js` to `truffle.js`,
or just run the following command:
```
~ $ bash rename.sh
```
## HWs
**Please describe how you get the point(s) in your report.**
### 1_Hello
```
~ $ cd 1_Hello/
```
- (1%) Compile the contracts
- Modify `truffle-config.js`(or `truffle.js`)
- (1%) Migrate the contracts
- Run `truffle console`
- (1%) Get the message below:
![image](https://github.com/Vimalakirti/EthHW/blob/master/images/1_hello_1.PNG)
- Change your name, we hold **Vimalakirti** up as an example here,
- (1%) And get the message below:
![image](https://github.com/Vimalakirti/EthHW/blob/master/images/1_hello_2.PNG)
### 2_Coin
```
~ $ cd 2_Coin/
~ $ npm install @openzeppelin/contracts
```
- Google "ERC20" first
- And you might need this doc: https://docs.openzeppelin.com/contracts/2.x/api/token/erc20#erc20
- Compile the contracts
- Modify `truffle-config.js`(or `truffle.js`)
- Migrate the contracts
- Write your test script(solidity)
- (4%) Test the functions below:
    totalSupply() - I've done for you
    balanceOf(account) - I've done for you
    transfer(recipient, amount) - TODO
    allowance(owner, spender) - TODO
    approve(spender, amount) - TODO
    transferFrom(sender, recipient, amount) - TODO
- You should test their functionalities and get 6 passing by running `truffle test`
### 3_PetShop
```
~ $ cd 3_PetShop/
```