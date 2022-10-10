# Mod19_challenge
# UW-finctech-2022
This is  a public repo for the Module 19 Challenge of the UW Fintech Bootcamp in 2022.


## Technologies and Libraries

Visual Studio Code,
Streamlit
Web3



## Installation Guide

Install visual studio code by downloading the app and running it.

Install the following dependencies an dmocdules from the libraries above

```
    import os
    import requests
    from dotenv import load_dotenv
    load_dotenv()
    from bip44 import Wallet
    from web3 import Account
    from web3 import middleware
    from web3.gas_strategies.time_based import medium_gas_price_strategy
    import streamlit as st
    from dataclasses import dataclass
    from typing import Any, List
    from web3 import Web3
    w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))
    ```


## Overview of the analysis

* Purpose of the analysis

Assuming the role of a Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency. Complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

## Results

Screenshot of added blocks

<img src="https://github.com/Virginia440/Mod19_challenge/blob/main/Screenshots/Transaction_Kendal.PNG" width=500 height=300>

Screenshot of Validate button

<img src="" width=500 height=300>

---


## License
 The code is made without a license, however, the materials used for research are licensed.
---


