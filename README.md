![grants_badge](https://s3cdn.yourator.co/attachments/attachments/000/088/943/original/a68bb24cc77367be4ffeaa14f478afd72601d530.jpg)
# NFT Marketplace
this a web3 application which perform basic nft markeet place prototype include minting, buying, take down. The backend part of the application is composed of a nft ERC721 contract and a marketplace contract interactive with nft contract


## Run locally

1. Clone the repo

```sh
git clone https://github.com/dabit3/full-stack-ethereum.git
```

2. Install the dependencies

```sh
npm install
```

3. Start the local test node

```sh
npx hardhat node
```

4. Compile the contract 
```
npx hardhat compile
```

5. Deploy the contract

```sh
npx hardhat run scripts/deploy.js --network localhost
```

6. Run the app

```sh
npm run dev
```

## Test Contract 
```sh
npx hardhat test
```
