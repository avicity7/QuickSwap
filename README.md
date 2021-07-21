# QuickSwap

A discrete Python based node-less sniper. 

## Usage
Web3 is required. Install the Web3 library by utilising the command below: 
```python 
pip3 install web3 
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
```

If you'd like to support QuickSwap further or kindly buy me a coffee, you can do so to this BEP20 address! 

```python
0x91FD856a6Ae3Df1a3501F75a40144bA2D306CB54
