# Ethereum Blockchain Wallet
![Crypto_Wallet](./Images/wallet_image.jpeg)

The goal of these Python files is to create an application named "Fintech Finder" that customers can use to find fintech professionals from among a list of candidates, hire them, and pay them using the Ethereum blockchain network. This will allow customers to instantly pay the fintech professionals whom they hire with cryptocurrency. 

---

## Technologies 
In addition to the standard Python 3.7 dev libraries, this file leverages the following libraries and/or dependencies:
* [Web3.py](https://web3py.readthedocs.io/en/stable/overview.html) - A Python library for connecting to and performing operations on Ethereum-based blockchains
* [Mnemonic](https://pypi.org/project/mnemonic/) - A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard
* [bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard
* [Ganache](https://trufflesuite.com/ganache/) - A program that allows you to quickly set up a local blockchain, which you can use to test and develop smart contracts
* [streamlit](https://streamlit.io/) - Turns data scripts into shareable web apps using Python
* [dotenv](https://pypi.org/project/python-dotenv/) - Python-dotenv reads key-value pairs from a .env file and can set them as environment variables
* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - A decorator that is used to add generated special methods to classes
* [typing](https://docs.python.org/3/library/typing.html) - Provides runtime support for type hints
* [requests](https://pypi.org/project/requests/) - A simple, yet elegant, HTTP library. Allows you to send HTTP/1.1 requests extremely easily

### Imports
Imports for `crypto_wallet.py` file: 
```
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```
Imports for `fintech_finder.py` file: 
```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
```
Ganache network: w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

---

## Installation Guide


---

## Usage


---

## Methods


---

## Results - Streamlit Application

### App Overview 


### Ganache Connection

---

## Contributors
Catherine Croft

Email: catherinecroft1014@gmail.com

LinkedIn: [catherine-croft](https://www.linkedin.com/in/catherine-croft-4715481aa/)

---

## License 
MIT