# SmartContractMarketplace

Web3 application that runs on the blockchain through Lappsnet network with token ESAT. You can upload new products and be able to buy them by connecting to metamask.

![la](https://user-images.githubusercontent.com/94976934/170391705-66d63d08-2940-4e99-8b58-d5b42f859cba.gif)

# Steps to start project
## Installing dependencies

## Clone project
```
git clone https://github.com/DanielCruz12/SmartContractMarketplace.git
```
## Once you are ready, make sure to configure your environment using NPM node.js
```
npm install
```
## Open new terminal and enter to the directory you just cloned like this:
```
cd marketplace
```
## Run application
```
npm start run
```

if you don't know how to add Lappsnet network to metamask you can check here [ConnectLappsnet](https://nuderebatsin-roal.gitbook.io/lappsnet/guide/network)




# Other way to run the project locally
## talk to ganache
If you want to run the application in the browser, you can download ganache and create a new workspace and add new account using private key and change port to [localhost](http://localhost/8545) if it doesnt work.
download Ganache: [Download Ganache](https://trufflesuite.com/ganache/)


![ganache](https://user-images.githubusercontent.com/94976934/169707865-f47bd67d-5813-429e-8fb9-07eeed073d77.png)


## You can see all these accounts in Ganache
![red](https://user-images.githubusercontent.com/94976934/169708330-7be9d64f-9310-4d75-8faa-562dd78d2c1c.png)


## Once you are ready, make sure to configure your environment using NPM node.js
```
npm install
```
## Clone project
```
git clone https://github.com/DanielCruz12/SmartContractMarketplace.git
```
## Install truffle:
```
npm install truffle -g truffle@5.0.5
```
## Open new terminal and enter to the directory you just cloned like this:
```
cd marketplace
```
## Now you can check the smart contract from the truffle console
```
truffle console
```
```
accounts = await web3.eth.getAccounts()
```
```
accounts
```

You will see all the accounts, yeah you did it! you are talking to ganache!

![accounts](https://user-images.githubusercontent.com/94976934/169708415-e8e8530d-8dc5-4f32-b7b0-7a300e035a37.png)



## Test
```
truffle test
```


## then run this command on your project:
```
truffle compile
```
# Successful configuration!! ???????????????

## Run application
```
npm start run
```
