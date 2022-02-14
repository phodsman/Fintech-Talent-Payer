# Fintech-Talent-Payer

A simple demonstration application of an application to pay Fintech talent in Ethereum.

## Technologies

This program was written in Python 3.7 and can be run in Streamlit. It requires Ganache to run example transactions.

The following libraries are used:

- streamlit
- dataclasses
- typing
- web3
- bip44

## Installation Guide

You will need to verify that you have installed the libraries listed in the Technologies section. In addition, you will need to install the application Ganache. Use the mnemonic phrase at the top of the running ganache application in a file labelled `.env` in the application folder with the following syntax:
```MNEMONIC = 'your long ganache mnemonic set of words should be put right here'```

## Usage

The application `fintech_finder.py` can be run with the command `streamlit run fintech_finder.py` . Please be sure to update streamlit if you experience any errors.

## Contributors
This program was written by Preston Hodsman based on a request from Trilogy Education Services, a 2U, Inc.

## License
MIT

## Examples of Interface:

Demonstration of the interface after several blocks have been added:

![](https://github.com/phodsman/Blockchain-Financial-Ledger-UI/blob/main/Screenshot%202022-02-06%20111000.png?raw=true)

Demonstration of the interface result when the `Validate Chain` button is pushed:

![](https://github.com/phodsman/Blockchain-Financial-Ledger-UI/blob/main/Screenshot%202022-02-06%20111109.png?raw=true)