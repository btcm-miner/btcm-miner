# Bitcoinereum Miner
“比特太坊幣” 

Coming in November


## Instructions
**Step 1**
Install `geth` and make sure it is synced up to the current block. This may take a while.
```
geth attach
> eth.blockNumber
> 4461476
```
Make an account `geth account new` and transfer 0.1 ETH to it.

## Coming soon
**Step 2**
Download btcm-miner `git clone http://github.com/btcm-miner／btcm-miner`

**Step 3**
Edit `mine_example.sh`: Enter your geth account address and keystore password.

**Step 4**
Run btcm-miner `mine_example.sh`

## Advanced Settings
**Step 5** 
Tune parameters `n`, `gas`, `delay`, `std` to find best combination for your computer and network.
