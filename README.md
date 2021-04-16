# petshop-smart-contract-
install 
download node js  
  check npm -v
  node -v

open cmd as administrator and run
npm install -g -production windows-build-tools

now install truffle//development framework for ethereum
open cmd prompt as administrator and run
npm install -g truffle

now download ganache from https://www.trufflesuite.com/ganache
ganache will create a personal blockchain for us which we can use to deploy our contracts and test our application

download and install VScode : editor

in VS code install following extentions
solidity
java script snippet
mocha
chai

reload

open windows powershell
PS C:\Users\Ni3> cd .\Desktop\
PS C:\Users\Ni3\Desktop> mkdir solidity
PS C:\Users\Ni3\Desktop> cd .\solidity\
PS C:\Users\Ni3\Desktop\solidity> truffle init
PS C:\Users\Ni3\Desktop\solidity> code .
PS C:\Users\Ni3\Desktop\solidity>

inside the directory we have following folders
contracts : to store the contact
migration : to store the network information where we need to save the network related information to deploy the contact
test : to test the contract 
truffle-config.js : for windows users
here we will use ganache as our local blockchain. for this open the ganache window and copy the local port. 
now go to the truffle-config.js and paste the port id 
development: {
      host: "127.0.0.1",
      port: 7545,
      network_id: "*" // Match any network id
    }
PS C:\Users\Ni3\Desktop\solidity> truffle deploy or truffle deploy --reset
PS C:\Users\Ni3\Desktop\solidity> truffle compile
PS C:\Users\Ni3\Desktop\solidity> truffle deploy or truffle migrate


follow this to unbox react box https://www.trufflesuite.com/boxes/react
to skip the role of metamask , you can copy the url and paste in new incognito tab

truffle networks : will give the contract address which have deployed to our networks
truffle develop : provides as local blockchain for the development and testing purpose
truffle deploy/truffle migrate/truffle deploy --reset : 
trufffle install : it only installs the contract
truffle unbox : it downloads the whole dapp application (https://www.trufflesuite.com/boxes/)
truffle compile
truffle migrate : where to deploy the network





