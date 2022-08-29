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



  <details><summary>bits.py</summary>
<p>
  
  ## Convert bits to and from compact or extended format
You must define "COIN" with two commands, ```COIN=examplecoin``` and ```export COIN```

Then you can run:
  ```
  ./bits.py
  ```
 usage: bits.py [-h] [-c] value 

	Example
```
./bits.py -c 0x1e0ffff0 
coming soon
```
```
./bits.py 486604799
bits value must be 4 bytes
```
  </p>
</details>

  <details><summary>blockchain_fundamentals.py.py</summary>
<p>
  
  </p>
</details>

  <details><summary>bs58.py</summary>
<p>
  
  </p>
</details>

  <details><summary>distribution.py</summary>
<p>
  
  </p>
</details>
  
  <details><summary>hash160.py</summary>
<p>
  
  </p>
</details>
  
  <details><summary>hash256.py</summary>
<p>
  
  </p>
</details>
  
  <details><summary>msgprefixgen.py</summary>
<p>

## Generates pchMessageStart prefixes
You must define "COIN" with two commands, ```COIN=examplecoin``` and ```export COIN```

Then you can run:
  ```
  ./msgprefixgen.py
  ```
  
Example
```
./msgprefixgen.py
Mainnet
pchMessageStart[0] = 0x84;
pchMessageStart[1] = 0xde;
pchMessageStart[2] = 0xab;
pchMessageStart[3] = 0xd5;

Testnet
pchMessageStart[0] = 0xb0;
pchMessageStart[1] = 0xd1;
pchMessageStart[2] = 0xb6;
pchMessageStart[3] = 0xc8;

Regtest
pchMessageStart[0] = 0xcf;
pchMessageStart[1] = 0xbe;
pchMessageStart[2] = 0xc1;
pchMessageStart[3] = 0xab;
```
  </p>
</details>
  
  <details><summary>p2pkh.py</summary>
<p>
  
  </p>
</details>
  
  <details><summary>p2shp2wpkh.py</summary>
<p>
  
  </p>
</details>

<details><summary>pubkey.py</summary>
<p>

## Generate a Private and Public Key
First you need to generate a Private key and use that to generate a Public key. You can use many programs to do this, just make sure you are not using an online generator. That may put your project at risk if they log the private keys. Use something local, you can run the command: 
```
openssl rand -hex 32 
``` 
which will output a secure 32-bit private key, which can be used to generate a public key : 

with command ```./pubkey.py -u YOUR PRIVATE KEY```

You must define "COIN" with two commands, ```COIN=examplecoin``` and ```export COIN```

</p>
</details>

  <details><summary>reverse_endian.py</summary>
<p>
  
  </p>
</details>

  <details><summary>ripemd160.py</summary>
<p>
  
  </p>
</details>

  <details><summary>sha256.py</summary>
<p>
  
  </p>
</details>

  <details><summary>test.py</summary>
<p>
  
  </p>
</details>

  <details><summary>wif.py</summary>
<p>
  
  </p>
</details>
