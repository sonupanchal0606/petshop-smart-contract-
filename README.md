# petshop-smart-contract-

steps
open terminal
C:\Users\Ni3>cd  Desktop
C:\Users\Ni3\Desktop>mkdir petshop
C:\Users\Ni3\Desktop>cd petshop
C:\Users\Ni3\Desktop\petshop>truffle unbox pet-shop //this will install the skeleton of the dapp application that we are going to create
C:\Users\Ni3\Desktop\petshop>code .

take help from here https://www.trufflesuite.com/boxes/pet-shop
now we need to write our contract 
in truffle terminal write

PS C:\Users\Ni3\Desktop\petshop> truffle create contract Adoption
edit the contract Adoption
PS C:\Users\Ni3\Desktop\petshop> truffle create migration DeployCont //this will create the migration file to create contract
PS C:\Users\Ni3\Desktop\petshop> truffle deploy
now open metamask and connect to custom rpc. copy the address from ganache "HTTP://127.0.0.1:7545" and paste into the metamask. 
Also import the private key from ganache into metamask
PS C:\Users\Ni3\Desktop\petshop> npm run dev



