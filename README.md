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
