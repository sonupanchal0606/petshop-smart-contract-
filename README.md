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
mkdir solidity
cd solidity

trfulle init
----------------------------------
Windows PowerShell
Copyright (C) 2015 Microsoft Corporation. All rights reserved.

PS C:\Users\Ni3> cd .\Desktop\
PS C:\Users\Ni3\Desktop> mkdir solidity


    Directory: C:\Users\Ni3\Desktop


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        4/14/2021   2:07 PM                solidity


PS C:\Users\Ni3\Desktop> cd .\solidity\
PS C:\Users\Ni3\Desktop\solidity> truffle init

Starting init...
================

> Copying project files to C:\Users\Ni3\Desktop\solidity

Init successful, sweet!

PS C:\Users\Ni3\Desktop\solidity> code .
PS C:\Users\Ni3\Desktop\solidity>



truffle develop : provides as local blockchain for the development and testing purpose
truffle deploy/truffle migrate/truffle deploy --reset : 
trufffle install : it only installs the contract
truffle unbox : it downloads the whole dapp application (https://www.trufflesuite.com/boxes/)
truffle compile
truffle migrate : where to deploy the network





