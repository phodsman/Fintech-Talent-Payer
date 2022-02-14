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

The application `fintech_finder.py` can be run with the command:

 `streamlit run fintech_finder.py`
 
Please be sure to update streamlit if you experience any errors.

## Contributors
This program was written by Preston Hodsman based on a request from Trilogy Education Services, a 2U, Inc.

## License
MIT

## Disclaimer

This program is for educational purposes only. It is not an endorsement of any cryptocurrency or financial advice.

## Examples of Interface:

Demonstration of the interface:

![](https://github.com/phodsman/Fintech-Talent-Payer/blob/main/Images/Screenshot%202022-02-13%20164213.png?raw=true)

Demonstration the Ganache account's reduction in starting value of 100 ETH after first transaction is executed:

![](https://github.com/phodsman/Fintech-Talent-Payer/blob/main/Images/Screenshot%202022-02-13%20164305.png?raw=true)

Demonstration of the executed transfer viewed in Ganache:

![](https://github.com/phodsman/Fintech-Talent-Payer/blob/main/Images/Screenshot%202022-02-13%20164350.png?raw=true)