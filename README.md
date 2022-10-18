# Ethereum NFT minter


## Purpose

The goal of this project is to create a web page in order to be able to mint NFT's.

Frontend to
- Interact with Metamask wallet
- Mint NFTs by selecting pictures and uploading to IPFS
- Display minted NFTs
- Transfer owned NFTs to other wallets
- Transfer owned NFTs to marketplaces, e.e. OpenSea, Rarible


## Solidity Contracts

### Test

#### Simple test


```
npx hardhat test
```

Test coverage is generated in the `coverage` folder and can be viewed using a browser.

#### Test with gas estimation

```
REPORT_GAS=true npx hardhat test
```

### Run

#### Deploy NFT smart contract

```
npx hardhat run scripts/deploy_mynft.js
```

To deploy on localhost network:

```
npx hardhat --network localhost run scripts/deploy_mynft.js
```


#### Start local node

```
npx hardhat node
```


## Frontend