# TransparentCharity

![main_image](https://blog.justgiving.com/wp-content/uploads/2020/09/Transparency-iStock-photo-paid-for_21-1.jpg)

## The need

##### We dont see platforms ensuring transparency in case of charity/donations.
##### Also there are security aspects involved.
##### Biggest problem being the transparency of the donation.

## Tech involved in the project

#### Node.js
Acting as the backend for our project

#### Solidity web3
It essentially has Inheritance properties in contracts including multiple level inheritance properties.

#### Metamask
easy to use secure wallet.

#### Ganache
Provides GUI for local based Ethereum blockchain development.

## How it works

* Create/login into your metamask wallet
* A ganache RPC Server is run with metamask as the wallet, using the node.js interface.
* A hash value is generated from charity and organisation details
* transaction hash is generated for each transaction between organisation and charity, when a transaction is carried out
* when the user mines all the transactions updates, a block is generated