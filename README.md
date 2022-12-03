# TransparentCharity

![main_image](https://blog.justgiving.com/wp-content/uploads/2020/09/Transparency-iStock-photo-paid-for_21-1.jpg)

## The need

We dont see platforms ensuring transparency in case of charity/donations. Also there are security aspects involved. Biggest problem being the transparency of the donation.That is what we have tried to solve using this project.

## Installation

To get Charity Blockchain up and running on your local machine, run the following in a terminal:

```shell
    $ git clone git@github.com:sswensen/Charity-Blockchain.git // Clone repo
```
Install dependencies manually:

``` shell
    $ cd project
    $ npm install // Install all dependencies
    $ cd ..
    $ npm install
```

Compile and deploy contracts to your local test net (Ganache):

```shell
    $ truffle compile
    $ truffle migrate
```

## How it works

* Create/login into your metamask wallet
* A ganache RPC Server is run with metamask as the wallet, using the node.js interface.
* A hash value is generated from charity and organisation details
* transaction hash is generated for each transaction between organisation and charity, when a transaction is carried out
* when the user mines all the transactions updates, a block is generated