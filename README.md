# blockchain-dev-tools
Blockchain Development Tools

## Installation
```
virtualenv blockchain && cd blockchain
git clone https://github.com/chrisbagsrocks/blockchain-dev-tools.git && cd blockchain-dev-tools
./INSTALL.sh
cd ..
source bin/activate
pip install ecdsa
```

Alternatively, copy all of the `*.py` files except `blockchain_fundamentals.py` into the python `bin` folder, and the `blockchain_fundamentals.py` file into the python `lib` folder.

## 1. Generate a Private and Public Key
First you need to generate a Private key and use that to generate a Public key. You can use many programs to do this, just make sure you are not using an online generator. That may put your project at risk if they log the private keys. Use something local, you can run the command: 
```
openssl rand -hex 32 
``` 
which will output a secure 32-bit private key, which can be used to generate a public key : 

with command ```./pubkey.py -u YOUR PRIVATE KEY```

You must define "COIN" with two commands, ```COIN=examplecoin``` and ```export COIN```
