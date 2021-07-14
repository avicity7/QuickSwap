# QuickSwap

A discrete Python based node-less sniper. 

## Usage
Two libraries are required, web3 and json. Installation commands are as follows: 
```python 
pip3 install web3 

pip3 install json 
```

Lines 10 and 11 need to be changed to your own address and personal key. 
```python
personal_wallet = "" #Enter your personal address here
private = "" #Enter your private key here
```

Other parameters that can be changed: 
```python 
'gas': 250000, #Line 22
'gasPrice': w3.toWei('10','gwei'), #Line 23 
tokenA = w3.toChecksumAddress('0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c') #This is the WBNB address, change it for tokens that have a different liquidity pool eg. WBUSD. Line 40.
