# Cryptocurrency Payment

Using this service, cryptocurrency payments are sent to fintech experts from a list of applicants who are being considered for employment.

---

## Technologies:

- [streamlit](https://pypi.org/project/streamlit/) - for creating & sharing customized beautiful web apps
- [Web3.py](https://pypi.org/project/web3/) - python library helps in connecting to & performing operations on Ethereum-based blockchains
- [ethereum-tester](https://pypi.org/project/ethereum-tester/) - provides access to the tools we’ll use to test Ethereum-based applications
- [mnemonic](https://pypi.org/project/mnemonic/) - for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard
- [bip44](https://pypi.org/project/bip44/) - for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard
- [Ganache](https://pypi.org/project/ganache/) - A program that allows to quickly set up a local blockchain, can be used to test & develop smart contracts


---


## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install streamlit
  pip install ethereum-tester
  pip install mnemonic
  pip install bip44

```

---

## Usage

Run the streamlit application by using the below command in terminal:
`streamlit run fintech_finder.py`

To run this program insert your mnemonic from Ganache suite in the sample.env file and then rename file to (dot)env and save.

`MNEMONIC='xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx'`

--- 

## Visualization

- Hiring Lane for 1 hour and making payment
![image-2](https://github.com/ragininegi/Challenge-19/blob/main/Images/Images-2.png)

- Sending transaction with Ethereum account information
![image-1](https://github.com/ragininegi/Challenge-19/blob/main/Images/Images-1.png)
![image-3](https://github.com/ragininegi/Challenge-19/blob/main/Images/Images-3.png)


---


## Contributors
 
Ragini Negi  
Email : negiragini16@gmail.com <br>
LinkedIn : https://www.linkedin.com/in/ragininegi/

---

## License

Apache 2.0

---
