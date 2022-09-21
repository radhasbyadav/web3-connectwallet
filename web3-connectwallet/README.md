# Instructions to replicate the project

## Clone the repo on your PC
### `git clone https://github.com/seetam-cto/web3-dapp-connect-wallet-react.git`
### Go to the directory
### `cd web3-dapp-connect-wallet-react`
### Install Packages
### `npm install`
### To Run The App with
### `npm start`
<br/><br/>
## Pollyfills Error
### Solution to pollyfills error
### Downgrade React-Scripts Version to 4.0.2
### `npm i --save --save-exact react-scripts@4.0.2`
<br/><br/>
## Install Metamask and Create Account 
### https://myterablock.medium.com/how-to-create-or-import-a-metamask-wallet-a551fc2f5a6b
<br/><br/>
## To know more on web3.js 
### Visit https://web3js.readthedocs.io
<br/><br/>
## Create Local Ethereum Blockchain
### https://trufflesuite.com/ganache/
<br/><br/>
## Connect Ganache Server with Metamask Wallet
* Click on Metamask in Browser
* Click on Networks
* Add Network
* Add the network details
  * Network Name : Enter A Name for Network
  * New RPC URL  : http://localhost:<port> either 8545 or 7545 Check in Ganache > Settings > Server
  * Chain ID : 1337
  * Currency Symbol: ETH
